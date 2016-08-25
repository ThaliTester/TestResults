#### Test 826421846ff00c4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-25 03:49:02.762   874   886 I ActivityManager: Start proc 3914:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,--------- beginning of main
08-25 03:49:02.842  3914  3914 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
08-25 03:49:02.962  3914  3914 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-25 03:49:02.986  3914  3914 I BooksApp: Created application version: 3.6.9 (30609)
08-25 03:49:03.065  3914  3933 I BooksSync: Starting books sync for 61035162, extras: ade
08-25 03:49:03.205  3914  3939 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
08-25 03:49:03.255  1535  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-25 03:49:03.256  1535  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:49:03.256  1535  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:03.257  1535  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 03:49:03.295  1535  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-25 03:49:03.295  1535  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:49:03.295  1535  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:03.295  1535  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 03:49:03.317  3914  3939 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:49:03.320  3914  3933 E BooksSync: Soft error
08-25 03:49:03.320  3914  3933 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:49:03.320  3914  3933 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:49:03.320  3914  3933 E BooksSync: Sync error
08-25 03:49:03.320  3914  3933 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:49:03.320  3914  3933 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:49:03.320  3914  3933 I BooksSync: Finished books sync
08-25 03:49:03.330   874  1399 I ActivityManager: Killing 3559:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
08-25 03:49:03.332   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 67783, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-25 03:49:03.414  3926  3926 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 03:49:03.419  3926  3926 D AndroidRuntime: CheckJNI is OFF
08-25 03:49:03.460  3926  3926 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 03:49:03.507  3926  3926 I Radio-JNI: register_android_hardware_Radio DONE
08-25 03:49:03.529  3926  3926 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-25 03:49:03.533   874  1403 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 03:49:03.555  1991  2423 W SearchService: Abort, client detached.
08-25 03:49:03.562  1991  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7d4dfa7
08-25 03:49:03.562  1991  1991 I HotwordDetector: Closing mic
08-25 03:49:03.562  1991  2360 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 03:49:03.586  3926  3926 D AndroidRuntime: Shutting down VM
08-25 03:49:03.599   874  1971 I ActivityManager: Start proc 3948:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 03:49:03.618   376  2362 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 03:49:03.620   376  2362 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 03:49:03.625   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 03:49:03.627  1991  2359 I MicroRecognitionRnrImpl: Detection finished
08-25 03:49:03.627  1991  2355 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 03:49:03.675  3948  3948 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 03:49:03.697  3948  3948 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 03:49:03.703  3948  3948 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8539-8542)
08-25 03:49:03.703  3948  3948 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:49:03.715  3948  3948 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30ab990}
08-25 03:49:03.715  3948  3948 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:49:03.715  3948  3948 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 03:49:03.720  3948  3948 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 03:49:03.722  3948  3948 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 03:49:03.732  3948  3948 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-25 03:49:03.742  3948  3948 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:49:03.742  3948  3948 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:49:03.742  3948  3948 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:49:03.742  3948  3948 I Adreno  : Build Date                       : 10/20/15
08-25 03:49:03.742  3948  3948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:49:03.742  3948  3948 I Adreno  : Local Branch                     : M14
08-25 03:49:03.742  3948  3948 I Adreno  : Remote Branch                    : 
08-25 03:49:03.742  3948  3948 I Adreno  : Remote Branch                    : 
08-25 03:49:03.742  3948  3948 I Adreno  : Reconstruct Branch               : 
08-25 03:49:03.789   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba0d506:true
08-25 03:49:03.825  3948  3948 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 03:49:03.840  3948  3948 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 03:49:03.876  3948  3988 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 03:49:03.886  3948  3974 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 03:49:03.921  3948  3988 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 03:49:03.970   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +385ms
,08-25 03:49:03.975  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 03:49:04.034  3948  3948 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3948
,08-25 03:49:04.172  3948  3948 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 03:49:04.316  3948  3990 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1699284688
,08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 03:49:04.329  3948  3990 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32bdc67 added. We now have 1 listener(s)
,08-25 03:49:04.333  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 03:49:04.338  3948  3990 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:49:04.339  3948  3990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:49:04.339  3948  3990 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 03:49:04.345  3948  3990 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@92da0b2 added. We now have 1 listener(s)
08-25 03:49:04.345  3948  3990 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:49:04.349   874  1318 D WifiService: New client listening to asynchronous messages
08-25 03:49:04.349  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:49:04.349  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 03:49:04.350  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 03:49:04.350  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 03:49:04.350  3948  3990 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 03:49:04.352  1535  1535 I ConfigService: onDestroy
08-25 03:49:04.353  3948  3990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:49:04.353  3948  3990 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 03:49:04.365  3948  3990 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:04.366  3948  3990 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:49:04.367  3948  3990 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 03:49:04.367  3948  3990 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:49:04.369  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:04.369  3948  3990 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 03:49:04.373  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:04.425   874  1971 I ActivityManager: Killing 3349:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 03:49:04.520   874  1971 I ActivityManager: Killing 2586:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-25 03:49:04.544  3948  3948 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 03:49:05.096  3948  3998 W jxcore-log: Initializing JXcore engine
,08-25 03:49:05.096  3948  3998 W jxcore-log: JXcore engine is ready
,08-25 03:49:05.130  3998  3998 W Thread-365: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 03:49:05.130  3998  3998 W Thread-365: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10435]" dev="sockfs" ino=10435 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 03:49:05.130  3998  3998 W Thread-365: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 03:49:05.130  3998  3998 W Thread-365: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25051]" dev="sockfs" ino=25051 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 03:49:05.144  3948  3998 W jxcore-log: Starting JXcore engine
,08-25 03:49:05.223  3948  3998 W jxcore-log: Platform android
08-25 03:49:05.223  3948  3998 W jxcore-log: 
08-25 03:49:05.223  3948  3998 W jxcore-log: Process ARCH arm
08-25 03:49:05.223  3948  3998 W jxcore-log: 
,08-25 03:49:05.388  3948  3998 I jxcore-log: JXcore Cordova bridge is ready!
08-25 03:49:05.388  3948  3998 I jxcore-log: 
,08-25 03:49:05.389  3948  3998 W jxcore-log: JXcore engine is started
,08-25 03:49:05.404  3948  3990 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 03:49:05.410  3948  3948 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 03:49:06.394   977   977 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
08-25 03:49:06.395   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,08-25 03:49:06.425   977   977 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
,08-25 03:49:06.425   977   977 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,08-25 03:49:07.010   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 03:49:07.407   977   977 I kickstart: STATUS: Received file 'm9kefs2'
,08-25 03:49:07.408   977   977 I kickstart: STATUS: 950272 bytes transferred in 0.982146 seconds
,08-25 03:49:07.408   977   977 I kickstart: STATUS: Successfully downloaded files from target 
,08-25 03:49:07.410   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,08-25 03:49:07.412   977   977 I kickstart: STATUS: Sahara protocol completed
,08-25 03:49:07.976  3914  3931 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-25 03:49:13.075  3661  3742 D Finsky  : [330] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-25 03:49:13.103  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:13.120  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:13.126  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:13.197  1535  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-25 03:49:13.198  1535  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-25 03:49:13.198  1535  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:13.199  1535  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:13.248  3661  3742 D Finsky  : [330] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-25 03:49:13.322   874   887 I ActivityManager: Waited long enough for: ServiceRecord{91cba0c u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-25 03:49:13.792  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:13.813  1535  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:49:13.813  1535  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:49:13.814  1535  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:13.814  1535  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:13.827  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:49:13.827  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 03:49:13.827  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-25 03:49:20.129  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 03:49:20.129  3948  3998 I jxcore-log: 
,08-25 03:49:20.132  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 03:49:20.132  3948  3998 I jxcore-log: 
,08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:20.142  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:49:20.146  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:20.148  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 03:49:20.148  3948  3998 I jxcore-log: 
,08-25 03:49:20.151  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 03:49:20.151  3948  3998 I jxcore-log: 
,08-25 03:49:20.522  3948  3998 I jxcore-log: Running unit tests
08-25 03:49:20.522  3948  3998 I jxcore-log: 
,08-25 03:49:20.523  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:49:20.523  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f430dd added. We now have 2 listener(s)
08-25 03:49:20.524  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:49:20.524  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:49:20.524  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 03:49:20.524  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:49:20.524  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dca5452 added. We now have 2 listener(s)
08-25 03:49:20.524  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:49:20.525  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:49:20.528  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:20.536  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:49:20.540  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.540  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:49:20.540  3948  3998 D ExecuteNativeTests: Running unit tests
,08-25 03:49:20.548  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:20.552  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:20.636  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:49:20.636  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 added. We now have 3 listener(s)
08-25 03:49:20.637  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:49:20.637  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:49:20.637  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:49:20.637  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:49:20.637  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 added. We now have 3 listener(s)
08-25 03:49:20.638  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:49:20.638  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:49:20.640  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:20.649  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:20.650  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.650  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:49:20.653  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:49:20.653  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:20.653  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:20.653  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:20.657  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:20.660  3948  3998 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 03:49:20.660  3948  3998 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 03:49:20.661  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:20.661  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:49:20.663  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:20.663  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:20.663  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:20.666  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:20.669  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:20.669  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:20.671  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:20.672  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.672  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:49:20.672  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:49:20.673  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 removed from the list
08-25 03:49:20.673  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:20.673  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 removed from the list
08-25 03:49:20.674  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:20.674  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.675  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.675  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:20.677  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:20.677  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:20.677  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:20.677  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:20.682  3948  3998 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 03:49:20.685  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:20.685  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:20.685  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:20.686  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:20.686  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:20.686  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.686  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:20.687  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:20.687  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:20.687  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:20.687  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.687  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.688  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.688  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.690  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:49:20.690  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:20.690  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:20.691  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:49:20.699  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 03:49:20.700  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 03:49:20.701  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 03:49:20.701  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:20.701  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:20.701  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:20.701  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:20.702  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.702  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.702  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:20.702  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:20.702  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:20.702  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:20.702  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:20.702  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.702  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:20.702  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:20.704  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:49:20.704  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:20.704  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:20.704  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:20.704  3948  3998 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 03:49:20.707  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:20.715  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:49:20.719  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:20.719  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:49:20.719  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:49:20.719  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 03:49:20.719  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:49:20.720  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:20.720  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:49:20.721  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:20.723  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:49:20.724  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:49:20.724  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:20.730  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:49:20.731  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:49:20.732  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:49:20.734  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 03:49:20.736  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 03:49:20.736  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:49:20.736  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:49:20.737  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:49:20.738  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:49:20.742  2793  2865 D BtGatt.GattService: registerClient() - UUID=160e001d-93ab-451d-a5e3-9dec424bd768
,08-25 03:49:20.743  2793  2812 D BtGatt.GattService: onClientRegistered() - UUID=160e001d-93ab-451d-a5e3-9dec424bd768, clientIf=5
,08-25 03:49:20.744  3948  3960 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 03:49:20.746  2793  2873 D BtGatt.GattService: start scan with filters
,08-25 03:49:20.751  2793  2815 D BtGatt.ScanManager: handling starting scan
,08-25 03:49:20.751  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:49:20.752  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:49:20.752  2793  2815 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:49:20.752  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:49:20.752  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:49:20.755  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:49:20.755  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 03:49:20.755  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:49:20.756  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:49:20.759  2793  2812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 03:49:20.759  3948  3998 I io.jxcore.node.ConnectionHelper: start: OK
08-25 03:49:20.759  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:20.760  2793  2815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:49:20.765  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 03:49:20.765  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:20.765  2793  2815 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:49:20.765  2793  2815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 03:49:20.778  2793  2812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 03:49:20.779  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:20.785  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 03:49:20.785  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:21.257  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-25 03:49:21.257  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:49:21.258  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:49:22.292  2793  2793 D BtGatt.ScanManager: awakened up at time 117131
,08-25 03:49:22.297  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:22.325  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-25 03:49:22.325  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:22.326  2793  2812 D BtGatt.GattService: current time is 117165099157
,08-25 03:49:22.327  2793  2812 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-25 03:49:22.332  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-25 03:49:22.335  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-25 03:49:22.336  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-25 03:49:22.336  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-25 03:49:22.337  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-25 03:49:23.829  2793  2793 D BtGatt.ScanManager: awakened up at time 118667
,08-25 03:49:23.830  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:23.844  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:49:23.844  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:25.346  2793  2793 D BtGatt.ScanManager: awakened up at time 120184
,08-25 03:49:25.348  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:25.377  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-25 03:49:25.377  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:25.377  2793  2812 D BtGatt.GattService: current time is 120216323439
08-25 03:49:25.378  2793  2812 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -92, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -91, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,08-25 03:49:25.378  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-25 03:49:25.378  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-25 03:49:25.378  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-25 03:49:25.769  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:25.770  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:25.770  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 03:49:25.770  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:25.771  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:49:25.771  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:49:25.771  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 03:49:25.772  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:49:25.772  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 03:49:25.774  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:49:25.775  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 03:49:25.777  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:49:25.779  2793  2865 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:49:25.782  2793  2873 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:49:25.783  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 03:49:25.784  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:49:25.784  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:49:25.786  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:49:25.787  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 03:49:25.790  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:49:25.792  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:49:25.792  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,08-25 03:49:25.793  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,08-25 03:49:25.795  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:49:25.799  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:49:25.799  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:49:25.800  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:49:25.800  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:25.801  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:25.801  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:49:25.802  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:25.802  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:25.803  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:25.803  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 03:49:25.803  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:25.804  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:25.804  2793  2815 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:49:25.804  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:25.811  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 03:49:25.812  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:25.812  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:25.838  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
08-25 03:49:25.839  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:25.839  2793  2812 D BtGatt.GattService: current time is 120678022967
08-25 03:49:25.839  2793  2812 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 03:49:25.840  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-25 03:49:26.301  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:49:27.013   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 03:49:28.492   874  1879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:49:30.806  3948  3998 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 03:49:30.812  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:30.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:49:30.832  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:30.833  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:49:30.834  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 03:49:30.834  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 03:49:30.834  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 03:49:30.835  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:30.835  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:49:30.845  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:30.849  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:49:30.849  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 03:49:30.853  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:30.864  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:49:30.866  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:49:30.866  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:49:30.877  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:49:30.878  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 03:49:30.878  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 03:49:30.881  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:49:30.888  2793  2803 D BtGatt.GattService: registerClient() - UUID=652e5d69-7e38-47d5-96fe-83ed56a8cb01
,08-25 03:49:30.889  2793  2812 D BtGatt.GattService: onClientRegistered() - UUID=652e5d69-7e38-47d5-96fe-83ed56a8cb01, clientIf=5
08-25 03:49:30.891  3948  3959 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 03:49:30.893  2793  2865 D BtGatt.GattService: start scan with filters
,08-25 03:49:30.902  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 03:49:30.902  2793  2815 D BtGatt.ScanManager: handling starting scan
08-25 03:49:30.902  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:49:30.903  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:49:30.903  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:49:30.913  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:49:30.913  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:49:30.914  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:49:30.919  2793  2812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 03:49:30.920  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:30.920  2793  2815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 03:49:30.922  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:49:30.932  3948  3998 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 03:49:30.937  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:30.938  3948  3998 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 03:49:30.938  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:30.938  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything,
,08-25 03:49:30.938  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:30.938  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:49:30.938  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:49:30.938  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:49:30.938  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:49:30.938  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:49:30.938  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:49:30.938  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 03:49:30.939  3948  3998 D BluetoothAdapter: STATE_ON
08-25 03:49:30.940  2793  2803 D BtGatt.GattService: stopScan() - queue size =1
08-25 03:49:30.940  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 03:49:30.940  2793  2865 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 03:49:30.940  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.940  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:49:30.941  2793  2815 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:49:30.941  2793  2815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 03:49:30.941  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:49:30.941  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:49:30.941  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:49:30.941  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 03:49:30.942  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:49:30.943  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 03:49:30.943  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:49:30.943  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:49:30.943  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:49:30.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:30.946  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:30.946  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:49:30.946  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:49:30.946  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:30.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:30.947  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:30.946  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:49:30.947  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:30.947  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:30.947  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:49:30.947  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:30.947  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:30.948  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:30.948  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:30.949  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:30.949  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:30.949  3948  3998 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 03:49:30.951  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:30.959  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:30.961  2793  2812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 03:49:30.961  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.961  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:30.961  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:49:30.962  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:49:30.962  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:49:30.962  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:49:30.962  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:49:30.962  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:49:30.965  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:30.967  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:49:30.967  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:49:30.967  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:30.968  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 03:49:30.968  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.971  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 03:49:30.971  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 03:49:30.971  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 03:49:30.975  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 03:49:30.975  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:49:30.975  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:49:30.975  3948  3998 D BluetoothAdapter: STATE_ON
08-25 03:49:30.976  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 03:49:30.976  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.976  2793  2815 D BtGatt.ScanManager: stopping BLe Batch
08-25 03:49:30.977  2793  2803 D BtGatt.GattService: registerClient() - UUID=6c2a849d-b149-4e8a-be67-ed1a68f25eca
08-25 03:49:30.978  2793  2812 D BtGatt.GattService: onClientRegistered() - UUID=6c2a849d-b149-4e8a-be67-ed1a68f25eca, clientIf=5
08-25 03:49:30.979  3948  3960 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 03:49:30.979  2793  2865 D BtGatt.GattService: start scan with filters
08-25 03:49:30.982  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 03:49:30.982  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:49:30.982  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:49:30.982  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 03:49:30.983  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 03:49:30.983  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.983  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 03:49:30.984  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:49:30.985  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:49:30.985  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 03:49:30.986  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 03:49:30.989  3948  3998 I io.jxcore.node.ConnectionHelper: start: OK
08-25 03:49:30.989  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:49:30.989  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.991  2793  2815 D BtGatt.ScanManager: handling starting scan
08-25 03:49:30.997  2793  2812 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 03:49:30.997  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:30.997  2793  2815 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 03:49:31.004  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 03:49:31.004  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:31.004  2793  2815 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:49:31.004  2793  2815 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 03:49:31.015  2793  2812 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 03:49:31.015  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:31.023  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 03:49:31.023  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:31.486  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-25 03:49:31.486  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 03:49:31.486  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:49:32.502   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-25 03:49:32.528  2793  2793 D BtGatt.ScanManager: awakened up at time 127366
,08-25 03:49:32.533  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:32.553  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-25 03:49:32.553  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:32.553  2793  2812 D BtGatt.GattService: current time is 127392402386
08-25 03:49:32.554  2793  2812 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -92, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -89, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -91, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-25 03:49:32.554  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 03:49:32.554  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-25 03:49:32.555  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-25 03:49:32.555  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-25 03:49:32.555  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-25 03:49:34.061  2793  2793 D BtGatt.ScanManager: awakened up at time 128900
,08-25 03:49:34.063  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:34.127  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:49:34.127  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:34.393  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:34.405  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:34.407  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:34.458  1535  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:49:34.458  1535  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:49:34.459  1535  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:49:34.459  1535  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:34.524  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:49:34.527  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 03:49:34.528  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-25 03:49:35.304  2793  2793 D BtGatt.ScanManager: awakened up at time 130142
,08-25 03:49:35.305  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:35.323  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-25 03:49:35.323  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:35.324  2793  2812 D BtGatt.GattService: current time is 130162555524
08-25 03:49:35.324  2793  2812 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -91, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:49:35.325  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-25 03:49:35.371  3190  4015 V KeepSync: Connecting to GoogleApiClient
,08-25 03:49:35.372   874  1939 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 03:49:35.493  1535  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 03:49:35.493  1535  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 03:49:35.494  1535  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:35.494  1535  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:35.530   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-25 03:49:35.546  1750  4016 V BaseAuthAsyncOperation: access token request failed
,08-25 03:49:35.547  3190  4015 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 03:49:35.635  1535  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-25 03:49:35.635  1535  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 03:49:35.635  1535  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:35.635  1535  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:35.681  3190  4015 E KeepSync: IOException
08-25 03:49:35.681  3190  4015 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 03:49:35.681  3190  4015 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 03:49:35.681  3190  4015 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 03:49:35.681  3190  4015 E KeepSync: 	... 10 more
08-25 03:49:35.681  3190  4015 W KeepSync: Sync result 2
,08-25 03:49:35.696   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 130094, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:49:35.827  2793  2793 D BtGatt.ScanManager: awakened up at time 130666
,08-25 03:49:35.829  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:35.873  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-25 03:49:35.873  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:35.874  2793  2812 D BtGatt.GattService: current time is 130712575321
,08-25 03:49:35.874  2793  2812 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-25 03:49:35.875  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-25 03:49:35.876  2793  2812 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-25 03:49:35.990  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:35.990  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:35.990  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:49:35.991  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:35.991  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:49:35.992  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:49:35.992  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:49:35.992  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 03:49:35.992  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:49:35.993  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 03:49:35.993  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 03:49:35.999  3948  3998 D BluetoothAdapter: STATE_ON
08-25 03:49:36.001  2793  2803 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:49:36.003  2793  2804 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:49:36.005  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 03:49:36.005  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 03:49:36.006  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 03:49:36.007  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 03:49:36.008  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 03:49:36.014  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:49:36.014  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 03:49:36.014  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 03:49:36.015  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 03:49:36.016  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:49:36.019  2793  2812 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 03:49:36.020  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:49:36.020  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:49:36.020  2793  2815 D BtGatt.ScanManager: stopping BLe Batch
08-25 03:49:36.020  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:49:36.020  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:49:36.027  2793  2812 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:49:36.028  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:36.028  2793  2815 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:49:36.036  2793  2812 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:49:36.036  2793  2812 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:49:36.521  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:49:36.522  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:36.522  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:49:41.021  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:41.022  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:41.022  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.023  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.023  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:41.023  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:49:41.024  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.024  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:41.024  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.025  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:41.025  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.026  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:41.027  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.030  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.030  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.031  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.031  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.033  3948  3998 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-25 03:49:41.036  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.036  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:41.036  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.037  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.037  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.037  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.039  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:41.039  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:41.039  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.040  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.040  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.040  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.040  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.040  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.043  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:49:41.043  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.043  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.043  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.044  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 03:49:41.044  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:41.044  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:41.044  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:49:41.044  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:41.044  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.045  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.045  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:41.045  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.045  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.045  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.045  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.045  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.045  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.045  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.047  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:49:41.047  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:41.047  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.047  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.048  3948  3998 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 03:49:41.048  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:41.048  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:41.048  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.048  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.048  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:41.048  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.048  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.049  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.049  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.049  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:41.049  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.049  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.049  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.049  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.050  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:49:41.050  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:41.050  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.050  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.051  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 03:49:41.051  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:49:41.051  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:41.051  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.052  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:41.052  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.052  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.052  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.052  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:41.052  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.052  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.052  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.052  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.052  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.052  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.053  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.054  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-25 03:49:41.054  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:41.054  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.054  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:49:41.056  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:41.057  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:41.057  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:49:41.057  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:41.057  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:41.057  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:49:41.057  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:41.057  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:49:41.057  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.057  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:41.058  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.058  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:41.058  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.058  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.058  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.058  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.058  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.058  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.058  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.058  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.058  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.059  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.060  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.060  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.060  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.060  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.061  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:49:41.061  3948  3998 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 03:49:41.061  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 03:49:41.065  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:49:41.066  3948  3998 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-25 03:49:41.066  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 03:49:41.067  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 03:49:41.068  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-25 03:49:41.068  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 03:49:41.069  3948  3998 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:49:41.069  3948  3998 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 03:49:41.069  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:49:41.069  3948  3998 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:49:41.069  3948  3998 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 03:49:41.069  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 03:49:41.070  3948  3998 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:49:41.070  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 03:49:41.072  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 03:49:41.073  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 03:49:41.073  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-25 03:49:41.074  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 03:49:41.074  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 03:49:41.074  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 03:49:41.074  3948  3998 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:49:41.074  3948  3998 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 03:49:41.075  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.075  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:41.076  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.076  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.076  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.077  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.077  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 03:49:41.078  3948  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
08-25 03:49:41.079  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:41.079  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.079  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.079  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.079  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.081  3948  4017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:49:41.079  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.082  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:41.082  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.082  3948  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
08-25 03:49:41.082  3948  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 429)
08-25 03:49:41.083  3948  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 429)
08-25 03:49:41.083  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.083  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:41.083  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.083  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.084  3948  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
08-25 03:49:41.085  3948  3998 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 03:49:41.085  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.085  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:41.085  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:49:41.086  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.086  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.086  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.087  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.087  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.088  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.088  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:41.088  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.088  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.089  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.089  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.091  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.092  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.092  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:41.092  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.093  3948  3998 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 03:49:41.093  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.094  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:41.094  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.094  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.094  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.094  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.094  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.094  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.094  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.095  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.095  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.095  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.095  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:41.095  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.096  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.096  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.096  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.096  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.097  3948  3998 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 03:49:41.097  3948  3998 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-25 03:49:41.097  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:49:41.097  3948  3998 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 03:49:41.097  3948  3998 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:49:41.097  3948  3998 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 03:49:41.097  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:49:41.097  3948  3998 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-25 03:49:41.098  3948  3998 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:49:41.098  3948  3998 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 03:49:41.098  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:49:41.098  3948  3998 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 03:49:41.098  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:41.098  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:41.098  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:41.098  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.099  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.099  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.099  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.099  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.099  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:41.099  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.099  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.099  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:41.099  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.099  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.100  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:41.100  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:41.100  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.100  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.101  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:41.101  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.101  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:41.101  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:41.101  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:41.101  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:41.101  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:41.102  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:41.102  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:46.102  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:46.103  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.103  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:46.103  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.104  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:46.104  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.105  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:46.105  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:46.105  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:46.106  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:46.107  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.107  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:46.107  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.108  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.108  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:46.108  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:46.109  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.109  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:46.109  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.109  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.113  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:46.113  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:46.113  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.114  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:46.119  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-25 03:49:46.120  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:49:46.123  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-25 03:49:46.126  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 03:49:46.126  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 03:49:46.127  3948  3948 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 03:49:46.127  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 03:49:46.127  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:49:46.128  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:46.128  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 03:49:46.129  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-25 03:49:46.129  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 03:49:46.129  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.129  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-25 03:49:46.129  3948  4020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:49:46.130  3948  3948 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 03:49:46.130  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
,08-25 03:49:46.130  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.134  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:49:46.134  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 03:49:46.134  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:49:46.136  3948  4020 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 03:49:46.136  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:46.136  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.136  3948  4020 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-25 03:49:46.137  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:49:46.137  3948  4020 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-25 03:49:46.138  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:49:46.138  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:49:46.138  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:49:46.138  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.138  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:46.138  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:49:46.139  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:46.139  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:49:46.139  3948  3948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-25 03:49:46.139  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:46.139  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.139  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.139  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.140  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
,08-25 03:49:46.140  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:46.140  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.140  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.140  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.140  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.141  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:46.142  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:46.142  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.142  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.143  3948  3998 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 03:49:46.144  3948  3998 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 03:49:46.144  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:49:46.145  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 03:49:46.145  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:49:46.146  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:46.146  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:46.151  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:49:46.151  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-25 03:49:46.152  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:46.152  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.152  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.152  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.152  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.152  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:46.152  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.152  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.152  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.152  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.154  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:46.154  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:46.154  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.154  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.158  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:46.158  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:46.158  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:46.158  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:46.159  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:46.159  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.159  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.159  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.159  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.159  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:46.159  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.159  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.159  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.159  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.160  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:46.161  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:49:46.161  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.161  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.163  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:49:46.163  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:49:46.163  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:49:46.163  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:49:46.163  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.163  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.163  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99b150 not in the list
08-25 03:49:46.163  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.164  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.164  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:49:46.164  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:46.164  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.164  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:46.164  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:49:46.165  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:49:46.166  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:49:46.166  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:49:46.166  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c570f49 not in the list
08-25 03:49:46.167  3948  3998 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-25 03:49:46.167  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:49:46.167  3948  3998 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 03:49:46.167  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:49:46.167  3948  3998 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 03:49:46.168  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-25 03:49:46.170  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 03:49:46.170  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 03:49:46.171  3948  3998 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 03:49:46.172  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-25 03:49:46.172  3948  3998 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 03:49:46.172  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 03:49:46.172  3948  3998 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 03:49:46.172  3948  3998 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-25 03:49:46.173  3948  3998 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 03:49:46.173  3948  3998 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 03:49:46.174  3948  3998 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-25 03:49:46.174  3948  3998 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 03:49:46.174  3948  3998 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 03:49:46.174  3948  3998 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-25 03:49:46.175  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:49:46.175  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c0df03 added. We now have 3 listener(s)
08-25 03:49:46.175  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:49:46.177  3948  3998 D BluetoothAdapter: enable(): BT is already enabled..!
,08-25 03:49:46.178   874  1932 D WifiService: setWifiEnabled: true pid=3948, uid=10000
08-25 03:49:46.178   874  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:49:46.216  2793  2859 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-25 03:49:46.217  2793  2861 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-25 03:49:46.639  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:49:51.185  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:49:51.185  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f640e80 added. We now have 4 listener(s)
08-25 03:49:51.186  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:49:51.202  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:51.204  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f640e80 removed from the list
08-25 03:49:51.204  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:51.205  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:49:51.205  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:51.207  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:49:51.208  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1055cb9 added. We now have 4 listener(s)
,08-25 03:49:51.208  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:49:51.213  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:49:51.213  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1055cb9 removed from the list
08-25 03:49:51.213  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:49:51.214  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:49:51.214  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:49:51.216  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:49:51.217  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19f08fe added. We now have 4 listener(s)
08-25 03:49:51.218  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:49:51.225   874  1399 D WifiService: setWifiEnabled: false pid=3948, uid=10000
,08-25 03:49:51.225   874  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:49:51.235  2793  2808 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 03:49:51.235  2793  2808 D BluetoothAdapterProperties: Setting state to 13
08-25 03:49:51.236  2793  2808 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 03:49:51.238  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:49:51.242  2793  2808 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 03:49:51.246  2793  2808 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:49:51.248  2793  2793 D BluetoothMapService: onReceive
08-25 03:49:51.248  2793  2793 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:49:51.249  2793  2793 D BluetoothMapService: STATE_TURNING_OFF
08-25 03:49:51.249  2793  2793 D BluetoothMapService: MAP Service closeService in
08-25 03:49:51.249  2793  2793 D BluetoothMapMasInstance0: MAP Service shutdown
,08-25 03:49:51.249  2793  2793 D ObexServerSockets0: shutdown(block = true)
08-25 03:49:51.251  2793  2793 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:49:51.252  2793  2878 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 03:49:51.253  2793  2877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 03:49:51.255  2793  2861 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 03:49:51.256  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:51.256  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:51.257  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.257  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:51.257  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:49:51.258  2793  2793 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 03:49:51.258  2793  2793 I BtOppRfcommListener: stopping Accept Thread
08-25 03:49:51.258  2793  3573 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:49:51.259  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 03:49:51.265  2793  3573 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 03:49:51.265   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 03:49:51.265   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 03:49:51.265   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:49:51.265  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:51.265   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:49:51.268  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:51.272  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:51.272  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:51.274  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:51.274  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:51.278  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:51.278  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:51.279  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.279   874   887 I ActivityManager: Start proc 4025:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-25 03:49:51.279  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:51.280  2793  2812 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:49:51.280  2793  2808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 03:49:51.283  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.285  2793  2793 D HeadsetService: Received stop request...Stopping profile...
08-25 03:49:51.286  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.286   874  1880 D DhcpClient: Clearing IP address
,08-25 03:49:51.286   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:49:51.288   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 03:49:51.288   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 03:49:51.289   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 03:49:51.289  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.289  1356  1373 D BluetoothHeadset: Proxy object disconnected
08-25 03:49:51.290  1926  2048 D BluetoothHeadset: Proxy object disconnected
08-25 03:49:51.290   372   872 D CommandListener: Setting iface cfg
08-25 03:49:51.290  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-25 03:49:51.290  2793  2793 D A2dpService: Received stop request...Stopping profile...
08-25 03:49:51.291  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:51.291  2793  2867 D A2dpStateMachine: Exit Disconnected: -1
,08-25 03:49:51.292   874   874 D BluetoothA2dp: Proxy object disconnected
08-25 03:49:51.292  1535  2107 V NativeCrypto: Read error: ssl=0xaa1fc800: I/O error during system call, Connection timed out
08-25 03:49:51.294  1535  2107 V NativeCrypto: SSL shutdown failed: ssl=0xaa1fc800: I/O error during system call, Broken pipe
08-25 03:49:51.295   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 03:49:51.295   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 03:49:51.297   395   395 E Parcel  : Reading a NULL string not supported here.
08-25 03:49:51.297  2793  2793 D HidService: Received stop request...Stopping profile...
08-25 03:49:51.297  2793  2793 D HidService: Stopping Bluetooth HidService
08-25 03:49:51.299   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-25 03:49:51.299  2793  2793 D HealthService: Received stop request...Stopping profile...
08-25 03:49:51.300   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:49:51.306  2793  2793 D PanService: Received stop request...Stopping profile...
08-25 03:49:51.307   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:49:51.308  2793  2793 V BluetoothAdapterState: isTurningOff()=true
08-25 03:49:51.308  1356  1356 D BluetoothA2dp: Proxy object disconnected
08-25 03:49:51.308   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 03:49:51.308  1356  1356 D BluetoothInputDevice: Proxy object disconnected
08-25 03:49:51.308  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.309  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.309  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:49:51.308  1356  1356 D HidProfile: Bluetooth service disconnected
08-25 03:49:51.314  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:49:51.314  1356  1356 D PanProfile: Bluetooth service disconnected
08-25 03:49:51.315  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:49:51.315  2793  2812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 03:49:51.315  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.315  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.315  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.315  2793  2812 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 03:49:51.316  2793  2793 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:49:51.318   874  1882 D DhcpClient: Receive thread stopped
08-25 03:49:51.318  2793  2793 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 03:49:51.318  2793  2793 D BluetoothMapService: stop()
08-25 03:49:51.318  2793  2793 D BluetoothMapAppObserver: deinitObservers()
08-25 03:49:51.318  2793  2793 D BluetoothMapAppObserver: removeReceiver()
08-25 03:49:51.320  2793  2793 V BluetoothAdapterState: isTurningOff()=true
08-25 03:49:51.320  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.320  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.320  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:49:51.321  2793  2812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 03:49:51.321  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.321  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.322  2793  2859 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:49:51.322  2793  2859 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 03:49:51.322  2793  2859 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:49:51.322  2793  2859 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:49:51.322  1356  1356 D BluetoothMap: Proxy object disconnected
08-25 03:49:51.322  1356  1356 D MapProfile: Bluetooth service disconnected
08-25 03:49:51.322  2793  2793 V BluetoothAdapterState: isTurningOff()=true
08-25 03:49:51.322  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.322  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.322  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:49:51.323  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:49:51.323  2793  2793 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 03:49:51.323  2793  2793 V BluetoothAdapterState: isTurningOff()=true
,08-25 03:49:51.323  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.323  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.323  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:49:51.323  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 03:49:51.323  2793  2812 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:49:51.323  2793  2812 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 03:49:51.323   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 03:49:51.324  2793  2793 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:49:51.324  2793  2793 V BluetoothAdapterState: isTurningOff()=true
08-25 03:49:51.324  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.324  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.325  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:49:51.325  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 03:49:51.325  2793  2793 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:49:51.327   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 03:49:51.327  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:51.327  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:49:51.327  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.327  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:49:51.329  2793  2793 D BluetoothMapService: MAP Service closeService in
08-25 03:49:51.329  2793  2793 V BluetoothAdapterState: isTurningOff()=true
08-25 03:49:51.329  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.329  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.329  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:51.329  2793  2793 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:51.329  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:49:51.329  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.329  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:49:51.331  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:51.331  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:49:51.331  2793  2808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 03:49:51.332  2793  2808 D BluetoothAdapterProperties: Setting state to 15
08-25 03:49:51.332  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:51.332  2793  2808 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 03:49:51.332  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:49:51.334  2793  2793 D BluetoothMapService: cleanup()
08-25 03:49:51.334  2793  2793 D BluetoothMapService: MAP Service closeService in
08-25 03:49:51.337  2793  2808 I BluetoothAdapterState: Entering BleOnState
08-25 03:49:51.343   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:49:51.344  1356  1373 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:49:51.345  1356  2186 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:49:51.346  1356  1371 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:49:51.348  1356  4011 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 03:49:51.348   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:49:51.348  1356  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:49:51.349  1926  1940 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:49:51.349   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:49:51.349  1356  2186 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:49:51.350   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:49:51.350  2793  2808 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 03:49:51.350  2793  2808 D BluetoothAdapterProperties: Setting state to 16
08-25 03:49:51.350  2793  2808 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 03:49:51.351  2793  2808 D BluetoothAdapterProperties: onBleDisable
08-25 03:49:51.351  2793  2808 I BluetoothAdapterState: Entering PendingCommandState
08-25 03:49:51.351  2793  2809 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 03:49:51.352  2793  2859 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 03:49:51.352  2793  2859 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:49:51.352  2793  2812 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:49:51.353  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:51.354  2117  2328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:49:51.354  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.355  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.357  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.358  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.358   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 03:49:51.359  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.359   874   883 I art     : Background partial concurrent mark sweep GC freed 53049(3MB) AllocSpace objects, 18(484KB) LOS objects, 33% free, 29MB/44MB, paused 1.371ms total 112.258ms
,08-25 03:49:51.373  4025  4025 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 03:49:51.379   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 03:49:51.380   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 03:49:51.380   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:49:51.382   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-25 03:49:51.384  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.385  3580  3580 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@57e6a14 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 03:49:51.385  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:49:51.386  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:49:51.395  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:49:51.399  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:49:51.401   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e7015b:true
,08-25 03:49:51.412   874  2077 I ActivityManager: Start proc 4045:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 03:49:51.420  4025  4025 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 03:49:51.421   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-25 03:49:51.424  4025  4025 D BluetoothMap: Create BluetoothMap proxy object
,08-25 03:49:51.428  4025  4025 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 03:49:51.439  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:49:51.444   874  1939 I ActivityManager: Killing 3172:com.google.android.talk/u0a61 (adj 15): empty #17
,08-25 03:49:51.453  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 03:49:51.556  2793  2812 I bt_hci  : shut_down
,08-25 03:49:51.556  2793  2816 D bt_hwcfg: hw_epilog_process
08-25 03:49:51.557  2793  2816 I bt_vendor: low_power_mode_cb
,08-25 03:49:51.580  2793  2816 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 03:49:51.581  2793  2816 I bt_vendor: epilog_cb
08-25 03:49:51.581  2793  2816 I bt_hci  : epilog_finished_callback
,08-25 03:49:51.586  2793  2812 I bt_hci_h4: hal_close
08-25 03:49:51.587  2793  2812 I bt_userial_vendor: device fd = 51 close
,08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.642  4045  4045 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.642  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.643  4045  4045 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.643  4045  4045 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:49:51.643  4045  4045 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:49:51.669   874  2630 I ActivityManager: Start proc 4075:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-25 03:49:51.670   874  2630 I ActivityManager: Killing 3716:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 03:49:51.750  2793  2809 D bt_stack_manager: event_shut_down_stack finished.
,08-25 03:49:51.751  2793  2808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-25 03:49:51.753  2793  2808 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-25 03:49:51.754  2793  2793 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:49:51.755  2793  2793 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 03:49:51.755  2793  2793 D BtGatt.GattService: stop()
08-25 03:49:51.755  2793  2793 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 03:49:51.759  2793  2793 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:49:51.759  2793  2793 V BluetoothAdapterState: isTurningOn()=false
08-25 03:49:51.759  2793  2793 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:49:51.760  2793  2793 V BluetoothAdapterState: isBleTurningOff()=true
08-25 03:49:51.760  2793  2808 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 03:49:51.760  2793  2808 D BluetoothAdapterProperties: Setting state to 10
08-25 03:49:51.760  2793  2808 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 03:49:51.761  2793  2808 I BluetoothAdapterState: Entering OffState
08-25 03:49:51.761   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 03:49:51.770  2793  2793 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 03:49:51.770  2793  2793 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 03:49:51.770  2793  2793 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 03:49:51.771  2793  2809 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 03:49:51.773  2793  2809 D bt_stack_manager: event_clean_up_stack finished.
,08-25 03:49:51.779  4075  4075 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 03:49:51.785  2793  2793 I art     : System.exit called, status: 0
,08-25 03:49:51.785  2793  2793 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 03:49:51.860   874  2630 I ActivityManager: Process com.android.bluetooth (pid 2793) has died
,08-25 03:49:52.025  4075  4095 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 03:49:52.025  4075  4095 I Babel_SMS: MmsConfig.loadMmsSettings
08-25 03:49:52.027  4075  4095 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-25 03:49:52.027  4075  4095 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 03:49:52.105  4075  4095 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 03:49:52.105  4075  4095 I Babel_SMS: MmsConfig.loadFromResources
,08-25 03:49:52.108  4075  4095 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 03:49:52.109  4075  4095 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 03:49:52.111  4075  4075 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:49:52.113  4075  4075 I Babel_Crash: startup - clean
,08-25 03:49:52.141  4075  4075 I Babel_telephony: TeleModule.launchCompleted
,08-25 03:49:52.152   874  2630 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 03:49:52.165  4075  4075 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 03:49:52.174  4075  4075 W Babel   : BAM#gBA: invalid account id: -1
,08-25 03:49:52.174  4075  4075 W Babel   : BAM#gBA: invalid account id: -1
08-25 03:49:52.174  4075  4075 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 03:49:52.185   874  1971 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
08-25 03:49:52.187  4075  4101 I Babel   : deleted: false for 0
,08-25 03:49:52.211   874  1965 I ActivityManager: Start proc 4103:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 03:49:52.278  4075  4075 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:49:52.280  4103  4103 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 03:49:52.287  4045  4065 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 03:49:52.350  4075  4075 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 03:49:52.362  4075  4075 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 03:49:52.364  4075  4075 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:49:52.383  4103  4103 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 03:49:52.387  4075  4075 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:49:52.406  4075  4075 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 03:49:52.411  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:49:52.432   874  1965 I ActivityManager: Start proc 4128:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 03:49:52.438  4075  4075 I vclib   : onServiceConnected
,08-25 03:49:52.446  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:49:52.454   874  1932 I ActivityManager: Killing 3580:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 03:49:52.507   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e8a4b3:true
,08-25 03:49:52.629  4128  4128 D AdapterServiceConfig: Adding HeadsetService
,08-25 03:49:52.629  4128  4128 D AdapterServiceConfig: Adding A2dpService
08-25 03:49:52.629  4128  4128 D AdapterServiceConfig: Adding HidService
,08-25 03:49:52.629  4128  4128 D AdapterServiceConfig: Adding HealthService
08-25 03:49:52.629  4128  4128 D AdapterServiceConfig: Adding PanService
08-25 03:49:52.630  4128  4128 D AdapterServiceConfig: Adding GattService
08-25 03:49:52.630  4128  4128 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 03:49:52.633   874  1965 I ActivityManager: Killing 3371:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 03:49:52.672  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:49:52.687  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:49:52.695  1750  1750 D SystemUpdateService: onCreate
,08-25 03:49:52.697  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:49:52.702  1750  4140 I SystemUpdateService: active receiver: enabled
,08-25 03:49:52.708  1750  4140 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:49:52.720  1750  4140 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 03:49:52.721  1750  4140 I SystemUpdateService: now status is 0 (complete)
08-25 03:49:52.722  1750  4140 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:49:52.722  1750  4140 I SystemUpdateService: file has been verified
,08-25 03:49:52.722  1750  4140 I SystemUpdateService: OTA package size = 12249756
,08-25 03:49:52.724  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-25 03:49:52.726  1750  2426 I iu.UploadsManager: num queued entries: 0
08-25 03:49:52.726  1750  2426 I iu.UploadsManager: num updated entries: 0
,08-25 03:49:52.728  1750  2426 I iu.SyncManager: NEXT; no task
,08-25 03:49:52.730  1750  4140 I SystemUpdateService: showing system update notification
,08-25 03:49:52.740  1750  1750 D SystemUpdateService: onDestroy
,08-25 03:49:52.746  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:49:52.747  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:49:52.762   874  1965 I ActivityManager: Start proc 4142:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 03:49:52.796  4142  4142 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 03:49:52.799  4142  4142 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:49:52.803  4142  4142 D SprintDMHelper: simOperator: 
08-25 03:49:52.803  4142  4142 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:49:52.823   874   885 I ActivityManager: Start proc 4154:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 03:49:52.824   874   885 I ActivityManager: Killing 3643:android.process.acore/u0a5 (adj 15): empty #17
,08-25 03:49:53.022   874   884 I ActivityManager: Start proc 4169:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 03:49:53.026  4075  4168 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 03:49:53.030   874  1965 I ActivityManager: Killing 3811:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 03:49:53.093  4169  4169 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 03:49:53.154  4169  4169 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 03:49:53.154  4169  4169 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 03:49:53.154  4169  4169 I GAv4    :   adb logcat -s GAv4
,08-25 03:49:53.171  4169  4169 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 03:49:53.177  4169  4169 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-25 03:49:53.208  4169  4186 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 03:49:53.328  4169  4169 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 03:49:53.370  4169  4169 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 03:49:53.382  4169  4169 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8214-8220)
,08-25 03:49:53.382  4169  4169 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 03:49:53.393  4169  4169 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {91a8044}
,08-25 03:49:53.394  4169  4169 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 03:49:53.394  4169  4169 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 03:49:53.403  4169  4169 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 03:49:53.404  4169  4169 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 03:49:53.423  4169  4169 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 03:49:53.436  4169  4169 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 03:49:53.436  4169  4169 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 03:49:53.436  4169  4169 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:49:53.436  4169  4169 I Adreno  : Build Date                       : 10/20/15
08-25 03:49:53.436  4169  4169 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:49:53.436  4169  4169 I Adreno  : Local Branch                     : M14
08-25 03:49:53.436  4169  4169 I Adreno  : Remote Branch                    : 
08-25 03:49:53.436  4169  4169 I Adreno  : Remote Branch                    : 
08-25 03:49:53.436  4169  4169 I Adreno  : Reconstruct Branch               : 
,08-25 03:49:53.484  4169  4216 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 03:49:53.503  4169  4169 I NSApplication: Starting up...
,08-25 03:49:53.544   874  1939 I ActivityManager: Start proc 4221:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 03:49:53.546   874  1939 I ActivityManager: Killing 3826:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 03:49:53.616  4221  4221 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 03:49:53.827   874  1937 I ActivityManager: Killing 2241:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 03:49:55.412   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 03:49:55.428  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 03:49:55.436   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 03:49:55.436   874   894 I Adreno  : Build Date                       : 10/20/15
08-25 03:49:55.436   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 03:49:55.436   874   894 I Adreno  : Local Branch                     : M14
08-25 03:49:55.436   874   894 I Adreno  : Remote Branch                    : 
08-25 03:49:55.436   874   894 I Adreno  : Remote Branch                    : 
08-25 03:49:55.436   874   894 I Adreno  : Reconstruct Branch               : 
,08-25 03:49:55.469   281   348 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
,08-25 03:49:56.099  3948  3948 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 03:49:56.100  3948  3948 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 03:49:56.136   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 03:49:56.138  3948  3948 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d7aa566 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@63b92ac, 16908290=android.view.AbsSavedState$1@63b92ac}, android:focusedViewId=100}]}],
,08-25 03:49:56.138  3948  3948 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 03:49:56.139  3948  3948 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 03:49:56.139  3948  3948 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-25 03:49:56.142   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 03:49:56.152   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-25 03:49:56.152   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 03:49:56.154   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 03:49:56.259   874  1937 D WifiService: setWifiEnabled: true pid=3948, uid=10000
,08-25 03:49:56.259   874  1937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:49:56.274   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-25 03:49:56.284  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:56.284  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:49:56.284  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:56.284  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:49:56.287  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:56.287  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:49:56.287  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:56.288  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:49:56.290  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:49:56.290  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:49:56.290  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:56.290  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:49:56.296   874  1316 D WifiConfigStore: loaded 0 passpoint configs
08-25 03:49:56.297   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 03:49:56.298   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 03:49:56.309   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 03:49:56.310   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 03:49:56.310   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 03:49:56.310   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 03:49:56.340   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 03:49:56.340   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.75 rxSuccessRate=12.12 delta 1000 -> 994
,08-25 03:49:56.341   372   872 D CommandListener: Setting iface cfg
08-25 03:49:56.342   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 03:49:56.342   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 03:49:56.352   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
08-25 03:49:56.353   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 03:49:56.355   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 03:49:56.355   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:49:56.364   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 03:49:56.370   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 03:49:56.372   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-25 03:49:56.373   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 221ms
,08-25 03:49:56.376   874   894 I DreamManagerService: Entering dreamland.
,08-25 03:49:56.376   874   894 I PowerManagerService: Dozing...
,08-25 03:49:56.377   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 03:49:56.422   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 03:49:56.422   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-25 03:49:56.435  1909  4247 D NfcService: Discovery configuration equal, not updating.
,08-25 03:49:56.457   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 03:49:56.459  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 03:49:56.481   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:49:56.497   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:49:56.499  1474  1474 E wpa_supplicant: PNO: In assoc process
08-25 03:49:56.500   874  1316 E WifiStateMachine:  Fail to set up pno, want true now false
,08-25 03:49:56.516   874  1316 E native  : do suspend false
,08-25 03:49:56.526   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
08-25 03:49:56.528   874  1316 E native  : do suspend true
,08-25 03:49:56.560   376  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 03:49:56.561   376  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 03:49:56.869  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 03:49:56.909  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:49:56.909  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 03:49:56.910   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:49:56.919   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:49:56.919   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:49:56.919   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 03:49:56.937   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:49:56.949   372   872 D CommandListener: Setting iface cfg
,08-25 03:49:56.951   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 03:49:56.956   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 03:49:56.985   874  4253 D DhcpClient: Receive thread started
,08-25 03:49:57.067   874  1316 E native  : do suspend false
,08-25 03:49:57.088   874  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 03:49:57.118   874  4253 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172669, domain null
,08-25 03:49:57.119   874  1880 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172669 seconds
,08-25 03:49:57.123   874  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 03:49:57.138   874  4253 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-25 03:49:57.140   874  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 03:49:57.145   372   872 D CommandListener: Setting iface cfg
,08-25 03:49:57.157   874  1880 D DhcpClient: Scheduling renewal in 86399s
,08-25 03:49:57.158   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-25 03:49:57.160   874  1316 E native  : do suspend true
,08-25 03:49:57.178   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 03:49:57.179   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 03:49:57.180   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 03:49:57.181   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 03:49:57.182   874  1319 D ConnectivityService: Adding iface wlan0 to network 101
08-25 03:49:57.183   874  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,08-25 03:49:57.225   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 03:49:57.225   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 03:49:57.227   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-25 03:49:57.228   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 03:49:57.229   874  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 03:49:57.236   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 03:49:57.242   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-25 03:49:57.242   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 03:49:57.243   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 03:49:57.243   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:49:57.244   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 03:49:57.244   874  1319 D ConnectivityService:    accepting network in place of null
,08-25 03:49:57.245   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:49:57.256   874  4252 D NetlinkSocketObserver: NeighborEvent{elapsedMs=152094, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:49:57.268   874  2077 I ActivityManager: Killing 3849:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 03:49:57.298   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:49:57.330   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:49:57.334   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 03:49:57.334   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:49:57.368   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 03:49:57.373   874   891 D Tethering: MasterInitialState.processMessage what=3
08-25 03:49:57.381   874   887 W BroadcastQueue: Failure sending broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 03:49:57.381   874   887 W BroadcastQueue: android.os.RemoteException: app.thread must not be null
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:457)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:594)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:667)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:49:57.381   874   887 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 03:49:57.386  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:57.387  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:57.387  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:57.387  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:57.391  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:57.391  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:57.391  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:57.392  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:57.398  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:49:57.398  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:49:57.399  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:49:57.399  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:49:57.404  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:49:57.412  1750  1750 D SystemUpdateService: onCreate
,08-25 03:49:57.418  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:49:57.448  1750  4262 I SystemUpdateService: active receiver: enabled
,08-25 03:49:57.448  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 03:49:57.452  1750  2426 I iu.UploadsManager: num queued entries: 0
08-25 03:49:57.452  1750  2426 I iu.UploadsManager: num updated entries: 0
,08-25 03:49:57.475  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:49:57.476  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 03:49:57.478  4142  4142 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:49:57.500  1750  4266 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 03:49:57.500  1750  4266 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 03:49:57.503  1750  4266 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 03:49:57.509  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 03:49:57.511  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:49:57.515  1750  2426 I iu.SyncManager: NEXT; no task
,08-25 03:49:57.517  1750  4262 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:49:57.522  4142  4142 D SprintDMHelper: simOperator: 
,08-25 03:49:57.522  4142  4142 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:49:57.542  1750  4262 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 03:49:57.545  1750  4262 I SystemUpdateService: now status is 0 (complete)
,08-25 03:49:57.545  1750  4262 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:49:57.545  1750  4262 I SystemUpdateService: file has been verified
,08-25 03:49:57.546  1750  4262 I SystemUpdateService: OTA package size = 12249756
,08-25 03:49:57.567  1535  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-25 03:49:57.568  1535  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 03:49:57.572  1535  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:49:57.572  1535  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:57.584  1750  4262 I SystemUpdateService: showing system update notification
,08-25 03:49:57.603  1750  4266 E MDM     : [176] SitrepService.a: Error sending sitrep.,
,08-25 03:49:57.641  1535  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:49:57.641  1535  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 03:49:57.641  1535  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:57.641  1535  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 03:49:57.645  4075  4269 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 03:49:57.663  3699  4267 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:49:57.663  3699  4267 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:49:57.663  3699  4267 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	... 12 more
08-25 03:49:57.663  3699  4267 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at fal.a(PG:38)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:49:57.663  3699  4267 E HttpOperation: 	... 14 more
,08-25 03:49:57.701  1750  1750 D SystemUpdateService: onDestroy
,08-25 03:49:57.720  1535  2083 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:49:57.720  1535  2083 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:49:57.721  1535  2083 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:49:57.721  1535  2083 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:49:57.733   874  1399 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-25 03:49:57.733  3699  4267 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:49:57.733  3699  4267 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at hec.a(PG:42)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at hee.a(PG:102)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at czr.a(PG:65)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at kka.a(PG:108)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:49:57.733  3699  4267 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	... 15 more
08-25 03:49:57.733  3699  4267 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at fal.a(PG:38)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:49:57.733  3699  4267 E HttpOperation: 	... 17 more
08-25 03:49:57.733  3699  4267 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:49:57.733  3699  4267 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	... 15 more
08-25 03:49:57.733  3699  4267 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:49:57.733  3699  4267 E ExperimentLoader: 	... 17 more
,08-25 03:49:57.739   874  1971 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-25 03:49:57.741   874  1932 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-25 03:49:57.745   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.83,2a00:1450:400d:802::200e
,08-25 03:49:57.771   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:49:57 GMT], X-Android-Received-Millis=[1472089797771], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472089797765]}
,08-25 03:49:57.772   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 03:49:57.772   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 03:49:57.772   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.83,2a00:1450:400d:802::200e
08-25 03:49:57.772   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 03:49:57.772   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 03:49:57.773   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 03:49:57.777   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:49:57 GMT], X-Android-Received-Millis=[1472089797777], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472089797774]}
,08-25 03:49:57.782   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 03:49:57.782   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-25 03:49:57.852   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 133317, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:49:58.334   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 03:50:00.683  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:00.742  1535  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 03:50:00.742  1535  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 03:50:00.742  1535  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:00.743  1535  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:00.777  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 03:50:00.777  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 03:50:00.778  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-25 03:50:01.264   874  1971 D WifiService: setWifiEnabled: false pid=3948, uid=10000
08-25 03:50:01.264   874  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:50:01.302  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 03:50:01.310   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 03:50:01.311   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 03:50:01.311   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 03:50:01.312   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:50:01.347   874  1316 E native  : do suspend true
,08-25 03:50:01.366   874  1880 D DhcpClient: Clearing IP address
,08-25 03:50:01.367   372   872 D CommandListener: Setting iface cfg
,08-25 03:50:01.372   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-25 03:50:01.375   874  4253 D DhcpClient: Receive thread stopped
08-25 03:50:01.375  1535  4271 V NativeCrypto: Read error: ssl=0x9a24ca00: I/O error during system call, Connection timed out
08-25 03:50:01.378  1535  4271 V NativeCrypto: SSL shutdown failed: ssl=0x9a24ca00: I/O error during system call, Broken pipe
,08-25 03:50:01.382   874  1399 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-25 03:50:01.383   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 03:50:01.388   874  4251 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 03:50:01.390   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-25 03:50:01.390   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 03:50:01.398   395   395 E Parcel  : Reading a NULL string not supported here.
,08-25 03:50:01.401   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 03:50:01.403   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-25 03:50:01.403   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 03:50:01.403   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-25 03:50:01.404   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:50:01.404   874  1316 E native  : do suspend true
,08-25 03:50:01.411   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 03:50:01.441   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:50:01.470   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:50:01.473   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 03:50:01.473   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:50:01.474   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-25 03:50:01.478   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-25 03:50:01.491   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:50:01.494  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.495  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:01.495  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.495  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:01.499  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.499  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:01.500  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:01.501  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:01.505  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.505  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:01.506  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.506  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:01.511   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:50:01.514  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.514  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:01.514  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:01.514  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:01.515  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.516  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:01.516  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.516  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:01.516  2117  2328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:50:01.517  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:01.517  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:01.518  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:01.518  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:01.519   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 03:50:01.525  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:50:01.530  1750  1750 D SystemUpdateService: onCreate
,08-25 03:50:01.535  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:50:01.544  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 03:50:01.546  1750  2426 I iu.UploadsManager: num queued entries: 0
,08-25 03:50:01.546  1750  2426 I iu.UploadsManager: num updated entries: 0
,08-25 03:50:01.547  1750  2426 I iu.SyncManager: NEXT; no task
,08-25 03:50:01.550  1750  4288 I SystemUpdateService: active receiver: enabled
,08-25 03:50:01.552  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:50:01.554  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:50:01.556  4142  4142 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:50:01.560  4142  4142 D SprintDMHelper: simOperator: 
,08-25 03:50:01.560  4142  4142 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-25 03:50:01.560  1750  4288 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 03:50:01.573   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-25 03:50:01.575   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 03:50:01.579  4075  4292 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 03:50:01.580  1750  4288 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 03:50:01.590  1750  4288 I SystemUpdateService: now status is 0 (complete)
,08-25 03:50:01.590  1750  4288 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:50:01.590  1750  4288 I SystemUpdateService: file has been verified
08-25 03:50:01.591  1750  4288 I SystemUpdateService: OTA package size = 12249756
,08-25 03:50:01.609  1750  4288 I SystemUpdateService: showing system update notification
,08-25 03:50:01.619  1750  1750 D SystemUpdateService: onDestroy
,08-25 03:50:02.753  2117  2771 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 03:50:05.246   874  1319 D ConnectivityService: handlePromptUnvalidated 101
,08-25 03:50:06.302   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f785dd:true
,08-25 03:50:06.304  4128  4128 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 03:50:06.313  4128  4128 I bt_bluedroid: init
08-25 03:50:06.314  4128  4295 I BluetoothAdapterState: Entering OffState
,08-25 03:50:06.320  4128  4296 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 03:50:06.320  4128  4296 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 03:50:06.320  4128  4296 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:50:06.321  4128  4296 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 03:50:06.323  4128  4128 I bt_bluedroid: get_profile_interface socket
,08-25 03:50:06.326  4128  4299 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:50:06.328  4128  4299 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:50:06.329  4128  4128 I bt_bluedroid: get_profile_interface sdp
,08-25 03:50:06.340  4128  4139 I bt_bluedroid: config_hci_snoop_log
,08-25 03:50:06.345   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 03:50:06.353  4128  4295 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 03:50:06.354  4128  4295 D BluetoothAdapterProperties: Setting state to 14
08-25 03:50:06.354  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 03:50:06.356  4128  4295 D BluetoothBondStateMachine: make
,08-25 03:50:06.360  4128  4300 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 03:50:06.363  4128  4295 I BluetoothAdapterState: Entering PendingCommandState
08-25 03:50:06.364  4128  4128 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 03:50:06.368  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:06.369  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:50:06.370  4128  4128 D BtGatt.GattService: Received start request. Starting profile...
08-25 03:50:06.370  4128  4128 D BtGatt.GattService: start()
,08-25 03:50:06.370  4128  4128 I bt_bluedroid: get_profile_interface gatt
,08-25 03:50:06.372  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:50:06.372  4128  4128 D BtGatt.AdvertiseManager: advertise manager created
,08-25 03:50:06.381  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:50:06.382  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:06.382  4128  4128 V BluetoothAdapterState: isBleTurningOn()=true
08-25 03:50:06.382  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:06.382  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 03:50:06.383  4128  4295 I bt_bluedroid: enable
,08-25 03:50:06.383  4128  4296 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 03:50:06.384  4128  4296 I bt_hci  : start_up
,08-25 03:50:06.402  4128  4296 I bt_vendor: alloc value 0xb3969189
,08-25 03:50:06.402  4128  4296 I bt_vendor: init
08-25 03:50:06.402  4128  4296 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 03:50:06.402  4128  4296 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 03:50:06.510  4128  4296 D bt_hci  : start_up starting async portion
,08-25 03:50:06.511  4128  4303 I bt_hci  : event_finish_startup
08-25 03:50:06.511  4128  4303 I bt_hci_h4: hal_open
08-25 03:50:06.512  4128  4303 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 03:50:06.520  4128  4303 I bt_userial_vendor: device fd = 51 open
,08-25 03:50:06.552  4128  4303 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:50:06.584  4128  4303 D bt_hwcfg: Chipset BCM4354A2
,08-25 03:50:06.585  4128  4303 D bt_hwcfg: Target name = [BCM4354A2]
08-25 03:50:06.585  4128  4303 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 03:50:07.277  4128  4303 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 03:50:07.278  4128  4303 D bt_hwcfg: Settlement delay -- 100 ms
08-25 03:50:07.279  4128  4303 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 03:50:07.396  4128  4303 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:50:07.397  4128  4303 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 03:50:07.425  4128  4303 I bt_hwcfg: vendor lib fwcfg completed
,08-25 03:50:07.425  4128  4303 I bt_vendor: firmware callback
,08-25 03:50:07.426  4128  4303 I bt_hci  : firmware_config_callback
,08-25 03:50:07.439  4128  4307 I bt_btu  : btu_task pending for preload complete event
,08-25 03:50:07.439  4128  4307 I bt_btu_task: Bluetooth chip preload is complete
08-25 03:50:07.439  4128  4307 I bt_btu  : btu_task received preload complete event
,08-25 03:50:07.451  4128  4307 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 03:50:07.451  4128  4307 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 03:50:07.452  4128  4307 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 03:50:07.452  4128  4307 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 03:50:07.452  4128  4307 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:50:07.452  4128  4307 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 03:50:07.453  4128  4307 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 03:50:07.453  4128  4307 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 03:50:07.454  4128  4307 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 03:50:07.454  4128  4307 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 03:50:07.454  4128  4307 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 03:50:07.455  4128  4307 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 03:50:07.455  4128  4307 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 03:50:07.456  4128  4307 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 03:50:07.456  4128  4307 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 03:50:07.589  4128  4307 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-25 03:50:07.590  4128  4307 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-25 03:50:07.619  4128  4299 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 03:50:07.621  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 03:50:07.621  4128  4299 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 03:50:07.623  4128  4299 D BluetoothAdapterProperties: Name is: Nexus 6
08-25 03:50:07.624  4128  4299 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:50:07.624  4128  4299 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:50:07.624  4128  4299 D bt_hci  : do_postload posting postload work item
08-25 03:50:07.625  4128  4303 I bt_hci  : event_postload
08-25 03:50:07.625  4128  4303 I bt_vendor: sco_config_cb
08-25 03:50:07.625  4128  4303 I bt_hci  : sco_config_callback postload finished.
,08-25 03:50:07.627  4128  4299 D bt_bte_conf: Device ID record 1 : primary
,08-25 03:50:07.627  4128  4299 D bt_bte_conf:   vendorId            = 000f
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   vendorIdSource      = 0001
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   product             = 1200
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   version             = 1436
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   clientExecutableURL = 
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   serviceDescription  = 
08-25 03:50:07.627  4128  4299 D bt_bte_conf:   documentationURL    = 
08-25 03:50:07.627  4128  4299 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-25 03:50:07.627  4128  4296 D bt_stack_manager: event_start_up_stack finished
08-25 03:50:07.628  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 03:50:07.628  4128  4295 D BluetoothAdapterProperties: Setting state to 15
08-25 03:50:07.628  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 03:50:07.629  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:07.632  4128  4295 I BluetoothAdapterState: Entering BleOnState
08-25 03:50:07.634  4128  4303 I bt_vendor: low_power_mode_cb
08-25 03:50:07.634  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.638  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.638  4128  4295 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 03:50:07.639  4128  4295 D BluetoothAdapterProperties: Setting state to 11
08-25 03:50:07.639  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 03:50:07.646  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:07.648  4128  4128 D HeadsetService: Received start request. Starting profile...
,08-25 03:50:07.655  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.658  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.659  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.660  4128  4128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:50:07.660  4128  4128 D HeadsetStateMachine: make
,08-25 03:50:07.665  4128  4295 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:50:07.669  4128  4128 D HeadsetStateMachine: max_hf_connections = 1
,08-25 03:50:07.669  4128  4128 I bt_bluedroid: get_profile_interface handsfree
08-25 03:50:07.670  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 03:50:07.670  4128  4299 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 03:50:07.676  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:07.676  4128  4128 D A2dpService: Received start request. Starting profile...
,08-25 03:50:07.677  4128  4128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 03:50:07.677  4128  4128 I bt_bluedroid: get_profile_interface avrcp
,08-25 03:50:07.683  4128  4128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 03:50:07.683  4128  4128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:50:07.683  4128  4128 D A2dpStateMachine: make
,08-25 03:50:07.685  4128  4128 I bt_bluedroid: get_profile_interface a2dp
,08-25 03:50:07.685  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 03:50:07.687  4128  4316 D A2dpStateMachine: Enter Disconnected: -2
08-25 03:50:07.688  4128  4128 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 03:50:07.688  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:50:07.690  4025  4025 D BluetoothInputDevice: Proxy object connected
,08-25 03:50:07.690  4128  4128 D HidService: Received start request. Starting profile...
,08-25 03:50:07.690  4128  4128 I bt_bluedroid: get_profile_interface hidhost
,08-25 03:50:07.691  4128  4299 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
,08-25 03:50:07.691  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 03:50:07.691  4128  4128 D HidService: setHidService(): set to: null
08-25 03:50:07.692  4128  4128 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:50:07.692  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:50:07.693  4128  4128 D HealthService: Received start request. Starting profile...
,08-25 03:50:07.694  4025  4025 D HidProfile: Bluetooth service connected
,08-25 03:50:07.696  4128  4128 I bt_bluedroid: get_profile_interface health
,08-25 03:50:07.697  4128  4128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 03:50:07.698  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:07.699  4025  4025 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 03:50:07.700  4025  4025 D PanProfile: Bluetooth service connected
08-25 03:50:07.700  4128  4128 D PanService: Received start request. Starting profile...
,08-25 03:50:07.700  4128  4128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 03:50:07.700  4128  4128 I bt_bluedroid: get_profile_interface pan
08-25 03:50:07.701  4128  4299 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 03:50:07.706  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:50:07.707  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:07.709  4025  4025 D BluetoothMap: Proxy object connected
08-25 03:50:07.710  4025  4025 D MapProfile: Bluetooth service connected
08-25 03:50:07.710  4025  4025 D BluetoothMap: getConnectedDevices()
,08-25 03:50:07.710  4128  4128 D BluetoothMapService: Received start request. Starting profile...
08-25 03:50:07.710  4128  4128 D BluetoothMapService: start()
,08-25 03:50:07.711  4025  4025 D BluetoothMap: Bluetooth is Not enabled
,08-25 03:50:07.715  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 03:50:07.716  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 03:50:07.716  4128  4128 D BluetoothMapAppObserver: createReceiver()
,08-25 03:50:07.717  4128  4128 D BluetoothMapAppObserver: initObservers()
,08-25 03:50:07.718  4128  4128 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 03:50:07.727  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:50:07.727  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.727  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:07.727  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:07.729  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:07.730  4128  4314 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:07.730  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 03:50:07.731  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:07.732  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:07.732  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:07.732  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:07.732  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:07.732  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 03:50:07.732  4128  4295 D BluetoothAdapterProperties: ScanMode =  20
,08-25 03:50:07.732  4128  4295 D BluetoothAdapterProperties: State =  11
08-25 03:50:07.735  4128  4295 D BluetoothAdapterProperties: Setting state to 12
08-25 03:50:07.735  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 03:50:07.736  4128  4295 I BluetoothAdapterState: Entering OnState
08-25 03:50:07.736   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 03:50:07.738  4128  4299 D BluetoothAdapterProperties: Scan Mode:21
,08-25 03:50:07.738  4128  4299 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 03:50:07.740  1356  1371 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:50:07.742   874   874 D BluetoothA2dp: Proxy object connected
08-25 03:50:07.744  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:50:07.744  1356  1356 D PanProfile: Bluetooth service connected
08-25 03:50:07.745  4025  4037 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 03:50:07.745  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 03:50:07.746  4128  4128 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:07.747  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:07.748  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:50:07.748  4025  4035 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:50:07.749  1356  2186 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:50:07.750  1356  1371 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 03:50:07.751  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:07.752  1356  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 03:50:07.753  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:07.754  1356  1356 D BluetoothInputDevice: Proxy object connected
08-25 03:50:07.754  1356  1356 D HidProfile: Bluetooth service connected
08-25 03:50:07.754  4025  4037 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:50:07.755  4128  4128 D ObexServerSockets: Succeed to create listening sockets 
,08-25 03:50:07.755   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:07.755  4128  4128 D ObexServerSockets0: startAccept()
08-25 03:50:07.755  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-25 03:50:07.755  1356  2186 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 03:50:07.756  1356  1356 D BluetoothMap: Proxy object connected
08-25 03:50:07.757  1356  1356 D MapProfile: Bluetooth service connected
08-25 03:50:07.757  1356  1356 D BluetoothMap: getConnectedDevices()
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:07.757  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:07.758  1926  1938 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:07.758   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:07.759  1356  4011 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:50:07.759  4128  4128 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 03:50:07.760  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:07.760  4128  4128 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 03:50:07.761  1356  1356 D BluetoothA2dp: Proxy object connected
08-25 03:50:07.761   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:07.761  4025  4035 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:07.763  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:07.764   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 03:50:07.765  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:07.766  4128  4324 D ObexServerSockets0: Accepting socket connection...
08-25 03:50:07.766  4128  4323 D ObexServerSockets0: Accepting socket connection...
08-25 03:50:07.768  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.769  4128  4128 D BluetoothMapService: onReceive
08-25 03:50:07.769  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:50:07.769  4128  4128 D BluetoothMapService: STATE_ON
08-25 03:50:07.770  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.771  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:07.773  4025  4025 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-25 03:50:07.776  4025  4025 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 03:50:07.781  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:50:07.783  4025  4025 D BluetoothA2dp: Proxy object connected
,08-25 03:50:07.786  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:50:07.787  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:50:07.798  1356  1356 D BluetoothPbap: Proxy object connected
,08-25 03:50:07.798  4025  4025 D BluetoothPbap: Proxy object connected
08-25 03:50:07.798  1356  1356 D PbapServerProfile: Bluetooth service connected
08-25 03:50:07.798  4025  4025 D PbapServerProfile: Bluetooth service connected
08-25 03:50:07.798  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener,
08-25 03:50:07.799  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-25 03:50:07.808  4128  4330 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:07.827  4128  4334 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:07.828  4128  4334 I BtOppRfcommListener: Accept thread started.
,08-25 03:50:07.851   874   874 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.851   874   874 D BluetoothHeadset: Proxy object connected
08-25 03:50:07.852   874   874 D BluetoothHeadset: Proxy object connected
08-25 03:50:07.852  1356  1373 D BluetoothHeadset: Proxy object connected
08-25 03:50:07.852  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-25 03:50:07.853  1926  1940 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.855   874   891 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.858  1926  2204 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.859   874   891 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.862   874   891 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.879  4025  4037 D BluetoothHeadset: Proxy object connected
,08-25 03:50:07.880  4025  4025 D HeadsetProfile: Bluetooth service connected
,08-25 03:50:11.281  4128  4295 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 03:50:11.282  4128  4295 D BluetoothAdapterProperties: Setting state to 13
08-25 03:50:11.282  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 03:50:11.284  4128  4295 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 03:50:11.292  4128  4295 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:50:11.294  4128  4128 D BluetoothMapService: onReceive
,08-25 03:50:11.294  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:50:11.295  4128  4128 D BluetoothMapService: STATE_TURNING_OFF,
08-25 03:50:11.295  4128  4128 D BluetoothMapService: MAP Service closeService in
08-25 03:50:11.296  4128  4128 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 03:50:11.296  4128  4128 D ObexServerSockets0: shutdown(block = true)
,08-25 03:50:11.296  4128  4323 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 03:50:11.305  4128  4299 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:50:11.305  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 03:50:11.307  4128  4128 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:50:11.308  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:11.308  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:11.307  4128  4324 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 03:50:11.309  4128  4309 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 03:50:11.309  4128  4128 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 03:50:11.310  4128  4128 I BtOppRfcommListener: stopping Accept Thread
,08-25 03:50:11.310  4128  4334 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:50:11.313  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:11.313  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:11.316  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:11.316  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:11.317  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:11.317  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:11.317  4128  4334 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 03:50:11.320  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:11.320  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:11.321  3948  3948 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:50:11.321  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:11.322  4128  4128 D HeadsetService: Received stop request...Stopping profile...
08-25 03:50:11.323  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:11.324  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:11.325  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:50:11.326  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:11.326   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 03:50:11.327   874   874 D BluetoothHeadset: Proxy object disconnected
,08-25 03:50:11.328  4025  4037 D BluetoothHeadset: Proxy object disconnected
08-25 03:50:11.328  4128  4128 D A2dpService: Received stop request...Stopping profile...
08-25 03:50:11.328   874   874 D BluetoothHeadset: Proxy object disconnected
08-25 03:50:11.329  4128  4316 D A2dpStateMachine: Exit Disconnected: -1
08-25 03:50:11.329  1356  4011 D BluetoothHeadset: Proxy object disconnected
,08-25 03:50:11.330  1926  2048 D BluetoothHeadset: Proxy object disconnected
08-25 03:50:11.331  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-25 03:50:11.333  1356  1356 D BluetoothA2dp: Proxy object disconnected
08-25 03:50:11.333   874   874 D BluetoothA2dp: Proxy object disconnected
,08-25 03:50:11.334  4128  4128 D HidService: Received stop request...Stopping profile...
08-25 03:50:11.334  4128  4128 D HidService: Stopping Bluetooth HidService
,08-25 03:50:11.335  1356  1356 D BluetoothInputDevice: Proxy object disconnected
08-25 03:50:11.336  1356  1356 D HidProfile: Bluetooth service disconnected
,08-25 03:50:11.336  4025  4025 D HeadsetProfile: Bluetooth service disconnected
08-25 03:50:11.336  4128  4128 D HealthService: Received stop request...Stopping profile...
08-25 03:50:11.337  4128  4128 D PanService: Received stop request...Stopping profile...
,08-25 03:50:11.338  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:50:11.338  1356  1356 D PanProfile: Bluetooth service disconnected
,08-25 03:50:11.339  4128  4128 D BluetoothMapService: Received stop request...Stopping profile...
08-25 03:50:11.339  4128  4128 D BluetoothMapService: stop()
,08-25 03:50:11.339  4128  4128 D BluetoothMapAppObserver: deinitObservers()
08-25 03:50:11.339  4128  4128 D BluetoothMapAppObserver: removeReceiver()
,08-25 03:50:11.341  1356  1356 D BluetoothMap: Proxy object disconnected
08-25 03:50:11.341  1356  1356 D MapProfile: Bluetooth service disconnected
,08-25 03:50:11.342  4128  4128 V BluetoothAdapterState: isTurningOff()=true
,08-25 03:50:11.342  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.342  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.342  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.343  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:50:11.344  4128  4128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:50:11.344  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 03:50:11.344  4025  4025 D BluetoothA2dp: Proxy object disconnected
08-25 03:50:11.344  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:50:11.345  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:50:11.345  4025  4025 D BluetoothInputDevice: Proxy object disconnected
08-25 03:50:11.345  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:50:11.345  4025  4025 D HidProfile: Bluetooth service disconnected
08-25 03:50:11.345  4025  4025 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 03:50:11.345  4025  4025 D PanProfile: Bluetooth service disconnected
08-25 03:50:11.345  4128  4299 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 03:50:11.346  4128  4128 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:50:11.345  4025  4025 D BluetoothMap: Proxy object disconnected
08-25 03:50:11.346  4025  4025 D MapProfile: Bluetooth service disconnected
08-25 03:50:11.346  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-25 03:50:11.347  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.347  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.347  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.349  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-25 03:50:11.349  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.349  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.349  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.349  4128  4128 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:50:11.349  4128  4128 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 03:50:11.351  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 03:50:11.351  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 03:50:11.351  4128  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:50:11.351  4128  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:50:11.351  4128  4307 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:50:11.351  4128  4307 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:50:11.351  4128  4128 V BluetoothAdapterState: isTurningOff()=true
,08-25 03:50:11.351  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 03:50:11.351  4128  4128 V BluetoothAdapterState: isTurningOn()=false
,08-25 03:50:11.352  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.352  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.352  4128  4299 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 03:50:11.352  4128  4128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 03:50:11.353  4128  4299 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 03:50:11.353  4128  4128 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:50:11.353  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-25 03:50:11.353  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.353  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.353  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.354  4128  4128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 03:50:11.354  4128  4128 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:50:11.354  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:50:11.354  4128  4128 D BluetoothMapService: MAP Service closeService in
,08-25 03:50:11.355  4128  4128 V BluetoothAdapterState: isTurningOff()=true
08-25 03:50:11.355  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.355  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.355  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:11.355  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 03:50:11.355  4128  4128 D BluetoothMapService: cleanup()
,08-25 03:50:11.355  4128  4295 D BluetoothAdapterProperties: Setting state to 15
08-25 03:50:11.355  4128  4128 D BluetoothMapService: MAP Service closeService in
08-25 03:50:11.355  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 03:50:11.356  4128  4295 I BluetoothAdapterState: Entering BleOnState
08-25 03:50:11.356   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:50:11.356  1356  1371 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:50:11.357  4025  4035 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:50:11.358  1356  1356 D BluetoothPbap: Proxy object disconnected
08-25 03:50:11.358  4025  4037 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:50:11.359  1356  1356 D PbapServerProfile: Bluetooth service disconnected
,08-25 03:50:11.359  4025  4035 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 03:50:11.360  1356  4011 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:50:11.360  4025  4025 D BluetoothPbap: Proxy object disconnected
08-25 03:50:11.360  1356  4011 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:50:11.360  4025  4025 D PbapServerProfile: Bluetooth service disconnected
08-25 03:50:11.362  4025  4035 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:50:11.362  1356  2186 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 03:50:11.364  4025  4037 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:50:11.365   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:50:11.365  1356  1373 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 03:50:11.368  1926  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 03:50:11.368   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:50:11.368  1356  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 03:50:11.369   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:50:11.369  4025  4339 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:50:11.370  4128  4295 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 03:50:11.370  4128  4295 D BluetoothAdapterProperties: Setting state to 16
08-25 03:50:11.370  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 03:50:11.371  4128  4295 D BluetoothAdapterProperties: onBleDisable
08-25 03:50:11.371  4128  4295 I BluetoothAdapterState: Entering PendingCommandState
08-25 03:50:11.372  4128  4296 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 03:50:11.373  4128  4307 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-25 03:50:11.373  4128  4307 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 03:50:11.374  4128  4299 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:50:11.375  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:11.376  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 03:50:11.376  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:11.379  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:11.381  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:11.382  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:50:11.383  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:11.385  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:11.387  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:50:11.577  4128  4299 I bt_hci  : shut_down
,08-25 03:50:11.578  4128  4303 D bt_hwcfg: hw_epilog_process
,08-25 03:50:11.589  4128  4303 I bt_vendor: low_power_mode_cb
,08-25 03:50:11.606  4128  4303 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 03:50:11.606  4128  4303 I bt_vendor: epilog_cb
,08-25 03:50:11.607  4128  4303 I bt_hci  : epilog_finished_callback
,08-25 03:50:11.617  4128  4299 I bt_hci_h4: hal_close
,08-25 03:50:11.619  4128  4299 I bt_userial_vendor: device fd = 51 close
,08-25 03:50:11.752  4128  4296 D bt_stack_manager: event_shut_down_stack finished.
,08-25 03:50:11.753  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 03:50:11.761  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:50:11.761  4128  4295 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 03:50:11.762  4128  4128 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 03:50:11.763  4128  4128 D BtGatt.GattService: stop()
08-25 03:50:11.764  4128  4128 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 03:50:11.770  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-25 03:50:11.770  4128  4128 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:11.770  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:11.771  4128  4128 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 03:50:11.772  4128  4295 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 03:50:11.773  4128  4295 D BluetoothAdapterProperties: Setting state to 10
08-25 03:50:11.773  4128  4295 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 03:50:11.775  4128  4295 I BluetoothAdapterState: Entering OffState
08-25 03:50:11.776   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 03:50:11.811  4128  4128 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-25 03:50:11.811  4128  4128 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 03:50:11.811  4128  4296 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 03:50:11.814  4128  4296 D bt_stack_manager: event_clean_up_stack finished.
08-25 03:50:11.814  4128  4128 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 03:50:11.816  4128  4128 I art     : System.exit called, status: 0
08-25 03:50:11.817  4128  4128 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 03:50:11.863   874  1965 I ActivityManager: Process com.android.bluetooth (pid 4128) has died
,08-25 03:50:16.278  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:16.279  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:16.283  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:16.284  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19f08fe removed from the list
,08-25 03:50:16.284  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:16.285  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:16.285  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:16.288  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:50:16.288  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b160b75 added. We now have 4 listener(s)
,08-25 03:50:16.289  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:50:16.291  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:16.291  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b160b75 removed from the list
,08-25 03:50:16.291  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:50:16.292  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:16.292  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:16.294  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:50:16.295  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15eb70a added. We now have 4 listener(s)
08-25 03:50:16.296  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:50:21.306  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:21.355   874   891 I ActivityManager: Start proc 4344:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 03:50:21.494  4344  4344 D AdapterServiceConfig: Adding HeadsetService
08-25 03:50:21.494  4344  4344 D AdapterServiceConfig: Adding A2dpService
08-25 03:50:21.494  4344  4344 D AdapterServiceConfig: Adding HidService
,08-25 03:50:21.495  4344  4344 D AdapterServiceConfig: Adding HealthService
08-25 03:50:21.495  4344  4344 D AdapterServiceConfig: Adding PanService
08-25 03:50:21.495  4344  4344 D AdapterServiceConfig: Adding GattService
,08-25 03:50:21.495  4344  4344 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 03:50:21.510   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e14d79d:true
,08-25 03:50:21.512  4344  4344 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 03:50:21.522  4344  4356 I BluetoothAdapterState: Entering OffState
,08-25 03:50:21.523  4344  4344 I bt_bluedroid: init
,08-25 03:50:21.530  4344  4357 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 03:50:21.530  4344  4357 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 03:50:21.530  4344  4357 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:50:21.531  4344  4357 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 03:50:21.533  4344  4344 I bt_bluedroid: get_profile_interface socket
,08-25 03:50:21.537  4344  4360 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:50:21.538  4344  4344 I bt_bluedroid: get_profile_interface sdp
,08-25 03:50:21.539  4344  4360 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:50:21.546  4344  4355 I bt_bluedroid: config_hci_snoop_log
,08-25 03:50:21.550   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 03:50:21.564  4344  4356 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 03:50:21.565  4344  4356 D BluetoothAdapterProperties: Setting state to 14
08-25 03:50:21.565  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 03:50:21.570  4344  4356 D BluetoothBondStateMachine: make
,08-25 03:50:21.577  4344  4361 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 03:50:21.588  4344  4356 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:50:21.590  4344  4344 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 03:50:21.599  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:21.602  4344  4344 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 03:50:21.603  4344  4344 D BtGatt.GattService: Received start request. Starting profile...
08-25 03:50:21.604  4344  4344 D BtGatt.GattService: start()
,08-25 03:50:21.604  4344  4344 I bt_bluedroid: get_profile_interface gatt
,08-25 03:50:21.607  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:50:21.607  4344  4344 D BtGatt.AdvertiseManager: advertise manager created
,08-25 03:50:21.615  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:21.615  4344  4344 V BluetoothAdapterState: isTurningOn()=false
08-25 03:50:21.615  4344  4344 V BluetoothAdapterState: isBleTurningOn()=true
08-25 03:50:21.615  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:21.616  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 03:50:21.616  4344  4356 I bt_bluedroid: enable
08-25 03:50:21.616  4344  4357 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 03:50:21.617  4344  4357 I bt_hci  : start_up
,08-25 03:50:21.637  4344  4357 I bt_vendor: alloc value 0xb39b9189
08-25 03:50:21.637  4344  4357 I bt_vendor: init
,08-25 03:50:21.638  4344  4357 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 03:50:21.639  4344  4357 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 03:50:21.750  4344  4357 D bt_hci  : start_up starting async portion
,08-25 03:50:21.750  4344  4364 I bt_hci  : event_finish_startup
,08-25 03:50:21.751  4344  4364 I bt_hci_h4: hal_open
,08-25 03:50:21.751  4344  4364 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 03:50:21.765  4344  4364 I bt_userial_vendor: device fd = 51 open
,08-25 03:50:21.793  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:50:21.824  4344  4364 D bt_hwcfg: Chipset BCM4354A2
08-25 03:50:21.825  4344  4364 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 03:50:21.826  4344  4364 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 03:50:22.691  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 03:50:22.693  4344  4364 D bt_hwcfg: Settlement delay -- 100 ms
08-25 03:50:22.693  4344  4364 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 03:50:22.811  4344  4364 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 03:50:22.813  4344  4364 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 03:50:22.841  4344  4364 I bt_hwcfg: vendor lib fwcfg completed
,08-25 03:50:22.842  4344  4364 I bt_vendor: firmware callback
08-25 03:50:22.842  4344  4364 I bt_hci  : firmware_config_callback
,08-25 03:50:22.855  4344  4366 I bt_btu  : btu_task pending for preload complete event
,08-25 03:50:22.855  4344  4366 I bt_btu_task: Bluetooth chip preload is complete
,08-25 03:50:22.855  4344  4366 I bt_btu  : btu_task received preload complete event
,08-25 03:50:22.868  4344  4366 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 03:50:22.868  4344  4366 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 03:50:22.869  4344  4366 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 03:50:22.869  4344  4366 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 03:50:22.869  4344  4366 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:50:22.869  4344  4366 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 03:50:22.870  4344  4366 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 03:50:22.870  4344  4366 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 03:50:22.871  4344  4366 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 03:50:22.871  4344  4366 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 03:50:22.872  4344  4366 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 03:50:22.872  4344  4366 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 03:50:22.873  4344  4366 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 03:50:22.873  4344  4366 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 03:50:22.873  4344  4366 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 03:50:23.027  4344  4366 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-25 03:50:23.027  4344  4366 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-25 03:50:23.035  4344  4360 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 03:50:23.036  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 03:50:23.037  4344  4360 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 03:50:23.041  4344  4360 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 03:50:23.046  4344  4360 D BluetoothAdapterProperties: Scan Mode:20
,08-25 03:50:23.046  4344  4360 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:50:23.049  4344  4360 D bt_hci  : do_postload posting postload work item
08-25 03:50:23.049  4344  4364 I bt_hci  : event_postload
08-25 03:50:23.049  4344  4364 I bt_vendor: sco_config_cb
08-25 03:50:23.050  4344  4364 I bt_hci  : sco_config_callback postload finished.
,08-25 03:50:23.053  4344  4360 D bt_bte_conf: Device ID record 1 : primary
08-25 03:50:23.053  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:23.053  4344  4360 D bt_bte_conf:   vendorId            = 000f
08-25 03:50:23.053  4344  4360 D bt_bte_conf:   vendorIdSource      = 0001
08-25 03:50:23.053  4344  4360 D bt_bte_conf:   product             = 1200
08-25 03:50:23.053  4344  4360 D bt_bte_conf:   version             = 1436
08-25 03:50:23.054  4344  4360 D bt_bte_conf:   clientExecutableURL = 
08-25 03:50:23.054  4344  4360 D bt_bte_conf:   serviceDescription  = 
08-25 03:50:23.054  4344  4360 D bt_bte_conf:   documentationURL    = 
08-25 03:50:23.055  4344  4360 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 03:50:23.055  4344  4357 D bt_stack_manager: event_start_up_stack finished
08-25 03:50:23.056  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 03:50:23.056  4344  4356 D BluetoothAdapterProperties: Setting state to 15
08-25 03:50:23.056  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 03:50:23.057  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:23.057  4344  4356 I BluetoothAdapterState: Entering BleOnState
08-25 03:50:23.058  4344  4364 I bt_vendor: low_power_mode_cb
,08-25 03:50:23.061  4344  4356 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 03:50:23.062  4344  4356 D BluetoothAdapterProperties: Setting state to 11
08-25 03:50:23.062  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 03:50:23.072  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:23.075  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:23.079  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:23.081  4344  4344 D HeadsetService: Received start request. Starting profile...
,08-25 03:50:23.084  4344  4344 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:50:23.084  4344  4344 D HeadsetStateMachine: make
,08-25 03:50:23.094  4344  4356 I BluetoothAdapterState: Entering PendingCommandState
,08-25 03:50:23.095  4344  4344 D HeadsetStateMachine: max_hf_connections = 1
08-25 03:50:23.095  4344  4344 I bt_bluedroid: get_profile_interface handsfree
08-25 03:50:23.096  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 03:50:23.096  4344  4360 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 03:50:23.100  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:23.102  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:50:23.102  4344  4344 D A2dpService: Received start request. Starting profile...
08-25 03:50:23.103  4344  4344 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 03:50:23.104  4344  4344 I bt_bluedroid: get_profile_interface avrcp
,08-25 03:50:23.115  4344  4344 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 03:50:23.116  4344  4344 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:50:23.116  4344  4344 D A2dpStateMachine: make
08-25 03:50:23.118  4344  4344 I bt_bluedroid: get_profile_interface a2dp
,08-25 03:50:23.120  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 03:50:23.123  4344  4375 D A2dpStateMachine: Enter Disconnected: -2
,08-25 03:50:23.124  4344  4344 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 03:50:23.126  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:23.127  4344  4344 D HidService: Received start request. Starting profile...
08-25 03:50:23.128  4344  4344 I bt_bluedroid: get_profile_interface hidhost
08-25 03:50:23.128  4344  4360 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
,08-25 03:50:23.129  4344  4360 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 03:50:23.129  4344  4344 D HidService: setHidService(): set to: null
08-25 03:50:23.129  4344  4344 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:50:23.130  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
08-25 03:50:23.130  4344  4344 D HealthService: Received start request. Starting profile...
,08-25 03:50:23.133  4344  4344 I bt_bluedroid: get_profile_interface health
,08-25 03:50:23.135  4344  4344 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 03:50:23.137  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:23.141  4344  4344 D PanService: Received start request. Starting profile...
08-25 03:50:23.142  4344  4344 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 03:50:23.142  4344  4344 I bt_bluedroid: get_profile_interface pan
08-25 03:50:23.143  4344  4360 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 03:50:23.149  4344  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:23.151  4344  4344 D BluetoothMapService: Received start request. Starting profile...
,08-25 03:50:23.151  4344  4344 D BluetoothMapService: start()
,08-25 03:50:23.156  4344  4344 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-25 03:50:23.158  4344  4344 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 03:50:23.158  4344  4344 D BluetoothMapAppObserver: createReceiver()
,08-25 03:50:23.160  4344  4344 D BluetoothMapAppObserver: initObservers()
08-25 03:50:23.160  4344  4344 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 03:50:23.176  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.176  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.176  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.176  4344  4372 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 03:50:23.176  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 03:50:23.180  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.180  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.180  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.180  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:23.180  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOff()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isTurningOn()=true
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOn()=false
08-25 03:50:23.181  4344  4344 V BluetoothAdapterState: isBleTurningOff()=false
08-25 03:50:23.182  4344  4356 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 03:50:23.182  4344  4356 D BluetoothAdapterProperties: ScanMode =  20
08-25 03:50:23.182  4344  4356 D BluetoothAdapterProperties: State =  11
08-25 03:50:23.183  4344  4356 D BluetoothAdapterProperties: Setting state to 12
08-25 03:50:23.183  4344  4356 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 03:50:23.184   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:50:23.184  1356  4011 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:50:23.186   874   874 D BluetoothA2dp: Proxy object connected
08-25 03:50:23.186  4344  4360 D BluetoothAdapterProperties: Scan Mode:21
08-25 03:50:23.188  4344  4360 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:50:23.188  4025  4339 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:50:23.189  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:50:23.189  1356  1356 D PanProfile: Bluetooth service connected
08-25 03:50:23.190  4344  4356 I BluetoothAdapterState: Entering OnState
,08-25 03:50:23.192  4025  4037 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:23.192  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:23.193  4025  4035 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:50:23.194  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:23.195  1356  1373 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:23.195  4344  4344 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 03:50:23.196  4025  4025 D BluetoothA2dp: Proxy object connected
08-25 03:50:23.196  1356  1371 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:50:23.196  4344  4344 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 03:50:23.197  4025  4025 D BluetoothMap: Proxy object connected
08-25 03:50:23.197  4025  4025 D MapProfile: Bluetooth service connected
08-25 03:50:23.198  4344  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:23.198  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:50:23.198  4025  4025 D BluetoothMap: getConnectedDevices()
08-25 03:50:23.200  4025  4037 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:23.200  4344  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:50:23.201  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:23.202  1356  4011 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 03:50:23.202  4344  4344 D ObexServerSockets: Succeed to create listening sockets 
08-25 03:50:23.202  4344  4344 D ObexServerSockets0: startAccept()
08-25 03:50:23.202  4344  4344 D ObexServerSockets0: prepareForNewConnect()
08-25 03:50:23.203  4025  4339 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:50:23.204  4344  4344 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 03:50:23.204  4344  4344 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 03:50:23.205  4344  4381 D ObexServerSockets0: Accepting socket connection...
08-25 03:50:23.205  4344  4382 D ObexServerSockets0: Accepting socket connection...
08-25 03:50:23.206   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:23.206  1356  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:50:23.206  1356  1356 D BluetoothInputDevice: Proxy object connected
08-25 03:50:23.206  1356  1356 D HidProfile: Bluetooth service connected
08-25 03:50:23.207  4025  4025 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:50:23.207  4025  4025 D PanProfile: Bluetooth service connected
08-25 03:50:23.207  4025  4025 D BluetoothInputDevice: Proxy object connected
08-25 03:50:23.207  4025  4025 D HidProfile: Bluetooth service connected
,08-25 03:50:23.212  1926  1940 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:50:23.212  1356  1356 D BluetoothMap: Proxy object connected
08-25 03:50:23.212  1356  1356 D MapProfile: Bluetooth service connected
08-25 03:50:23.212  1356  1356 D BluetoothMap: getConnectedDevices()
08-25 03:50:23.212   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:23.212  1356  4011 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 03:50:23.214   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:50:23.214  4025  4035 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 03:50:23.216  1356  1356 D BluetoothA2dp: Proxy object connected
,08-25 03:50:23.217   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 03:50:23.218  4344  4344 D BluetoothMapService: onReceive
,08-25 03:50:23.218  4344  4344 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:50:23.218  4344  4344 D BluetoothMapService: STATE_ON
,08-25 03:50:23.221  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:23.222  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:23.223  4025  4025 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 03:50:23.229  1535  1535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:50:23.229  4025  4025 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:50:23.236  4025  4025 D BluetoothPbap: Proxy object connected
08-25 03:50:23.237  4025  4025 D PbapServerProfile: Bluetooth service connected
,08-25 03:50:23.241  4344  4344 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 03:50:23.242  4344  4344 D ObexServerSockets0: prepareForNewConnect()
,08-25 03:50:23.245  4344  4387 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:23.254  1356  1356 D BluetoothPbap: Proxy object connected
08-25 03:50:23.254  1356  1356 D PbapServerProfile: Bluetooth service connected
,08-25 03:50:23.261  4344  4391 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:23.263  4344  4391 I BtOppRfcommListener: Accept thread started.
,08-25 03:50:23.297   874   874 D BluetoothHeadset: Proxy object connected
,08-25 03:50:23.297   874   874 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.297  4025  4035 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.297   874   874 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.297  4025  4025 D HeadsetProfile: Bluetooth service connected
08-25 03:50:23.298  1356  1373 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.298  1356  1356 D HeadsetProfile: Bluetooth service connected
08-25 03:50:23.299  1926  2204 D BluetoothHeadset: Proxy object connected
,08-25 03:50:23.302  4025  4339 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.302  4025  4025 D HeadsetProfile: Bluetooth service connected
,08-25 03:50:23.306   874   891 D BluetoothHeadset: Proxy object connected
,08-25 03:50:23.313  1926  2048 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.313   874   891 D BluetoothHeadset: Proxy object connected
08-25 03:50:23.313   874   891 D BluetoothHeadset: Proxy object connected
,08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:26.329  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:26.335  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:26.336  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:26.337  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15eb70a removed from the list
08-25 03:50:26.337  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:26.337  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:26.337  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:26.342  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:50:26.343  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd52b7b added. We now have 4 listener(s)
08-25 03:50:26.343  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:50:26.347   874   884 D WifiService: setWifiEnabled: false pid=3948, uid=10000
,08-25 03:50:26.348   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:50:26.824  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:26.835  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:26.837  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:26.885  1535  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:50:26.886  1535  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:50:26.886  1535  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:26.886  1535  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:26.928  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 03:50:26.929  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 03:50:26.929  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 03:50:31.361  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:31.363   874  1399 D WifiService: setWifiEnabled: true pid=3948, uid=10000
08-25 03:50:31.363   874  1399 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:50:31.376   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:31.394  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:31.400  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:50:31.410  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:50:31.414   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-25 03:50:31.414  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:50:31.415   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-25 03:50:31.415   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 03:50:31.416   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 03:50:31.417   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 03:50:31.417   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 03:50:31.417   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 03:50:31.434   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:50:31.435   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 03:50:31.439   372   872 D CommandListener: Setting iface cfg
,08-25 03:50:31.488   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-25 03:50:31.489   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 03:50:31.493   874  1316 E native  : do suspend true
,08-25 03:50:31.500   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 03:50:31.516   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 03:50:31.533   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:50:32.848   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 03:50:33.007   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.36 rxSuccessRate=0.49 delta 1000 -> 1000
,08-25 03:50:33.009   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 03:50:33.009   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:50:33.026   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 03:50:33.105   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 03:50:33.112  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 03:50:33.555  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 03:50:33.600  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:50:33.602  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 03:50:33.606   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 03:50:33.620   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:50:33.620   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:50:33.621   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 03:50:33.646   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 03:50:33.662   372   872 D CommandListener: Setting iface cfg
,08-25 03:50:33.666   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 03:50:33.681   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 03:50:33.737   874  4402 D DhcpClient: Receive thread started
,08-25 03:50:33.834   874  1316 E native  : do suspend false
,08-25 03:50:33.860   874  1880 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 03:50:33.877   874  4402 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-25 03:50:33.879   874  1880 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-25 03:50:33.884   874  1880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 03:50:33.900   874  4402 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 03:50:33.902   874  1880 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 03:50:33.908   372   872 D CommandListener: Setting iface cfg
,08-25 03:50:33.921   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 03:50:33.923   874  1880 D DhcpClient: Scheduling renewal in 86399s
08-25 03:50:33.925   874  1316 E native  : do suspend true
,08-25 03:50:33.956   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 03:50:33.960   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 03:50:33.961   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 03:50:33.965   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 03:50:33.965   874  1319 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 03:50:34.023   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 03:50:34.023   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 03:50:34.024   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 03:50:34.027   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 03:50:34.031   874  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 03:50:34.047   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 03:50:34.052   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-25 03:50:34.052   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-25 03:50:34.052   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 03:50:34.053   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 03:50:34.053   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 03:50:34.053   874  1319 D ConnectivityService:    accepting network in place of null
,08-25 03:50:34.056   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 03:50:34.103   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:50:34.137   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 03:50:34.147   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 03:50:34.148   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:50:34.160   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-25 03:50:34.164   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:34.178  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:34.180  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:34.183  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:34.187  3948  3948 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:34.190  3948  3948 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:34.193  1750  1750 D SystemUpdateService: onCreate
,08-25 03:50:34.198  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 03:50:34.229  1750  4411 I SystemUpdateService: active receiver: enabled
,08-25 03:50:34.236  1750  4411 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-25 03:50:34.238  1750  4411 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 03:50:34.239  1750  4411 I SystemUpdateService: now status is 0 (complete)
08-25 03:50:34.239  1750  4411 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 03:50:34.239  1750  4411 I SystemUpdateService: file has been verified
08-25 03:50:34.239  1750  4411 I SystemUpdateService: OTA package size = 12249756
,08-25 03:50:34.243  1750  4411 I SystemUpdateService: showing system update notification
,08-25 03:50:34.261  3914  4413 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:50:34.267  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:34.301  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 03:50:34.309  1750  2426 I iu.UploadsManager: num queued entries: 0
,08-25 03:50:34.316  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 03:50:34.317  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 03:50:34.319  4142  4142 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-25 03:50:34.323  1750  4418 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 03:50:34.323  1750  4418 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 03:50:34.328  1750  4418 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 03:50:34.331  4142  4142 D SprintDMHelper: simOperator: 
,08-25 03:50:34.331  4142  4142 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 03:50:34.338  1750  2426 I iu.UploadsManager: num updated entries: 0
,08-25 03:50:34.443  1750  1750 D SystemUpdateService: onDestroy
,08-25 03:50:34.468  1750  2426 I iu.SyncManager: NEXT; no task
,08-25 03:50:34.485  3914  4422 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:50:34.520  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:34.525  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:34.539  1535  4423 I VacuumService: Vacuum at: now=1472089834539 tag=VacuumService
,08-25 03:50:34.650  1535  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 03:50:34.650  1535  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:50:34.650  1535  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:34.650  1535  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:34.651  1535  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-25 03:50:34.654  1535  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:50:34.654  1535  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:50:34.654  1535  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:34.666  3699  4415 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 03:50:34.666  3699  4415 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at blb.a(PG:3937)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at czp.a(PG:18188)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:50:34.666  3699  4415 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	... 12 more
08-25 03:50:34.666  3699  4415 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at fal.a(PG:38)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:50:34.666  3699  4415 E HttpOperation: 	... 14 more
,08-25 03:50:34.678   874  4401 D NetlinkSocketObserver: NeighborEvent{elapsedMs=189516, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 03:50:34.717  1535  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:50:34.717  1535  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:50:34.717  1535  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:50:34.717  1535  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:34.722  1535  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-25 03:50:34.722  1535  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 03:50:34.722  1535  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:50:34.722  1535  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:34.739  3914  4422 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 03:50:34.740  3914  4413 E BooksSync: Soft error
08-25 03:50:34.740  3914  4413 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:50:34.740  3914  4413 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:50:34.740  3914  4413 E BooksSync: Sync error
08-25 03:50:34.740  3914  4413 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:50:34.740  3914  4413 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:50:34.740  3914  4413 I BooksSync: Finished books sync
,08-25 03:50:34.757  3699  4415 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 03:50:34.757  3699  4415 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jdm.a(PG:82)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jcs.o(PG:406)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jcn.a(PG:1379)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jcs.i(PG:143)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at hec.a(PG:42)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at hee.a(PG:102)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at czr.a(PG:65)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at kka.a(PG:108)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at czp.a(PG:19176)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at czp.a(PG:9081)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at czq.run(PG:1686)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:50:34.757  3699  4415 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jdj.a(PG:4091)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jdj.a(PG:1125)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jdm.a(PG:77)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	... 15 more
08-25 03:50:34.757  3699  4415 E HttpOperation: Caused by: faj: BadAuthentication
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at fal.a(PG:38)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	at jdj.a(PG:4089)
08-25 03:50:34.757  3699  4415 E HttpOperation: 	... 17 more
,08-25 03:50:34.758  3699  4415 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 03:50:34.758  3699  4415 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at hec.a(PG:42)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at hee.a(PG:102)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at czr.a(PG:65)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at kka.a(PG:108)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	... 15 more
08-25 03:50:34.758  3699  4415 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at fal.a(PG:38)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 03:50:34.758  3699  4415 E ExperimentLoader: 	... 17 more
,08-25 03:50:34.762   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163182, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:50:34.779  1535  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-25 03:50:34.779  1535  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 03:50:34.779  1535  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:34.779  1535  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:34.829  1750  4418 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-25 03:50:34.940   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 182952, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:50:34.949  1535  4425 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-25 03:50:34.955  1535  4425 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 03:50:34.988  1535  4425 W Uploader:  no longer exists, so no auth token.
,08-25 03:50:35.145   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-25 03:50:35.157  4075  4420 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 03:50:35.163   874  4400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.91,2a00:1450:400d:802::200e
,08-25 03:50:35.174   874  4400 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:50:35 GMT], X-Android-Received-Millis=[1472089835173], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472089835170]}
08-25 03:50:35.176   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 03:50:35.176   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-25 03:50:35.176   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 03:50:35.177   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:36.384  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:36.389  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:36.390  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:36.390  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd52b7b removed from the list
08-25 03:50:36.391  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:50:36.391  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:36.391  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:36.400  3948  4440 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-25 03:50:36.400  3948  4440 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 03:50:37.303  1535  4425 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-25 03:50:37.303  1535  4425 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-25 03:50:37.303  1535  4425 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:37.304  1535  4425 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:37.342  1535  4425 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:50:37.342  1535  4425 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:50:37.342  1535  4425 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:50:37.767  1535  4425 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-25 03:50:37.768  1535  4425 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-25 03:50:37.768  1535  4425 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:37.768  1535  4425 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:37.789  1535  4425 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:50:37.789  1535  4425 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:50:37.789  1535  4425 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:50:38.395  1535  4425 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-25 03:50:38.395  1535  4425 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-25 03:50:38.395  1535  4425 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:50:38.395  1535  4425 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:38.416  1535  4425 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 03:50:38.416  1535  4425 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 03:50:38.416  1535  4425 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 03:50:39.400  3948  4446 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-25 03:50:39.400  3948  4446 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:50:39.400  3948  4446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:50:39.401  3948  4446 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:50:39.402  3948  4440 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-25 03:50:39.402  3948  4446 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-25 03:50:39.402  3948  4440 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-25 03:50:39.405  3948  4449 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: IncomingSocketThread/Receiver)
,08-25 03:50:39.405  3948  4448 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: IncomingSocketThread/Sender)
,08-25 03:50:39.406  3948  4440 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:50:39.406  3948  4449 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: IncomingSocketThread/Receiver)
08-25 03:50:39.406  3948  4449 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:50:39.407  3948  4449 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-25 03:50:39.407  3948  4440 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:50:39.408  3948  4450 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: OutgoingSocketThread/Sender)
08-25 03:50:39.408  3948  4440 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-25 03:50:39.410  3948  4451 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: OutgoingSocketThread/Receiver)
08-25 03:50:39.411  3948  4451 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: OutgoingSocketThread/Receiver)
08-25 03:50:39.411  3948  4451 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:50:39.411  3948  4451 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-25 03:50:42.059   874  1319 D ConnectivityService: handlePromptUnvalidated 102
,08-25 03:50:42.408  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 03:50:42.410  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 03:50:42.417  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d7aa566 Bundle[{}]
,08-25 03:50:42.418  3948  3998 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 03:50:42.418  3948  3998 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 03:50:42.418  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 03:50:42.419  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 03:50:42.419  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 03:50:42.420  3948  3998 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 03:50:42.424  3948  3998 I System.out: Running OutgoingSocketThread
,08-25 03:50:42.429  3948  4452 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-25 03:50:42.429  3948  4452 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 03:50:45.438  3948  4453 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-25 03:50:45.438  3948  4453 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-25 03:50:45.439  3948  4453 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:50:45.439  3948  4452 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-25 03:50:45.439  3948  4452 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:50:45.440  3948  4452 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:50:45.440  3948  4453 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:50:45.443  3948  4453 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-25 03:50:45.443  3948  4452 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:50:45.445  3948  4455 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: IncomingSocketThread/Sender)
,08-25 03:50:45.449  3948  4456 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: OutgoingSocketThread/Sender)
,08-25 03:50:45.450  3948  4452 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-25 03:50:45.453  3948  4457 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: IncomingSocketThread/Receiver)
,08-25 03:50:45.453  3948  4457 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 474, thread name: IncomingSocketThread/Receiver)
,08-25 03:50:45.453  3948  4457 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:50:45.453  3948  4457 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 474, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-25 03:50:45.456  3948  4458 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 475, name: OutgoingSocketThread/Receiver)
08-25 03:50:45.457  3948  4458 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 475, thread name: OutgoingSocketThread/Receiver)
,08-25 03:50:45.457  3948  4458 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:50:45.458  3948  4458 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 475, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-25 03:50:47.094  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:47.100  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:47.101  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:50:47.128  1535  2422 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:50:47.128  1535  2422 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 03:50:47.128  1535  2422 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:50:47.128  1535  2422 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:50:47.164  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:50:47.164  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 03:50:47.164  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-25 03:50:48.439  3948  3998 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 484)
,08-25 03:50:48.441  3948  3998 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 03:50:48.442  3948  3998 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 485)
,08-25 03:50:48.448  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:50:48.448  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6252d98 added. We now have 3 listener(s)
,08-25 03:50:48.450  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:50:48.450  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:50:48.450  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:50:48.450  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:50:48.450  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d48e9f1 added. We now have 4 listener(s)
08-25 03:50:48.450  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:50:48.452  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:50:48.455  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:48.466  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:48.470  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:48.470  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:50:48.472  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:50:48.473  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:48.473  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:50:48.473  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:50:48.473  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:48.474  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:48.474  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:50:48.474  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 03:50:48.474  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6252d98 removed from the list
08-25 03:50:48.475  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:48.475  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d48e9f1 removed from the list
08-25 03:50:48.476  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:48.476  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:50:48.476  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:48.477  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:48.477  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:48.481  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:48.481  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:50:48.481  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:48.482  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d48e9f1 not in the list
08-25 03:50:48.482  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:48.482  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:48.486  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:48.486  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:48.486  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:48.487  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d48e9f1 not in the list
08-25 03:50:48.487  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:48.487  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:48.487  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:48.488  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6252d98 not in the list
,08-25 03:50:48.490  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:50:48.490  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10457 added. We now have 3 listener(s)
,08-25 03:50:48.496  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:50:48.497  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:50:48.497  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:50:48.497  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:50:48.498  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8b44 added. We now have 4 listener(s)
08-25 03:50:48.498  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:50:48.499  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:50:48.506  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:48.513  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:48.517  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:48.517  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:50:48.517  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:50:48.518  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:50:48.518  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:50:48.518  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:50:48.518  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:50:48.521  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:48.522  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 03:50:48.522  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 03:50:48.524  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:48.528  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 03:50:48.529  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 03:50:48.529  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:50:48.536  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:50:48.536  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:50:48.537  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 03:50:48.538  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:50:48.542  4344  4354 D BtGatt.GattService: registerClient() - UUID=d547c769-36a0-4b30-957d-2469bccedda5
,08-25 03:50:48.543  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=d547c769-36a0-4b30-957d-2469bccedda5, clientIf=5
,08-25 03:50:48.544  3948  3959 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 03:50:48.546  4344  4355 D BtGatt.GattService: start scan with filters
,08-25 03:50:48.555  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 03:50:48.555  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 03:50:48.555  4344  4363 D BtGatt.ScanManager: handling starting scan
08-25 03:50:48.556  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:50:48.556  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:50:48.560  4344  4363 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@45d899a
,08-25 03:50:48.567  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:50:48.568  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 03:50:48.568  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:50:48.574  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:50:48.577  4344  4360 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 03:50:48.577  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:48.579  4344  4363 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:50:48.579  3948  3998 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 03:50:48.580  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:50:48.580  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 03:50:48.580  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:48.580  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:50:48.580  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:50:48.580  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:50:48.580  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:50:48.581  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:50:48.581  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 03:50:48.581  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 03:50:48.582  3948  3998 D BluetoothAdapter: STATE_ON
08-25 03:50:48.583  4344  4354 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:50:48.584  4344  4355 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 03:50:48.586  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:50:48.586  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 03:50:48.586  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 03:50:48.587  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:50:48.598  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 03:50:48.606  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:48.607  4344  4363 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:50:48.607  4344  4363 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 03:50:48.606  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 03:50:48.610  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:50:48.610  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 03:50:48.610  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 03:50:48.610  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:50:48.611  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:48.612  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:50:48.612  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:50:48.612  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 03:50:48.627  4344  4360 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 03:50:48.627  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:48.636  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 03:50:48.637  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:48.647  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 03:50:48.647  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:48.648  4344  4363 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:50:48.659  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:50:48.659  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:48.659  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:50:48.668  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 03:50:48.669  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:49.113  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:50:49.114  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:50:49.114  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:50:51.613  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:50:51.613  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:50:51.614  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:50:51.615  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:50:51.615  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:51.616  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:51.616  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:50:51.616  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10457 removed from the list
,08-25 03:50:51.616  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:51.617  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8b44 removed from the list
,08-25 03:50:51.617  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:51.617  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:51.619  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:51.619  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:51.623  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:51.623  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:51.623  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:51.624  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8b44 not in the list
08-25 03:50:51.624  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:51.624  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:51.628  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:51.629  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:51.629  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:51.629  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8b44 not in the list
08-25 03:50:51.629  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:51.630  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:51.630  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:51.630  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10457 not in the list
08-25 03:50:51.633  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:50:51.633  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b59e629 added. We now have 3 listener(s)
,08-25 03:50:51.641  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:50:51.641  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:50:51.641  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:50:51.642  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 03:50:51.643  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61dadae added. We now have 4 listener(s)
08-25 03:50:51.643  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:50:51.645  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:50:51.651  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:51.659  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:51.662  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:51.662  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:50:51.662  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:50:51.663  3948  3998 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-25 03:50:51.663  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-25 03:50:51.665  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:50:51.665  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-25 03:50:51.665  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 03:50:51.665  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:50:51.667  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 03:50:51.668  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-25 03:50:51.668  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 03:50:51.668  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-25 03:50:51.668  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-25 03:50:51.668  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:50:51.668  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:50:51.669  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:51.673  3948  4459 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:50:51.677  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:51.677  3948  3948 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-25 03:50:51.679  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 03:50:51.680  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 03:50:51.681  3948  4459 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-25 03:50:51.687  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:50:51.688  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:50:51.688  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:50:51.693  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-25 03:50:51.693  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:50:51.695  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-25 03:50:51.697  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-25 03:50:51.698  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-25 03:50:51.698  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-25 03:50:51.700  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:50:51.705  4344  4380 D BtGatt.GattService: registerClient() - UUID=95447118-c3e3-413b-9aab-4d45d615bb1c
,08-25 03:50:51.706  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=95447118-c3e3-413b-9aab-4d45d615bb1c, clientIf=5
,08-25 03:50:51.707  3948  3960 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-25 03:50:51.710  4344  4362 D BtGatt.AdvertiseManager: message : 0
,08-25 03:50:51.715  4344  4362 D BtGatt.AdvertiseManager: starting multi advertising
,08-25 03:50:51.740  4344  4360 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-25 03:50:51.761  4344  4360 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-25 03:50:51.763  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-25 03:50:51.763  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:50:51.767  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 03:50:51.770  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-25 03:50:51.770  3948  3948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-25 03:50:51.771  3948  3948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-25 03:50:51.771  3948  3948 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-25 03:50:51.771  3948  3948 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-25 03:50:51.772  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-25 03:50:51.776  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-25 03:50:51.782  3948  3948 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-25 03:50:51.782  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-25 03:50:52.283  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-25 03:50:52.284  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 03:50:52.284  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:50:54.778  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:50:54.778  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-25 03:50:54.779  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:50:54.779  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-25 03:50:54.779  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 03:50:54.779  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 03:50:54.780  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:50:54.780  3948  4459 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 03:50:54.781  3948  4459 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 03:50:54.781  3948  3998 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 03:50:54.781  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:50:54.781  3948  4459 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 03:50:54.781  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:50:54.781  3948  3948 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 03:50:54.782  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:50:54.782  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:50:54.782  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:50:54.785  3948  3998 D BluetoothAdapter: STATE_ON
08-25 03:50:54.785  3948  3998 D BluetoothLeScanner: could not find callback wrapper
08-25 03:50:54.785  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:50:54.786  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-25 03:50:54.788  4344  4362 D BtGatt.AdvertiseManager: message : 1
08-25 03:50:54.789  4344  4362 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-25 03:50:54.799  4344  4360 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-25 03:50:54.799  4344  4360 D BtGatt.GattService: Client app is not null!
,08-25 03:50:54.800  4344  4383 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 03:50:54.801  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 03:50:54.801  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-25 03:50:54.801  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-25 03:50:54.801  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-25 03:50:54.801  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-25 03:50:54.802  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-25 03:50:54.802  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:50:54.803  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:50:54.803  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:54.805  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:54.805  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:54.805  3948  3948 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-25 03:50:54.805  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:54.806  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:50:54.806  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b59e629 removed from the list
08-25 03:50:54.806  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:54.806  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:50:54.806  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61dadae removed from the list
08-25 03:50:54.807  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:54.807  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:54.807  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:50:54.807  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:50:54.808  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:54.808  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:54.809  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:54.809  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:54.809  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:54.809  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61dadae not in the list
08-25 03:50:54.809  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:54.809  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:54.810  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:54.810  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:54.810  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:54.810  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61dadae not in the list
08-25 03:50:54.810  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:54.810  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:54.811  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:54.811  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b59e629 not in the list
,08-25 03:50:54.811  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:50:54.812  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e96b added. We now have 3 listener(s)
08-25 03:50:54.813  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 03:50:54.813  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:50:54.814  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:50:54.814  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:50:54.814  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b2cc8 added. We now have 4 listener(s)
08-25 03:50:54.814  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:50:54.815  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:50:54.820  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:54.826  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:54.828  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:54.829  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:50:54.829  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:50:54.829  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:50:54.829  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:50:54.829  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:50:54.829  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:50:54.832  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:54.835  3948  3998 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 03:50:54.838  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:50:54.838  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:54.843  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:50:54.844  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 03:50:54.844  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 03:50:54.849  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 03:50:54.850  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 03:50:54.850  3948  3998 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 03:50:54.852  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:50:54.855  4344  4355 D BtGatt.GattService: registerClient() - UUID=537896e4-3b31-4f80-964a-1c66f374bc28
,08-25 03:50:54.856  4344  4360 D BtGatt.GattService: onClientRegistered() - UUID=537896e4-3b31-4f80-964a-1c66f374bc28, clientIf=5
,08-25 03:50:54.857  3948  3960 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 03:50:54.857  4344  4383 D BtGatt.GattService: start scan with filters
,08-25 03:50:54.860  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 03:50:54.861  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 03:50:54.861  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 03:50:54.861  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 03:50:54.861  4344  4363 D BtGatt.ScanManager: handling starting scan
,08-25 03:50:54.864  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 03:50:54.864  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 03:50:54.866  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 03:50:54.867  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 03:50:54.872  4344  4360 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 03:50:54.872  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:54.873  4344  4363 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 03:50:54.883  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 03:50:54.883  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:54.883  4344  4363 D BtGatt.ScanManager: Starting BLE batch scan
08-25 03:50:54.883  4344  4363 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-25 03:50:54.900  4344  4360 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 03:50:54.901  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-25 03:50:54.911  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 03:50:54.911  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:55.309  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:50:55.367  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-25 03:50:55.367  3948  3948 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:50:55.368  3948  3948 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 03:50:55.469  1865  1984 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-25 03:50:55.470  1865  1984 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-25 03:50:55.522  1535  1535 I ConfigService: onCreate
,08-25 03:50:56.416  4344  4344 D BtGatt.ScanManager: awakened up at time 211255
,08-25 03:50:56.418  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:50:56.468  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-25 03:50:56.468  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 03:50:56.469  4344  4360 D BtGatt.GattService: current time is 211307947942
,08-25 03:50:56.471  4344  4360 D BtGatt.GattService: Batch record : [37, 47, -54, -124, 39, 124, 1, -128, -51, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -79, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-25 03:50:56.475  4344  4360 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
,08-25 03:50:56.478  4344  4360 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-25 03:50:56.479  4344  4360 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-25 03:50:56.480  4344  4360 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-25 03:50:56.481  4344  4360 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-25 03:50:56.487  3948  3948 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,08-25 03:50:56.488  3948  3948 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-25 03:50:57.877  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:50:57.878  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:50:57.878  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 03:50:57.878  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.879  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-25 03:50:57.879  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:50:57.879  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:50:57.879  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 03:50:57.880  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:50:57.881  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 03:50:57.881  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 03:50:57.884  3948  3998 D BluetoothAdapter: STATE_ON
,08-25 03:50:57.886  4344  4355 D BtGatt.GattService: stopScan() - queue size =1
,08-25 03:50:57.888  4344  4383 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 03:50:57.890  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 03:50:57.890  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 03:50:57.891  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 03:50:57.891  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 03:50:57.892  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 03:50:57.896  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:50:57.897  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 03:50:57.897  3948  3998 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:50:57.897  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 03:50:57.898  4344  4344 D BtGatt.ScanManager: awakened up at time 212736
08-25 03:50:57.899  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:57.900  3948  3998 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-25 03:50:57.905  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:50:57.905  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:57.906  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.906  3948  3948 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 03:50:57.906  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:57.906  3948  3948 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:50:57.906  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:50:57.907  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e96b removed from the list
08-25 03:50:57.907  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:57.907  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b2cc8 removed from the list
,08-25 03:50:57.908  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:57.909  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:57.910  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.911  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:57.911  4344  4360 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 03:50:57.911  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:57.912  4344  4363 D BtGatt.ScanManager: stopping BLe Batch
,08-25 03:50:57.913  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:57.913  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:57.913  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:57.913  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b2cc8 not in the list
08-25 03:50:57.914  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.914  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:57.916  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:57.916  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:50:57.916  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:50:57.916  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b2cc8 not in the list
08-25 03:50:57.916  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:50:57.916  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.916  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:50:57.916  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e96b not in the list
08-25 03:50:57.917  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:50:57.917  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f95a312 added. We now have 3 listener(s)
,08-25 03:50:57.919  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 03:50:57.919  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:50:57.919  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:50:57.919  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:50:57.919  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c521ae3 added. We now have 4 listener(s)
08-25 03:50:57.920  3948  3998 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:50:57.920  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:50:57.923  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:50:57.925  4344  4360 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 03:50:57.925  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 03:50:57.925  4344  4363 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:50:57.935  3948  3998 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:50:57.937  3948  3998 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 03:50:57.937  3948  3998 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:50:57.938  3948  3998 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:50:57.938  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:50:57.938  3948  3998 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:50:57.939  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:50:57.939  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.939  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:50:57.939  3948  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:50:57.939  3948  3998 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f95a312 removed from the list
08-25 03:50:57.939  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:57.939  3948  3998 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c521ae3 removed from the list
,08-25 03:50:57.939  4344  4360 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 03:50:57.939  4344  4360 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-25 03:50:57.941  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:50:57.943  3948  3948 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:50:57.943  3948  3998 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:50:57.943  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:57.944  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.944  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:57.944  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:57.945  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:50:57.945  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 03:50:57.945  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c521ae3 not in the list
08-25 03:50:57.945  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:50:57.945  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:57.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:50:57.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:50:57.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:50:57.946  3948  3998 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c521ae3 not in the list
08-25 03:50:57.946  3948  3998 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:50:57.946  3948  3998 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:50:57.946  3948  3998 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:50:57.946  3948  3998 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f95a312 not in the list
08-25 03:50:57.947  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 03:50:57.947  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-25 03:50:57.948  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 03:50:57.948  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:50:57.948  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-25 03:50:57.948  3948  3998 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 03:50:58.407  3948  3948 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:50:59.963  3948  4461 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 494, name: My test thread name)
,08-25 03:51:00.610  1535  1535 I ConfigService: onDestroy
,08-25 03:51:01.960  3948  3998 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 494
,08-25 03:51:01.961  3948  3998 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 494, name: My test thread name)
,08-25 03:51:01.967  3948  4463 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: My test thread name)
,08-25 03:51:01.968  3948  4463 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 495, thread name: My test thread name)
08-25 03:51:01.968  3948  4463 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 495, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-25 03:51:01.972  3948  3998 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:51:01.981  3948  4464 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 499, name: My test thread name)
,08-25 03:51:01.982  3948  4464 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 499, thread name: My test thread name): Test exception.
,08-25 03:51:01.983  3948  4464 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 499, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-25 03:51:01.989  3948  3998 I jxcore-log: Total number of executed tests:  82
08-25 03:51:01.989  3948  3998 I jxcore-log: 
,08-25 03:51:01.990  3948  3998 I jxcore-log: Number of passed tests:  82
08-25 03:51:01.990  3948  3998 I jxcore-log: 
,08-25 03:51:01.991  3948  3998 I jxcore-log: Number of failed tests:  0
08-25 03:51:01.991  3948  3998 I jxcore-log: 
,08-25 03:51:01.991  3948  3998 I jxcore-log: Number of ignored tests:  0
08-25 03:51:01.991  3948  3998 I jxcore-log: 
,08-25 03:51:01.993  3948  3998 I jxcore-log: Total duration:  101351
08-25 03:51:01.993  3948  3998 I jxcore-log: 
,08-25 03:51:01.999  3948  3998 I jxcore-log: Unit Test app is loaded
08-25 03:51:01.999  3948  3998 I jxcore-log: 
,08-25 03:51:02.022  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.022  3948  3998 I jxcore-log: 
,08-25 03:51:02.027  3948  3948 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-25 03:51:02.037  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.037  3948  3998 I jxcore-log: 
,08-25 03:51:02.041  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.041  3948  3998 I jxcore-log: 
,08-25 03:51:02.045  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.045  3948  3998 I jxcore-log: 
,08-25 03:51:02.049  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-25 03:51:02.049  3948  3998 I jxcore-log: 
,08-25 03:51:02.055  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.055  3948  3998 I jxcore-log: 
,08-25 03:51:02.058  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.058  3948  3998 I jxcore-log: 
,08-25 03:51:02.060  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.060  3948  3998 I jxcore-log: 
,08-25 03:51:02.061  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-25 03:51:02.061  3948  3998 I jxcore-log: 
,08-25 03:51:02.062  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.062  3948  3998 I jxcore-log: 
08-25 03:51:02.062  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.062  3948  3998 I jxcore-log: 
,08-25 03:51:02.063  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.063  3948  3998 I jxcore-log: 
08-25 03:51:02.064  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.064  3948  3998 I jxcore-log: 
,08-25 03:51:02.065  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.065  3948  3998 I jxcore-log: 
08-25 03:51:02.066  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.066  3948  3998 I jxcore-log: 
,08-25 03:51:02.067  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.067  3948  3998 I jxcore-log: 
,08-25 03:51:02.068  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.068  3948  3998 I jxcore-log: 
08-25 03:51:02.069  3948  4461 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 494, name: My test thread name), during the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
08-25 03:51:02.069  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.069  3948  3998 I jxcore-log: 
08-25 03:51:02.070  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.070  3948  3998 I jxcore-log: 
08-25 03:51:02.071  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.071  3948  3998 I jxcore-log: 
,08-25 03:51:02.072  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.072  3948  3998 I jxcore-log: 
08-25 03:51:02.072  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.072  3948  3998 I jxcore-log: 
,08-25 03:51:02.073  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.073  3948  3998 I jxcore-log: 
,08-25 03:51:02.074  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.074  3948  3998 I jxcore-log: 
08-25 03:51:02.075  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.075  3948  3998 I jxcore-log: 
,08-25 03:51:02.076  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.076  3948  3998 I jxcore-log: 
08-25 03:51:02.077  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.077  3948  3998 I jxcore-log: 
,08-25 03:51:02.077  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.077  3948  3998 I jxcore-log: 
,08-25 03:51:02.078  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.078  3948  3998 I jxcore-log: 
,08-25 03:51:02.080  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.080  3948  3998 I jxcore-log: 
,08-25 03:51:02.081  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.081  3948  3998 I jxcore-log: 
08-25 03:51:02.082  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.082  3948  3998 I jxcore-log: 
,08-25 03:51:02.083  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.083  3948  3998 I jxcore-log: 
08-25 03:51:02.083  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.083  3948  3998 I jxcore-log: 
,08-25 03:51:02.084  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.084  3948  3998 I jxcore-log: 
08-25 03:51:02.085  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.085  3948  3998 I jxcore-log: 
,08-25 03:51:02.086  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.086  3948  3998 I jxcore-log: 
,08-25 03:51:02.086  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:51:02.086  3948  3998 I jxcore-log: 
08-25 03:51:02.087  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.087  3948  3998 I jxcore-log: 
,08-25 03:51:02.088  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:51:02.088  3948  3998 I jxcore-log: 
08-25 03:51:02.089  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.089  3948  3998 I jxcore-log: 
,08-25 03:51:02.090  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.090  3948  3998 I jxcore-log: 
08-25 03:51:02.090  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.090  3948  3998 I jxcore-log: 
,08-25 03:51:02.091  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.091  3948  3998 I jxcore-log: 
08-25 03:51:02.092  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.092  3948  3998 I jxcore-log: 
,08-25 03:51:02.093  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.093  3948  3998 I jxcore-log: 
08-25 03:51:02.094  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.094  3948  3998 I jxcore-log: 
,08-25 03:51:02.094  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-25 03:51:02.094  3948  3998 I jxcore-log: 
,08-25 03:51:02.096  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.096  3948  3998 I jxcore-log: 
,08-25 03:51:02.097  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.097  3948  3998 I jxcore-log: 
08-25 03:51:02.097  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-25 03:51:02.097  3948  3998 I jxcore-log: 
,08-25 03:51:02.098  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-25 03:51:02.098  3948  3998 I jxcore-log: 
08-25 03:51:02.099  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:51:02.099  3948  3998 I jxcore-log: 
,08-25 03:51:02.099  3948  3998 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:51:02.099  3948  3998 I jxcore-log: 
,08-25 03:51:02.102  3948  3998 I jxcore-log: My device name is: motorola-Nexus 6
08-25 03:51:02.102  3948  3998 I jxcore-log: 
,08-25 03:51:04.692  3948  3998 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-25 03:51:04.692  3948  3998 I jxcore-log: 
,08-25 03:51:05.169  3948  3998 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-25 03:51:05.169  3948  3998 I jxcore-log: 
,08-25 03:51:05.194  3948  3998 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-25 03:51:05.194  3948  3998 I jxcore-log: 
,08-25 03:51:06.397  3914  4465 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 03:51:06.423  3914  4466 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 03:51:06.436  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:06.440  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:06.477  1535  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:51:06.477  1535  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 03:51:06.477  1535  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:51:06.477  1535  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:51:06.506  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:06.508  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:06.536  1535  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 03:51:06.536  1535  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 03:51:06.536  1535  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 03:51:06.536  1535  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:51:06.553  3914  4466 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:51:06.554  3914  4465 E BooksSync: Soft error
08-25 03:51:06.554  3914  4465 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:51:06.554  3914  4465 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:51:06.554  3914  4465 E BooksSync: Sync error
08-25 03:51:06.554  3914  4465 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 03:51:06.554  3914  4465 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-25 03:51:06.554  3914  4465 I BooksSync: Finished books sync
,08-25 03:51:06.565   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 221014, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 03:51:06.650  3948  3998 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-25 03:51:06.650  3948  3998 I jxcore-log: 
,08-25 03:51:06.892  3948  3998 I jxcore-log: ERROR runTests: 
08-25 03:51:06.892  3948  3998 I jxcore-log: 
,08-25 03:51:06.894  3948  3998 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-25 03:51:06.894  3948  3998 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-25 03:51:06.908  3948  3998 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _functionName: 'loadFile',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _lineNumber: '26',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _columnNumber: '11',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-25 03:51:06.908  3948  3998 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _functionName: '',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _lineNumber: '38',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _columnNumber: '7',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-25 03:51:06.908  3948  3998 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _functionName: '',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _lineNumber: '35',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _columnNumber: '3',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-25 03:51:06.908  3948  3998 I jxcore-log:   { _fileName: 'module.js',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _functionName: '$w.prototype._compile',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _lineNumber: '621',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _columnNumber: '8',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-25 03:51:06.908  3948  3998 I jxcore-log:   { _fileName: 'module.js',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _lineNumber: '651',
08-25 03:51:06.908  3948  3998 I jxcore-log:     _columnNumber: '1',
08-25 03:51:06.908  3948  3998 I jxcore-log:    
08-25 03:51:06.908  3948  3998 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-25 03:51:06.908  3948  3998 I jxcore-log: 
,08-25 03:51:06.909  3948  3998 E jxcore-log: Error: 
08-25 03:51:06.909  3948  3998 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-25 03:51:06.909  3948  3998 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-25 03:51:06.909  3948  3998 E jxcore-log: 
,08-25 03:51:07.362  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:07.372  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:07.376  1535  1535 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 03:51:07.435  1535  1556 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 03:51:07.435  1535  1556 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 03:51:07.436  1535  1556 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 03:51:07.436  1535  1556 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 03:51:07.487  3661  3661 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 03:51:07.488  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 03:51:07.488  3661  3661 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-25 03:51:07.582  4467  4467 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 03:51:07.586  4467  4467 D AndroidRuntime: CheckJNI is OFF
,08-25 03:51:07.627  4467  4467 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 03:51:07.665   874  4401 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 03:51:07.675  4467  4467 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 03:51:07.698  4467  4467 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 03:51:07.709   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 03:51:07.710   874   887 I ActivityManager: Killing 3948:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 03:51:07.810   874  1965 I WindowState: WIN DEATH: Window{5ce8bb6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 03:51:07.810   874   884 D GraphicsStats: Buffer count: 2
,08-25 03:51:07.812   874  1318 D WifiService: Client connection lost with reason: 4
,08-25 03:51:07.879   874   897 W PackageSettings: Skipping PackageSetting{902ce3f com.example.hello/10273} due to missing metadata
,08-25 03:51:07.902   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 03:51:07.902   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 03:51:07.903   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-25 03:51:07.903   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 03:51:07.903   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:07.903   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:07.903   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:51:07.903   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 03:51:07.904   874   887 I ActivityManager:   Force finishing activity ActivityRecord{2767edf u0 com.test.thalitest/.MainActivity t2}
,08-25 03:51:07.904   874   897 I art     : Starting a blocking GC Explicit
,08-25 03:51:07.920   874   884 W ActivityManager: Spurious death for ProcessRecord{11b98e0 0:com.test.thalitest/u0a0}, curProc for 3948: null
,08-25 03:51:07.948   874   897 I art     : Explicit concurrent mark sweep GC freed 16457(1175KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 707us total 43.709ms
,08-25 03:51:07.976   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 03:51:07.982  4467  4467 I art     : System.exit called, status: 0
,08-25 03:51:07.982  4467  4467 I AndroidRuntime: VM exiting with result code 0.
,08-25 03:51:07.990   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 03:51:08.016   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 03:51:08.019  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
08-25 03:51:08.019  4344  4344 D BluetoothMapAppObserver: onReceive
08-25 03:51:08.019  4344  4344 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 03:51:08.025  2117  2287 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 03:51:08.029   874  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 03:51:08.032  3797  3797 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 03:51:08.040  1865  4480 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 03:51:08.046  1926  1926 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 03:51:08.047  1865  4480 I Decoder : createOrResetDecoder
,08-25 03:51:08.092   874  2630 I ActivityManager: Start proc 4483:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 03:51:08.099  1535  1535 I ConfigService: onCreate
,08-25 03:51:08.109   874  1312 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-25 03:51:08.122  1535  4495 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 03:51:08.122  1535  4495 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 03:51:08.122  1535  4495 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-25 03:51:08.123  1535  4495 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-25 03:51:08.126   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 03:51:08.129  4483  4483 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 03:51:08.141   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 03:51:08.143   874   886 E PackageManager: Failed to write settings, restoring backup
08-25 03:51:08.143   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 03:51:08.143   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 03:51:08.143   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 03:51:08.143   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 03:51:08.143   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 03:51:08.143   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.143   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.143   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.146   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-25 03:51:08.146   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 03:51:08.146   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.146   874   887 E DropBoxManagerService: 	... 13 more
,08-25 03:51:08.146  1941  2016 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 03:51:08.146   874  1937 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3948 uid 10000
,08-25 03:51:08.156  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 03:51:08.157  1865  4480 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-25 03:51:08.158   874  2630 I ActivityManager: Start proc 4496:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-25 03:51:08.159  1941  2016 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 03:51:08.159  1941  2016 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1941
08-25 03:51:08.159  1941  2016 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.159  1941  2016 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.162   874  4503 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:51:08.162   874  4503 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.162   874  4503 E DropBoxManagerService: 	... 5 more
,08-25 03:51:08.165   874  1965 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 03:51:08.171  1941  2016 I Process : Sending signal. PID: 1941 SIG: 9
,08-25 03:51:08.203  1865  4480 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 03:51:08.204  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 03:51:08.205  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 03:51:08.207  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-25 03:51:08.207  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 03:51:08.208  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 03:51:08.208  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 03:51:08.209  1865  4480 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 03:51:08.209  1865  4480 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit),
08-25 03:51:08.209  1865  4480 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 03:51:08.209  1865  4480 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-25 03:51:08.209  1865  4480 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 03:51:08.209  1865  4480 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 03:51:08.219   874  1932 D GraphicsStats: Buffer count: 1
,08-25 03:51:08.219   874  1965 I WindowState: WIN DEATH: Window{3f1d3fd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 03:51:08.232   874  1403 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1941) has died
,08-25 03:51:08.235   874  1403 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 03:51:08.240   874  1403 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 03:51:08.248  4483  4512 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.248  4483  4512 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.248  4483  4512 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.254  4483  4483 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 03:51:08.263   874   887 I ActivityManager: Start proc 4515:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 03:51:08.277  4483  4527 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 03:51:08.283   874  1399 I ActivityManager: Start proc 4529:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 03:51:08.318  4515  4515 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:51:08.318  4515  4515 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:51:08.319  4515  4515 D AndroidRuntime: Shutting down VM
08-25 03:51:08.322  4529  4529 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-25 03:51:08.327  4515  4515 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:51:08.327  4,515  4515 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4515
08-25 03:51:08.327  4515  4515 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	at android.app.Activity,Thread.installProvider(ActivityThread.java:5153)
08-25 03:51:08.327  4515  4515 E AndroidRuntime: 	... 10 more
08-25 03:51:08.330   874  1932 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:51:08.331  4515  4515 I Process : Sending signal. PID: 4515 SIG: 9
08-25 03:51:08.332   874  4542 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:51:08.332   874  4542 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.332   874  4542 E DropBoxManagerService: 	... 5 more
08-25 03:51:08.346  1750  4539 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-25 03:51:08.347  1750  4539 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-25 03:51:08.358  1750  4539 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-25 03:51:08.359  1750  4539 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-25 03:51:08.362   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4515) has died
,08-25 03:51:08.363   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 03:51:08.370  1535  1535 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-25 03:51:08.370  1535  1535 D AndroidRuntime: Shutting down VM
08-25 03:51:08.371  1535  1535 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:51:08.371  1535  1535 E AndroidRuntime: Process: com.google.process.gapps, PID: 1535
08-25 03:51:08.371  1535  1535 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 03:51:08.371  1535  1535 E AndroidRuntime: 	... 8 more
,08-25 03:51:08.382   874   887 I ActivityManager: Start proc 4546:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:51:08.387   874  4556 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:51:08.387   874  4556 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.387   874  4556 E DropBoxManagerService: 	... 5 more
08-25 03:51:08.387  1535  1535 I Process : Sending signal. PID: 1535 SIG: 9
,08-25 03:51:08.415  4483  4512 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-25 03:51:08.420  4483  4527 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.420  4483  4527 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.421  4483  4527 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 03:51:08.421  4483  4527 E AndroidRuntime: Process: android.process.acore, PID: 4483
08-25 03:51:08.421  4483  4527 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.421  4483  4527 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 03:51:08.425   874  4559 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:51:08.425   874  4559 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.425   874  4559 E DropBoxManagerService: 	... 5 more
,08-25 03:51:08.440   874  1318 D WifiService: Client connection lost with reason: 4
,08-25 03:51:08.444  4546  4546 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:51:08.444  4546  4546 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 03:51:08.444  4546  4546 D AndroidRuntime: Shutting down VM
,08-25 03:51:08.448  4483  4527 I Process : Sending signal. PID: 4483 SIG: 9
,08-25 03:51:08.450   874  1403 I ActivityManager: Process com.google.process.gapps (pid 1535) has died
,08-25 03:51:08.450   874  1403 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-25 03:51:08.450   874  1403 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
08-25 03:51:08.450   874  1403 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-25 03:51:08.459  1750  1750 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-25 03:51:08.462  4546  4546 E AndroidRuntime: FATAL EXCEPTION: main
08-25 03:51:08.462  4546  4546 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4546
08-25 03:51:08.462  4546  4546 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 03:51:08.462  4546  4546 E AndroidRuntime: 	... 10 more
08-25 03:51:08.464   874  1939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 03:51:08.465  4546  4546 I Process : Sending signal. PID: 4546 SIG: 9
08-25 03:51:08.467   874  4560 E DropBoxManagerService: Can't write: system_app_crash
08-25 03:51:08.467   874  4560 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 03:51:08.467   874  4560 E DropBoxManagerService: 	... 5 more
08-25 03:51:08.474   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
