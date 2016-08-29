#### Test 82883341eb96f76_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-29 15:17:44.223  3743  3911 I BooksSync: Starting books sync for 61035162, extras: ade
08-29 15:17:44.275  3743  3912 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
08-29 15:17:44.303  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:44.309  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:44.375  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 15:17:44.376  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:17:44.376  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:44.376  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 15:17:44.456  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:44.462  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:44.519  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 15:17:44.519  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:17:44.519  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:44.520  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 15:17:44.571  3743  3912 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:17:44.585  3743  3911 E BooksSync: Soft error
08-29 15:17:44.585  3743  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:17:44.585  3743  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:17:44.586  3743  3911 E BooksSync: Sync error
08-29 15:17:44.586  3743  3911 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:17:44.586  3743  3911 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:17:44.586  3743  3911 I BooksSync: Finished books sync
08-29 15:17:44.596   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129030, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-29 15:17:44.934  3913  3913 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 15:17:44.940  3913  3913 D AndroidRuntime: CheckJNI is OFF
08-29 15:17:44.985  3913  3913 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 15:17:45.037  3913  3913 I Radio-JNI: register_android_hardware_Radio DONE
08-29 15:17:45.060  3913  3913 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 15:17:45.069   869  2033 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 15:17:45.111  2072  2087 W SearchService: Abort, client detached.
08-29 15:17:45.113  3913  3913 D AndroidRuntime: Shutting down VM
08-29 15:17:45.122  2072  2072 I HotwordDetector: Closing mic
08-29 15:17:45.122  2072  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@68567bc
08-29 15:17:45.123  2072  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 15:17:45.156   869  2022 I ActivityManager: Start proc 3923:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 15:17:45.170   373  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 15:17:45.172   373  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 15:17:45.182   373  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 15:17:45.189  2072  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 15:17:45.189  2072  2354 I MicroRecognitionRnrImpl: Detection finished
08-29 15:17:45.241  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:45.241  3923  3923 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 15:17:45.243  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:17:45.259  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-29 15:17:45.259  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-29 15:17:45.259  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:45.259  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:17:45.269  2072  2211 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-29 15:17:45.271  2072  3937 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 15:17:45.275  3923  3923 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 15:17:45.282  3923  3923 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 125-127)
08-29 15:17:45.283  3923  3923 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:17:45.298  3923  3923 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fda9892}
08-29 15:17:45.298  3923  3923 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:17:45.299  3923  3923 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 15:17:45.300  2072  3937 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 15:17:45.305  2072  3937 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 148-150)
08-29 15:17:45.305  2072  3937 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 15:17:45.306  3923  3923 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 15:17:45.307  3923  3923 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 15:17:45.331  3923  3923 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 15:17:45.342  3923  3923 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 15:17:45.342  3923  3923 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 15:17:45.342  3923  3923 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:17:45.342  3923  3923 I Adreno  : Build Date                       : 10/20/15
08-29 15:17:45.342  3923  3923 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:17:45.342  3923  3923 I Adreno  : Local Branch                     : M14
08-29 15:17:45.342  3923  3923 I Adreno  : Remote Branch                    : 
08-29 15:17:45.342  3923  3923 I Adreno  : Remote Branch                    : 
08-29 15:17:45.342  3923  3923 I Adreno  : Reconstruct Branch               : 
,08-29 15:17:45.395   869   886 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d59021c:true
,08-29 15:17:45.435  3923  3923 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 15:17:45.449  3923  3923 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 15:17:45.486  3923  3977 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 15:17:45.492  3923  3956 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 15:17:45.515  3923  3977 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 15:17:45.569   869   887 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +430ms
,08-29 15:17:45.570  1898  1898 I Keyboard.Facilitator: onFinishInput()
,08-29 15:17:45.638  3923  3923 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3923
,08-29 15:17:45.741  3923  3923 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 15:17:45.887  3923  3979 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700792016
,08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 15:17:45.892  3923  3979 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@479e11 added. We now have 1 listener(s)
,08-29 15:17:45.896  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 15:17:45.897  3923  3979 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:17:45.898  3923  3979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:17:45.898  3923  3979 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-29 15:17:45.904  3923  3979 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@865e4 added. We now have 1 listener(s)
08-29 15:17:45.904  3923  3979 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:17:45.907   869  1317 D WifiService: New client listening to asynchronous messages
,08-29 15:17:45.908  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:17:45.908  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-29 15:17:45.909  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 15:17:45.909  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 15:17:45.909  3923  3979 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 15:17:45.915  3923  3979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:17:45.915  3923  3979 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-29 15:17:45.926  3923  3979 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:17:45.927  3923  3979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:17:45.927  3923  3979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-29 15:17:45.927  3923  3979 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:17:45.928  3923  3979 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:17:45.929  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:45.931  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:17:45.981   869  3218 I ActivityManager: Killing 3110:com.google.android.talk/u0a61 (adj 15): empty #17
,08-29 15:17:46.018   869  3218 I ActivityManager: Killing 3015:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 15:17:46.089  3923  3923 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 15:17:46.877  3923  3986 W jxcore-log: Initializing JXcore engine
,08-29 15:17:46.877  3923  3986 W jxcore-log: JXcore engine is ready
,08-29 15:17:46.912  3986  3986 W Thread-349: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-29 15:17:46.912  3986  3986 W Thread-349: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13449]" dev="sockfs" ino=13449 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 15:17:46.912  3986  3986 W Thread-349: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 15:17:46.912  3986  3986 W Thread-349: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26356]" dev="sockfs" ino=26356 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 15:17:46.927  3923  3986 W jxcore-log: Starting JXcore engine
,08-29 15:17:47.005  3923  3986 W jxcore-log: Platform android
08-29 15:17:47.005  3923  3986 W jxcore-log: 
,08-29 15:17:47.005  3923  3986 W jxcore-log: Process ARCH arm
08-29 15:17:47.005  3923  3986 W jxcore-log: 
,08-29 15:17:47.200  3923  3986 I jxcore-log: JXcore Cordova bridge is ready!
08-29 15:17:47.200  3923  3986 I jxcore-log: 
,08-29 15:17:47.201  3923  3986 W jxcore-log: JXcore engine is started
,08-29 15:17:47.212  3923  3979 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 15:17:47.216  3923  3923 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 15:17:55.287  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:17:55.289  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:17:55.298  3494  3997 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:17:55.317  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 15:17:55.317  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 15:17:55.317  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:55.317  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 15:17:55.329  3494  3997 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 15:17:55.427  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:17:55.429  1514  3999 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 15:17:55.431  1514  3999 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 15:17:55.446  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 15:17:55.446  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 15:17:55.446  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:55.446  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:17:55.456  1514  3999 W Uploader:  no longer exists, so no auth token.
,08-29 15:17:55.460  3607  3607 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 15:17:55.461  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 15:17:55.461  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 15:17:56.467  1514  3999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 15:17:56.467  1514  3999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 15:17:56.467  1514  3999 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:17:56.467  1514  3999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:17:56.494  1514  3999 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 15:17:56.494  1514  3999 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 15:17:56.494  1514  3999 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 15:17:56.819  1514  3999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 15:17:56.820  1514  3999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-29 15:17:56.820  1514  3999 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:17:56.820  1514  3999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:17:56.870  1514  3999 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 15:17:56.870  1514  3999 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 15:17:56.870  1514  3999 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 15:17:57.277  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 15:17:57.277  3923  3986 I jxcore-log: 
,08-29 15:17:57.279  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 15:17:57.279  3923  3986 I jxcore-log: 
,08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:17:57.288  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:17:57.293  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:17:57.295  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 15:17:57.295  3923  3986 I jxcore-log: 
,08-29 15:17:57.296  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 15:17:57.296  3923  3986 I jxcore-log: 
,08-29 15:17:57.435  1514  3999 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 15:17:57.435  1514  3999 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 15:17:57.436  1514  3999 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:17:57.436  1514  3999 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:17:57.475  1514  3999 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 15:17:57.475  1514  3999 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 15:17:57.475  1514  3999 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 15:17:57.805   869  2022 D WifiService: setWifiEnabled: true pid=3923, uid=10000
,08-29 15:17:57.805   869  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:17:57.812  3923  3986 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 15:17:57.814  3923  3986 I jxcore-log: Unit Test app is loaded
08-29 15:17:57.814  3923  3986 I jxcore-log: 
,08-29 15:17:57.818  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:17:57.818  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1293397 added. We now have 2 listener(s)
08-29 15:17:57.819  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:17:57.819  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:17:57.819  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:17:57.819  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:17:57.819  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a0d2984 added. We now have 2 listener(s)
08-29 15:17:57.819  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:17:57.821  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:17:57.825  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 15:17:57.830   869  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 15:17:57.831   869  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 15:17:57.831  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:17:57.831   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:17:57.832   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:17:57.841  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:17:57.842  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:17:57.842  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:17:57.842  3923  3986 D ExecuteNativeTests: Running unit tests
08-29 15:17:57.844  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:17:57.846  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:57.847  3923  3923 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 15:17:57.850   869  1919 D DhcpClient: Clearing IP address
,08-29 15:17:57.850   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:17:57.854   369   868 D CommandListener: Setting iface cfg
,08-29 15:17:57.856  1514  2759 V NativeCrypto: Read error: ssl=0x9ad88400: I/O error during system call, Connection timed out
08-29 15:17:57.858  1514  2759 V NativeCrypto: SSL shutdown failed: ssl=0x9ad88400: I/O error during system call, Broken pipe
,08-29 15:17:57.860   869  2068 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-29 15:17:57.860   869  1886 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-29 15:17:57.862   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 15:17:57.862   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 15:17:57.864   403   403 E Parcel  : Reading a NULL string not supported here.
08-29 15:17:57.866   869  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 15:17:57.868   869  1921 D DhcpClient: Receive thread stopped
08-29 15:17:57.869   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:17:57.871   869  1886 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 15:17:57.876   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:17:57.884   869   882 I ActivityManager: Start proc 4010:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-29 15:17:57.884   869  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 15:17:57.888   869  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 15:17:57.889   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:17:57.916   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:17:57.934  4010  4010 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-29 15:17:57.945   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:17:57.946  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:17:57.946  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 added. We now have 3 listener(s)
08-29 15:17:57.946   869  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 15:17:57.947   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 15:17:57.947  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:17:57.947  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:17:57.947  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:17:57.947  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:17:57.948  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 added. We now have 3 listener(s)
08-29 15:17:57.948  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:17:57.948  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:17:57.948   869   886 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:17:57.952  3456  3456 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@9e394c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 15:17:57.954  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:17:57.955  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:17:57.956  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:17:57.957  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:17:57.958  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:17:57.960  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:17:57.960  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:17:57.961  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:17:57.962  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 15:17:57.962  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-29 15:17:57.962  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:17:57.962  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:17:57.962  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 15:17:57.963  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:57.964  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:57.964  3923  3986 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 15:17:57.964  3923  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 15:17:57.964  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:17:57.965  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:17:57.965  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 15:17:57.965  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:17:57.966  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:17:57.966  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:17:57.966  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:17:57.966  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:17:57.966  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:17:57.966  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:17:57.966  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:17:57.966  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 removed from the list
08-29 15:17:57.966  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.967  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 removed from the list
08-29 15:17:57.967  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 15:17:57.967  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:17:57.968  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:17:57.968  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:17:57.969  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:17:57.969  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:17:57.969  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.969  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:17:57.970  3923  3986 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 15:17:57.970  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:17:57.970  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:17:57.970  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:17:57.971  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:17:57.971  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:17:57.971  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:17:57.971  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:17:57.971  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.971  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:17:57.971  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:17:57.971  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:17:57.971  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:17:57.971  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:17:57.971  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:17:57.972  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:17:57.972  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:17:57.972  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.972  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-29 15:17:57.976  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:17:57.977  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 15:17:57.978  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 15:17:57.978  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 15:17:57.978  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:17:57.978  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:17:57.978  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:17:57.978  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:17:57.978  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:17:57.978  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:17:57.978  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:17:57.978  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.978  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:17:57.978  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:17:57.978  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:17:57.978  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:17:57.978  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:17:57.978  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:17:57.979  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:17:57.979  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:17:57.979  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:17:57.979  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:17:57.981  3923  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
08-29 15:17:57.983  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:17:57.985  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:17:57.986  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:17:57.986  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:17:57.987  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:57.988  3923  3986 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-29 15:17:57.988  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-29 15:17:57.988  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:17:57.989  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 15:17:57.989  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 15:17:57.989  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 15:17:57.989  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:17:57.990  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 15:17:57.991  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 15:17:57.991  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:17:57.991  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 15:17:57.996  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 15:17:57.996  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 15:17:57.996  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:17:57.996  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:17:57.997  3923  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:17:57.998   369   868 E Netd    : netlink response contains error (No such file or directory)
08-29 15:17:57.999  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 15:17:57.999  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:17:57.999   869  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 15:17:57.999   869  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 15:17:57.999  3923  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-29 15:17:58.002  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 15:17:58.004  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:17:58.004  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:17:58.005  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 15:17:58.005  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:17:58.006  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-29 15:17:58.006  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 15:17:58.007  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 15:17:58.007  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 15:17:58.007  3923  3986 D BluetoothAdapter: STATE_ON
08-29 15:17:58.011  2720  2730 D BtGatt.GattService: registerClient() - UUID=e1da8c2b-19f9-4197-88ed-e24aaa90c017
08-29 15:17:58.012  2720  2775 D BtGatt.GattService: onClientRegistered() - UUID=e1da8c2b-19f9-4197-88ed-e24aaa90c017, clientIf=5
08-29 15:17:58.012  3923  3935 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-29 15:17:58.015  2720  2778 D BtGatt.AdvertiseManager: message : 0
,08-29 15:17:58.018  2720  2778 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 15:17:58.031  2720  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 15:17:58.036  2720  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 15:17:58.037  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 15:17:58.037  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 15:17:58.038  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:17:58.039  3923  3986 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:17:58.039  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 15:17:58.040  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 15:17:58.040  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-29 15:17:58.040  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-29 15:17:58.040  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 15:17:58.040  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 15:17:58.042  3923  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 15:17:58.042  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 15:17:58.117  4010  4036 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 15:17:58.117  4010  4036 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 15:17:58.120  4010  4036 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 15:17:58.120  4010  4036 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 15:17:58.150  4010  4036 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 15:17:58.150  4010  4036 I Babel_SMS: MmsConfig.loadFromResources,
08-29 15:17:58.151  4010  4036 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 15:17:58.152  4010  4036 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 15:17:58.185  4010  4010 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:17:58.187  4010  4010 I Babel_Crash: startup - clean
,08-29 15:17:58.206  4010  4010 I Babel_telephony: TeleModule.launchCompleted
,08-29 15:17:58.220   869  1691 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 15:17:58.233  4010  4010 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 15:17:58.240  4010  4010 W Babel   : BAM#gBA: invalid account id: -1
,08-29 15:17:58.240  4010  4010 W Babel   : BAM#gBA: invalid account id: -1
,08-29 15:17:58.240  4010  4010 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-29 15:17:58.242  4010  4041 I Babel   : deleted: false for 0
,08-29 15:17:58.252   869  3218 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 15:17:58.285  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:17:58.293  1717  1717 D SystemUpdateService: onCreate
,08-29 15:17:58.315  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:17:58.346  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 15:17:58.348  1717  2473 I iu.UploadsManager: num queued entries: 0
,08-29 15:17:58.373  1717  4043 I SystemUpdateService: active receiver: enabled
,08-29 15:17:58.380  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:17:58.381  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:17:58.393  1717  2473 I iu.UploadsManager: num updated entries: 0
,08-29 15:17:58.393  1717  2473 I iu.SyncManager: NEXT; no task
,08-29 15:17:58.397   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:17:58.404  4010  4010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 15:17:58.415  1717  4043 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:17:58.427   869  1690 I ActivityManager: Start proc 4045:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 15:17:58.450  1717  4043 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-29 15:17:58.450  1717  4043 I SystemUpdateService: now status is 0 (complete)
08-29 15:17:58.450  1717  4043 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 15:17:58.460  4045  4045 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 15:17:58.450  1717  4043 I SystemUpdateService: file has been verified
08-29 15:17:58.470  1717  4043 I SystemUpdateService: OTA package size = 12249756
,08-29 15:17:58.473  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:17:58.496  4010  4010 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 15:17:58.499  4045  4045 D SprintDMHelper: simOperator: 
,08-29 15:17:58.499  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:17:58.521  4010  4010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-29 15:17:58.523   869  3218 I ActivityManager: Start proc 4057:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 15:17:58.528  4010  4010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 15:17:58.536  1717  4043 I SystemUpdateService: showing system update notification
,08-29 15:17:58.541  4010  4010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 15:17:58.543  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 15:17:58.544  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:17:58.544  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:17:58.554  4010  4010 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 15:17:58.558   869  1377 I ActivityManager: Killing 3661:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 15:17:58.599  4010  4010 I vclib   : onServiceConnected
,08-29 15:17:58.657  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:17:58.659   869  2022 I ActivityManager: Killing 3456:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 15:17:58.714   869   880 I ActivityManager: Start proc 4072:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 15:17:58.718  4010  4071 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 15:17:58.734   869  1377 I ActivityManager: Killing 3546:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-29 15:17:58.753  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 15:17:58.813  4072  4072 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 15:17:58.813  4072  4072 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 15:17:58.813  4072  4072 I GAv4    :   adb logcat -s GAv4
,08-29 15:17:58.825  4072  4072 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 15:17:58.831  4072  4072 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 15:17:58.851  4072  4089 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 15:17:58.976  4072  4072 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 15:17:59.029  4072  4072 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 15:17:59.037  4072  4072 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3879-3882)
,08-29 15:17:59.038  4072  4072 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 15:17:59.049  4072  4072 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7d5de26}
,08-29 15:17:59.052  4072  4072 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 15:17:59.052  4072  4072 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 15:17:59.061  4072  4072 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 15:17:59.063  4072  4072 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 15:17:59.083  4072  4072 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 15:17:59.095  4072  4072 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 15:17:59.096  4072  4072 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 15:17:59.096  4072  4072 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:17:59.096  4072  4072 I Adreno  : Build Date                       : 10/20/15
08-29 15:17:59.096  4072  4072 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:17:59.096  4072  4072 I Adreno  : Local Branch                     : M14
08-29 15:17:59.096  4072  4072 I Adreno  : Remote Branch                    : 
08-29 15:17:59.096  4072  4072 I Adreno  : Remote Branch                    : 
08-29 15:17:59.096  4072  4072 I Adreno  : Reconstruct Branch               : 
,08-29 15:17:59.159  4072  4072 I NSApplication: Starting up...
,08-29 15:17:59.167  4072  4118 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 15:17:59.197   869  1687 I ActivityManager: Start proc 4123:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 15:17:59.198   869  1687 I ActivityManager: Killing 3702:com.google.android.keep/u0a79 (adj 15): empty #17
,08-29 15:17:59.199   280   280 E lowmemorykiller: Error writing /proc/3702/oom_score_adj; errno=22
,08-29 15:17:59.276  4123  4123 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 15:17:59.418   869  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=30.25 rxSuccessRate=27.00 delta 1000 -> 1
,08-29 15:17:59.420   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 15:17:59.420   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 15:17:59.450   869  1316 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:17:59.469   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
08-29 15:17:59.471  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 15:17:59.480   869   880 I ActivityManager: Killing 3590:android.process.acore/u0a5 (adj 15): empty #17
,08-29 15:17:59.889  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 15:17:59.925  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 15:17:59.928  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 15:17:59.937   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:17:59.947   869  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-29 15:17:59.948   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:17:59.948   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 15:17:59.970   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:17:59.980   369   868 D CommandListener: Setting iface cfg
,08-29 15:17:59.982   869  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 15:17:59.986   869  4143 D DhcpClient: Receive thread started
,08-29 15:17:59.995   869  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-29 15:17:59.996   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 15:18:00.080   869  1316 E native  : do suspend false
,08-29 15:18:00.090   869  1919 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 15:18:00.104   869  4143 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172678, domain null
,08-29 15:18:00.104   869  1919 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172678 seconds
,08-29 15:18:00.107   869  1919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 15:18:00.120   869  4143 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 15:18:00.120   869  1919 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 15:18:00.124   369   868 D CommandListener: Setting iface cfg
,08-29 15:18:00.133   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 15:18:00.135   869  1919 D DhcpClient: Scheduling renewal in 86399s
,08-29 15:18:00.153   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 15:18:00.154   869  1316 D WifiConfigStore: No blacklist allowed without epno enabled
08-29 15:18:00.155   869  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 15:18:00.155   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 15:18:00.158   869  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 15:18:00.164   869  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:18:00.242   869  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 15:18:00.242   869  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 15:18:00.246   869  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 15:18:00.253   869  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 15:18:00.256   869  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 15:18:00.268   869  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 15:18:00.274   869  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 15:18:00.274   869  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 15:18:00.274   869  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-29 15:18:00.274   869  1318 D ConnectivityService:    accepting network in place of null
08-29 15:18:00.276   869  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:18:00.281   869  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 15:18:00.281   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:18:00.316   869  4142 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145160, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 15:18:00.323   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:00.359   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:00.366   869  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 15:18:00.366   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:00.368   869  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-29 15:18:00.378   869   886 D Tethering: MasterInitialState.processMessage what=3
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:00.407  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:18:00.409  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:00.414  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:18:00.416  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:00.419  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:00.420  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:18:00.422  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:00.423  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:18:00.430  1717  1717 D SystemUpdateService: onCreate
,08-29 15:18:00.433  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:18:00.436   869  4141 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.206,2a00:1450:4001:815::200e
,08-29 15:18:00.445  1717  4153 I SystemUpdateService: active receiver: enabled
,08-29 15:18:00.448  1717  4153 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:18:00.450   869   881 I ActivityManager: Start proc 4158:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,08-29 15:18:00.458  1717  4153 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 15:18:00.458  1717  4153 I SystemUpdateService: now status is 0 (complete)
08-29 15:18:00.458  1717  4153 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 15:18:00.458  1717  4153 I SystemUpdateService: file has been verified
08-29 15:18:00.459  1717  4153 I SystemUpdateService: OTA package size = 12249756
,08-29 15:18:00.470  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 15:18:00.479  1717  2473 I iu.UploadsManager: num queued entries: 0
08-29 15:18:00.479  1717  2473 I iu.UploadsManager: num updated entries: 0
,08-29 15:18:00.481  1717  4153 I SystemUpdateService: showing system update notification
,08-29 15:18:00.483  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:18:00.484  4158  4158 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-29 15:18:00.484  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:18:00.487  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:00.490  1717  4170 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 15:18:00.490  1717  4170 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 15:18:00.492  4045  4045 D SprintDMHelper: simOperator: 
,08-29 15:18:00.492  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:18:00.500  1717  4170 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:18:00.523  1717  2473 I iu.SyncManager: NEXT; no task
,08-29 15:18:00.551  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:18:00.557  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 15:18:00.557  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 15:18:00.557  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:00.557  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:00.571   869  4141 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:18:00 GMT], X-Android-Received-Millis=[1472476680570], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472476680535]}
,08-29 15:18:00.571   869  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 15:18:00.571   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-29 15:18:00.571   869  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 15:18:00.572   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 15:18:00.580  1717  4170 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-29 15:18:00.652  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:18:00.652  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:18:00.652  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:00.652  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:00.666  4010  4174 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 15:18:00.676  3645  4173 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:18:00.676  3645  4173 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:00.676  3645  4173 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	... 12 more
08-29 15:18:00.676  3645  4173 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at fal.a(PG:38)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:18:00.676  3645  4173 E HttpOperation: 	... 14 more
,08-29 15:18:00.723  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:18:00.724  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
,08-29 15:18:00.724  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:00.724  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 15:18:00.742  4158  4183 V KeepSync: Connecting to GoogleApiClient
,08-29 15:18:00.743   869  1687 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-29 15:18:00.746  3645  4173 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:18:00.746  3645  4173 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at hec.a(PG:42)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at hee.a(PG:102)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at czr.a(PG:65)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at kka.a(PG:108)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:00.746  3645  4173 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	... 15 more
08-29 15:18:00.746  3645  4173 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at fal.a(PG:38)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:18:00.746  3645  4173 E HttpOperation: 	... 17 more
08-29 15:18:00.746  3645  4173 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:18:00.746  3645  4173 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08,-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	... 15 more
08-29 15:18:00.746  3645  4173 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:18:00.746  3645  4173 E ExperimentLoader: 	... 17 more
,08-29 15:18:00.815  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 15:18:00.815  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 15:18:00.815  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:18:00.815  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:00.831  1717  4193 V BaseAuthAsyncOperation: access token request failed
08-29 15:18:00.833  4158  4183 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:18:00.886  1514  1526 I art     : Background partial concurrent mark sweep GC freed 89611(6MB) AllocSpace objects, 5(240KB) LOS objects, 39% free, 24MB/40MB, paused 6.347ms total 49.178ms
,08-29 15:18:00.910   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131019, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:18:00.973  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 15:18:00.973  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 15:18:00.973  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:00.973  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:00.999  4158  4183 E KeepSync: IOException
08-29 15:18:00.999  4158  4183 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:18:00.999  4158  4183 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:18:00.999  4158  4183 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:18:00.999  4158  4183 E KeepSync: 	... 10 more
08-29 15:18:00.999  4158  4183 W KeepSync: Sync result 2
,08-29 15:18:01.012   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129569, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:18:01.367   869  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 15:18:01.377   869  1687 I ActivityManager: Killing 3801:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 15:18:03.046  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:03.047  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 15:18:03.047  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:18:03.047  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-29 15:18:03.048  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 15:18:03.048  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 15:18:03.051  3923  4030 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-29 15:18:03.051  3923  4030 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 15:18:03.052  3923  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:18:03.052  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 15:18:03.052  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 15:18:03.052  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 15:18:03.052  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 15:18:03.053  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:18:03.053  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:18:03.053  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:18:03.054  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:18:03.057  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:18:03.058  3923  3986 D BluetoothLeScanner: could not find callback wrapper
08-29 15:18:03.058  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:18:03.058  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-29 15:18:03.060  2720  2778 D BtGatt.AdvertiseManager: message : 1
,08-29 15:18:03.062  2720  2778 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 15:18:03.070  2720  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 15:18:03.070  2720  2775 D BtGatt.GattService: Client app is not null!
,08-29 15:18:03.075  2720  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 15:18:03.076  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 15:18:03.078  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 15:18:03.078  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 15:18:03.078  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 15:18:03.079  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-29 15:18:03.082  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:18:03.082  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:18:03.082  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:18:03.089  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:18:03.090  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:03.090  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:03.090  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:18:03.090  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:03.090  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:03.091  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:03.091  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:03.091  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:03.091  3923  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 15:18:03.091  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:18:03.091  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:18:03.091  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:18:03.592  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:18:05.544  4158  4165 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@752fb6e)
,08-29 15:18:08.098  3923  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-29 15:18:08.105  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:08.119  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:18:08.126  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:08.126  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:18:08.127  3923  3986 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-29 15:18:08.127  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-29 15:18:08.132  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 15:18:08.132  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 15:18:08.133  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-29 15:18:08.135  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:08.134  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:18:08.141  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 15:18:08.145  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:08.144  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 15:18:08.146  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:18:08.148  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 15:18:08.148  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 15:18:08.148  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-29 15:18:08.149  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:18:08.149  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:18:08.152  3923  4197 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:18:08.157  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:18:08.158  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:18:08.158  3923  4197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 15:18:08.165  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:18:08.166  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:18:08.167  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:18:08.170  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 15:18:08.171  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:18:08.171  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,08-29 15:18:08.172  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 15:18:08.172  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 15:18:08.172  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 15:18:08.173  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:18:08.178  2720  2927 D BtGatt.GattService: registerClient() - UUID=237fd432-82bd-45ca-bde8-f5c93ea2718c
,08-29 15:18:08.179  2720  2775 D BtGatt.GattService: onClientRegistered() - UUID=237fd432-82bd-45ca-bde8-f5c93ea2718c, clientIf=5
,08-29 15:18:08.179  3923  3934 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 15:18:08.181  2720  2778 D BtGatt.AdvertiseManager: message : 0
,08-29 15:18:08.185  2720  2778 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 15:18:08.194   869   889 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 15:18:08.205  2720  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 15:18:08.221  2720  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 15:18:08.222   869   889 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 15:18:08.222   869   889 I Adreno  : Build Date                       : 10/20/15
08-29 15:18:08.222   869   889 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 15:18:08.222   869   889 I Adreno  : Local Branch                     : M14
08-29 15:18:08.222   869   889 I Adreno  : Remote Branch                    : 
08-29 15:18:08.222   869   889 I Adreno  : Remote Branch                    : 
08-29 15:18:08.222   869   889 I Adreno  : Reconstruct Branch               : 
08-29 15:18:08.223  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-29 15:18:08.223  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:18:08.230  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:18:08.235  3923  3986 I io.jxcore.node.ConnectionHelper: start: OK
08-29 15:18:08.234  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 15:18:08.239  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 15:18:08.241  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-29 15:18:08.242  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-29 15:18:08.243  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 15:18:08.244  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 15:18:08.249  3923  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 15:18:08.250  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 15:18:08.245  1898  1898 I Keyboard.Facilitator: onFinishInput()
,08-29 15:18:08.251   282   307 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (176 us)
,08-29 15:18:08.278   869  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-29 15:18:08.750  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 15:18:08.750  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:18:08.751  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:18:08.919  3923  3923 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 15:18:08.919  3923  3923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 15:18:08.956  3923  3923 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed3b978 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a09b238, 16908290=android.view.AbsSavedState$1@a09b238}, android:focusedViewId=100}]}]
,08-29 15:18:08.956  3923  3923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 15:18:08.956  3923  3923 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 15:18:08.956  3923  3923 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 15:18:08.956   869   889 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 15:18:08.969   869   889 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 15:18:08.975   869   887 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 15:18:08.978   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-29 15:18:08.979   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 15:18:09.217   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 15:18:09.221   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 15:18:09.228   869  1339 D SurfaceControl: Excessive delay in setPowerMode(): 254ms
,08-29 15:18:09.235   869   889 I DreamManagerService: Entering dreamland.
,08-29 15:18:09.236   869   889 I PowerManagerService: Dozing...
,08-29 15:18:09.238   869   884 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 15:18:09.278   373  1472 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 15:18:09.279   373  1472 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 15:18:09.290   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:18:09.292  1986  4201 D NfcService: Discovery configuration equal, not updating.
,08-29 15:18:09.302   869  1316 E native  : do suspend false
,08-29 15:18:09.321   869  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 15:18:09.334   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:18:09.337   869  1316 E native  : do suspend true
,08-29 15:18:09.415   373   373 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 15:18:09.416   373   373 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 15:18:09.794   869  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,08-29 15:18:13.244  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:13.245  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 15:18:13.245  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:18:13.246  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 15:18:13.246  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 15:18:13.246  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 15:18:13.247  3923  4197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 15:18:13.247  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 15:18:13.247  3923  4197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 15:18:13.248  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-29 15:18:13.248  3923  4197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:18:13.249  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 15:18:13.248  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 15:18:13.249  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:18:13.249  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:18:13.249  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:18:13.250  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:18:13.251  3923  3986 D BluetoothAdapter: STATE_ON
08-29 15:18:13.252  3923  3986 D BluetoothLeScanner: could not find callback wrapper
08-29 15:18:13.252  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:18:13.252  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 15:18:13.254  2720  2778 D BtGatt.AdvertiseManager: message : 1
08-29 15:18:13.255  2720  2778 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 15:18:13.255  1717  4206 I EventLogService: Opted in for usage reporting
08-29 15:18:13.256  1717  4206 I EventLogService: Aggregate from 1472474890478 (log), 1472474890478 (data)
,08-29 15:18:13.262  2720  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 15:18:13.263  2720  2775 D BtGatt.GattService: Client app is not null!
,08-29 15:18:13.263  2720  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 15:18:13.264  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:18:13.264  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-29 15:18:13.264  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-29 15:18:13.264  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-29 15:18:13.265  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-29 15:18:13.266  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:18:13.267  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:18:13.267  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:18:13.268  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:18:13.271  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:13.271  3923  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 15:18:13.271  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:13.272  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:18:13.272  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:13.272  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:18:13.272  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:13.272  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:18:13.273  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:13.273  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:13.273  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:18:13.273  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:13.274  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:13.275  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:13.277  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:13.278  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:18:13.278  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:13.278  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:13.280  3923  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 15:18:13.284  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:13.289  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:18:13.291  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:13.292  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:18:13.292  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:18:13.292  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:18:13.292  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 15:18:13.292  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:18:13.292  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:18:13.294  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:13.296  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 15:18:13.296  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:13.296  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:18:13.300  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:18:13.300  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:18:13.300  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:18:13.302  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 15:18:13.304  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 15:18:13.305  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 15:18:13.305  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:18:13.306  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 15:18:13.307  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:18:13.310  2720  2733 D BtGatt.GattService: registerClient() - UUID=340593af-ab69-4080-86ca-1ce549d7eed1
08-29 15:18:13.310  2720  2775 D BtGatt.GattService: onClientRegistered() - UUID=340593af-ab69-4080-86ca-1ce549d7eed1, clientIf=5
08-29 15:18:13.310  3923  3934 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 15:18:13.311  2720  2730 D BtGatt.GattService: start scan with filters
,08-29 15:18:13.315  2720  2779 D BtGatt.ScanManager: handling starting scan
,08-29 15:18:13.315  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 15:18:13.316  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 15:18:13.316  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:18:13.316  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 15:18:13.316  2720  2779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:13.319  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:18:13.320  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 15:18:13.320  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:18:13.321  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:18:13.322  2720  2775 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 15:18:13.322  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:18:13.324  3923  3986 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 15:18:13.324  2720  2779 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:18:13.329  2720  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:18:13.329  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:18:13.330  2720  2779 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:18:13.330  2720  2779 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 15:18:13.333  1717  4206 W EventLogAggregator: Unknown tag: snet_gcore
,08-29 15:18:13.333  1717  4206 W EventLogAggregator: Unknown tag: snet_launch_service
,08-29 15:18:13.339  2720  2775 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 15:18:13.339  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:18:13.344  2720  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:18:13.344  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:18:13.360  1717  4206 I ServiceDumpSys: dumping service [account]
,08-29 15:18:13.398   869  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 14 -> obsolete
,08-29 15:18:13.820  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 15:18:13.820  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:18:13.821  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:18:13.848  2720  2720 D BtGatt.ScanManager: awakened up at time 158693
,08-29 15:18:13.851  2720  2779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:18:13.893  2720  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-29 15:18:13.894  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:18:13.895  2720  2775 D BtGatt.GattService: current time is 158739820460
,08-29 15:18:13.896  2720  2775 D BtGatt.GattService: Batch record : [88, 120, 34, 16, 80, 103, 1, -128, -58, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96, 0, 81, 34, 97, 112, -14, -5, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -104, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 15:18:13.902  2720  2775 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96]
,08-29 15:18:13.906  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 15:18:13.907  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 15:18:13.922  3923  3923 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 2], added - the peer count is 1
,08-29 15:18:13.924  3923  3923 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 2], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-29 15:18:14.367  1864  2656 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 15:18:15.398  2720  2720 D BtGatt.ScanManager: awakened up at time 160242
,08-29 15:18:15.402  2720  2779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:18:15.448  2720  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-29 15:18:15.448  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:18:15.448  2720  2775 D BtGatt.GattService: current time is 160293371241
08-29 15:18:15.448  2720  2775 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 88, 120, 34, 16, 80, 103, 1, -128, -58, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -85, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -96, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-29 15:18:15.449  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 15:18:15.449  2720  2775 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 2, 124, -7, 14, 52, -118, -96]
,08-29 15:18:15.449  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 15:18:15.450  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 15:18:15.450  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 15:18:15.450  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-29 15:18:15.451  3923  3923 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 2] updated - the peer count is 1
,08-29 15:18:16.964  2720  2720 D BtGatt.ScanManager: awakened up at time 161809
,08-29 15:18:16.967  2720  2779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:18:16.999  2720  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 15:18:16.999  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:18:17.227  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:17.242  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:17.247  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:17.295  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 15:18:17.295  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 15:18:17.296  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:18:17.296  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:17.336  3607  3607 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 15:18:17.337  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 15:18:17.337  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-29 15:18:18.324  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:18.325  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:18.325  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 15:18:18.325  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:18.326  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 15:18:18.326  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 15:18:18.326  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:18:18.326  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:18:18.327  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 15:18:18.328  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:18:18.328  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 15:18:18.331  3923  3986 D BluetoothAdapter: STATE_ON
08-29 15:18:18.333  2720  2733 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:18:18.335  2720  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:18:18.336  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:18:18.336  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 15:18:18.337  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:18:18.337  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 15:18:18.338  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 15:18:18.342  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:18:18.342  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 15:18:18.343  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 15:18:18.343  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:18:18.345  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:18:18.345  3923  3986 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
08-29 15:18:18.346  2720  2720 D BtGatt.ScanManager: awakened up at time 163191
08-29 15:18:18.349  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:18:18.349  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:18:18.350  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:18:18.350  2720  2775 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 15:18:18.351  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:18:18.351  2720  2779 D BtGatt.ScanManager: stopping BLe Batch
,08-29 15:18:18.363  2720  2775 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 15:18:18.363  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:18:18.363  2720  2779 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:18:18.377  2720  2775 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-29 15:18:18.378  2720  2775 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:18:18.378  2720  2775 D BtGatt.GattService: current time is 163223277202
,08-29 15:18:18.379  2720  2775 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 15:18:18.379  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 15:18:18.380  2720  2775 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 15:18:18.851  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:18:18.852  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:18.852  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:18:20.250   869  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-29 15:18:23.350  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:23.350  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.351  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:18:23.351  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.352  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.352  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:18:23.352  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:23.353  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.353  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.353  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:18:23.353  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.357  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.357  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.361  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.361  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.362  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.362  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.364  3923  3986 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 15:18:23.366  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.367  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.367  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:18:23.367  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.368  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.368  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.369  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.369  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.369  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.369  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.370  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.370  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.370  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:23.370  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.373  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.373  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.373  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.374  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.376  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 15:18:23.377  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.377  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.377  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.378  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.378  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.378  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.378  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.379  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.379  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.379  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.379  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.380  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.380  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.380  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.382  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:23.382  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.383  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.383  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.385  3923  3986 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 15:18:23.385  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.386  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.386  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.386  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.386  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.387  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.387  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.387  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.387  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.388  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.388  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.388  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.388  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.389  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.391  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:23.391  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.391  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.392  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.393  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 15:18:23.394  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.394  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.394  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.394  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.394  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.395  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.395  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.395  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.395  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.395  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.396  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.396  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.396  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.396  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.398  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.398  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.398  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.399  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.400  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 15:18:23.400  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:18:23.401  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:18:23.401  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:18:23.401  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 15:18:23.401  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 15:18:23.402  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 15:18:23.402  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:18:23.402  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 15:18:23.402  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.402  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:23.403  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.403  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:23.403  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.403  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.404  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.404  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:23.404  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.404  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.404  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.405  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.405  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.405  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.407  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:23.407  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.407  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.407  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.409  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 15:18:23.409  3923  3986 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 15:18:23.410  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 15:18:23.415  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 15:18:23.415  3923  3986 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 15:18:23.415  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 15:18:23.415  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 15:18:23.415  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 15:18:23.415  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 15:18:23.416  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 15:18:23.417  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 15:18:23.418  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 15:18:23.418  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 15:18:23.418  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-29 15:18:23.418  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 15:18:23.418  3923  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:18:23.419  3923  3986 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 15:18:23.419  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:18:23.419  3923  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:18:23.419  3923  3986 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 15:18:23.419  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 15:18:23.419  3923  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 15:18:23.419  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 15:18:23.422  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 15:18:23.423  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 15:18:23.423  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-29 15:18:23.424  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 15:18:23.424  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 15:18:23.424  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 15:18:23.424  3923  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 15:18:23.424  3923  3986 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 15:18:23.425  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.425  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.425  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.425  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:23.426  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.426  3923  4208 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 415)
08-29 15:18:23.426  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.426  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 15:18:23.426  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.427  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:23.429  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.429  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.429  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.429  3923  4209 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 415,
08-29 15:18:23.429  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.429  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.429  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.430  3923  4208 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:18:23.431  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.431  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.431  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:23.431  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.432  3923  3986 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-29 15:18:23.437  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:23.437  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.437  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.437  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:23.438  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.438  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.438  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:23.438  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.439  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.439  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.439  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.439  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.439  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.439  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.440  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.440  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:18:23.440  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.440  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.441  3923  3986 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 15:18:23.441  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:23.442  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.442  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.442  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:23.442  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:23.442  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.442  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.442  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.442  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.442  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.442  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.442  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.442  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:23.443  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.443  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.443  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:23.444  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.444  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.444  3923  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 15:18:23.444  3923  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-29 15:18:23.445  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:18:23.445  3923  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 15:18:23.445  3923  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:18:23.445  3923  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 15:18:23.445  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:18:23.445  3923  3986 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-29 15:18:23.445  3923  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 15:18:23.445  3923  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-29 15:18:23.445  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 15:18:23.445  3923  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 15:18:23.446  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:23.446  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:18:23.446  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:23.446  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:23.446  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.446  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:23.446  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.446  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.446  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.446  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.446  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:23.446  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.446  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.447  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.448  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:23.448  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:18:23.448  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:23.448  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:23.448  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:23.448  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.449  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:23.449  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:23.449  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:23.449  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:23.449  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:23.449  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:23.449  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.450  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:28.451  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.451  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.451  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.452  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.452  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:28.452  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:28.453  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:28.453  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:28.454  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.454  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.454  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.455  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:28.455  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:28.455  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.455  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:28.456  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.456  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.456  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.457  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.462  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:28.462  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:28.464  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.464  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:28.471  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 15:18:28.472  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:18:28.474  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 15:18:28.474  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-29 15:18:28.474  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:18:28.474  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 15:18:28.475  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:18:28.475  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 15:18:28.476  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.476  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 15:18:28.476  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 15:18:28.476  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 15:18:28.477  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.477  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 15:18:28.477  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:28.477  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:28.477  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:18:28.477  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 15:18:28.477  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:18:28.477  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:18:28.477  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.477  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.478  3923  4210 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:18:28.480  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:18:28.481  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.481  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:18:28.481  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:18:28.481  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:28.481  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:18:28.482  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:28.482  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:28.482  3923  4210 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 15:18:28.482  3923  4210 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-29 15:18:28.482  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.483  3923  4210 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:18:28.483  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.483  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.483  3923  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 15:18:28.483  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:28.483  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.484  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.484  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:28.484  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.484  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.485  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.485  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.488  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:28.488  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-29 15:18:28.488  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.489  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.492  3923  3986 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 15:18:28.492  3923  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 15:18:28.493  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 15:18:28.497  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 15:18:28.497  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 15:18:28.497  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:18:28.497  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:28.497  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:28.497  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.497  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.498  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.498  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
,08-29 15:18:28.498  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.498  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.498  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:28.498  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.498  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.498  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.499  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.500  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:18:28.501  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:28.501  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.501  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:28.509  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:28.510  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:28.510  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:18:28.510  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:18:28.510  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.511  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.511  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:28.511  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:28.512  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.512  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:18:28.512  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.512  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.512  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:18:28.513  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.515  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:28.515  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:18:28.515  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.516  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
,08-29 15:18:28.517  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:18:28.518  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:18:28.518  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:18:28.518  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:18:28.519  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.519  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:28.519  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6fc9b52 not in the list
08-29 15:18:28.519  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.520  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.520  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:28.520  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.520  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.520  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:28.521  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:18:28.523  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:18:28.523  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:18:28.523  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:18:28.524  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44d4e23 not in the list
08-29 15:18:28.526  3923  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 15:18:28.527  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:18:28.527  3923  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 15:18:28.527  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 15:18:28.527  3923  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 15:18:28.528  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 15:18:28.532  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 15:18:28.533  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 15:18:28.533  3923  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 15:18:28.533  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:18:28.533  3923  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 15:18:28.533  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 15:18:28.534  3923  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 15:18:28.534  3923  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-29 15:18:28.534  3923  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 15:18:28.534  3923  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 15:18:28.535  3923  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-29 15:18:28.535  3923  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 15:18:28.535  3923  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 15:18:28.535  3923  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 15:18:28.536  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:18:28.536  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf49050 added. We now have 3 listener(s)
08-29 15:18:28.536  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:18:28.538  3923  3986 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 15:18:28.539   869  1687 D WifiService: setWifiEnabled: true pid=3923, uid=10000
,08-29 15:18:28.539   869  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:18:28.560  2720  2893 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-29 15:18:28.560  2720  2914 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 6
08-29 15:18:28.560  3923  4208 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 415)
,08-29 15:18:28.983  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:18:32.306  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:32.310  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:32.350  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 15:18:32.350  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:18:32.350  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:32.350  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:32.376  3645  4213 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:18:32.376  3645  4213 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	,at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:32.376  3645  4213 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	... 12 more
08-29 15:18:32.376  3645  4213 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at fal.a(PG:38)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:18:32.376  3645  4213 E HttpOperation: 	... 14 more
,08-29 15:18:32.420  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:18:32.420  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 15:18:32.420  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:32.420  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:32.437  3645  4213 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:18:32.437  3645  4213 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at hec.a(PG:42)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at hee.a(PG:102)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at czr.a(PG:65)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at kka.a(PG:108)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:32.437  3645  4213 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	... 15 more
08-29 15:18:32.437  3645  4213 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at fal.a(PG:38)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:18:32.437  3645  4213 E HttpOperation: 	... 17 more
,08-29 15:18:32.437  3645  4213 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:18:32.437  3645  4213 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	... 15 more
08-29 15:18:32.437  3645  4213 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:18:32.437  3645  4213 E ExperimentLoader: 	... 17 more
,08-29 15:18:32.592   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 176774, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:18:33.548  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:18:33.548  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fa0249 added. We now have 4 listener(s)
,08-29 15:18:33.549  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:18:33.566  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:33.566  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5fa0249 removed from the list
08-29 15:18:33.567  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:18:33.567  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:33.567  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:33.570  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:18:33.570  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59b674e added. We now have 4 listener(s)
,08-29 15:18:33.571  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:18:33.574  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:33.574  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59b674e removed from the list
08-29 15:18:33.575  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:18:33.575  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:33.575  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:33.578  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:18:33.578  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8f06f added. We now have 4 listener(s)
08-29 15:18:33.578  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:18:33.586   869  1377 D WifiService: setWifiEnabled: false pid=3923, uid=10000
,08-29 15:18:33.586   869  1377 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:18:33.604  2720  2771 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 15:18:33.604  2720  2771 D BluetoothAdapterProperties: Setting state to 13
08-29 15:18:33.604  2720  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 15:18:33.605  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:18:33.607  2720  2771 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 15:18:33.610  2720  2771 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:18:33.613  2720  2775 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:18:33.617  2720  2720 D BluetoothMapService: onReceive
08-29 15:18:33.617  2720  2720 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 15:18:33.618  2720  2720 D BluetoothMapService: STATE_TURNING_OFF
08-29 15:18:33.618  2720  2720 D BluetoothMapService: MAP Service closeService in
,08-29 15:18:33.619  2720  2720 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 15:18:33.619  2720  2720 D ObexServerSockets0: shutdown(block = true)
08-29 15:18:33.620  2720  2930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 15:18:33.622  2720  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 15:18:33.623  2720  2720 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:18:33.623  2720  2914 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 15:18:33.623  2720  2720 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 15:18:33.624  2720  2931 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 15:18:33.625  2720  2720 I BtOppRfcommListener: stopping Accept Thread
08-29 15:18:33.626  2720  3470 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 15:18:33.626  2720  3470 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:18:33.627  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:33.627  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:33.628  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:33.628  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:33.628  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:18:33.631  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.633  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.637  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:33.637  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:33.637  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.638  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:33.638  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 15:18:33.641   869  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 15:18:33.641  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.641   869  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:33.641  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:33.641   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:18:33.641   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:18:33.642  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.642  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:33.644  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.648  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.649   869   882 I ActivityManager: Start proc 4217:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 15:18:33.651  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.652  2720  2720 D HeadsetService: Received stop request...Stopping profile...
08-29 15:18:33.652   869  1316 E native  : do suspend true
08-29 15:18:33.653   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:33.653   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:33.653   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:33.654  2002  2092 D BluetoothHeadset: Proxy object disconnected
,08-29 15:18:33.654  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:33.654  1371  1389 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:33.655  2720  2720 D A2dpService: Received stop request...Stopping profile...
,08-29 15:18:33.655  1371  1371 D HeadsetProfile: Bluetooth service disconnected
08-29 15:18:33.656  2720  2922 D A2dpStateMachine: Exit Disconnected: -1
08-29 15:18:33.656   869   869 D BluetoothA2dp: Proxy object disconnected
08-29 15:18:33.657  2720  2720 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:33.657  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.657  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:33.657  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:33.657  1371  1371 D BluetoothA2dp: Proxy object disconnected
08-29 15:18:33.657  2720  2720 D HidService: Received stop request...Stopping profile...
08-29 15:18:33.657  2720  2720 D HidService: Stopping Bluetooth HidService
08-29 15:18:33.658  1371  1371 D BluetoothInputDevice: Proxy object disconnected
08-29 15:18:33.658  1371  1371 D HidProfile: Bluetooth service disconnected
08-29 15:18:33.659  2720  2720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:18:33.659  2720  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 15:18:33.659  2720  2720 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 15:18:33.660  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:33.660  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:33.660  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:18:33.660  2720  2720 D HealthService: Received stop request...Stopping profile...
08-29 15:18:33.661  2720  2775 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 15:18:33.662  2720  2720 V BluetoothAdapterState: isTurningOff()=true
,08-29 15:18:33.663  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.663  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:33.663  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:18:33.663  2720  2720 D PanService: Received stop request...Stopping profile...
08-29 15:18:33.664  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 15:18:33.664  1371  1371 D PanProfile: Bluetooth service disconnected
08-29 15:18:33.665   369   868 D CommandListener: Clearing all IP addresses on wlan0
08-29 15:18:33.665   869  1919 D DhcpClient: Clearing IP address
08-29 15:18:33.666  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:33.666  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:33.666  2720  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:18:33.666  2720  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:18:33.666  2720  2893 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 15:18:33.666  2720  2893 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:18:33.666  2720  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 15:18:33.667  2720  2720 D BluetoothMapService: Received stop request...Stopping profile...
08-29 15:18:33.668  2720  2720 D BluetoothMapService: stop()
08-29 15:18:33.668  2720  2720 D BluetoothMapAppObserver: deinitObservers()
08-29 15:18:33.668  2720  2720 D BluetoothMapAppObserver: removeReceiver()
08-29 15:18:33.669   369   868 D CommandListener: Setting iface cfg
08-29 15:18:33.670  1371  1371 D BluetoothMap: Proxy object disconnected
,08-29 15:18:33.670  1371  1371 D MapProfile: Bluetooth service disconnected
08-29 15:18:33.671  2720  2720 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:33.672  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.672  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:33.672  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:33.673   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 15:18:33.673   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-29 15:18:33.675   869  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-29 15:18:33.676   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:18:33.676   869  1316 E native  : do suspend true
08-29 15:18:33.679  2720  2720 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:18:33.679  2720  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 15:18:33.680  2720  2720 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:18:33.680  2720  2720 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:33.680  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.680  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:33.680  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:33.680   869  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 15:18:33.681  2720  2720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 15:18:33.681  2720  2775 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 15:18:33.681  2720  2720 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:18:33.682  2720  2720 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:33.683  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.683  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:33.683  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:33.686  1514  4188 V NativeCrypto: Read error: ssl=0x99ad7a00: I/O error during system call, Connection timed out
,08-29 15:18:33.686   403   403 E Parcel  : Reading a NULL string not supported here.
08-29 15:18:33.689   869  4143 D DhcpClient: Receive thread stopped
,08-29 15:18:33.705  2720  2720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-29 15:18:33.706  2720  2720 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:18:33.707  2720  2720 D BluetoothMapService: MAP Service closeService in
08-29 15:18:33.707  2720  2720 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:33.707  2720  2720 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:33.707  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:33.707  2720  2720 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:33.707  2720  2720 D BluetoothMapService: cleanup()
,08-29 15:18:33.707  2720  2720 D BluetoothMapService: MAP Service closeService in
08-29 15:18:33.707  2720  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-29 15:18:33.707  2720  2771 D BluetoothAdapterProperties: Setting state to 15
,08-29 15:18:33.707  2720  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 15:18:33.708  2720  2771 I BluetoothAdapterState: Entering BleOnState
,08-29 15:18:33.708  1371  1390 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:18:33.708  1514  4188 V NativeCrypto: SSL shutdown failed: ssl=0x99ad7a00: I/O error during system call, Broken pipe
,08-29 15:18:33.708   869   886 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:18:33.709  1371  1697 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:18:33.709   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:33.709   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:33.709  1371  2277 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:33.711  1371  1389 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:18:33.712   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:33.712  1371  1390 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 15:18:33.713  1371  1697 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:18:33.713  2002  2028 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:33.714  2720  2771 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 15:18:33.714  2720  2771 D BluetoothAdapterProperties: Setting state to 16
08-29 15:18:33.714  2720  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 15:18:33.714  2720  2771 D BluetoothAdapterProperties: onBleDisable
08-29 15:18:33.715  2720  2771 I BluetoothAdapterState: Entering PendingCommandState
08-29 15:18:33.715  2720  2772 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 15:18:33.716  2720  2775 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:18:33.716  2720  2893 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 15:18:33.716  2720  2893 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:18:33.718  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.718  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:33.719  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.719  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:33.721  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.721  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:33.721  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.721  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:33.722   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:33.723  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.723  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:33.724  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.724  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:33.725  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.726  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.727  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.749   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:33.749   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:18:33.751   869  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 15:18:33.751   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:33.751   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:18:33.753   869   886 D Tethering: MasterInitialState.processMessage what=3
08-29 15:18:33.758  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-29 15:18:33.758  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.760  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.761  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:33.763  4217  4217 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-29 15:18:33.769   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 15:18:33.771   869  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 15:18:33.772  1864  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 15:18:33.772  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.772  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:33.772  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.772  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:33.774  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.774  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:33.774  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.774  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:33.776  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:33.776  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:33.777  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:33.777  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:33.781  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:18:33.785   869   886 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d57524f:true
,08-29 15:18:33.786  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:18:33.799   869  2035 I ActivityManager: Start proc 4236:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 15:18:33.825  4217  4217 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 15:18:33.828   369   868 E Netd    : netlink response contains error (No such file or directory)
,08-29 15:18:33.829  4217  4217 D BluetoothMap: Create BluetoothMap proxy object
08-29 15:18:33.830   869  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 15:18:33.835  4236  4236 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 15:18:33.843  4217  4217 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 15:18:33.856  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:18:33.860   869   880 I ActivityManager: Killing 3817:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 15:18:33.939  2720  2775 I bt_hci  : shut_down
,08-29 15:18:33.940  2720  2780 D bt_hwcfg: hw_epilog_process
,08-29 15:18:33.953  2720  2780 I bt_vendor: low_power_mode_cb
,08-29 15:18:33.983  2720  2780 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 15:18:33.984  2720  2780 I bt_vendor: epilog_cb
,08-29 15:18:33.984  2720  2780 I bt_hci  : epilog_finished_callback
,08-29 15:18:33.990  2720  2775 I bt_hci_h4: hal_close
,08-29 15:18:33.991  2720  2775 I bt_userial_vendor: device fd = 51 close
,08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 15:18:34.006  423,6  4236 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.006  4236  4236 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.006  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.007  4236  4236 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:18:34.007  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:18:34.011  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 15:18:34.021  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:18:34.028  4217  4217 D DockEventReceiver: finishStartingService: stopping service
08-29 15:18:34.035   869  2036 I ActivityManager: Killing 3526:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 15:18:34.105  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:18:34.110  1717  1717 D SystemUpdateService: onCreate
,08-29 15:18:34.114  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:18:34.118  2720  2772 D bt_stack_manager: event_shut_down_stack finished.
,08-29 15:18:34.118  2720  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 15:18:34.121  2720  2771 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 15:18:34.121  2720  2720 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 15:18:34.122  2720  2720 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 15:18:34.122  2720  2720 D BtGatt.GattService: stop()
08-29 15:18:34.122  2720  2720 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 15:18:34.126  2720  2720 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:18:34.127  2720  2720 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:18:34.127  2720  2720 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:34.127  2720  2720 V BluetoothAdapterState: isBleTurningOff()=true
08-29 15:18:34.128  2720  2771 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 15:18:34.128  2720  2771 D BluetoothAdapterProperties: Setting state to 10
,08-29 15:18:34.128  2720  2771 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 15:18:34.129  2720  2771 I BluetoothAdapterState: Entering OffState
08-29 15:18:34.129   869   886 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 15:18:34.130  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 15:18:34.134  1717  2473 I iu.UploadsManager: num queued entries: 0
08-29 15:18:34.120  1717  4268 I SystemUpdateService: active receiver: enabled
,08-29 15:18:34.146  1717  4268 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:18:34.152  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:18:34.152  1717  2473 I iu.UploadsManager: num updated entries: 0
08-29 15:18:34.153  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:18:34.156  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:34.159  2720  2720 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 15:18:34.159  2720  2720 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-29 15:18:34.159  2720  2772 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 15:18:34.159  2720  2720 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 15:18:34.161  2720  2772 D bt_stack_manager: event_clean_up_stack finished.
,08-29 15:18:34.166  4045  4045 D SprintDMHelper: simOperator: 
,08-29 15:18:34.166  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:18:34.167  1717  2473 I iu.SyncManager: NEXT; no task
,08-29 15:18:34.171  2720  2720 I art     : System.exit called, status: 0
,08-29 15:18:34.171  2720  2720 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 15:18:34.178  1717  4268 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 15:18:34.178  1717  4268 I SystemUpdateService: now status is 0 (complete)
08-29 15:18:34.178  1717  4268 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 15:18:34.180  1717  4268 I SystemUpdateService: file has been verified
,08-29 15:18:34.184  1717  4268 I SystemUpdateService: OTA package size = 12249756,
,08-29 15:18:34.214  4010  4271 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 15:18:34.233  1717  4268 I SystemUpdateService: showing system update notification
,08-29 15:18:34.263   869  1690 I ActivityManager: Process com.android.bluetooth (pid 2720) has died
,08-29 15:18:34.301  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:18:34.382  4236  4254 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 15:18:34.412   869   886 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2054e6:true
,08-29 15:18:38.612  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:38.625  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 15:18:38.628  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:18:38.633   869  1688 D WifiService: setWifiEnabled: true pid=3923, uid=10000
,08-29 15:18:38.633   869  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:18:38.642   869  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-29 15:18:38.650  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:38.650  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:38.650  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:38.651  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:38.657  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:38.658  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:38.658  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:38.658  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:38.660  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:38.661  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:38.661  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:38.661  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:38.678   869  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-29 15:18:38.679   869  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 15:18:38.680   869  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 15:18:38.681   869  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 15:18:38.681   869  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 15:18:38.682   869  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 15:18:38.682   869  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 15:18:38.687  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 15:18:38.688  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 15:18:38.688  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:18:38.688  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:38.692   369   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 15:18:38.693   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:18:38.694   369   868 D CommandListener: Setting iface cfg
,08-29 15:18:38.695   869  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-29 15:18:38.695   869  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 15:18:38.705  3607  3607 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 15:18:38.705  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 15:18:38.706  3607  3607 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
08-29 15:18:38.706   869  1316 E native  : do suspend true
,08-29 15:18:38.715   869  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 15:18:38.720   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:18:38.721   869  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 15:18:40.079   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:18:40.156   869  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.44 rxSuccessRate=8.31 delta 1000 -> 994
,08-29 15:18:40.158   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 15:18:40.159   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:18:40.173   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 15:18:40.210   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 15:18:40.212  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 15:18:40.644  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 15:18:40.702  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 15:18:40.706  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 15:18:40.716   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:18:40.730   869  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:18:40.730   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 15:18:40.730   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 15:18:40.758   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:18:40.770   369   868 D CommandListener: Setting iface cfg
,08-29 15:18:40.771   869  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 15:18:40.780   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 15:18:40.816   869  4285 D DhcpClient: Receive thread started
,08-29 15:18:40.903   869  1316 E native  : do suspend false
,08-29 15:18:40.922   869  1919 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 15:18:40.963   869  4285 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172759, domain null
,08-29 15:18:40.964   869  1919 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172759 seconds
,08-29 15:18:40.968   869  1919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 15:18:40.984   869  4285 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 15:18:40.986   869  1919 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 15:18:40.991   369   868 D CommandListener: Setting iface cfg
,08-29 15:18:41.002   869  1919 D DhcpClient: Scheduling renewal in 86399s
,08-29 15:18:41.004   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-29 15:18:41.006   869  1316 E native  : do suspend true
,08-29 15:18:41.029   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 15:18:41.032   869  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 15:18:41.035   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 15:18:41.039   869  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 15:18:41.046   869  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:18:41.125   869  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 15:18:41.125   869  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-29 15:18:41.126   869  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 15:18:41.127   869  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-29 15:18:41.128   869  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 15:18:41.151   869  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 15:18:41.163   869  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 15:18:41.163   869  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-29 15:18:41.163   869  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-29 15:18:41.163   869  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 15:18:41.163   869  1318 D ConnectivityService:    accepting network in place of null
08-29 15:18:41.164   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:18:41.167   869  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:18:41.178   869  4283 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 15:18:41.204   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:41.249   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:41.258   869  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 15:18:41.258   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:41.263   869  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 15:18:41.264   869   886 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:18:41.275   869  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:815::200e
,08-29 15:18:41.283  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:41.283  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:41.284  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:41.284  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:41.288  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:41.288  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:41.288  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:41.288  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:41.290  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:18:41.290  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:18:41.290  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:41.291  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:18:41.303  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-29 15:18:41.307  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 15:18:41.312  1717  1717 D SystemUpdateService: onCreate
,08-29 15:18:41.318  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:18:41.339  1717  4295 I SystemUpdateService: active receiver: enabled
,08-29 15:18:41.343  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 15:18:41.356  1717  2473 I iu.UploadsManager: num queued entries: 0
,08-29 15:18:41.356  1717  2473 I iu.UploadsManager: num updated entries: 0
,08-29 15:18:41.358  1717  4295 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:18:41.360  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:18:41.361  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:18:41.364  1717  4295 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 15:18:41.364  1717  4295 I SystemUpdateService: now status is 0 (complete)
08-29 15:18:41.364  1717  4295 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 15:18:41.364  1717  4295 I SystemUpdateService: file has been verified
,08-29 15:18:41.364  1717  4295 I SystemUpdateService: OTA package size = 12249756
08-29 15:18:41.365  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:41.371  1717  2473 I iu.SyncManager: NEXT; no task
,08-29 15:18:41.372   869  4281 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:18:41 GMT], X-Android-Received-Millis=[1472476721371], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472476721329]}
,08-29 15:18:41.373   869  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 15:18:41.373   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 15:18:41.373   869  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-29 15:18:41.374   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 15:18:41.380  1717  4297 I MDM     : [188] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 15:18:41.381  1717  4297 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 15:18:41.382  4045  4045 D SprintDMHelper: simOperator: 
,08-29 15:18:41.382  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:18:41.383  1717  4297 V GoogleAuthProtoRequest: [188] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:18:41.391  1717  4295 I SystemUpdateService: showing system update notification
,08-29 15:18:41.429  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:18:41.488  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 15:18:41.488  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 15:18:41.489  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:41.489  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:41.492  4158  4293 V KeepSync: Connecting to GoogleApiClient
,08-29 15:18:41.492   869  3218 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:18:41.524  1717  4297 E MDM     : [188] SitrepService.a: Error sending sitrep.
,08-29 15:18:41.568  4010  4301 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 15:18:41.576  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 15:18:41.577  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 15:18:41.577  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:18:41.577  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:41.597  1717  4305 V BaseAuthAsyncOperation: access token request failed
08-29 15:18:41.598  4158  4293 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:18:41.658  1514  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:18:41.658  1514  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 15:18:41.658  1514  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:18:41.658  1514  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:18:41.676  4158  4293 E KeepSync: IOException
08-29 15:18:41.676  4158  4293 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:18:41.676  4158  4293 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:18:41.676  4158  4293 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:18:41.676  4158  4293 E KeepSync: 	... 10 more
08-29 15:18:41.676  4158  4293 W KeepSync: Sync result 2
,08-29 15:18:41.686   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 177933, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:18:42.257   869  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 15:18:42.862  1514  2233 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 15:18:43.639   869   879 D WifiService: setWifiEnabled: false pid=3923, uid=10000
08-29 15:18:43.639   869   879 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:18:43.673  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 15:18:43.682   869  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 15:18:43.682   869  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-29 15:18:43.683   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 15:18:43.683   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:18:43.713   869  1316 E native  : do suspend true
,08-29 15:18:43.728   869  1919 D DhcpClient: Clearing IP address
,08-29 15:18:43.730   369   868 D CommandListener: Setting iface cfg
,08-29 15:18:43.735   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:18:43.737   869  4285 D DhcpClient: Receive thread stopped
,08-29 15:18:43.741  1514  4306 V NativeCrypto: Read error: ssl=0x99ad7a00: I/O error during system call, Connection timed out
,08-29 15:18:43.747  1514  4306 V NativeCrypto: SSL shutdown failed: ssl=0x99ad7a00: I/O error during system call, Broken pipe
,08-29 15:18:43.753   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 15:18:43.754   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
08-29 15:18:43.762   403   403 E Parcel  : Reading a NULL string not supported here.
08-29 15:18:43.767   869  1316 D WifiStateMachine: Start Disconnecting Watchdog 3
08-29 15:18:43.767   869  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
08-29 15:18:43.768   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:18:43.768   869  1316 E native  : do suspend true
,08-29 15:18:43.806   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:43.834   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:18:43.835   369   868 D CommandListener: Clearing all IP addresses on wlan0
,08-29 15:18:43.837   869  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 15:18:43.837   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:43.843   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:18:43.844   869   886 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:18:43.853  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.854  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:43.854  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.854  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:43.858  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.858  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:43.858  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.859  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:43.861  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.863  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:43.863  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:43.863  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:43.875  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-29 15:18:43.875   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-29 15:18:43.878  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.878  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:43.878  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:43.878  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 15:18:43.878  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:43.879  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.879  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:43.879  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.879  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:43.880   869  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 15:18:43.880  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:43.880  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:43.881  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:43.881  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:43.881  1864  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 15:18:43.883  1717  1717 D SystemUpdateService: onCreate
,08-29 15:18:43.895  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:18:43.907  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 15:18:43.911  1717  2473 I iu.UploadsManager: num queued entries: 0
,08-29 15:18:43.911  1717  2473 I iu.UploadsManager: num updated entries: 0
,08-29 15:18:43.916  1717  4315 I SystemUpdateService: active receiver: enabled
,08-29 15:18:43.917  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:18:43.918  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 15:18:43.921  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:18:43.926  4045  4045 D SprintDMHelper: simOperator: 
,08-29 15:18:43.926  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:18:43.939   369   868 E Netd    : netlink response contains error (No such file or directory)
,08-29 15:18:43.940   869  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-29 15:18:43.936  1717  4315 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:18:43.945  1717  2473 I iu.SyncManager: NEXT; no task
,08-29 15:18:43.950  4010  4319 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 15:18:43.951  1717  4315 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 15:18:43.951  1717  4315 I SystemUpdateService: now status is 0 (complete)
,08-29 15:18:43.951  1717  4315 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-29 15:18:43.957  1717  4315 I SystemUpdateService: file has been verified
,08-29 15:18:43.957  1717  4315 I SystemUpdateService: OTA package size = 12249756
,08-29 15:18:43.967  1717  4315 I SystemUpdateService: showing system update notification
,08-29 15:18:43.975  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:18:48.696   869   886 I ActivityManager: Start proc 4322:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 15:18:48.810  4322  4322 D AdapterServiceConfig: Adding HeadsetService
,08-29 15:18:48.811  4322  4322 D AdapterServiceConfig: Adding A2dpService
08-29 15:18:48.811  4322  4322 D AdapterServiceConfig: Adding HidService
,08-29 15:18:48.811  4322  4322 D AdapterServiceConfig: Adding HealthService
,08-29 15:18:48.812  4322  4322 D AdapterServiceConfig: Adding PanService
08-29 15:18:48.812  4322  4322 D AdapterServiceConfig: Adding GattService
08-29 15:18:48.812  4322  4322 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 15:18:48.827   869   886 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8815265:true
,08-29 15:18:48.830  4322  4322 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 15:18:48.840  4322  4334 I BluetoothAdapterState: Entering OffState
08-29 15:18:48.840  4322  4322 I bt_bluedroid: init
,08-29 15:18:48.844  4322  4335 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 15:18:48.844  4322  4335 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 15:18:48.844  4322  4335 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 15:18:48.845  4322  4335 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 15:18:48.847  4322  4322 I bt_bluedroid: get_profile_interface socket
,08-29 15:18:48.850  4322  4322 I bt_bluedroid: get_profile_interface sdp
,08-29 15:18:48.852  4322  4338 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:18:48.855  4322  4333 I bt_bluedroid: config_hci_snoop_log
,08-29 15:18:48.857  4322  4338 D BluetoothAdapterProperties: Name is: Nexus 6
08-29 15:18:48.859   869   886 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 15:18:48.869  4322  4334 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 15:18:48.870  4322  4334 D BluetoothAdapterProperties: Setting state to 14
,08-29 15:18:48.870  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 15:18:48.876  4322  4334 D BluetoothBondStateMachine: make
,08-29 15:18:48.881  4322  4339 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 15:18:48.891  4322  4334 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:18:48.893  4322  4322 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 15:18:48.902  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:48.904  4322  4322 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:18:48.906  4322  4322 D BtGatt.GattService: Received start request. Starting profile...
,08-29 15:18:48.906  4322  4322 D BtGatt.GattService: start()
08-29 15:18:48.906  4322  4322 I bt_bluedroid: get_profile_interface gatt
,08-29 15:18:48.909  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:48.910  4322  4322 D BtGatt.AdvertiseManager: advertise manager created
,08-29 15:18:48.926  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 15:18:48.927  4322  4322 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:18:48.927  4322  4322 V BluetoothAdapterState: isBleTurningOn()=true
08-29 15:18:48.927  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:48.928  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 15:18:48.929  4322  4334 I bt_bluedroid: enable
08-29 15:18:48.929  4322  4335 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 15:18:48.930  4322  4335 I bt_hci  : start_up
,08-29 15:18:48.950  4322  4335 I bt_vendor: alloc value 0xb39a3189
,08-29 15:18:48.950  4322  4335 I bt_vendor: init
08-29 15:18:48.951  4322  4335 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 15:18:48.951  4322  4335 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 15:18:49.060  4322  4335 D bt_hci  : start_up starting async portion
,08-29 15:18:49.061  4322  4342 I bt_hci  : event_finish_startup
08-29 15:18:49.061  4322  4342 I bt_hci_h4: hal_open
08-29 15:18:49.061  4322  4342 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 15:18:49.072  4322  4342 I bt_userial_vendor: device fd = 51 open
,08-29 15:18:49.103  4322  4342 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:18:49.134  4322  4342 D bt_hwcfg: Chipset BCM4354A2
08-29 15:18:49.135  4322  4342 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 15:18:49.135  4322  4342 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 15:18:49.168   869  1318 D ConnectivityService: handlePromptUnvalidated 102
,08-29 15:18:49.795  4322  4342 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 15:18:49.797  4322  4342 D bt_hwcfg: Settlement delay -- 100 ms
08-29 15:18:49.797  4322  4342 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 15:18:49.914  4322  4342 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:18:49.915  4322  4342 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 15:18:49.944  4322  4342 I bt_hwcfg: vendor lib fwcfg completed
,08-29 15:18:49.944  4322  4342 I bt_vendor: firmware callback
08-29 15:18:49.944  4322  4342 I bt_hci  : firmware_config_callback
,08-29 15:18:49.955  4322  4344 I bt_btu  : btu_task pending for preload complete event
,08-29 15:18:49.956  4322  4344 I bt_btu_task: Bluetooth chip preload is complete
08-29 15:18:49.956  4322  4344 I bt_btu  : btu_task received preload complete event
,08-29 15:18:49.966  4322  4344 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:18:49.966  4322  4344 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 15:18:49.966  4322  4344 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 15:18:49.967  4322  4344 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 15:18:49.967  4322  4344 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 15:18:49.967  4322  4344 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 15:18:49.967  4322  4344 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 15:18:49.968  4322  4344 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 15:18:49.968  4322  4344 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 15:18:49.968  4322  4344 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 15:18:49.968  4322  4344 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:18:49.969  4322  4344 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:18:49.969  4322  4344 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 15:18:49.969  4322  4344 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:18:49.969  4322  4344 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 15:18:50.107  4322  4344 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3920d9d
,08-29 15:18:50.107  4322  4344 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3920d9d 
,08-29 15:18:50.117  4322  4338 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-29 15:18:50.119  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 15:18:50.120  4322  4338 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:18:50.125  4322  4338 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:18:50.127  4322  4338 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:18:50.128  4322  4338 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 15:18:50.128  4322  4338 D bt_hci  : do_postload posting postload work item
,08-29 15:18:50.130  4322  4342 I bt_hci  : event_postload
08-29 15:18:50.130  4322  4342 I bt_vendor: sco_config_cb
,08-29 15:18:50.130  4322  4342 I bt_hci  : sco_config_callback postload finished.
08-29 15:18:50.133  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:50.136  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:50.137  4322  4338 D bt_bte_conf: Device ID record 1 : primary
08-29 15:18:50.137  4322  4338 D bt_bte_conf:   vendorId            = 000f
,08-29 15:18:50.137  4322  4338 D bt_bte_conf:   vendorIdSource      = 0001
08-29 15:18:50.138  4322  4338 D bt_bte_conf:   product             = 1200
,08-29 15:18:50.138  4322  4338 D bt_bte_conf:   version             = 1436
08-29 15:18:50.138  4322  4338 D bt_bte_conf:   clientExecutableURL = 
,08-29 15:18:50.138  4322  4338 D bt_bte_conf:   serviceDescription  = 
08-29 15:18:50.138  4322  4338 D bt_bte_conf:   documentationURL    = 
08-29 15:18:50.139  4322  4338 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 15:18:50.139  4322  4335 D bt_stack_manager: event_start_up_stack finished
08-29 15:18:50.140  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:50.141  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 15:18:50.141  4322  4342 I bt_vendor: low_power_mode_cb
08-29 15:18:50.141  4322  4334 D BluetoothAdapterProperties: Setting state to 15
,08-29 15:18:50.142  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 15:18:50.143  4322  4334 I BluetoothAdapterState: Entering BleOnState
,08-29 15:18:50.147  4322  4334 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 15:18:50.147  4322  4334 D BluetoothAdapterProperties: Setting state to 11
,08-29 15:18:50.147  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 15:18:50.152  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:50.152  4322  4322 D HeadsetService: Received start request. Starting profile...
,08-29 15:18:50.155  4322  4322 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 15:18:50.156  4322  4322 D HeadsetStateMachine: make
08-29 15:18:50.165  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:50.166  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:50.168  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:50.168  4322  4334 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:18:50.170  4322  4322 D HeadsetStateMachine: max_hf_connections = 1
08-29 15:18:50.170  4322  4322 I bt_bluedroid: get_profile_interface handsfree
08-29 15:18:50.170  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 15:18:50.170  4322  4338 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 15:18:50.175  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:50.176  4322  4322 D A2dpService: Received start request. Starting profile...
08-29 15:18:50.176  4322  4322 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:18:50.176  4322  4322 I bt_bluedroid: get_profile_interface avrcp
,08-29 15:18:50.181  4322  4322 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 15:18:50.182  4322  4322 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:18:50.182  4322  4322 D A2dpStateMachine: make
08-29 15:18:50.183  4322  4322 I bt_bluedroid: get_profile_interface a2dp
,08-29 15:18:50.183  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 15:18:50.186  4322  4354 D A2dpStateMachine: Enter Disconnected: -2
,08-29 15:18:50.186  4322  4322 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 15:18:50.187  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:18:50.188  4217  4217 D BluetoothInputDevice: Proxy object connected
08-29 15:18:50.188  4322  4322 D HidService: Received start request. Starting profile...
08-29 15:18:50.188  4322  4322 I bt_bluedroid: get_profile_interface hidhost
08-29 15:18:50.189  4322  4338 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39023e5
08-29 15:18:50.189  4322  4322 D HidService: setHidService(): set to: null
,08-29 15:18:50.189  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 15:18:50.189  4322  4322 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 15:18:50.189  4217  4217 D HidProfile: Bluetooth service connected
08-29 15:18:50.190  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:18:50.190  4322  4322 D HealthService: Received start request. Starting profile...
,08-29 15:18:50.192  4322  4322 I bt_bluedroid: get_profile_interface health
,08-29 15:18:50.192  4322  4322 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 15:18:50.193  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:18:50.194  4322  4322 D PanService: Received start request. Starting profile...
08-29 15:18:50.194  4322  4322 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 15:18:50.194  4322  4322 I bt_bluedroid: get_profile_interface pan
08-29 15:18:50.195  4322  4338 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 15:18:50.195  4217  4217 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 15:18:50.201  4322  4322 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:18:50.203  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:18:50.204  4217  4217 D PanProfile: Bluetooth service connected
08-29 15:18:50.204  4217  4217 D BluetoothMap: Proxy object connected
08-29 15:18:50.204  4322  4322 D BluetoothMapService: Received start request. Starting profile...
08-29 15:18:50.204  4322  4322 D BluetoothMapService: start()
,08-29 15:18:50.209  4217  4217 D MapProfile: Bluetooth service connected
,08-29 15:18:50.209  4217  4217 D BluetoothMap: getConnectedDevices(),
,08-29 15:18:50.210  4322  4322 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 15:18:50.210  4217  4217 D BluetoothMap: Bluetooth is Not enabled
08-29 15:18:50.211  4322  4322 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 15:18:50.211  4322  4322 D BluetoothMapAppObserver: createReceiver()
08-29 15:18:50.212  4322  4322 D BluetoothMapAppObserver: initObservers()
,08-29 15:18:50.212  4322  4322 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 15:18:50.219  4322  4322 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:18:50.219  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 15:18:50.219  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:50.219  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:18:50.219  4322  4350 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:50.221  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:50.222  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:50.223  4322  4322 V BluetoothAdapterState: isTurningOff()=false
08-29 15:18:50.223  4322  4322 V BluetoothAdapterState: isTurningOn()=true
08-29 15:18:50.223  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:50.223  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:50.224  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 15:18:50.224  4322  4334 D BluetoothAdapterProperties: ScanMode =  20
08-29 15:18:50.224  4322  4334 D BluetoothAdapterProperties: State =  11
08-29 15:18:50.225  4322  4334 D BluetoothAdapterProperties: Setting state to 12
08-29 15:18:50.225  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 15:18:50.226  4322  4334 I BluetoothAdapterState: Entering OnState
08-29 15:18:50.227  1371  1389 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:18:50.227  4322  4338 D BluetoothAdapterProperties: Scan Mode:21
08-29 15:18:50.227  4322  4338 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:18:50.230  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:18:50.231  1371  1371 D PanProfile: Bluetooth service connected
08-29 15:18:50.231   869   886 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:18:50.232  4217  4230 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:18:50.232  1371  1697 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:18:50.232   869   869 D BluetoothA2dp: Proxy object connected
08-29 15:18:50.234  1371  1371 D BluetoothMap: Proxy object connected
,08-29 15:18:50.234  1371  1371 D MapProfile: Bluetooth service connected
08-29 15:18:50.234  1371  1371 D BluetoothMap: getConnectedDevices()
08-29 15:18:50.235  4217  4227 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:18:50.235   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:18:50.235   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:18:50.236  4217  4230 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:50.236  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:50.236  1371  2277 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 15:18:50.237  1371  1389 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:18:50.238  1371  1371 D BluetoothInputDevice: Proxy object connected
08-29 15:18:50.238  1371  1371 D HidProfile: Bluetooth service connected
08-29 15:18:50.239  4217  4227 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:18:50.239  4322  4322 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 15:18:50.240  4322  4322 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 15:18:50.240  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:50.242  4322  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:18:50.242   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:18:50.243  1371  1697 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 15:18:50.244  4322  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 15:18:50.244  1371  2277 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:18:50.246  1371  1371 D BluetoothA2dp: Proxy object connected
08-29 15:18:50.246  4322  4322 D ObexServerSockets: Succeed to create listening sockets 
08-29 15:18:50.246  4322  4322 D ObexServerSockets0: startAccept()
08-29 15:18:50.246  2002  2091 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:18:50.246  4322  4322 D ObexServerSockets0: prepareForNewConnect()
,08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:50.247  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:50.248   869   869 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 15:18:50.250  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:50.253  4322  4322 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 15:18:50.253  4322  4322 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 15:18:50.253  4322  4322 D BluetoothMapService: onReceive
08-29 15:18:50.253  4322  4322 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:18:50.253  4322  4322 D BluetoothMapService: STATE_ON
08-29 15:18:50.254  4322  4360 D ObexServerSockets0: Accepting socket connection...
08-29 15:18:50.254  4322  4361 D ObexServerSockets0: Accepting socket connection...
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:50.254  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:50.255  4217  4217 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 15:18:50.256  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:50.258  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:50.259  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:50.260  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:50.264  4217  4217 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 15:18:50.270  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:18:50.273  4217  4217 D BluetoothA2dp: Proxy object connected
,08-29 15:18:50.275  4322  4322 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 15:18:50.275  4322  4322 D ObexServerSockets0: prepareForNewConnect()
08-29 15:18:50.276  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 15:18:50.284  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:18:50.285  1371  1371 D BluetoothPbap: Proxy object connected
08-29 15:18:50.285  1371  1371 D PbapServerProfile: Bluetooth service connected
,08-29 15:18:50.287  4217  4217 D BluetoothPbap: Proxy object connected
,08-29 15:18:50.287  4217  4217 D PbapServerProfile: Bluetooth service connected
,08-29 15:18:50.294  4322  4365 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:18:50.309  4322  4369 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:18:50.311  4322  4369 I BtOppRfcommListener: Accept thread started.
,08-29 15:18:50.337   869   869 D BluetoothHeadset: Proxy object connected
,08-29 15:18:50.337   869   869 D BluetoothHeadset: Proxy object connected
08-29 15:18:50.337   869   869 D BluetoothHeadset: Proxy object connected
08-29 15:18:50.338  2002  2092 D BluetoothHeadset: Proxy object connected
08-29 15:18:50.338  1371  2277 D BluetoothHeadset: Proxy object connected
08-29 15:18:50.338  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 15:18:50.342   869   886 D BluetoothHeadset: Proxy object connected
,08-29 15:18:50.347  2002  2282 D BluetoothHeadset: Proxy object connected
,08-29 15:18:50.368  4217  4227 D BluetoothHeadset: Proxy object connected
,08-29 15:18:50.371  4217  4217 D HeadsetProfile: Bluetooth service connected
,08-29 15:18:53.657  4322  4334 D BluetoothAdapterState: Current state: ON, message: 23
08-29 15:18:53.658  4322  4334 D BluetoothAdapterProperties: Setting state to 13
,08-29 15:18:53.658  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 15:18:53.660  4322  4334 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 15:18:53.663  4322  4334 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:18:53.666  4322  4338 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:18:53.669  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 15:18:53.674  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:53.675  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:53.677  4322  4322 D HeadsetService: Received stop request...Stopping profile...
,08-29 15:18:53.679  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:53.679  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:53.684   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.684   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.684   869   869 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.686  2002  2028 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.687  1371  2277 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.688  1371  1371 D HeadsetProfile: Bluetooth service disconnected
08-29 15:18:53.689  4322  4322 D A2dpService: Received stop request...Stopping profile...
08-29 15:18:53.689  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:53.689  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:18:53.690  4322  4354 D A2dpStateMachine: Exit Disconnected: -1
08-29 15:18:53.690  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:53.690  4217  4227 D BluetoothHeadset: Proxy object disconnected
08-29 15:18:53.690  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:18:53.691  4217  4217 D HeadsetProfile: Bluetooth service disconnected
,08-29 15:18:53.692   869   869 D BluetoothA2dp: Proxy object disconnected
,08-29 15:18:53.692  1371  1371 D BluetoothA2dp: Proxy object disconnected
08-29 15:18:53.692  4322  4322 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:53.693  4322  4322 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:18:53.693  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:18:53.693  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:53.693  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 15:18:53.693  4322  4322 D HidService: Received stop request...Stopping profile...
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:18:53.693  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:18:53.693  4322  4322 D HidService: Stopping Bluetooth HidService
08-29 15:18:53.693  4217  4217 D BluetoothA2dp: Proxy object disconnected
,08-29 15:18:53.694  3923  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 15:18:53.694  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:18:53.694  1371  1371 D BluetoothInputDevice: Proxy object disconnected
08-29 15:18:53.694  1371  1371 D HidProfile: Bluetooth service disconnected
08-29 15:18:53.695  4217  4217 D BluetoothInputDevice: Proxy object disconnected
08-29 15:18:53.695  4217  4217 D HidProfile: Bluetooth service disconnected
08-29 15:18:53.696  4322  4322 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 15:18:53.696  4322  4322 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 15:18:53.696  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 15:18:53.696  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:53.697  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:53.697  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:53.697  4322  4338 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-29 15:18:53.697  4322  4322 D HealthService: Received stop request...Stopping profile...
08-29 15:18:53.700  4322  4322 D PanService: Received stop request...Stopping profile...
08-29 15:18:53.701  1371  1371 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 15:18:53.701  1371  1371 D PanProfile: Bluetooth service disconnected
08-29 15:18:53.703  4217  4217 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 15:18:53.703  4322  4322 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 15:18:53.703  4217  4217 D PanProfile: Bluetooth service disconnected
08-29 15:18:53.703  4322  4322 D BluetoothMapService: stop()
08-29 15:18:53.704  4322  4322 D BluetoothMapAppObserver: deinitObservers()
08-29 15:18:53.704  4322  4322 D BluetoothMapAppObserver: removeReceiver()
08-29 15:18:53.706  1371  1371 D BluetoothMap: Proxy object disconnected
08-29 15:18:53.706  1371  1371 D MapProfile: Bluetooth service disconnected
08-29 15:18:53.706  4322  4322 V BluetoothAdapterState: isTurningOff()=true
,08-29 15:18:53.706  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:53.706  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:53.706  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:53.706  4217  4217 D BluetoothMap: Proxy object disconnected
08-29 15:18:53.706  4217  4217 D MapProfile: Bluetooth service disconnected
08-29 15:18:53.707  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 15:18:53.708  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 15:18:53.708  4322  4344 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:18:53.708  4322  4344 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:18:53.708  4322  4344 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 15:18:53.708  4322  4344 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 15:18:53.708  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-29 15:18:53.709  4322  4322 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:53.709  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:53.709  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:53.709  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:53.710  4322  4322 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 15:18:53.710  4322  4338 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 15:18:53.710  4322  4322 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 15:18:53.711  4322  4322 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:53.711  4322  4322 V BluetoothAdapterState: isTurningOn()=false
,08-29 15:18:53.711  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:53.711  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:53.711  4322  4322 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 15:18:53.711  4322  4338 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 15:18:53.712  4322  4322 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 15:18:53.712  4322  4322 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:53.712  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:53.712  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:53.712  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:18:53.712  4322  4322 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 15:18:53.713  4322  4322 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 15:18:53.717  4322  4322 D BluetoothMapService: MAP Service closeService in
,08-29 15:18:53.717  4322  4322 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 15:18:53.717  4322  4322 D ObexServerSockets0: shutdown(block = true)
08-29 15:18:53.717  4322  4360 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 15:18:53.718  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.718  4322  4322 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:18:53.719  4322  4361 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-29 15:18:53.719  4322  4347 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 15:18:53.719  4322  4322 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 15:18:53.719  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.720  4322  4322 V BluetoothAdapterState: isTurningOff()=true
08-29 15:18:53.720  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:53.720  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:53.720  4322  4322 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:18:53.720  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 15:18:53.720  4322  4334 D BluetoothAdapterProperties: Setting state to 15
08-29 15:18:53.720  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 15:18:53.721  4217  4230 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:18:53.721  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.722  4322  4334 I BluetoothAdapterState: Entering BleOnState
08-29 15:18:53.722  1371  2277 D BluetoothPan: onBluetoothStateChange on: false
08-29 15:18:53.723   869   886 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:18:53.723  4217  4227 D BluetoothPan: onBluetoothStateChange on: false
,08-29 15:18:53.724  4217  4230 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:18:53.725  1371  1389 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 15:18:53.726  4217  4227 D BluetoothMap: onBluetoothStateChange: up=false
08-29 15:18:53.727   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:53.727   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 15:18:53.727  4217  4230 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:18:53.728  1371  1697 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:18:53.729  1371  1390 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 15:18:53.729  4217  4227 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 15:18:53.730   869   886 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:18:53.730  4322  4322 D BluetoothMapService: cleanup()
08-29 15:18:53.730  4322  4322 D BluetoothMapService: MAP Service closeService in
08-29 15:18:53.730  1371  2277 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 15:18:53.731  1371  1389 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 15:18:53.732  2002  2091 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 15:18:53.732  4322  4334 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 15:18:53.732  4322  4334 D BluetoothAdapterProperties: Setting state to 16
08-29 15:18:53.732  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-29 15:18:53.733  4322  4334 D BluetoothAdapterProperties: onBleDisable
08-29 15:18:53.733  4322  4334 I BluetoothAdapterState: Entering PendingCommandState,
08-29 15:18:53.734  4322  4335 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 15:18:53.734  4322  4338 D BluetoothAdapterProperties: Scan Mode:20
08-29 15:18:53.735  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 15:18:53.736  4322  4344 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 15:18:53.736  4322  4344 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
08-29 15:18:53.736  4322  4369 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 15:18:53.736  4322  4322 I BtOppRfcommListener: stopping Accept Thread
08-29 15:18:53.736  4322  4369 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 15:18:53.737  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.740  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:53.742  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.744  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.745  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:18:53.747  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:18:53.749  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:18:53.758  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:18:53.760  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:18:53.764  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:18:53.769  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:18:53.950  4322  4338 I bt_hci  : shut_down
08-29 15:18:53.950  4322  4342 D bt_hwcfg: hw_epilog_process
,08-29 15:18:53.961  4322  4342 I bt_vendor: low_power_mode_cb
,08-29 15:18:53.987  4322  4342 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 15:18:53.988  4322  4342 I bt_vendor: epilog_cb
,08-29 15:18:53.988  4322  4342 I bt_hci  : epilog_finished_callback
,08-29 15:18:53.996  4322  4338 I bt_hci_h4: hal_close
,08-29 15:18:53.998  4322  4338 I bt_userial_vendor: device fd = 51 close
,08-29 15:18:54.139  4322  4335 D bt_stack_manager: event_shut_down_stack finished.
,08-29 15:18:54.140  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 15:18:54.146  4322  4334 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 15:18:54.146  4322  4322 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:18:54.148  4322  4322 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 15:18:54.149  4322  4322 D BtGatt.GattService: stop()
08-29 15:18:54.149  4322  4322 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 15:18:54.156  4322  4322 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:18:54.156  4322  4322 V BluetoothAdapterState: isTurningOn()=false
08-29 15:18:54.157  4322  4322 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:18:54.157  4322  4322 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 15:18:54.158  4322  4334 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 15:18:54.159  4322  4334 D BluetoothAdapterProperties: Setting state to 10
08-29 15:18:54.159  4322  4334 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 15:18:54.160  4322  4334 I BluetoothAdapterState: Entering OffState
,08-29 15:18:54.163   869   886 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 15:18:54.187  4322  4322 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 15:18:54.187  4322  4322 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 15:18:54.188  4322  4335 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 15:18:54.190  4322  4322 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 15:18:54.202  4322  4335 D bt_stack_manager: event_clean_up_stack finished.
,08-29 15:18:54.207  4322  4322 I art     : System.exit called, status: 0
08-29 15:18:54.207  4322  4322 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 15:18:54.250   869   879 I ActivityManager: Process com.android.bluetooth (pid 4322) has died
,08-29 15:18:58.654  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:18:58.655  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:58.660  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:58.660  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f8f06f removed from the list
08-29 15:18:58.660  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:58.661  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:58.661  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:58.664  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:18:58.664  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed77a05 added. We now have 4 listener(s)
08-29 15:18:58.665  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:18:58.666  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:18:58.667  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ed77a05 removed from the list
08-29 15:18:58.667  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:18:58.667  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:18:58.668  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:18:58.670  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:18:58.670  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dcaaa5a added. We now have 4 listener(s)
08-29 15:18:58.671  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:19:03.684  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:03.740   869   886 I ActivityManager: Start proc 4381:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 15:19:03.893  4381  4381 D AdapterServiceConfig: Adding HeadsetService
08-29 15:19:03.893  4381  4381 D AdapterServiceConfig: Adding A2dpService
08-29 15:19:03.894  4381  4381 D AdapterServiceConfig: Adding HidService
08-29 15:19:03.894  4381  4381 D AdapterServiceConfig: Adding HealthService
08-29 15:19:03.894  4381  4381 D AdapterServiceConfig: Adding PanService
08-29 15:19:03.894  4381  4381 D AdapterServiceConfig: Adding GattService
08-29 15:19:03.894  4381  4381 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 15:19:03.908   869   886 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ce04ee:true
,08-29 15:19:03.910  4381  4381 D BluetoothAdapterState: make() - Creating AdapterState
08-29 15:19:03.912  4381  4381 I bt_bluedroid: init
,08-29 15:19:03.914  4381  4393 I BluetoothAdapterState: Entering OffState
,08-29 15:19:03.916  4381  4394 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 15:19:03.917  4381  4394 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 15:19:03.917  4381  4394 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 15:19:03.917  4381  4394 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 15:19:03.917  4381  4381 I bt_bluedroid: get_profile_interface socket
08-29 15:19:03.919  4381  4397 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-29 15:19:03.919  4381  4381 I bt_bluedroid: get_profile_interface sdp
08-29 15:19:03.921  4381  4397 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:19:03.926  4381  4392 I bt_bluedroid: config_hci_snoop_log
,08-29 15:19:03.928   869   886 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 15:19:03.939  4381  4393 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 15:19:03.939  4381  4393 D BluetoothAdapterProperties: Setting state to 14
08-29 15:19:03.940  4381  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 15:19:03.945  4381  4393 D BluetoothBondStateMachine: make
,08-29 15:19:03.948  4381  4398 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 15:19:03.952  4381  4393 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:19:03.954  4381  4381 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 15:19:03.958  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:03.959  4381  4381 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 15:19:03.961  4381  4381 D BtGatt.GattService: Received start request. Starting profile...
08-29 15:19:03.961  4381  4381 D BtGatt.GattService: start()
08-29 15:19:03.961  4381  4381 I bt_bluedroid: get_profile_interface gatt
,08-29 15:19:03.963  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:19:03.963  4381  4381 D BtGatt.AdvertiseManager: advertise manager created
,08-29 15:19:03.973  4381  4381 V BluetoothAdapterState: isTurningOff()=false
08-29 15:19:03.973  4381  4381 V BluetoothAdapterState: isTurningOn()=false
08-29 15:19:03.973  4381  4381 V BluetoothAdapterState: isBleTurningOn()=true
08-29 15:19:03.973  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:19:03.974  4381  4393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 15:19:03.974  4381  4393 I bt_bluedroid: enable
08-29 15:19:03.974  4381  4394 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-29 15:19:03.975  4381  4394 I bt_hci  : start_up
,08-29 15:19:03.984  4381  4394 I bt_vendor: alloc value 0xb39a3189
08-29 15:19:03.984  4381  4394 I bt_vendor: init
08-29 15:19:03.984  4381  4394 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-29 15:19:03.984  4381  4394 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 15:19:04.093  4381  4394 D bt_hci  : start_up starting async portion
,08-29 15:19:04.094  4381  4401 I bt_hci  : event_finish_startup
,08-29 15:19:04.095  4381  4401 I bt_hci_h4: hal_open
08-29 15:19:04.096  4381  4401 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 15:19:04.107  4381  4401 I bt_userial_vendor: device fd = 51 open
,08-29 15:19:04.137  4381  4401 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:19:04.168  4381  4401 D bt_hwcfg: Chipset BCM4354A2
,08-29 15:19:04.168  4381  4401 D bt_hwcfg: Target name = [BCM4354A2]
08-29 15:19:04.169  4381  4401 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 15:19:05.006  4381  4401 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 15:19:05.008  4381  4401 D bt_hwcfg: Settlement delay -- 100 ms
08-29 15:19:05.008  4381  4401 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 15:19:05.125  4381  4401 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 15:19:05.126  4381  4401 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 15:19:05.156  4381  4401 I bt_hwcfg: vendor lib fwcfg completed
,08-29 15:19:05.156  4381  4401 I bt_vendor: firmware callback
08-29 15:19:05.156  4381  4401 I bt_hci  : firmware_config_callback
,08-29 15:19:05.167  4381  4403 I bt_btu  : btu_task pending for preload complete event
,08-29 15:19:05.167  4381  4403 I bt_btu_task: Bluetooth chip preload is complete
08-29 15:19:05.168  4381  4403 I bt_btu  : btu_task received preload complete event
,08-29 15:19:05.178  4381  4403 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 15:19:05.178  4381  4403 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 15:19:05.179  4381  4403 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 15:19:05.179  4381  4403 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 15:19:05.179  4381  4403 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 15:19:05.179  4381  4403 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 15:19:05.180  4381  4403 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 15:19:05.180  4381  4403 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 15:19:05.180  4381  4403 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 15:19:05.180  4381  4403 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 15:19:05.181  4381  4403 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 15:19:05.181  4381  4403 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 15:19:05.181  4381  4403 I         : BTE_InitTraceLevels -- TRC_SMP
,08-29 15:19:05.181  4381  4403 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 15:19:05.182  4381  4403 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 15:19:05.319  4381  4403 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3920d9d
,08-29 15:19:05.319  4381  4403 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3920d9d 
,08-29 15:19:05.330  4381  4397 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 15:19:05.332  4381  4397 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 15:19:05.333  4381  4397 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 15:19:05.361  4381  4397 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 15:19:05.363  4381  4397 D BluetoothAdapterProperties: Scan Mode:20
,08-29 15:19:05.363  4381  4397 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 15:19:05.363  4381  4397 D bt_hci  : do_postload posting postload work item
,08-29 15:19:05.363  4381  4401 I bt_hci  : event_postload
,08-29 15:19:05.363  4381  4401 I bt_vendor: sco_config_cb
,08-29 15:19:05.363  4381  4401 I bt_hci  : sco_config_callback postload finished.
,08-29 15:19:05.366  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:05.366  4381  4397 D bt_bte_conf: Device ID record 1 : primary
,08-29 15:19:05.366  4381  4401 I bt_vendor: low_power_mode_cb
,08-29 15:19:05.366  4381  4397 D bt_bte_conf:   vendorId            = 000f
08-29 15:19:05.367  4381  4397 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 15:19:05.367  4381  4397 D bt_bte_conf:   product             = 1200
08-29 15:19:05.367  4381  4397 D bt_bte_conf:   version             = 1436
08-29 15:19:05.367  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:05.367  4381  4397 D bt_bte_conf:   clientExecutableURL = 
08-29 15:19:05.367  4381  4397 D bt_bte_conf:   serviceDescription  = 
,08-29 15:19:05.367  4381  4397 D bt_bte_conf:   documentationURL    = 
08-29 15:19:05.368  4381  4397 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 15:19:05.368  4381  4394 D bt_stack_manager: event_start_up_stack finished
,08-29 15:19:05.370  4381  4393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 15:19:05.371  4381  4393 D BluetoothAdapterProperties: Setting state to 15
08-29 15:19:05.371  4381  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 15:19:05.372  4381  4393 I BluetoothAdapterState: Entering BleOnState
,08-29 15:19:05.382  4381  4393 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 15:19:05.382  4381  4393 D BluetoothAdapterProperties: Setting state to 11
,08-29 15:19:05.382  4381  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 15:19:05.387  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:05.389  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:05.394  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:19:05.394  4381  4381 D HeadsetService: Received start request. Starting profile...
,08-29 15:19:05.397  4381  4381 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-29 15:19:05.398  4381  4381 D HeadsetStateMachine: make
,08-29 15:19:05.401  4381  4393 I BluetoothAdapterState: Entering PendingCommandState
,08-29 15:19:05.406  4381  4381 D HeadsetStateMachine: max_hf_connections = 1
,08-29 15:19:05.406  4381  4381 I bt_bluedroid: get_profile_interface handsfree
08-29 15:19:05.407  4381  4397 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 15:19:05.407  4381  4397 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-29 15:19:05.413  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:19:05.415  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:05.416  4381  4381 D A2dpService: Received start request. Starting profile...
,08-29 15:19:05.417  4381  4381 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 15:19:05.417  4381  4381 I bt_bluedroid: get_profile_interface avrcp
,08-29 15:19:05.424  4381  4381 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 15:19:05.425  4381  4381 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 15:19:05.425  4381  4381 D A2dpStateMachine: make
,08-29 15:19:05.426  4381  4381 I bt_bluedroid: get_profile_interface a2dp
,08-29 15:19:05.427  4381  4397 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 15:19:05.428  4381  4412 D A2dpStateMachine: Enter Disconnected: -2
08-29 15:19:05.429  4381  4381 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 15:19:05.430  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:05.430  4381  4381 D HidService: Received start request. Starting profile...
08-29 15:19:05.430  4381  4381 I bt_bluedroid: get_profile_interface hidhost
08-29 15:19:05.431  4381  4381 D HidService: setHidService(): set to: null
08-29 15:19:05.431  4381  4397 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39023e5
,08-29 15:19:05.431  4381  4397 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 15:19:05.431  4381  4381 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 15:19:05.432  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:05.433  4381  4381 D HealthService: Received start request. Starting profile...
,08-29 15:19:05.434  4381  4381 I bt_bluedroid: get_profile_interface health
,08-29 15:19:05.435  4381  4381 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 15:19:05.436  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
08-29 15:19:05.436  4381  4381 D PanService: Received start request. Starting profile...
,08-29 15:19:05.437  4381  4381 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 15:19:05.437  4381  4381 I bt_bluedroid: get_profile_interface pan
,08-29 15:19:05.437  4381  4397 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 15:19:05.439  4381  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:05.440  4381  4381 D BluetoothMapService: Received start request. Starting profile...
08-29 15:19:05.440  4381  4381 D BluetoothMapService: start()
,08-29 15:19:05.443  4381  4381 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 15:19:05.443  4381  4381 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 15:19:05.443  4381  4381 D BluetoothMapAppObserver: createReceiver()
,08-29 15:19:05.444  4381  4381 D BluetoothMapAppObserver: initObservers()
,08-29 15:19:05.445  4381  4381 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 15:19:05.453  4381  4381 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:19:05.453  4381  4381 V BluetoothAdapterState: isTurningOn()=true
08-29 15:19:05.453  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:19:05.453  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:19:05.455  4381  4410 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isTurningOff()=false
08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isTurningOn()=true
08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:19:05.458  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isTurningOff()=false
,08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isTurningOff()=false
08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
08-29 15:19:05.459  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
08-29 15:19:05.460  4381  4381 V BluetoothAdapterState: isTurningOff()=false
08-29 15:19:05.460  4381  4381 V BluetoothAdapterState: isTurningOn()=true
,08-29 15:19:05.460  4381  4381 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 15:19:05.460  4381  4381 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 15:19:05.460  4381  4393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 15:19:05.460  4381  4393 D BluetoothAdapterProperties: ScanMode =  20
,08-29 15:19:05.460  4381  4393 D BluetoothAdapterProperties: State =  11
08-29 15:19:05.461  4381  4393 D BluetoothAdapterProperties: Setting state to 12
08-29 15:19:05.461  4381  4393 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 15:19:05.461  4217  4227 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:19:05.462  4381  4397 D BluetoothAdapterProperties: Scan Mode:21
08-29 15:19:05.462  4381  4397 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 15:19:05.463  4381  4393 I BluetoothAdapterState: Entering OnState
,08-29 15:19:05.464  1371  1697 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:19:05.465  4217  4217 D BluetoothA2dp: Proxy object connected
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:19:05.467  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:19:05.469  1371  1371 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:19:05.469  1371  1371 D PanProfile: Bluetooth service connected
,08-29 15:19:05.468   869   886 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 15:19:05.470   869   869 D BluetoothA2dp: Proxy object connected
08-29 15:19:05.470  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:19:05.470  4217  4227 D BluetoothPan: onBluetoothStateChange on: true
08-29 15:19:05.473  4217  4230 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:19:05.473  4381  4381 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 15:19:05.474  1371  1390 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:19:05.474  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 15:19:05.475  4381  4381 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 15:19:05.476  4217  4227 D BluetoothMap: onBluetoothStateChange: up=true
08-29 15:19:05.476  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:19:05.478   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:19:05.478   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 15:19:05.478  4217  4230 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:19:05.478  4381  4381 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:19:05.480  4217  4217 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 15:19:05.480  1371  1389 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:19:05.480  4217  4217 D PanProfile: Bluetooth service connected
08-29 15:19:05.481  1371  1697 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 15:19:05.483  4381  4381 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:19:05.483  4217  4227 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:19:05.484  4381  4381 D ObexServerSockets: Succeed to create listening sockets 
,08-29 15:19:05.484  4381  4381 D ObexServerSockets0: startAccept()
,08-29 15:19:05.484  4381  4381 D ObexServerSockets0: prepareForNewConnect()
08-29 15:19:05.485   869   886 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 15:19:05.485  1371  2277 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 15:19:05.486  4381  4381 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-29 15:19:05.487  4381  4381 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 15:19:05.487  4381  4419 D ObexServerSockets0: Accepting socket connection...
08-29 15:19:05.488  1371  1390 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 15:19:05.489  1371  1371 D BluetoothMap: Proxy object connected
,08-29 15:19:05.489  1371  1371 D MapProfile: Bluetooth service connected
08-29 15:19:05.489  1371  1371 D BluetoothMap: getConnectedDevices()
,08-29 15:19:05.489  4381  4420 D ObexServerSockets0: Accepting socket connection...
08-29 15:19:05.491  4217  4217 D BluetoothMap: Proxy object connected
08-29 15:19:05.491  1371  1371 D BluetoothInputDevice: Proxy object connected
08-29 15:19:05.491  1371  1371 D HidProfile: Bluetooth service connected
08-29 15:19:05.491  4217  4217 D MapProfile: Bluetooth service connected
08-29 15:19:05.491  4217  4217 D BluetoothMap: getConnectedDevices()
08-29 15:19:05.491  2002  2282 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 15:19:05.494   869   869 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 15:19:05.494  4217  4217 D BluetoothInputDevice: Proxy object connected
08-29 15:19:05.494  1371  1371 D BluetoothA2dp: Proxy object connected
08-29 15:19:05.494  4217  4217 D HidProfile: Bluetooth service connected
08-29 15:19:05.495  4381  4381 D BluetoothMapService: onReceive
08-29 15:19:05.495  4381  4381 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 15:19:05.496  4381  4381 D BluetoothMapService: STATE_ON
08-29 15:19:05.497  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:05.499  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:05.504  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 15:19:05.510  1514  1514 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 15:19:05.511  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,08-29 15:19:05.520  4217  4217 D BluetoothPbap: Proxy object connected
,08-29 15:19:05.520  4217  4217 D PbapServerProfile: Bluetooth service connected
,08-29 15:19:05.523  1371  1371 D BluetoothPbap: Proxy object connected
,08-29 15:19:05.523  1371  1371 D PbapServerProfile: Bluetooth service connected
,08-29 15:19:05.526  4381  4381 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 15:19:05.526  4381  4381 D ObexServerSockets0: prepareForNewConnect()
,08-29 15:19:05.528  4381  4425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:19:05.543  4381  4429 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:19:05.544  4381  4429 I BtOppRfcommListener: Accept thread started.
,08-29 15:19:05.575   869   869 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.575   869   869 D BluetoothHeadset: Proxy object connected
08-29 15:19:05.575   869   869 D BluetoothHeadset: Proxy object connected
08-29 15:19:05.575  2002  2014 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.576  1371  1697 D BluetoothHeadset: Proxy object connected
08-29 15:19:05.576  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 15:19:05.577  4217  4230 D BluetoothHeadset: Proxy object connected
08-29 15:19:05.577  4217  4217 D HeadsetProfile: Bluetooth service connected
,08-29 15:19:05.579   869   886 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.579   869   886 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.580  1371  1389 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.581  1371  1371 D HeadsetProfile: Bluetooth service connected
,08-29 15:19:05.585   869   886 D BluetoothHeadset: Proxy object connected
,08-29 15:19:05.593  2002  2028 D BluetoothHeadset: Proxy object connected
,08-29 15:19:08.291  1898  1964 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-29 15:19:08.291  1898  1964 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 15:19:08.332  1514  1514 I ConfigService: onCreate
,08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:19:08.703  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:19:08.711  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:19:08.712  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:08.712  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dcaaa5a removed from the list
08-29 15:19:08.712  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:19:08.713  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:08.713  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:08.716  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 15:19:08.716  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ace248b added. We now have 4 listener(s)
08-29 15:19:08.716  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:19:08.720   869  1688 D WifiService: setWifiEnabled: false pid=3923, uid=10000
,08-29 15:19:08.721   869  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:19:13.411  1514  1514 I ConfigService: onDestroy
,08-29 15:19:13.734  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:13.735   869  1691 D WifiService: setWifiEnabled: true pid=3923, uid=10000
08-29 15:19:13.735   869  1691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 15:19:13.750   869  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:19:13.766  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:19:13.773  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 15:19:13.782  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 15:19:13.785   869  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-29 15:19:13.786   869  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 15:19:13.786   869  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 15:19:13.787   869  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 15:19:13.787  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 15:19:13.787   869  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 15:19:13.788   869  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-29 15:19:13.788   869  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 15:19:13.802   369   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 15:19:13.802   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:19:13.808   369   868 D CommandListener: Setting iface cfg
,08-29 15:19:13.853   869  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '179 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 179 Failed to set address (No such device)'
,08-29 15:19:13.853   869  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 15:19:13.854   869  1316 E native  : do suspend true
,08-29 15:19:13.874   869  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 15:19:13.881   869  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 15:19:13.883   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:19:15.267   869  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 15:19:15.390   869  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.31 rxSuccessRate=9.81 delta 1000 -> 994
,08-29 15:19:15.393   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-29 15:19:15.393   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:19:15.418   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 15:19:15.505   869  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 15:19:15.510  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 15:19:15.941  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 15:19:15.977  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 15:19:15.979  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 15:19:15.995   869  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 15:19:16.014   869  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:19:16.014   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:19:16.015   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 15:19:16.040   869  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 15:19:16.062   369   868 D CommandListener: Setting iface cfg
,08-29 15:19:16.063   869  1316 D WifiStateMachine: Start Dhcp Watchdog 4
,08-29 15:19:16.078   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 15:19:16.097   869  4441 D DhcpClient: Receive thread started
,08-29 15:19:16.194   869  1316 E native  : do suspend false
,08-29 15:19:16.221   869  1919 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 15:19:16.235   869  4441 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-29 15:19:16.236   869  1919 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-29 15:19:16.240   869  1919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 15:19:16.259   869  4441 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 15:19:16.261   869  1919 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 15:19:16.266   369   868 D CommandListener: Setting iface cfg
,08-29 15:19:16.277   869  1919 D DhcpClient: Scheduling renewal in 86399s
,08-29 15:19:16.277   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 15:19:16.283   869  1316 E native  : do suspend true
,08-29 15:19:16.311   869  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 15:19:16.314   869  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 15:19:16.316   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 15:19:16.319   869  1318 D ConnectivityService: Adding iface wlan0 to network 103
,08-29 15:19:16.333   869  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 15:19:16.395   869  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 15:19:16.395   869  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,08-29 15:19:16.398   869  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,08-29 15:19:16.401   869  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,08-29 15:19:16.404   869  1318 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,08-29 15:19:16.415   869  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,08-29 15:19:16.421   869  1318 D ConnectivityService: scheduleUnvalidatedPrompt 103
08-29 15:19:16.421   869  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
08-29 15:19:16.421   869  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 15:19:16.422   869  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 15:19:16.422   869  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
08-29 15:19:16.422   869  1318 D ConnectivityService:    accepting network in place of null
08-29 15:19:16.424   869  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 15:19:16.439   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221284, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 15:19:16.465   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:19:16.499   369   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 15:19:16.508   869  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,08-29 15:19:16.509   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:19:16.516   869  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,08-29 15:19:16.520   869   886 D Tethering: MasterInitialState.processMessage what=3
,08-29 15:19:16.520   869  4439 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:801::200e
,08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:16.538  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:19:16.541  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:16.544  2072  2072 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-29 15:19:16.546  1717  1717 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:16.547  3923  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:19:16.551  3923  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:16.556  1717  1717 D SystemUpdateService: onCreate
,08-29 15:19:16.559  1717  1717 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 15:19:16.576  1717  4450 I SystemUpdateService: active receiver: enabled
,08-29 15:19:16.579  1717  1717 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 15:19:16.587  1717  2473 I iu.UploadsManager: num queued entries: 0
,08-29 15:19:16.587  1717  2473 I iu.UploadsManager: num updated entries: 0
08-29 15:19:16.587  1717  2473 I iu.SyncManager: NEXT; no task,
,08-29 15:19:16.593  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 15:19:16.595  1717  1717 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-29 15:19:16.597  4045  4045 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 15:19:16.601  4045  4045 D SprintDMHelper: simOperator: 
08-29 15:19:16.601  4045  4045 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 15:19:16.611  1717  4453 I MDM     : [194] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 15:19:16.611  1717  4453 W BaseAppContext: Using Auth Proxy for data requests.
08-29 15:19:16.621  1717  4453 V GoogleAuthProtoRequest: [194] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:19:16.652  1717  4450 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 15:19:16.660   869  4439 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 13:19:16 GMT], X-Android-Received-Millis=[1472476756660], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472476756574]}
,08-29 15:19:16.662   869  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 15:19:16.662   869  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
08-29 15:19:16.662   869  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
08-29 15:19:16.663   869  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 15:19:16.664  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:16.665  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:16.677  1717  4450 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 15:19:16.686  1717  4450 I SystemUpdateService: now status is 0 (complete)
08-29 15:19:16.686  1717  4450 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 15:19:16.686  1717  4450 I SystemUpdateService: file has been verified
,08-29 15:19:16.686  1717  4450 I SystemUpdateService: OTA package size = 12249756
,08-29 15:19:16.707  1717  4450 I SystemUpdateService: showing system update notification
,08-29 15:19:16.730  1717  1717 D SystemUpdateService: onDestroy
,08-29 15:19:16.748  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 15:19:16.748  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 15:19:16.748  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:19:16.749  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:16.758  4158  4455 V KeepSync: Connecting to GoogleApiClient
,08-29 15:19:16.758   869  1691 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:19:16.834  4010  4456 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 15:19:16.842  1717  4453 E MDM     : [194] SitrepService.a: Error sending sitrep.
,08-29 15:19:16.877  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-29 15:19:16.877  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 15:19:16.877  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:19:16.877  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:16.912  1717  4462 V BaseAuthAsyncOperation: access token request failed
,08-29 15:19:16.916  4158  4455 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:19:16.991  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:19:16.991  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 15:19:16.992  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:19:16.992  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:17.030  4158  4455 E KeepSync: IOException
08-29 15:19:17.030  4158  4455 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:19:17.030  4158  4455 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:19:17.030  4158  4455 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:19:17.030  4158  4455 E KeepSync: 	... 10 more
,08-29 15:19:17.030  4158  4455 W KeepSync: Sync result 2
,08-29 15:19:17.040   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 216597, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:19:17.507   869  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:18.763  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:19:18.769  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:18.770  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:18.771  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ace248b removed from the list
08-29 15:19:18.771  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:19:18.772  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:18.772  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:18.784  3923  4465 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-29 15:19:18.784  3923  4465 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 15:19:21.791  3923  4465 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 15:19:21.792  3923  4466 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-29 15:19:21.793  3923  4465 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 15:19:21.794  3923  4465 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 15:19:21.795  3923  4466 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-29 15:19:21.795  3923  4465 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 15:19:21.796  3923  4466 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 15:19:21.799  3923  4468 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: OutgoingSocketThread/Sender)
08-29 15:19:21.800  3923  4465 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 15:19:21.800  3923  4466 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 15:19:21.804  3923  4469 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: OutgoingSocketThread/Receiver)
,08-29 15:19:21.805  3923  4466 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 15:19:21.806  3923  4469 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 447, thread name: OutgoingSocketThread/Receiver)
08-29 15:19:21.806  3923  4469 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-29 15:19:21.807  3923  4469 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 447, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 15:19:21.807  3923  4470 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: IncomingSocketThread/Sender)
08-29 15:19:21.810  3923  4471 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: IncomingSocketThread/Receiver)
,08-29 15:19:21.811  3923  4471 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 449, thread name: IncomingSocketThread/Receiver)
08-29 15:19:21.811  3923  4471 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 15:19:21.812  3923  4471 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 449, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 15:19:24.427   869  1318 D ConnectivityService: handlePromptUnvalidated 103
,08-29 15:19:24.791  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 15:19:24.793  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 15:19:24.801  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed3b978 Bundle[{}]
,08-29 15:19:24.801  3923  3986 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 15:19:24.801  3923  3986 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 15:19:24.802  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 15:19:24.802  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 15:19:24.803  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 15:19:24.803  3923  3986 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 15:19:24.807  3923  3986 I System.out: Running OutgoingSocketThread
,08-29 15:19:24.811  3923  4472 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-29 15:19:24.811  3923  4472 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 15:19:27.820  3923  4473 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-29 15:19:27.820  3923  4473 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 15:19:27.821  3923  4472 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-29 15:19:27.821  3923  4473 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 15:19:27.821  3923  4472 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-29 15:19:27.822  3923  4472 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 15:19:27.822  3923  4473 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 15:19:27.825  3923  4475 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: IncomingSocketThread/Sender)
08-29 15:19:27.826  3923  4473 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 15:19:27.828  3923  4472 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 15:19:27.831  3923  4476 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: IncomingSocketThread/Receiver)
,08-29 15:19:27.833  3923  4476 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: IncomingSocketThread/Receiver)
08-29 15:19:27.833  3923  4476 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-29 15:19:27.834  3923  4476 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 15:19:27.834  3923  4477 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: OutgoingSocketThread/Sender)
,08-29 15:19:27.836  3923  4472 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 15:19:27.841  3923  4478 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: OutgoingSocketThread/Receiver)
08-29 15:19:27.843  3923  4478 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: OutgoingSocketThread/Receiver)
08-29 15:19:27.843  3923  4478 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 15:19:27.843  3923  4478 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 15:19:30.823  3923  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 470)
,08-29 15:19:30.825  3923  3986 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 15:19:30.825  3923  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 471)
,08-29 15:19:30.832  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:19:30.832  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76a1968 added. We now have 3 listener(s)
,08-29 15:19:30.834  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:19:30.834  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 15:19:30.834  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:19:30.834  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:19:30.834  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5ab181 added. We now have 4 listener(s)
08-29 15:19:30.834  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:19:30.835  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:19:30.842  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:30.849  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:19:30.851  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:30.851  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:19:30.852  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:19:30.852  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:19:30.852  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 15:19:30.852  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:19:30.852  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:30.852  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:19:30.852  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 15:19:30.852  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76a1968 removed from the list
,08-29 15:19:30.852  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:30.853  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5ab181 removed from the list
,08-29 15:19:30.857  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:30.863  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:30.863  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:19:30.863  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:30.864  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:30.864  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:30.866  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:30.866  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 15:19:30.866  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:19:30.866  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5ab181 not in the list
,08-29 15:19:30.866  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 15:19:30.866  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:30.867  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:30.868  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:30.868  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:30.868  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a5ab181 not in the list
,08-29 15:19:30.868  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:30.868  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:30.868  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:30.868  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76a1968 not in the list
08-29 15:19:30.869  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:19:30.869  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7787e67 added. We now have 3 listener(s)
,08-29 15:19:30.871  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:19:30.871  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:19:30.871  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:19:30.871  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:19:30.871  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7b6414 added. We now have 4 listener(s)
08-29 15:19:30.871  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 15:19:30.873  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:19:30.875  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:30.882  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:19:30.885  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:30.886  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:19:30.886  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:19:30.886  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:19:30.886  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 15:19:30.886  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:30.886  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:19:30.892  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:30.901  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:30.902  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:19:30.903  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:19:30.907  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:19:30.908  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:19:30.908  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:19:30.912  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 15:19:30.912  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:19:30.912  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 15:19:30.913  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:19:30.917  4381  4417 D BtGatt.GattService: registerClient() - UUID=02538e94-8cf5-4675-a85b-fee2a353d3e3
,08-29 15:19:30.919  4381  4397 D BtGatt.GattService: onClientRegistered() - UUID=02538e94-8cf5-4675-a85b-fee2a353d3e3, clientIf=5
,08-29 15:19:30.920  3923  3935 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 15:19:30.922  4381  4421 D BtGatt.GattService: start scan with filters
,08-29 15:19:30.927  4381  4400 D BtGatt.ScanManager: handling starting scan
,08-29 15:19:30.928  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 15:19:30.928  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 15:19:30.928  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:19:30.928  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:19:30.929  4381  4400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b0f208c
,08-29 15:19:30.932  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:19:30.932  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 15:19:30.933  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:19:30.936  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:19:30.939  4381  4397 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 15:19:30.939  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:30.940  3923  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 15:19:30.940  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 15:19:30.940  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:19:30.940  4381  4400 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 15:19:30.940  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:30.940  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 15:19:30.941  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:19:30.941  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 15:19:30.941  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:19:30.941  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:19:30.941  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 15:19:30.941  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 15:19:30.943  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:19:30.946  4381  4421 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:19:30.947  4381  4409 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 15:19:30.948  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:19:30.948  4381  4397 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 15:19:30.948  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:19:30.948  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:30.948  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:19:30.949  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:19:30.949  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:19:30.949  4381  4400 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:19:30.949  4381  4400 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 15:19:30.953  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:19:30.953  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:19:30.953  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:19:30.954  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 15:19:30.955  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:19:30.959  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:19:30.959  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:19:30.960  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:19:30.964  4381  4397 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 15:19:30.964  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:30.973  4381  4397 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:19:30.973  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:30.983  4381  4397 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 15:19:30.983  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:30.984  4381  4400 D BtGatt.ScanManager: stopping BLe Batch
,08-29 15:19:30.991  4381  4397 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 15:19:30.992  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:30.992  4381  4400 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:19:30.999  4381  4397 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 15:19:30.999  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:31.461  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:19:31.462  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:19:31.462  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:19:33.959  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:19:33.960  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:19:33.960  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:19:33.960  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:19:33.961  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:33.961  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:19:33.961  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:19:33.962  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7787e67 removed from the list
,08-29 15:19:33.962  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:33.962  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7b6414 removed from the list
08-29 15:19:33.963  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:19:33.963  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:33.965  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:33.965  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:33.968  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:33.968  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:33.969  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:33.969  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7b6414 not in the list
,08-29 15:19:33.969  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:33.970  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:33.973  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:33.973  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:19:33.973  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:33.974  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7b6414 not in the list
08-29 15:19:33.974  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:33.974  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:33.974  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:33.975  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7787e67 not in the list
08-29 15:19:33.977  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 15:19:33.977  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecb0fb9 added. We now have 3 listener(s)
,08-29 15:19:33.981  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:19:33.981  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:19:33.981  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:19:33.982  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:19:33.982  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d563ffe added. We now have 4 listener(s)
08-29 15:19:33.982  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:19:33.982  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:19:33.986  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:33.993  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 15:19:33.996  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:33.996  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:19:33.996  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 15:19:33.997  3923  3986 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-29 15:19:33.997  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,08-29 15:19:33.998  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-29 15:19:33.999  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-29 15:19:33.999  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 15:19:34.000  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:33.999  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:34.001  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 15:19:34.002  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 15:19:34.002  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 15:19:34.003  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-29 15:19:34.003  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-29 15:19:34.003  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:34.003  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:34.003  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-29 15:19:34.003  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 15:19:34.004  3923  4479 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 15:19:34.007  3923  4479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 15:19:34.017  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 15:19:34.017  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 15:19:34.026  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:19:34.027  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 15:19:34.027  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:19:34.030  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-29 15:19:34.030  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 15:19:34.030  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-29 15:19:34.031  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-29 15:19:34.031  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 15:19:34.031  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-29 15:19:34.032  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:19:34.035  4381  4421 D BtGatt.GattService: registerClient() - UUID=5b477b64-1790-4ca1-833d-260484f1b2f4
,08-29 15:19:34.035  4381  4397 D BtGatt.GattService: onClientRegistered() - UUID=5b477b64-1790-4ca1-833d-260484f1b2f4, clientIf=5
08-29 15:19:34.036  3923  3934 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 15:19:34.038  4381  4399 D BtGatt.AdvertiseManager: message : 0
,08-29 15:19:34.041  4381  4399 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 15:19:34.057  4381  4397 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 15:19:34.069  4381  4397 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 15:19:34.071  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 15:19:34.071  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 15:19:34.077  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:19:34.081  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 15:19:34.081  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-29 15:19:34.082  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-29 15:19:34.082  3923  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-29 15:19:34.082  3923  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-29 15:19:34.083  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-29 15:19:34.088  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:19:34.092  3923  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-29 15:19:34.092  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 15:19:34.593  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 15:19:34.594  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:19:34.594  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:19:37.089  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:19:37.090  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-29 15:19:37.090  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:19:37.090  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 15:19:37.090  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 15:19:37.091  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 15:19:37.092  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 15:19:37.092  3923  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 15:19:37.092  3923  4479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 15:19:37.092  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:19:37.092  3923  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 15:19:37.093  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:19:37.093  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:19:37.093  3923  4479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 15:19:37.093  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:19:37.093  3923  4479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 15:19:37.094  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:19:37.096  3923  3986 D BluetoothAdapter: STATE_ON
08-29 15:19:37.096  3923  3986 D BluetoothLeScanner: could not find callback wrapper
08-29 15:19:37.097  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 15:19:37.097  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 15:19:37.099  4381  4399 D BtGatt.AdvertiseManager: message : 1
08-29 15:19:37.101  4381  4399 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 15:19:37.112  4381  4397 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-29 15:19:37.112  4381  4397 D BtGatt.GattService: Client app is not null!
,08-29 15:19:37.113  4381  4391 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 15:19:37.114  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:19:37.114  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 15:19:37.114  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 15:19:37.114  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 15:19:37.114  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 15:19:37.115  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 15:19:37.116  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 15:19:37.116  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:19:37.116  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:19:37.119  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:19:37.120  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:37.120  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:19:37.120  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:19:37.120  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecb0fb9 removed from the list
08-29 15:19:37.121  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:37.121  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d563ffe removed from the list
08-29 15:19:37.121  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-29 15:19:37.121  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:37.122  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:19:37.122  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:19:37.122  3923  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 15:19:37.122  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:19:37.124  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:37.124  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:37.126  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:37.127  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:37.128  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:37.128  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d563ffe not in the list
08-29 15:19:37.128  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:37.128  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:37.129  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:37.130  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:37.130  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:37.130  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d563ffe not in the list
,08-29 15:19:37.130  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:37.130  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:37.130  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:37.130  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ecb0fb9 not in the list
08-29 15:19:37.131  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:19:37.131  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f5467b added. We now have 3 listener(s)
08-29 15:19:37.133  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:19:37.133  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:19:37.133  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:19:37.133  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:19:37.133  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30aac98 added. We now have 4 listener(s)
08-29 15:19:37.133  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:19:37.134  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 15:19:37.136  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:37.140  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:19:37.142  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:37.142  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 15:19:37.143  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:19:37.143  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 15:19:37.143  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-29 15:19:37.143  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:37.143  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 15:19:37.146  3923  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 15:19:37.146  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 15:19:37.147  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:37.150  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:37.151  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 15:19:37.151  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 15:19:37.151  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 15:19:37.154  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 15:19:37.154  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 15:19:37.155  3923  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 15:19:37.155  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:19:37.157  4381  4392 D BtGatt.GattService: registerClient() - UUID=cb207556-7d4d-40e8-b26f-74150175ff46
,08-29 15:19:37.158  4381  4397 D BtGatt.GattService: onClientRegistered() - UUID=cb207556-7d4d-40e8-b26f-74150175ff46, clientIf=5
08-29 15:19:37.158  3923  3935 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 15:19:37.159  4381  4417 D BtGatt.GattService: start scan with filters
,08-29 15:19:37.161  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 15:19:37.161  4381  4400 D BtGatt.ScanManager: handling starting scan
08-29 15:19:37.162  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 15:19:37.162  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 15:19:37.162  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 15:19:37.164  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 15:19:37.165  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 15:19:37.165  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 15:19:37.167  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 15:19:37.169  4381  4397 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 15:19:37.169  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:37.169  4381  4400 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 15:19:37.175  4381  4397 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 15:19:37.176  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:37.176  4381  4400 D BtGatt.ScanManager: Starting BLE batch scan
08-29 15:19:37.176  4381  4400 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 15:19:37.187  4381  4397 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 15:19:37.187  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:37.194  4381  4397 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 15:19:37.194  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:37.623  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:19:37.666  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 15:19:37.666  3923  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 15:19:37.667  3923  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 15:19:38.703  4381  4381 D BtGatt.ScanManager: awakened up at time 243547
,08-29 15:19:38.707  4381  4400 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 15:19:38.769  4381  4397 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
08-29 15:19:38.770  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:38.770  4381  4397 D BtGatt.GattService: current time is 243615236842
08-29 15:19:38.772  4381  4397 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -85, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -102, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -88, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 33, -66, 95, -51, -2, 97, 1, -128, -58, 8, 0, 0, 0, 33, -66, 95, -51, -2, 97, 1, -128, -57, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96, 0]
08-29 15:19:38.775  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 15:19:38.777  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 15:19:38.778  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 15:19:38.779  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 15:19:38.779  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 15:19:38.780  4381  4397 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 15:19:38.781  4381  4397 D BtGatt.GattService: ScanRecord : []
08-29 15:19:38.781  4381  4397 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96]
,08-29 15:19:38.789  3923  3923 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 3], added - the peer count is 1
,08-29 15:19:38.791  3923  3923 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 3], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,08-29 15:19:40.178  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 15:19:40.178  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:19:40.179  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 15:19:40.179  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.179  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 15:19:40.180  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 15:19:40.180  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 15:19:40.180  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 15:19:40.181  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 15:19:40.182  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 15:19:40.182  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 15:19:40.185  3923  3986 D BluetoothAdapter: STATE_ON
,08-29 15:19:40.187  4381  4421 D BtGatt.GattService: stopScan() - queue size =1
,08-29 15:19:40.189  4381  4392 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 15:19:40.190  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 15:19:40.191  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 15:19:40.191  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 15:19:40.192  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 15:19:40.192  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 15:19:40.195  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:19:40.196  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 15:19:40.196  3923  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 15:19:40.197  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 15:19:40.201  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 15:19:40.201  3923  3986 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-29 15:19:40.203  4381  4381 D BtGatt.ScanManager: awakened up at time 245048
,08-29 15:19:40.207  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:40.207  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:40.207  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 15:19:40.207  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:19:40.208  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 15:19:40.208  3923  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 15:19:40.208  3923  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 15:19:40.208  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f5467b removed from the list
,08-29 15:19:40.209  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 15:19:40.210  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30aac98 removed from the list
,08-29 15:19:40.210  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:19:40.210  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:40.211  4381  4397 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 15:19:40.211  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 15:19:40.211  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.211  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:40.211  4381  4400 D BtGatt.ScanManager: stopping BLe Batch
08-29 15:19:40.212  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:40.212  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:40.212  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:40.212  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30aac98 not in the list
08-29 15:19:40.212  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 15:19:40.212  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:40.213  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:40.215  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:40.215  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:40.216  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30aac98 not in the list
08-29 15:19:40.216  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 15:19:40.216  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.216  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:40.216  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f5467b not in the list
08-29 15:19:40.218  4381  4397 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 15:19:40.218  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:40.218  4381  4400 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 15:19:40.219  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 15:19:40.219  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8a462 added. We now have 3 listener(s)
08-29 15:19:40.225  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 15:19:40.226  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 15:19:40.226  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 15:19:40.227  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 15:19:40.227  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75009f3 added. We now have 4 listener(s)
08-29 15:19:40.227  3923  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 15:19:40.229  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 15:19:40.230  4381  4397 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-29 15:19:40.231  4381  4397 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 15:19:40.231  4381  4397 D BtGatt.GattService: current time is 245075974753
08-29 15:19:40.231  4381  4397 D BtGatt.GattService: Batch record : [33, -66, 95, -51, -2, 97, 1, -128, -68, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96, 0]
08-29 15:19:40.231  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 15:19:40.232  4381  4397 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, 124, -7, 14, 52, -118, -96]
,08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 15:19:40.237  3923  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 15:19:40.239  3923  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 15:19:40.239  3923  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 15:19:40.239  3923  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 15:19:40.239  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 15:19:40.240  3923  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 15:19:40.240  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:40.240  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.240  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 15:19:40.240  3923  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 15:19:40.240  3923  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8a462 removed from the list
08-29 15:19:40.240  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:40.240  3923  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75009f3 removed from the list
,08-29 15:19:40.241  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 15:19:40.241  3923  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 15:19:40.242  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:40.242  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.242  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 15:19:40.244  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 15:19:40.244  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:40.244  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:40.244  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75009f3 not in the list
08-29 15:19:40.244  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.244  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:40.244  3923  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 15:19:40.245  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 15:19:40.245  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 15:19:40.245  3923  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 15:19:40.245  3923  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75009f3 not in the list
,08-29 15:19:40.245  3923  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 15:19:40.245  3923  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 15:19:40.246  3923  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 15:19:40.246  3923  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8a462 not in the list
08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 15:19:40.247  3923  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 15:19:40.709  3923  3923 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 15:19:42.262  3923  4481 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 480, name: My test thread name)
,08-29 15:19:44.260  3923  3986 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 480
,08-29 15:19:44.260  3923  3986 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 480, name: My test thread name)
,08-29 15:19:44.267  3923  4482 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 481, name: My test thread name)
,08-29 15:19:44.267  3923  4482 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 481, thread name: My test thread name)
08-29 15:19:44.268  3923  4482 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 481, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-29 15:19:44.272  3923  3986 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 15:19:44.281  3923  4483 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 485, name: My test thread name)
,08-29 15:19:44.282  3923  4483 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 485, thread name: My test thread name): Test exception.
08-29 15:19:44.282  3923  4483 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 485, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-29 15:19:44.289  3923  3986 I jxcore-log: Total number of executed tests:  82
08-29 15:19:44.289  3923  3986 I jxcore-log: 
,08-29 15:19:44.290  3923  3986 I jxcore-log: Number of passed tests:  82
08-29 15:19:44.290  3923  3986 I jxcore-log: 
08-29 15:19:44.291  3923  3986 I jxcore-log: Number of failed tests:  0
08-29 15:19:44.291  3923  3986 I jxcore-log: 
,08-29 15:19:44.292  3923  3986 I jxcore-log: Number of ignored tests:  0
08-29 15:19:44.292  3923  3986 I jxcore-log: 
,08-29 15:19:44.294  3923  3986 I jxcore-log: Total duration:  106340
08-29 15:19:44.294  3923  3986 I jxcore-log: 
,08-29 15:19:44.320  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.320  3923  3986 I jxcore-log: 
,08-29 15:19:44.325  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.325  3923  3986 I jxcore-log: 
,08-29 15:19:44.326  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.326  3923  3986 I jxcore-log: 
,08-29 15:19:44.327  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.327  3923  3986 I jxcore-log: 
08-29 15:19:44.328  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.328  3923  3986 I jxcore-log: 
,08-29 15:19:44.329  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.329  3923  3986 I jxcore-log: 
,08-29 15:19:44.332  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 15:19:44.332  3923  3986 I jxcore-log: 
,08-29 15:19:44.333  3923  4481 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 480, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
08-29 15:19:44.334  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.334  3923  3986 I jxcore-log: 
,08-29 15:19:44.335  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.335  3923  3986 I jxcore-log: 
08-29 15:19:44.336  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.336  3923  3986 I jxcore-log: 
,08-29 15:19:44.337  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.337  3923  3986 I jxcore-log: 
08-29 15:19:44.337  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.337  3923  3986 I jxcore-log: 
,08-29 15:19:44.338  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 15:19:44.338  3923  3986 I jxcore-log: 
08-29 15:19:44.340  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.340  3923  3986 I jxcore-log: 
,08-29 15:19:44.341  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 15:19:44.341  3923  3986 I jxcore-log: 
,08-29 15:19:44.342  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-29 15:19:44.342  3923  3986 I jxcore-log: 
08-29 15:19:44.343  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.343  3923  3986 I jxcore-log: 
,08-29 15:19:44.343  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.343  3923  3986 I jxcore-log: 
08-29 15:19:44.344  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.344  3923  3986 I jxcore-log: 
,08-29 15:19:44.345  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.345  3923  3986 I jxcore-log: 
08-29 15:19:44.346  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.346  3923  3986 I jxcore-log: 
08-29 15:19:44.346  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.346  3923  3986 I jxcore-log: 
,08-29 15:19:44.347  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.347  3923  3986 I jxcore-log: 
08-29 15:19:44.348  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.348  3923  3986 I jxcore-log: 
08-29 15:19:44.349  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.349  3923  3986 I jxcore-log: 
,08-29 15:19:44.349  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.349  3923  3986 I jxcore-log: 
08-29 15:19:44.350  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.350  3923  3986 I jxcore-log: 
08-29 15:19:44.351  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.351  3923  3986 I jxcore-log: 
,08-29 15:19:44.352  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.352  3923  3986 I jxcore-log: 
08-29 15:19:44.352  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.352  3923  3986 I jxcore-log: 
08-29 15:19:44.353  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.353  3923  3986 I jxcore-log: 
,08-29 15:19:44.354  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.354  3923  3986 I jxcore-log: 
08-29 15:19:44.355  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.355  3923  3986 I jxcore-log: 
,08-29 15:19:44.356  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.356  3923  3986 I jxcore-log: 
,08-29 15:19:44.356  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.356  3923  3986 I jxcore-log: 
08-29 15:19:44.357  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.357  3923  3986 I jxcore-log: 
08-29 15:19:44.358  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.358  3923  3986 I jxcore-log: 
08-29 15:19:44.359  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.359  3923  3986 I jxcore-log: 
,08-29 15:19:44.360  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.360  3923  3986 I jxcore-log: 
08-29 15:19:44.360  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.360  3923  3986 I jxcore-log: 
08-29 15:19:44.361  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.361  3923  3986 I jxcore-log: 
08-29 15:19:44.361  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.361  3923  3986 I jxcore-log: 
,08-29 15:19:44.362  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.362  3923  3986 I jxcore-log: 
08-29 15:19:44.362  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.362  3923  3986 I jxcore-log: 
08-29 15:19:44.363  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.363  3923  3986 I jxcore-log: 
,08-29 15:19:44.363  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.363  3923  3986 I jxcore-log: 
08-29 15:19:44.364  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.364  3923  3986 I jxcore-log: 
08-29 15:19:44.364  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 15:19:44.364  3923  3986 I jxcore-log: 
08-29 15:19:44.365  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.365  3923  3986 I jxcore-log: 
,08-29 15:19:44.365  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 15:19:44.365  3923  3986 I jxcore-log: 
08-29 15:19:44.366  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.366  3923  3986 I jxcore-log: 
08-29 15:19:44.366  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.366  3923  3986 I jxcore-log: 
08-29 15:19:44.367  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.367  3923  3986 I jxcore-log: 
,08-29 15:19:44.367  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.367  3923  3986 I jxcore-log: 
08-29 15:19:44.368  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.368  3923  3986 I jxcore-log: 
08-29 15:19:44.368  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.368  3923  3986 I jxcore-log: 
,08-29 15:19:44.369  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.369  3923  3986 I jxcore-log: 
08-29 15:19:44.369  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-29 15:19:44.369  3923  3986 I jxcore-log: 
08-29 15:19:44.370  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.370  3923  3986 I jxcore-log: 
08-29 15:19:44.370  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.370  3923  3986 I jxcore-log: 
08-29 15:19:44.371  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-29 15:19:44.371  3923  3986 I jxcore-log: 
08-29 15:19:44.371  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-29 15:19:44.371  3923  3986 I jxcore-log: 
08-29 15:19:44.372  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 15:19:44.372  3923  3986 I jxcore-log: 
08-29 15:19:44.372  3923  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 15:19:44.372  3923  3986 I jxcore-log: 
,08-29 15:19:44.375  3923  3986 I jxcore-log: My device name is: motorola-Nexus 6
08-29 15:19:44.375  3923  3986 I jxcore-log: 
,08-29 15:19:47.304  3743  4486 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 15:19:47.392  3743  4487 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 15:19:47.408  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:47.415  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:47.452  1514  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:19:47.452  1514  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:19:47.452  1514  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:19:47.452  1514  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:47.463  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:19:47.463  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 15:19:47.463  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:19:47.463  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:47.485  3645  4485 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:19:47.485  3645  4485 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:19:47.485  3645  4485 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	... 12 more
08-29 15:19:47.485  3645  4485 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at fal.a(PG:38)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:19:47.485  3645  4485 E HttpOperation: 	... 14 more
,08-29 15:19:47.532  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:19:47.533  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:19:47.533  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:19:47.533  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 15:19:47.534  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:19:47.534  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:19:47.534  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:19:47.534  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:47.556  3645  4485 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:19:47.556  3645  4485 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at hec.a(PG:42)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at hee.a(PG:102)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at czr.a(PG:65)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at kka.a(PG:108)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588),
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:19:47.556  3645  4485 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	... 15 more
08-29 15:19:47.556  3645  4485 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at fal.a(PG:38)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:19:47.556  3645  4485 E HttpOperation: 	... 17 more
,08-29 15:19:47.557  3645  4485 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:19:47.557  3645  4485 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: ,	at hec.a(PG:42)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	... 15 more
08-29 15:19:47.557  3645  4485 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:19:47.557  3645  4485 E ExperimentLoader: 	... 17 more
,08-29 15:19:47.572  3743  4487 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 15:19:47.573  3743  4486 E BooksSync: Soft error
08-29 15:19:47.573  3743  4486 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:19:47.573  3743  4486 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 15:19:47.573  3743  4486 E BooksSync: Sync error
08-29 15:19:47.573  3743  4486 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:19:47.573  3743  4486 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:19:47.573  3743  4486 I BooksSync: Finished books sync
,08-29 15:19:47.584   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 251205, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:19:47.675   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 239475, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:19:48.518  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-29 15:19:48.518  3923  3986 I jxcore-log: 
,08-29 15:19:49.487  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-29 15:19:49.487  3923  3986 I jxcore-log: 
,08-29 15:19:49.514  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-29 15:19:49.514  3923  3986 I jxcore-log: 
,08-29 15:19:49.519  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-29 15:19:49.519  3923  3986 I jxcore-log: 
,08-29 15:19:49.525  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-29 15:19:49.525  3923  3986 I jxcore-log: 
,08-29 15:19:49.542  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-29 15:19:49.542  3923  3986 I jxcore-log: 
,08-29 15:19:49.547  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-29 15:19:49.547  3923  3986 I jxcore-log: 
,08-29 15:19:50.746   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255590, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:19:52.804  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-29 15:19:52.804  3923  3986 I jxcore-log: 
,08-29 15:19:52.815  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-29 15:19:52.815  3923  3986 I jxcore-log: 
,08-29 15:19:52.824  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-29 15:19:52.824  3923  3986 I jxcore-log: 
,08-29 15:19:52.983  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-29 15:19:52.983  3923  3986 I jxcore-log: 
,08-29 15:19:53.796  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-29 15:19:53.796  3923  3986 I jxcore-log: 
,08-29 15:19:54.046  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-29 15:19:54.046  3923  3986 I jxcore-log: 
,08-29 15:19:54.054  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-29 15:19:54.054  3923  3986 I jxcore-log: 
,08-29 15:19:54.251  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-29 15:19:54.251  3923  3986 I jxcore-log: 
,08-29 15:19:54.273  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-29 15:19:54.273  3923  3986 I jxcore-log: 
,08-29 15:19:54.278  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-29 15:19:54.278  3923  3986 I jxcore-log: 
,08-29 15:19:54.284  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-29 15:19:54.284  3923  3986 I jxcore-log: 
,08-29 15:19:54.300  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-29 15:19:54.300  3923  3986 I jxcore-log: 
,08-29 15:19:54.320  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-29 15:19:54.320  3923  3986 I jxcore-log: 
,08-29 15:19:54.403  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-29 15:19:54.403  3923  3986 I jxcore-log: 
,08-29 15:19:54.409  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-29 15:19:54.409  3923  3986 I jxcore-log: 
,08-29 15:19:54.436  3923  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-29 15:19:54.436  3923  3986 I jxcore-log: 
,08-29 15:19:54.451  3923  3986 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-29 15:19:54.452  3923  3986 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-29 15:19:54.452  3923  3986 I jxcore-log: 
,08-29 15:19:55.427  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:55.429  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:19:55.449  3494  4492 V GoogleAuthProtoRequest: [285] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:19:55.490  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 15:19:55.491  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 15:19:55.491  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:19:55.491  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:19:55.514  3494  4492 W ExperimentUpdateService: [285] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: [285] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 15:19:55.515  3494  4492 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 15:20:07.326   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=272170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:20:17.914  4158  4494 V KeepSync: Connecting to GoogleApiClient
,08-29 15:20:17.915   869  2022 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:20:18.009  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:20:18.016  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:20:18.078  1514  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-29 15:20:18.078  1514  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 15:20:18.079  1514  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:20:18.079  1514  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:18.128  1717  4495 V BaseAuthAsyncOperation: access token request failed
,08-29 15:20:18.132  4158  4494 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:20:18.234  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:20:18.235  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 15:20:18.235  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:20:18.236  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:18.274  4158  4494 E KeepSync: IOException
08-29 15:20:18.274  4158  4494 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:20:18.274  4158  4494 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:20:18.274  4158  4494 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:20:18.274  4158  4494 E KeepSync: 	... 10 more
08-29 15:20:18.274  4158  4494 W KeepSync: Sync result 2
,08-29 15:20:18.287   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 252743, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:20:41.126   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:20:48.679  3743  4501 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 15:20:48.788  3743  4504 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 15:20:48.800  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:20:48.807  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:20:48.844  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:20:48.844  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:20:48.844  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:20:48.844  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:48.862  3645  4503 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:20:48.862  3645  4503 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:20:48.862  3645  4503 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	... 12 more
08-29 15:20:48.862  3645  4503 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at fal.a(PG:38)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:20:48.862  3645  4503 E HttpOperation: 	... 14 more
,08-29 15:20:48.881  1514  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:20:48.881  1514  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:20:48.881  1514  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:20:48.881  1514  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:48.906  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:20:48.906  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:20:48.906  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:20:48.906  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:48.922  3645  4503 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:20:48.922  3645  4503 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at hec.a(PG:42)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at hee.a(PG:102)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at czr.a(PG:65)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at kka.a(PG:108)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	,at czp.a(PG:9081)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:20:48.922  3645  4503 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	... 15 more
08-29 15:20:48.922  3645  4503 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at fal.a(PG:38)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:20:48.922  3645  4503 E HttpOperation: 	... 17 more
,08-29 15:20:48.922  3645  4503 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:20:48.922  3645  4503 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	... 15 more
08-29 15:20:48.922  3645  4503 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:20:48.922  3645  4503 E ExperimentLoader: 	... 17 more
,08-29 15:20:48.958  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 15:20:48.958  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:20:48.958  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:20:48.958  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:20:48.975  3743  4504 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 15:20:48.978  3743  4501 E BooksSync: Soft error
08-29 15:20:48.978  3743  4501 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:20:48.978  3743  4501 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:20:48.979  3743  4501 E BooksSync: Sync error
08-29 15:20:48.979  3743  4501 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:20:48.979  3743  4501 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 15:20:48.979  3743  4501 I BooksSync: Finished books sync
,08-29 15:20:48.984   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 283409, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:20:49.080   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 284674, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:20:58.940   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:21:19.974  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:19.983  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:19.987  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:20.051  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-29 15:21:20.051  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-29 15:21:20.054  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:21:20.055  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:21:20.084  1514  1962 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-29 15:21:20.084  1514  1962 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 15:21:20.091  3607  3637 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 15:21:20.091  3607  3637 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-29 15:21:20.091  3607  3637 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-29 15:21:20.091  3607  3637 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-29 15:21:20.091  3607  3637 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-29 15:21:20.091  3607  3637 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-29 15:21:20.091  3607  3637 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 15:21:20.146  4158  4508 V KeepSync: Connecting to GoogleApiClient
,08-29 15:21:20.147   869  2068 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:21:20.239  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 15:21:20.239  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 15:21:20.239  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:21:20.240  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:21:20.268  1717  4510 V BaseAuthAsyncOperation: access token request failed
08-29 15:21:20.269  4158  4508 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:21:20.346  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:21:20.346  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 15:21:20.346  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:21:20.346  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:21:20.399  4158  4508 E KeepSync: IOException
08-29 15:21:20.399  4158  4508 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:21:20.399  4158  4508 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:21:20.399  4158  4508 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:21:20.399  4158  4508 E KeepSync: 	... 10 more
,08-29 15:21:20.399  4158  4508 W KeepSync: Sync result 2
,08-29 15:21:20.414   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 344848, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:21:51.008  3743  4515 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 15:21:51.056  3743  4516 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 15:21:51.083  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:51.091  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:51.168  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:21:51.168  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:21:51.169  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:21:51.169  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:21:51.219  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:51.223  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:21:51.276  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 15:21:51.276  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:21:51.276  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:21:51.276  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:21:51.303  3743  4516 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 15:21:51.305  3743  4515 E BooksSync: Soft error
08-29 15:21:51.305  3743  4515 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:21:51.305  3743  4515 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 15:21:51.305  3743  4515 E BooksSync: Sync error
08-29 15:21:51.305  3743  4515 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:21:51.305  3743  4515 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 15:21:51.305  3743  4515 I BooksSync: Finished books sync
,08-29 15:21:51.316   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 375785, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:21:54.299   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:22:02.833   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=387677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:22:21.794  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:22:21.799  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:22:21.843  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 15:22:21.843  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 15:22:21.843  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:22:21.843  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:22:21.865  3645  4519 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:22:21.865  3645  4519 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:22:21.865  3645  4519 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	... 12 more
08-29 15:22:21.865  3645  4519 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at fal.a(PG:38)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:22:21.865  3645  4519 E HttpOperation: 	... 14 more
,08-29 15:22:21.930  1514  1959 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:22:21.930  1514  1959 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:22:21.930  1514  1959 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:22:21.930  1514  1959 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:22:21.953  3645  4519 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:22:21.953  3645  4519 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at hec.a(PG:42)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at hee.a(PG:102)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at czr.a(PG:65)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at kka.a(PG:108)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:22:21.953  3645  4519 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	... 15 more
08-29 15:22:21.953  3645  4519 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at fal.a(PG:38)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:22:21.953  3645  4519 E HttpOperation: 	... 17 more
,08-29 15:22:21.953  3645  4519 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:22:21.953  3645  4519 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	... 15 more
08-29 15:22:21.953  3645  4519 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:22:21.953  3645  4519 E ExperimentLoader: 	... 17 more
,08-29 15:22:22.053   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 378233, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:22:36.752   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:22:46.566   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=431410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:23:20.486   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=465330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:23:23.956  4158  4523 V KeepSync: Connecting to GoogleApiClient
,08-29 15:23:23.957   869  2068 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 15:23:24.023  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:24.026  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:24.077  1514  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 15:23:24.078  1514  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 15:23:24.078  1514  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:23:24.078  1514  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:23:24.117  1717  4524 V BaseAuthAsyncOperation: access token request failed
,08-29 15:23:24.119  4158  4523 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 15:23:24.196  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 15:23:24.196  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 15:23:24.196  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 15:23:24.196  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:23:24.224  4158  4523 E KeepSync: IOException
08-29 15:23:24.224  4158  4523 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 15:23:24.224  4158  4523 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 15:23:24.224  4158  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 15:23:24.224  4158  4523 E KeepSync: 	... 10 more
,08-29 15:23:24.224  4158  4523 W KeepSync: Sync result 2
,08-29 15:23:24.237   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 468693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:23:55.411  3743  4526 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 15:23:55.462  3743  4527 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 15:23:55.471  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:55.473  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:55.504  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 15:23:55.504  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 15:23:55.504  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:23:55.504  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:23:55.566  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:55.568  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:23:55.601  3494  4529 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:23:55.605  1514  1962 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 15:23:55.605  1514  1962 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 15:23:55.605  1514  1962 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:23:55.606  1514  1962 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:23:55.628  3743  4527 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 15:23:55.630  3743  4526 E BooksSync: Soft error
08-29 15:23:55.630  3743  4526 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:23:55.630  3743  4526 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:23:55.630  3743  4526 E BooksSync: Sync error
08-29 15:23:55.630  3743  4526 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 15:23:55.630  3743  4526 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 15:23:55.630  3743  4526 I BooksSync: Finished books sync
,08-29 15:23:55.646   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 500073, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:23:55.663  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-29 15:23:55.664  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 15:23:55.664  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:23:55.664  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 15:23:55.687  3494  4529 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 15:24:21.673   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=526517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:24:30.953  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:24:30.955  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:24:30.995  1514  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:24:30.995  1514  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:24:30.995  1514  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:24:30.995  1514  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:24:31.016  3645  4532 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 15:24:31.016  3645  4532 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at blb.a(PG:3937)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at czp.a(PG:18188)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:24:31.016  3645  4532 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	... 12 more
08-29 15:24:31.016  3645  4532 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at fal.a(PG:38)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:24:31.016  3645  4532 E HttpOperation: 	... 14 more
,08-29 15:24:31.072  1514  2911 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 15:24:31.072  1514  2911 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 15:24:31.072  1514  2911 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:24:31.072  1514  2911 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:24:31.090  3645  4532 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 15:24:31.090  3645  4532 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jdm.a(PG:82)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jcs.o(PG:406)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jcn.a(PG:1379)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jcs.i(PG:143)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at hec.a(PG:42)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at hee.a(PG:102)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at czr.a(PG:65)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at kka.a(PG:108)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at czp.a(PG:19176)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at czp.a(PG:9081)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at czq.run(PG:1686)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:24:31.090  3645  4532 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jdj.a(PG:4091)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jdj.a(PG:1125)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jdm.a(PG:77)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	... 15 more
08-29 15:24:31.090  3645  4532 E HttpOperation: Caused by: faj: BadAuthentication
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at fal.a(PG:38)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	at jdj.a(PG:4089)
08-29 15:24:31.090  3645  4532 E HttpOperation: 	... 17 more
,08-29 15:24:31.090  3645  4532 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 15:24:31.090  3645  4532 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at hec.a(PG:42)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at hee.a(PG:102)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at czr.a(PG:65)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at kka.a(PG:108)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	,at jdm.a(PG:77)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	... 15 more
08-29 15:24:31.090  3645  4532 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at fal.a(PG:38)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 15:24:31.090  3645  4532 E ExperimentLoader: 	... 17 more
,08-29 15:24:31.182   869   881 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 535514, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-29 15:24:55.633   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=560477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:25:25.726   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:25:59.633   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=624477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:26:25.526   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 15:26:59.366   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=684210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:34:17.152  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:34:17.155  1514  1514 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 15:34:17.174  3494  4568 V GoogleAuthProtoRequest: [287] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 15:34:17.200  1514  3687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 15:34:17.200  1514  3687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 15:34:17.200  1514  3687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 15:34:17.201  1514  3687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: [287] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: [287] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 15:34:17.219  3494  4568 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 15:34:22.152   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 15:34:33.259   869  4440 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1138103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 15:35:54.364   869   881 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-29 15:41:16.012  4590  4590 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 15:41:16.017  4590  4590 D AndroidRuntime: CheckJNI is OFF
08-29 15:41:16.059  4590  4590 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 15:41:16.106  4590  4590 I Radio-JNI: register_android_hardware_Radio DONE
08-29 15:41:16.130  4590  4590 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 15:41:16.143   869   882 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-29 15:41:16.144   869   882 I ActivityManager: Killing 3923:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-29 15:41:16.274   869  1691 I WindowState: WIN DEATH: Window{6ef1476 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 15:41:16.274   869  1317 D WifiService: Client connection lost with reason: 4
08-29 15:41:16.274   869   879 D GraphicsStats: Buffer count: 2
08-29 15:41:16.288   869   894 W PackageSettings: Skipping PackageSetting{3df6029 com.example.hello/10273} due to missing metadata
08-29 15:41:16.323   869   882 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-29 15:41:16.323   869   882 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-29 15:41:16.324   869   882 E ActivityManager: Failure starting process com.test.thalitest
08-29 15:41:16.324   869   882 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 15:41:16.324   869   882 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.324   869   882 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.324   869   882 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.324   869   882 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:41:16.324   869   882 I ActivityManager:   Force finishing activity ActivityRecord{7fb2daf u0 com.test.thalitest/.MainActivity t2}
08-29 15:41:16.325   869   894 I art     : Starting a blocking GC Explicit
08-29 15:41:16.341   869  1690 W ActivityManager: Spurious death for ProcessRecord{9953b48 0:com.test.thalitest/u0a0}, curProc for 3923: null
08-29 15:41:16.372   869   894 I art     : Explicit concurrent mark sweep GC freed 61073(3MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 733us total 44.751ms
08-29 15:41:16.401   869   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-29 15:41:16.409  4590  4590 I art     : System.exit called, status: 0
08-29 15:41:16.410  4590  4590 I AndroidRuntime: VM exiting with result code 0.
08-29 15:41:16.424   869   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-29 15:41:16.438   869   882 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-29 15:41:16.440  1898  1898 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 15:41:16.441  4381  4381 D BluetoothMapAppObserver: onReceive
08-29 15:41:16.441  4381  4381 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 15:41:16.443  3787  3787 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-29 15:41:16.446   869  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 15:41:16.446  1864  2208 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 15:41:16.462  1898  4604 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 15:41:16.487  1898  4604 I Decoder : createOrResetDecoder
08-29 15:41:16.501  2002  2002 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-29 15:41:16.509   869   879 I ActivityManager: Start proc 4607:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-29 15:41:16.518   869   869 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 15:41:16.519  1514  1514 I ConfigService: onCreate
08-29 15:41:16.540  4607  4607 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-29 15:41:16.547  1898  4604 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-29 15:41:16.566   869   880 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3923 uid 10000
08-29 15:41:16.567  1898  1898 I Keyboard.Facilitator: onFinishInput()
08-29 15:41:16.576  1898  4604 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-29 15:41:16.578  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 15:41:16.578  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-29 15:41:16.580  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 15:41:16.580  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 15:41:16.581  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 15:41:16.581  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 15:41:16.582  1898  4604 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 15:41:16.583  1898  4604 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 15:41:16.583  1898  4604 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 15:41:16.583  1898  4604 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 15:41:16.583  1898  4604 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 15:41:16.583  1898  4604 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-29 15:41:16.588   869   881 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-29 15:41:16.589   869   881 E PackageManager: Failed to write settings, restoring backup
08-29 15:41:16.589   869   881 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 15:41:16.589   869   881 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 15:41:16.589   869   881 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 15:41:16.589   869   881 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 15:41:16.589   869   881 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 15:41:16.589   869   881 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.589   869   881 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.589   869   881 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.594   869   882 E DropBoxManagerService: Can't write: system_server_wtf
08-29 15:41:16.594   869   882 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:41:16.594   869   882 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:41:16.594   869   882 E DropBoxManagerService: 	... 13 more
08-29 15:41:16.600  2015  2098 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.605  4607  4622 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.606  4607  4622 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.613   869  2068 I ActivityManager: Start proc 4624:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-29 15:41:16.613  2015  2098 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 15:41:16.613  2015  2098 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2015
08-29 15:41:16.613  2015  2098 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.613  2015  2098 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.615   869  3218 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:41:16.616  4607  4607 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-29 15:41:16.619  2015  2098 I Process : Sending signal. PID: 2015 SIG: 9
08-29 15:41:16.619   869  4629 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:41:16.619   869  4629 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:41:16.619   869  4629 E DropBoxManagerService: 	... 5 more
08-29 15:41:16.640   869  1687 I ActivityManager: Start proc 4639:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 15:41:16.646  4607  4638 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 15:41:16.670  4639  4639 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-29 15:41:16.711  1514  1514 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-29 15:41:16.715  1514  1514 D AndroidRuntime: Shutting down VM
08-29 15:41:16.716  1514  1514 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:41:16.716  1514  1514 E AndroidRuntime: Process: com.google.process.gapps, PID: 1514
08-29 15:41:16.716  1514  1514 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 15:41:16.716  1514  1514 E AndroidRuntime: 	... 8 more
08-29 15:41:16.718   869  4657 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:41:16.718   869  4657 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:41:16.718   869  4657 E DropBoxManagerService: 	... 5 more
08-29 15:41:16.719   869  1690 D GraphicsStats: Buffer count: 1
08-29 15:41:16.719   869  2033 I WindowState: WIN DEATH: Window{3952002 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 15:41:16.725  1514  1514 I Process : Sending signal. PID: 1514 SIG: 9
08-29 15:41:16.736   869  2022 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2015) has died
08-29 15:41:16.736   869  2022 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 15:41:16.739   869  2022 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 15:41:16.756   869   882 I ActivityManager: Start proc 4658:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:41:16.761   869  1377 I ActivityManager: Killing 3842:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-29 15:41:16.796  4607  4622 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.802  4607  4638 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 15:41:16.803  4607  4638 E AndroidRuntime: Process: android.process.acore, PID: 4607
08-29 15:41:16.803  4607  4638 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.803  4607  4638 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.803  4607  4622 I Process : Sending signal. PID: 4607 SIG: 9
08-29 15:41:16.811   869  1317 D WifiService: Client connection lost with reason: 4
08-29 15:41:16.828   869   887 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 116)
08-29 15:41:16.828   869   887 W DisplayManagerService: Failed to notify process 4607 that displays changed, assuming it died.
08-29 15:41:16.828   869   887 W DisplayManagerService: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1166)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1004)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.-wrap6(DisplayManagerService.java)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1099)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:41:16.828   869   887 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:41:16.836   869  3218 I ActivityManager: Process com.google.process.gapps (pid 1514) has died
08-29 15:41:16.837   869  3218 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-29 15:41:16.837   869  3218 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
08-29 15:41:16.837   869  3218 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
08-29 15:41:16.846   869  4670 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:41:16.846   869  4670 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:41:16.846   869  4670 E DropBoxManagerService: 	... 5 more
08-29 15:41:16.857   869  2068 I ActivityManager: Start proc 4671:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-29 15:41:16.857   869  1690 I ActivityManager: Process android.process.acore (pid 4607) has died
08-29 15:41:16.857   869  1690 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30979ms
08-29 15:41:16.871  1717  1717 W RocketImpressions: ClearcutLogger connection suspended: 1
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:41:16.889  4658  4658 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:41:16.889  4658  4658 D AndroidRuntime: Shutting down VM
08-29 15:41:16.899  4658  4658 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:41:16.899  4658  4658 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4658
08-29 15:41:16.899  4658  4658 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:41:16.899  4658  4658 E AndroidRuntime: 	... 10 more
08-29 15:41:16.901  4671  4671 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-29 15:41:16.902   869  1688 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:41:16.903  4658  4658 I Process : Sending signal. PID: 4658 SIG: 9
08-29 15:41:16.903   869  4685 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:41:16.903   869  4685 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:41:16.903   869  4685 E DropBoxManagerService: 	... 5 more
08-29 15:41:16.907  4671  4671 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 15:41:16.911  1717  1717 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 15:41:16.911  1717  1717 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 15:41:16.920   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
