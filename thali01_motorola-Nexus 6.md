#### Test 80807573a8c39da_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-17 19:50:42.113   874  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-17 19:50:42.804  3768  3768 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 19:50:42.810  3768  3768 D AndroidRuntime: CheckJNI is OFF
08-17 19:50:42.853  3768  3768 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 19:50:42.904  3768  3768 I Radio-JNI: register_android_hardware_Radio DONE
08-17 19:50:42.928  3768  3768 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 19:50:42.937   874  1970 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 19:50:42.985  2030  2041 W SearchService: Abort, client detached.
08-17 19:50:42.995  2030  2030 I HotwordDetector: Closing mic
08-17 19:50:42.996  2030  2329 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1eb1609
08-17 19:50:42.997  2030  2342 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 19:50:43.031  3768  3768 D AndroidRuntime: Shutting down VM
08-17 19:50:43.061   375  2344 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 19:50:43.061   874  2736 I ActivityManager: Start proc 3777:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 19:50:43.066   375  2344 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 19:50:43.075   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 19:50:43.077  2030  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 19:50:43.079  2030  2341 I MicroRecognitionRnrImpl: Detection finished
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:50:43.107  2030  2126 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:50:43.112  2030  2137 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 19:50:43.129  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 19:50:43.131  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 19:50:43.136  3777  3777 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 19:50:43.150  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-17 19:50:43.150  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-17 19:50:43.150  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:50:43.151  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 19:50:43.158  3777  3777 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:50:43.163  2030  2175 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:50:43.164  2030  2145 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 19:50:43.165  3777  3777 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4208-4210)
08-17 19:50:43.165  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:50:43.179  3777  3777 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cf8c43f}
08-17 19:50:43.180  3777  3777 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:50:43.180  3777  3777 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 19:50:43.188  3777  3777 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 19:50:43.190  3777  3777 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 19:50:43.201  3777  3777 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 19:50:43.210  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:50:43.210  3777  3777 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:50:43.210  3777  3777 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:50:43.210  3777  3777 I Adreno  : Build Date                       : 10/20/15
08-17 19:50:43.210  3777  3777 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:50:43.210  3777  3777 I Adreno  : Local Branch                     : M14
08-17 19:50:43.210  3777  3777 I Adreno  : Remote Branch                    : 
08-17 19:50:43.210  3777  3777 I Adreno  : Remote Branch                    : 
08-17 19:50:43.210  3777  3777 I Adreno  : Reconstruct Branch               : 
08-17 19:50:43.249   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7b0432d:true
,08-17 19:50:43.297  3777  3777 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 19:50:43.312  3777  3777 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 19:50:43.378  3777  3819 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 19:50:43.389  3777  3805 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 19:50:43.453  3777  3819 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 19:50:43.586   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms
,08-17 19:50:43.599  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-17 19:50:43.655  3777  3777 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3777
,08-17 19:50:43.745  3777  3777 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 19:50:43.867   874  2736 I ActivityManager: Killing 3213:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 19:50:43.914   874  2736 I ActivityManager: Killing 3118:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 19:50:44.047  3777  3822 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684014800
,08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 19:50:44.054  3777  3822 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff35c93 added. We now have 1 listener(s)
,08-17 19:50:44.057  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 19:50:44.058  3777  3822 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:50:44.059  3777  3822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:50:44.059  3777  3822 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true,
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 19:50:44.062  3777  3822 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d78fce added. We now have 1 listener(s)
,08-17 19:50:44.062  3777  3822 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:50:44.065   874  1308 D WifiService: New client listening to asynchronous messages
,08-17 19:50:44.070  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:50:44.070  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 19:50:44.070  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 19:50:44.071  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 19:50:44.071  3777  3822 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 19:50:44.076  3777  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:44.076  3777  3822 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-17 19:50:44.086  3777  3822 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:44.086  3777  3822 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:44.086  3777  3822 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 19:50:44.086  3777  3822 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:50:44.088  3777  3822 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:50:44.229  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:44.236  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:44.242  3777  3777 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 19:50:44.516  3017  3831 V KeepSync: Connecting to GoogleApiClient
,08-17 19:50:44.516   874  1970 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 19:50:44.565  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 19:50:44.565  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 19:50:44.565  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:50:44.565  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:50:44.578  1738  3832 V BaseAuthAsyncOperation: access token request failed
08-17 19:50:44.579  3017  3831 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 19:50:44.616  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 19:50:44.617  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 19:50:44.617  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:50:44.617  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:50:44.634  3017  3831 E KeepSync: IOException
08-17 19:50:44.634  3017  3831 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 19:50:44.634  3017  3831 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 19:50:44.634  3017  3831 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 19:50:44.634  3017  3831 E KeepSync: 	... 10 more
08-17 19:50:44.634  3017  3831 W KeepSync: Sync result 2
,08-17 19:50:44.637   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 125478, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:50:45.107  3777  3830 W jxcore-log: Initializing JXcore engine
,08-17 19:50:45.107  3777  3830 W jxcore-log: JXcore engine is ready
,08-17 19:50:45.152  3830  3830 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 19:50:45.152  3830  3830 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12881]" dev="sockfs" ino=12881 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-17 19:50:45.152  3830  3830 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 19:50:45.152  3830  3830 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24973]" dev="sockfs" ino=24973 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 19:50:45.168  3777  3830 W jxcore-log: Starting JXcore engine
,08-17 19:50:45.235  3777  3786 I art     : Background partial concurrent mark sweep GC freed 54675(5MB) AllocSpace objects, 7(2MB) LOS objects, 38% free, 25MB/41MB, paused 2.125ms total 134.203ms
,08-17 19:50:45.266  3777  3830 W jxcore-log: Platform android
08-17 19:50:45.266  3777  3830 W jxcore-log: 
,08-17 19:50:45.266  3777  3830 W jxcore-log: Process ARCH arm
08-17 19:50:45.266  3777  3830 W jxcore-log: 
,08-17 19:50:45.534  3777  3830 I jxcore-log: JXcore Cordova bridge is ready!
08-17 19:50:45.534  3777  3830 I jxcore-log: 
,08-17 19:50:45.534  3777  3830 W jxcore-log: JXcore engine is started
,08-17 19:50:45.542  3777  3822 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 19:50:45.547  3777  3777 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 19:50:48.247  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:50:48.271  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 19:50:48.272  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-17 19:50:48.272  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 19:50:48.272  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:50:48.296  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 19:50:48.297  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 19:50:48.297  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 19:50:48.978   874  1914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 19:50:55.452  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 19:50:55.452  3777  3830 I jxcore-log: 
,08-17 19:50:55.454  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 19:50:55.454  3777  3830 I jxcore-log: 
,08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:55.465  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:55.470  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:55.476  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 19:50:55.476  3777  3830 I jxcore-log: 
,08-17 19:50:55.483  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 19:50:55.483  3777  3830 I jxcore-log: 
,08-17 19:50:55.841  3777  3830 D ExecuteNativeTests: Running unit tests
,08-17 19:50:55.900  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:50:55.900  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 added. We now have 2 listener(s)
,08-17 19:50:55.901  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:50:55.901  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:50:55.901  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:50:55.901  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:50:55.901  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e added. We now have 2 listener(s)
08-17 19:50:55.902  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:50:55.902  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:50:55.905  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:55.914  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:55.917  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:55.917  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:55.919  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 19:50:55.921  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:50:55.921  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 19:50:55.923  3777  3830 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 19:50:55.923  3777  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:50:55.923  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:55.923  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:50:55.923  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:50:55.924  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:55.924  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:55.924  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:55.925  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:55.925  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.925  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:55.925  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:50:55.925  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 removed from the list
,08-17 19:50:55.925  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.926  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e removed from the list
,08-17 19:50:55.925  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:55.926  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:55.926  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.927  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.927  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.931  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:55.931  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:55.931  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.931  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:55.933  3777  3830 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 19:50:55.933  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:55.933  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:55.933  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:55.933  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:55.933  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.933  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.933  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:55.933  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.934  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:55.935  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:55.935  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:55.935  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:55.935  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.935  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.935  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:55.937  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:55.937  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:55.937  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.937  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 19:50:55.946  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:50:55.947  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:50:55.948  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:50:55.948  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 19:50:55.948  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:55.948  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:55.948  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:55.948  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:55.948  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.948  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.948  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:55.948  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.948  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:55.948  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:55.948  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.948  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.948  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:55.948  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:55.950  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:55.950  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:55.950  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:55.950  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:55.950  3777  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 19:50:55.953  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:55.963  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:55.967  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:55.968  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:50:55.968  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:50:55.969  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:55.970  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:50:55.970  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:55.970  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:55.970  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:50:55.974  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:55.980  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:50:55.980  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:50:55.995  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:50:55.999  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:50:56.000  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:50:56.006  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:56.011  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 19:50:56.011  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 19:50:56.012  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:50:56.013  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:50:56.015  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:50:56.024  2640  2654 D BtGatt.GattService: registerClient() - UUID=ef490716-6fcd-4913-889b-2cff1ab80b99
,08-17 19:50:56.026  2640  2673 D BtGatt.GattService: onClientRegistered() - UUID=ef490716-6fcd-4913-889b-2cff1ab80b99, clientIf=5
,08-17 19:50:56.028  3777  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 19:50:56.030  2640  2651 D BtGatt.GattService: start scan with filters
,08-17 19:50:56.040  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:50:56.041  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:56.041  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:50:56.041  2640  2676 D BtGatt.ScanManager: handling starting scan
,08-17 19:50:56.044  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:50:56.046  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:56.047  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:56.047  2640  2676 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:50:56.048  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:50:56.049  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:56.052  3777  3830 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:56.058  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:56.058  3777  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:50:56.058  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.058  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:50:56.058  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.058  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:50:56.058  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:50:56.071  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:50:56.074  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:50:56.058  2640  2673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:50:56.074  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:50:56.074  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.075  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:50:56.075  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:50:56.075  2640  2676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:50:56.076  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:50:56.076  2640  2785 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:50:56.077  2640  2760 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:50:56.077  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:50:56.077  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:50:56.077  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:50:56.077  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:50:56.077  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:50:56.081  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:56.081  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:50:56.081  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:50:56.082  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:50:56.082  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:56.091  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:56.092  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:56.092  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:56.092  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.092  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.093  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:56.093  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.093  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.093  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.093  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:56.093  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.094  3777  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:50:56.096  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 19:50:56.096  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.097  2640  2676 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:50:56.097  2640  2676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:50:56.098  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:56.118  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:56.120  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:56.120  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:50:56.121  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:50:56.121  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:56.122  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 19:50:56.122  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:56.122  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:50:56.127  2640  2673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 19:50:56.127  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.127  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.128  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:50:56.129  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:50:56.129  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.138  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:50:56.139  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:50:56.139  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:50:56.141  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:50:56.141  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.148  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:50:56.148  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:50:56.148  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:50:56.149  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:50:56.152  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:50:56.152  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.152  2640  2676 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:50:56.154  2640  2651 D BtGatt.GattService: registerClient() - UUID=1266d874-5db9-4d8b-a929-c1e09ad987ba
,08-17 19:50:56.154  2640  2673 D BtGatt.GattService: onClientRegistered() - UUID=1266d874-5db9-4d8b-a929-c1e09ad987ba, clientIf=5
08-17 19:50:56.155  3777  3787 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:50:56.155  2640  2785 D BtGatt.GattService: start scan with filters
,08-17 19:50:56.158  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:50:56.158  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:56.158  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:50:56.158  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:50:56.160  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:50:56.160  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:50:56.160  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:56.161  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:56.163  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:50:56.163  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.164  2640  2676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 19:50:56.164  3777  3830 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:56.166  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.166  3777  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:56.166  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.166  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:50:56.166  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.166  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:50:56.166  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:56.166  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:50:56.166  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:56.166  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:56.166  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:50:56.166  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:50:56.167  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:50:56.168  2640  2760 D BtGatt.GattService: stopScan() - queue size =0
,08-17 19:50:56.169  2640  2654 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:50:56.169  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:50:56.169  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:50:56.170  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:50:56.170  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-17 19:50:56.170  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:50:56.172  2640  2673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:50:56.172  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.173  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:56.173  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:50:56.173  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:50:56.173  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 19:50:56.174  2640  2676 D BtGatt.ScanManager: handling starting scan
08-17 19:50:56.174  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:56.176  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.176  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:56.176  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:56.176  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.176  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:56.177  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.177  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.177  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.176  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:56.177  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.177  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.178  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.178  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.180  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.180  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.180  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.181  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.181  2640  2673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:50:56.181  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.182  2640  2676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:50:56.182  3777  3830 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 19:50:56.186  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:56.188  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:50:56.188  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.188  2640  2676 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:50:56.188  2640  2676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:56.194  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:56.196  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:56.196  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:50:56.197  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:50:56.197  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:50:56.197  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:50:56.197  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:56.197  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:50:56.199  2640  2673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:50:56.199  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.200  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:50:56.200  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:50:56.201  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.207  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.208  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:50:56.209  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 19:50:56.209  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 19:50:56.210  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:50:56.210  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.218  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:50:56.218  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.218  2640  2676 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:50:56.218  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:50:56.219  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 19:50:56.219  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:50:56.220  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:50:56.226  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 19:50:56.226  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.226  2640  2676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:50:56.228  2640  2651 D BtGatt.GattService: registerClient() - UUID=05f9a425-2594-467e-8c64-2f1f18491cdf
08-17 19:50:56.229  2640  2673 D BtGatt.GattService: onClientRegistered() - UUID=05f9a425-2594-467e-8c64-2f1f18491cdf, clientIf=5
,08-17 19:50:56.229  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:50:56.229  2640  2786 D BtGatt.GattService: start scan with filters
,08-17 19:50:56.233  2640  2673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:50:56.233  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.235  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:50:56.235  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:50:56.235  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:50:56.235  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 19:50:56.238  2640  2676 D BtGatt.ScanManager: handling starting scan
08-17 19:50:56.239  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:50:56.239  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:50:56.239  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:50:56.240  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:50:56.243  3777  3830 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 19:50:56.243  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.243  3777  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 19:50:56.243  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.243  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 19:50:56.243  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.243  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:50:56.243  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:56.243  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:50:56.243  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:56.243  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 19:50:56.243  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:50:56.243  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:50:56.245  3777  3830 D BluetoothAdapter: STATE_ON
08-17 19:50:56.246  2640  2760 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:50:56.247  2640  2786 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:50:56.248  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:50:56.248  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:50:56.248  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 19:50:56.248  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:50:56.248  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:50:56.249  2640  2673 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 19:50:56.249  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.249  2640  2676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:50:56.250  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:56.250  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:50:56.250  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:50:56.250  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:50:56.251  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:50:56.253  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:50:56.254  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-17 19:50:56.254  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:56.254  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:56.254  3777  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:50:56.254  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.254  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:56.254  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.254  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.254  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:50:56.255  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.255  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.255  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.255  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:56.255  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.256  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.256  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.257  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 19:50:56.257  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.257  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.257  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.257  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.257  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.257  2640  2676 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:50:56.258  2640  2676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 19:50:56.259  3777  3830 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-17 19:50:56.259  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-17 19:50:56.259  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.259  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:56.259  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.259  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.259  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.260  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.260  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.260  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.260  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.260  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.260  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.260  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.260  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.261  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:56.261  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.261  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.261  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list,
08-17 19:50:56.264  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-17 19:50:56.264  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 19:50:56.264  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.264  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:56.264  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.265  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.265  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.265  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.265  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-17 19:50:56.265  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.265  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:56.265  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.265  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.265  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.265  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.267  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.267  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.267  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.267  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.268  3777  3830 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 19:50:56.268  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.268  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.268  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:50:56.268  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.268  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.268  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.268  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.268  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.268  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.268  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.269  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.269  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.269  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.269  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.270  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.270  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.270  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.270  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.270  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 19:50:56.271  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:56.271  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.271  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.271  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.271  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.271  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.271  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.271  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.271  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.271  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.271  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.271  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.271  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.271  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.273  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:56.273  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.273  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.273  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.273  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:50:56.275  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:50:56.275  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:56.275  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 19:50:56.275  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 19:50:56.275  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 19:50:56.275  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.275  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.276  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.276  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.276  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.276  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.276  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.276  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.276  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.276  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:56.276  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.276  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.276  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.276  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.277  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.277  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.277  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.278  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.278  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:56.278  3777  3830 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 19:50:56.278  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 19:50:56.283  2640  2673 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:50:56.283  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:50:56.284  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:56.285  3777  3830 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 19:50:56.286  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 19:50:56.286  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 19:50:56.287  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 19:50:56.288  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-17 19:50:56.289  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 19:50:56.289  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-17 19:50:56.290  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 19:50:56.290  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.290  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 19:50:56.291  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 19:50:56.291  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 19:50:56.291  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-17 19:50:56.291  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 19:50:56.291  3777  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:50:56.291  3777  3830 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 19:50:56.291  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:56.292  3777  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:50:56.292  3777  3830 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-17 19:50:56.292  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:56.292  3777  3830 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 19:50:56.292  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 19:50:56.297  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 19:50:56.298  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 19:50:56.298  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 19:50:56.298  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-17 19:50:56.298  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 19:50:56.298  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 19:50:56.299  3777  3830 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 19:50:56.299  3777  3830 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 19:50:56.300  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:56.300  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.300  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.300  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.301  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.301  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.301  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 19:50:56.302  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.302  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.302  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.302  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.302  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.302  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.302  2640  2673 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:50:56.302  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.302  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.302  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.303  2640  2676 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:50:56.303  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.304  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.304  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.304  3777  3844 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
,08-17 19:50:56.304  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.304  3777  3830 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 19:50:56.305  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.305  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.305  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.305  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.305  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.305  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.305  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.305  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.306  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.306  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.306  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.306  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.306  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.306  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.307  3777  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-17 19:50:56.307  3777  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-17 19:50:56.309  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.309  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.309  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.309  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.311  3777  3830 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 19:50:56.311  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.311  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.312  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.312  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.312  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.312  2640  2673 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:50:56.312  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.313  2640  2676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 19:50:56.313  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.313  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.313  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.314  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.314  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.314  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.314  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.314  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.314  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.316  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:50:56.316  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.316  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.317  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.317  3777  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 19:50:56.317  3777  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-17 19:50:56.317  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:56.318  3777  3830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 19:50:56.318  3777  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:50:56.318  3777  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 19:50:56.318  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:50:56.318  3777  3830 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 19:50:56.318  3777  3830 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 19:50:56.318  3777  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-17 19:50:56.318  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:50:56.318  3777  3830 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 19:50:56.318  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.318  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.318  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.319  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.319  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.319  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.319  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.319  2640  2673 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:50:56.319  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.319  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.319  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:50:56.319  2640  2673 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:50:56.319  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.319  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.319  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.319  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.320  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.321  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.321  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.321  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.321  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.321  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.321  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.321  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.321  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:50:56.322  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.322  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.322  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.322  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.322  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.322  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.322  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.322  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.322  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.322  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.322  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.322  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.322  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.323  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.323  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.323  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.323  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.323  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.323  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.323  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.323  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.323  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.323  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.323  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.324  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.325  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.325  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.325  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.327  3777  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 19:50:56.328  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:50:56.329  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 19:50:56.331  3777  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 19:50:56.331  3777  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 19:50:56.332  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-17 19:50:56.332  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 19:50:56.332  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 19:50:56.332  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.333  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 19:50:56.333  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 19:50:56.333  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 19:50:56.333  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.333  3777  3830 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-17 19:50:56.334  3777  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:50:56.334  3777  3777 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 19:50:56.334  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.334  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.334  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:50:56.334  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:50:56.334  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:50:56.335  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.335  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.337  3777  3845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 19:50:56.337  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:50:56.337  3777  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 19:50:56.338  3777  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 19:50:56.338  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:56.338  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:50:56.338  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.338  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:50:56.338  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:50:56.338  3777  3777 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 19:50:56.338  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.338  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.338  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.339  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.339  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.339  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.339  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.339  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.340  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.340  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.340  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.340  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.340  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.342  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.342  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.342  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.342  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.345  3777  3830 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 19:50:56.345  3777  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 19:50:56.345  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 19:50:56.345  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 19:50:56.345  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.345  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.345  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.345  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 19:50:56.345  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:50:56.345  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.346  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.346  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.346  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.346  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.346  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.346  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.346  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.346  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.347  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.347  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.347  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.347  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.350  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.350  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:50:56.350  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.350  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:50:56.350  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.350  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.350  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
,08-17 19:50:56.351  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.351  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.351  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.351  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.351  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:50:56.351  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.351  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.352  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.352  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:50:56.352  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.352  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.353  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:50:56.353  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:50:56.353  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:50:56.353  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:50:56.353  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.353  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.353  3777  3830 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c4d89 not in the list
08-17 19:50:56.353  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.353  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
,08-17 19:50:56.353  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:50:56.353  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.353  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.353  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:50:56.353  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:50:56.354  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:50:56.354  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:50:56.354  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:50:56.355  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2f18e not in the list
08-17 19:50:56.355  3777  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 19:50:56.355  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:56.356  3777  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-17 19:50:56.356  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 19:50:56.356  3777  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-17 19:50:56.356  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 19:50:56.358  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 19:50:56.358  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 19:50:56.358  3777  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-17 19:50:56.358  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:50:56.358  3777  3830 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 19:50:56.358  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 19:50:56.358  3777  3830 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 19:50:56.359  3777  3830 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-17 19:50:56.359  3777  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 19:50:56.359  3777  3830 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 19:50:56.360  3777  3830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 19:50:56.360  3777  3830 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 19:50:56.360  3777  3830 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-17 19:50:56.360  3777  3830 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 19:50:56.361  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:56.361  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c1cadc0 added. We now have 2 listener(s)
08-17 19:50:56.361  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:56.363  3777  3830 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 19:50:56.364   874  1704 D WifiService: setWifiEnabled: true pid=3777, uid=10000
08-17 19:50:56.364   874  1704 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 19:50:56.364  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:56.365  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a6aaf9 added. We now have 3 listener(s)
,08-17 19:50:56.365  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:56.370  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:50:56.370  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fa4da3e added. We now have 4 listener(s)
,08-17 19:50:56.371  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:50:56.372  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:50:56.372  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da4009f added. We now have 5 listener(s)
08-17 19:50:56.372  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:50:56.375   874  1392 D WifiService: setWifiEnabled: false pid=3777, uid=10000
,08-17 19:50:56.375   874  1392 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:50:56.380  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:50:56.382  2640  2669 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 19:50:56.382  2640  2669 D BluetoothAdapterProperties: Setting state to 13
08-17 19:50:56.382  2640  2669 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:50:56.383  2640  2669 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 19:50:56.383  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:56.383  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:56.383  2640  2669 I BluetoothAdapterState: Entering PendingCommandState
08-17 19:50:56.385  2640  2673 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:50:56.385  2640  2669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 19:50:56.385  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.385  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:56.386  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:50:56.387  2640  2640 D HeadsetService: Received stop request...Stopping profile...
08-17 19:50:56.391  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:56.394  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.396  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 19:50:56.399   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 19:50:56.399   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 19:50:56.400   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 19:50:56.400  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.400   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:50:56.400  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:56.401  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:56.401  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:50:56.406  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.409  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.410   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:50:56.412  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.412   874  1923 D DhcpClient: Clearing IP address
,08-17 19:50:56.413   371   872 D CommandListener: Setting iface cfg
,08-17 19:50:56.415   874   887 I ActivityManager: Start proc 3848:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 19:50:56.417  1518  2183 V NativeCrypto: Read error: ssl=0x9b402c00: I/O error during system call, Connection timed out
,08-17 19:50:56.417   874  1925 D DhcpClient: Receive thread stopped
,08-17 19:50:56.420   874   874 D BluetoothHeadset: Proxy object disconnected
,08-17 19:50:56.421  1354  1383 D BluetoothHeadset: Proxy object disconnected
,08-17 19:50:56.421  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,08-17 19:50:56.421   874   874 D BluetoothHeadset: Proxy object disconnected
,08-17 19:50:56.422  1518  2183 V NativeCrypto: SSL shutdown failed: ssl=0x9b402c00: I/O error during system call, Broken pipe
,08-17 19:50:56.423  1952  1963 D BluetoothHeadset: Proxy object disconnected
08-17 19:50:56.423  2640  2640 D BluetoothMapService: onReceive
08-17 19:50:56.423   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 19:50:56.424  2640  2640 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:50:56.424  2640  2640 D BluetoothMapService: STATE_TURNING_OFF
08-17 19:50:56.424  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.424  2640  2640 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:50:56.424  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.424  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:50:56.427   874  1392 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-17 19:50:56.428  2640  2640 D A2dpService: Received stop request...Stopping profile...
08-17 19:50:56.428   874  1899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-17 19:50:56.429   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 19:50:56.429   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 19:50:56.429  2640  2765 D A2dpStateMachine: Exit Disconnected: -1
,08-17 19:50:56.431   874  1899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 19:50:56.431   399   399 E Parcel  : Reading a NULL string not supported here.
,08-17 19:50:56.434  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-17 19:50:56.435   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 19:50:56.436   874   874 D BluetoothA2dp: Proxy object disconnected
08-17 19:50:56.437   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 19:50:56.440   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:50:56.441  2640  2640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 19:50:56.441  2640  2640 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:50:56.442  2640  2640 D HidService: Received stop request...Stopping profile...
08-17 19:50:56.442  2640  2640 D HidService: Stopping Bluetooth HidService
08-17 19:50:56.443  2640  2673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 19:50:56.443  1354  1354 D BluetoothInputDevice: Proxy object disconnected
,08-17 19:50:56.443  1354  1354 D HidProfile: Bluetooth service disconnected
08-17 19:50:56.443  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:50:56.443  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:50:56.443  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:50:56.443  2640  2673 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 19:50:56.443  2640  2640 D HealthService: Received stop request...Stopping profile...
08-17 19:50:56.445  2640  2640 D BluetoothMapService: MAP Service closeService in
08-17 19:50:56.446  2640  2640 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 19:50:56.446  2640  2640 D ObexServerSockets0: shutdown(block = true)
08-17 19:50:56.446  2640  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 19:50:56.447  2640  2640 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:50:56.447  2640  2757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 19:50:56.447  2640  2640 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:50:56.447  2640  2788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 19:50:56.448  2640  2640 I BtOppRfcommListener: stopping Accept Thread
,08-17 19:50:56.448  2640  3420 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 19:50:56.448  2640  3420 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 19:50:56.448   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 19:50:56.449  2640  2640 D PanService: Received stop request...Stopping profile...
,08-17 19:50:56.451   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-17 19:50:56.451  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:50:56.451  1354  1354 D PanProfile: Bluetooth service disconnected
08-17 19:50:56.453  2640  2640 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 19:50:56.453  2640  2640 D BluetoothMapService: stop()
08-17 19:50:56.453  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:56.453  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:50:56.453  2640  2640 D BluetoothMapAppObserver: deinitObservers()
08-17 19:50:56.453  2640  2640 D BluetoothMapAppObserver: removeReceiver()
08-17 19:50:56.453  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.453  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:50:56.455   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 19:50:56.457  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:56.458  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:50:56.457  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.458  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.458  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:50:56.458  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:50:56.457  1354  1354 D BluetoothMap: Proxy object disconnected
08-17 19:50:56.458  1354  1354 D MapProfile: Bluetooth service disconnected
08-17 19:50:56.459  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.459  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:50:56.460  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.460  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.460  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.460  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:50:56.460  2640  2640 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:50:56.460  2640  2640 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:50:56.461  2640  2673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 19:50:56.461  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:50:56.461  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:50:56.461  2640  2751 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:56.461  2640  2751 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:56.461  2640  2751 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:50:56.461  2640  2751 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:50:56.463  2149  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:50:56.464  2640  2673 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 19:50:56.464  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.464  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.464  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.464  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:50:56.464  2640  2640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:50:56.465  2640  2673 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 19:50:56.465  2640  2640 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 19:50:56.467  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.467  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.467  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.467  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:50:56.467  2640  2640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 19:50:56.467  2640  2640 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 19:50:56.468  2640  2640 D BluetoothMapService: MAP Service closeService in
08-17 19:50:56.469  2640  2640 V BluetoothAdapterState: isTurningOff()=true
08-17 19:50:56.469  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.469  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.469  2640  2640 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:50:56.469  2640  2669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 19:50:56.469  2640  2669 D BluetoothAdapterProperties: Setting state to 15
08-17 19:50:56.469  2640  2669 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 19:50:56.470   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:50:56.470  1952  1965 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:50:56.470  1354  1382 D BluetoothPan: onBluetoothStateChange on: false
08-17 19:50:56.471   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:50:56.471  1354  2055 D BluetoothMap: onBluetoothStateChange: up=false
08-17 19:50:56.471  2640  2669 I BluetoothAdapterState: Entering BleOnState
08-17 19:50:56.472   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:50:56.472  1354  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:50:56.472  1354  2056 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:50:56.472   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 19:50:56.472  1354  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 19:50:56.473  1354  2055 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 19:50:56.474  2640  2669 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 19:50:56.474  2640  2669 D BluetoothAdapterProperties: Setting state to 16
08-17 19:50:56.474  2640  2669 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 19:50:56.474  2640  2640 D BluetoothMapService: cleanup()
08-17 19:50:56.474  2640  2640 D BluetoothMapService: MAP Service closeService in
08-17 19:50:56.475  2640  2669 D BluetoothAdapterProperties: onBleDisable
08-17 19:50:56.475  2640  2669 I BluetoothAdapterState: Entering PendingCommandState
08-17 19:50:56.475  2640  2670 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 19:50:56.476  2640  2751 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:50:56.476  2640  2751 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:50:56.477  2640  2673 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:50:56.478  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:56.481  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:56.490  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:56.490  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:56.491  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:50:56.492  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.496   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:50:56.506  3848  3848 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 19:50:56.515   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:50:56.515   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 19:50:56.516   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:56.517   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:50:56.520  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.520  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:50:56.520  3408  3408 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ff35c93 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 19:50:56.531  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:50:56.535  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:50:56.537   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@951f985:true
,08-17 19:50:56.547   874  2736 I ActivityManager: Start proc 3868:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 19:50:56.556  3848  3848 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 19:50:56.558  3848  3848 D BluetoothMap: Create BluetoothMap proxy object
,08-17 19:50:56.562   371   872 E Netd    : netlink response contains error (No such file or directory)
,08-17 19:50:56.563   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 19:50:56.563   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 19:50:56.568  3848  3848 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 19:50:56.578  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 19:50:56.581  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:50:56.589   874  2736 I ActivityManager: Killing 2968:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 19:50:56.678  2640  2673 I bt_hci  : shut_down
08-17 19:50:56.678  2640  2677 D bt_hwcfg: hw_epilog_process
,08-17 19:50:56.690  2640  2677 I bt_vendor: low_power_mode_cb
,08-17 19:50:56.718  2640  2677 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-17 19:50:56.718  2640  2677 I bt_vendor: epilog_cb
08-17 19:50:56.718  2640  2677 I bt_hci  : epilog_finished_callback
,08-17 19:50:56.724  2640  2673 I bt_hci_h4: hal_close
08-17 19:50:56.725  2640  2673 I bt_userial_vendor: device fd = 51 close
,08-17 19:50:56.824  3868  3868 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:50:56.824  3868  3868 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.824  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:50:56.825  3868  3868 D StrictMode: StrictMode policy violation; ~duration=157 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:50:56.825  3868  3868 D StrictMode: StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:50:56.825  3868  3868 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 19:50:56.825  3868  3868 D StrictMode: 	,at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:50:56.825  3868  3868 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.825  3868  3868 D StrictMod,e: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.825  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:50:56.826  3868  3868 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707),
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:50:56.826  3868  3868 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 19:50:56.826  3868  3868 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:50:56.826  3868  3868 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:50:56.839  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:50:56.859   874  2736 I ActivityManager: Start proc 3900:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 19:50:56.860   874  2736 I ActivityManager: Killing 3408:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 19:50:56.978  2640  2670 D bt_stack_manager: event_shut_down_stack finished.
08-17 19:50:56.978  2640  2669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 19:50:56.980  2640  2669 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 19:50:56.981  2640  2640 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:50:56.981  2640  2640 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:50:56.982  2640  2640 D BtGatt.GattService: stop()
,08-17 19:50:56.982  2640  2640 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:50:56.984  2640  2640 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:50:56.984  2640  2640 V BluetoothAdapterState: isTurningOn()=false
08-17 19:50:56.984  2640  2640 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:50:56.984  2640  2640 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 19:50:56.985  2640  2669 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 19:50:56.985  2640  2669 D BluetoothAdapterProperties: Setting state to 10
08-17 19:50:56.985  2640  2669 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 19:50:56.986   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-17 19:50:56.986  2640  2669 I BluetoothAdapterState: Entering OffState
08-17 19:50:56.993  2640  2640 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 19:50:56.993  2640  2640 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 19:50:56.993  2640  2640 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 19:50:56.993  2640  2670 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 19:50:56.995  2640  2640 I art     : System.exit called, status: 0
,08-17 19:50:56.995  2640  2640 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 19:50:57.006  3900  3900 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 19:50:57.051   874   885 I ActivityManager: Process com.android.bluetooth (pid 2640) has died
,08-17 19:50:57.088  3900  3900 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 19:50:57.103  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:50:57.124   874  1972 I ActivityManager: Start proc 3929:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-17 19:50:57.125  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:50:57.132  3868  3892 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 19:50:57.159   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b2a5cf:true
,08-17 19:50:57.218  3929  3929 D AdapterServiceConfig: Adding HeadsetService
08-17 19:50:57.218  3929  3929 D AdapterServiceConfig: Adding A2dpService
08-17 19:50:57.218  3929  3929 D AdapterServiceConfig: Adding HidService
08-17 19:50:57.218  3929  3929 D AdapterServiceConfig: Adding HealthService
,08-17 19:50:57.218  3929  3929 D AdapterServiceConfig: Adding PanService
,08-17 19:50:57.220  3929  3929 D AdapterServiceConfig: Adding GattService
08-17 19:50:57.220  3929  3929 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 19:50:57.226   874  2736 I ActivityManager: Killing 3578:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-17 19:50:57.275  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:50:57.291  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:50:57.294  1738  1738 D SystemUpdateService: onCreate
,08-17 19:50:57.296  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:50:57.298  1738  3942 I SystemUpdateService: active receiver: enabled
,08-17 19:50:57.301  1738  3942 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:50:57.303  1738  3942 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 19:50:57.303  1738  3942 I SystemUpdateService: now status is 0 (complete)
08-17 19:50:57.303  1738  3942 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 19:50:57.303  1738  3942 I SystemUpdateService: file has been verified
08-17 19:50:57.303  1738  3942 I SystemUpdateService: OTA package size = 12249756
,08-17 19:50:57.306  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 19:50:57.308  1738  3942 I SystemUpdateService: showing system update notification
,08-17 19:50:57.310  1738  2416 I iu.UploadsManager: num queued entries: 0
,08-17 19:50:57.311  1738  2416 I iu.UploadsManager: num updated entries: 0
08-17 19:50:57.313  1738  2416 I iu.SyncManager: NEXT; no task
,08-17 19:50:57.317  1738  1738 D SystemUpdateService: onDestroy
,08-17 19:50:57.324  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:50:57.325  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 19:50:57.337   874  1704 I ActivityManager: Start proc 3944:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 19:50:57.377  3944  3944 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 19:50:57.380  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:50:57.385  3944  3944 D SprintDMHelper: simOperator: 
08-17 19:50:57.385  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:50:57.407   874  1983 I ActivityManager: Start proc 3956:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 19:50:57.409   874  1983 I ActivityManager: Killing 3461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 19:50:57.557   874  2736 I ActivityManager: Start proc 3971:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 19:50:57.560  3070  3970 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 19:50:57.564   874  1390 I ActivityManager: Killing 1691:android.process.acore/u0a5 (adj 15): empty #17
,08-17 19:50:57.619  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 19:50:57.679  3971  3971 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 19:50:57.679  3971  3971 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 19:50:57.679  3971  3971 I GAv4    :   adb logcat -s GAv4
,08-17 19:50:57.699  3971  3971 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:57.706  3971  3971 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:57.736  3971  3988 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 19:50:57.863  3971  3971 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 19:50:57.902  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 19:50:57.916  3971  3971 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8958-8961)
08-17 19:50:57.916  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 19:50:57.929  3971  3971 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {67c9083}
,08-17 19:50:57.930  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 19:50:57.930  3971  3971 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 19:50:57.938  3971  3971 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 19:50:57.940  3971  3971 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 19:50:57.954  3971  3971 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 19:50:57.967  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:50:57.967  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 19:50:57.967  3971  3971 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:50:57.967  3971  3971 I Adreno  : Build Date                       : 10/20/15
08-17 19:50:57.967  3971  3971 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:50:57.967  3971  3971 I Adreno  : Local Branch                     : M14
08-17 19:50:57.967  3971  3971 I Adreno  : Remote Branch                    : 
08-17 19:50:57.967  3971  3971 I Adreno  : Remote Branch                    : 
08-17 19:50:57.967  3971  3971 I Adreno  : Reconstruct Branch               : 
,08-17 19:50:58.032  3971  3971 I NSApplication: Starting up...
,08-17 19:50:58.043  3971  4017 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 19:50:58.078   874   884 I ActivityManager: Start proc 4022:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 19:50:58.080   874   884 I ActivityManager: Killing 3662:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 19:50:58.172  4022  4022 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 19:50:58.355   874   884 I ActivityManager: Killing 3627:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-17 19:50:59.388   874  3913 D WifiService: setWifiEnabled: true pid=3777, uid=10000
,08-17 19:50:59.389   874  3913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:50:59.402   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:50:59.409  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:59.410  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:59.410  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.410  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:50:59.414  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:50:59.414  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:50:59.415  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:50:59.415  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:50:59.450   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 19:50:59.451   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 19:50:59.452   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 19:50:59.453   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:50:59.453   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 19:50:59.453   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 19:50:59.453   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 19:50:59.466   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 19:50:59.467   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.00 rxSuccessRate=11.25 delta 1000 -> 994
,08-17 19:50:59.469   371   872 D CommandListener: Setting iface cfg
,08-17 19:50:59.470   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 19:50:59.470   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:50:59.476   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 19:50:59.476   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:50:59.477   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 19:50:59.478   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 19:50:59.490   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 19:50:59.566   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 19:50:59.568  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 19:50:59.986  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 19:51:00.024  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 19:51:00.024  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 19:51:00.035   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:51:00.045   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:51:00.046   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 19:51:00.046   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:00.064   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:00.075   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:00.077   874  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 19:51:00.090   874  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 19:51:00.092   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 19:51:00.109   874  4046 D DhcpClient: Receive thread started
,08-17 19:51:00.192   874  1307 E native  : do suspend false
,08-17 19:51:00.211   874  1923 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 19:51:00.224   874  4046 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-17 19:51:00.225   874  1923 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
08-17 19:51:00.228   874  1923 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 19:51:00.245   874  4046 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 19:51:00.246   874  1923 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 19:51:00.252   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:00.262   874  1923 D DhcpClient: Scheduling renewal in 86399s
,08-17 19:51:00.263   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 19:51:00.287   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 19:51:00.290   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 19:51:00.290   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:00.293   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 19:51:00.296   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 19:51:00.319   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:51:00.367   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 19:51:00.368   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 19:51:00.369   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 19:51:00.371   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 19:51:00.372   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 19:51:00.384   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:00.389   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-17 19:51:00.389   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:00.389   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 19:51:00.390   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 19:51:00.390   874  1309 D ConnectivityService:    accepting network in place of null
08-17 19:51:00.390   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:51:00.390   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:51:00.395   874  4045 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141441, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 19:51:00.436   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:00.468   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:00.478   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 19:51:00.479   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:00.482   874  4044 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:816::200e
,08-17 19:51:00.491   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:00.508  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:00.509  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:51:00.509  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:00.509  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:00.511   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:51:00.514  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:00.514  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:51:00.514  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 19:51:00.514  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:00.522  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:51:00.525  1738  1738 D SystemUpdateService: onCreate
,08-17 19:51:00.532  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 19:51:00.535  1738  4057 I SystemUpdateService: active receiver: enabled
,08-17 19:51:00.541  1738  4057 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:51:00.544  1738  4057 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 19:51:00.545  1738  4057 I SystemUpdateService: now status is 0 (complete)
,08-17 19:51:00.545  1738  4057 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 19:51:00.545  1738  4057 I SystemUpdateService: file has been verified
08-17 19:51:00.545  1738  4057 I SystemUpdateService: OTA package size = 12249756
,08-17 19:51:00.551   874  4044 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:51:00 GMT], X-Android-Received-Millis=[1471456260550], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471456260525]}
08-17 19:51:00.551  1738  4057 I SystemUpdateService: showing system update notification
,08-17 19:51:00.552   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 19:51:00.552   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-17 19:51:00.552   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:00.553   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 19:51:00.557  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 19:51:00.560  1738  4060 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-17 19:51:00.560  1738  4060 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 19:51:00.561  1738  4060 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
08-17 19:51:00.562  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:51:00.562  1738  2416 I iu.UploadsManager: num queued entries: 0
08-17 19:51:00.563  1738  2416 I iu.UploadsManager: num updated entries: 0
08-17 19:51:00.563  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 19:51:00.565  1738  2416 I iu.SyncManager: NEXT; no task
08-17 19:51:00.566  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:00.569  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:00.570  3944  3944 D SprintDMHelper: simOperator: 
08-17 19:51:00.571  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 19:51:00.570  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:51:00.618   874   886 I ActivityManager: Start proc 4063:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-17 19:51:00.626  1738  1738 D SystemUpdateService: onDestroy
,08-17 19:51:00.647  4063  4063 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-17 19:51:00.696  1518  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 19:51:00.697  1518  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 19:51:00.697  1518  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:00.698  1518  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:00.723  1738  4060 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-17 19:51:00.730  4063  4063 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-17 19:51:00.739  4063  4063 I BooksApp: Created application version: 3.6.9 (30609)
,08-17 19:51:00.791  3070  4075 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 19:51:00.795  4063  4089 I BooksSync: Starting books sync for 61035162, extras: ade
08-17 19:51:00.795  1518  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 19:51:00.796  1518  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 19:51:00.796  1518  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:00.796  1518  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:00.811  3536  4079 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 19:51:00.811  3536  4079 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jdm.a(PG:82)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jcs.o(PG:406)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jcn.a(PG:1379)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jcs.i(PG:143)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at blb.a(PG:3937)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at czp.a(PG:18188)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at czp.a(PG:9081)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at czq.run(PG:1686)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:51:00.811  3536  4079 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jdj.a(PG:4091)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jdj.a(PG:1125)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jdm.a(PG:77)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	... 12 more
08-17 19:51:00.811  3536  4079 E HttpOperation: Caused by: faj: BadAuthentication
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at fal.a(PG:38)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	at jdj.a(PG:4089)
08-17 19:51:00.811  3536  4079 E HttpOperation: 	... 14 more
,08-17 19:51:00.851  1518  2312 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 19:51:00.851  1518  2312 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 19:51:00.851  1518  2312 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:00.851  1518  2312 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:00.864  3536  4079 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 19:51:00.864  3536  4079 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jdm.a(PG:82)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jcs.o(PG:406)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jcn.a(PG:1379)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jcs.i(PG:143)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at hec.a(PG:42)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at hee.a(PG:102)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at czr.a(PG:65)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at kka.a(PG:108)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at czp.a(PG:19176)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at czp.a(PG:9081)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at czq.run(PG:1686)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:51:00.864  3536  4079 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jdj.a(PG:4091)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jdj.a(PG:1125)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jdm.a(PG:77)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	... 15 more
08-17 19:51:00.864  3536  4079 E HttpOperation: Caused by: faj: BadAuthentication
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at fal.a(PG:38)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	at jdj.a(PG:4089)
08-17 19:51:00.864  3536  4079 E HttpOperation: 	... 17 more
,08-17 19:51:00.864  3536  4079 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 19:51:00.864  3536  4079 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at hec.a(PG:42)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at hee.a(PG:102)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at czr.a(PG:65)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at kka.a(PG:108)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	... 15 more
08-17 19:51:00.864  3536  4079 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at fal.a(PG:38)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 19:51:00.864  3536  4079 E ExperimentLoader: 	... 17 more
,08-17 19:51:00.973   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 131084, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:51:00.984  4063  4097 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 19:51:01.048  1518  2312 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-17 19:51:01.048  1518  2312 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 19:51:01.049  1518  2312 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:01.049  1518  2312 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:01.118  1518  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 19:51:01.118  1518  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 19:51:01.118  1518  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:01.119  1518  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:01.145  4063  4097 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 19:51:01.148  4063  4089 E BooksSync: Soft error
08-17 19:51:01.148  4063  4089 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 19:51:01.148  4063  4089 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 19:51:01.148  4063  4089 E BooksSync: Sync error
08-17 19:51:01.148  4063  4089 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 19:51:01.148  4063  4089 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 19:51:01.148  4063  4089 I BooksSync: Finished books sync
,08-17 19:51:01.161   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127426, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 19:51:01.162   874  1890 I ActivityManager: Killing 3678:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 19:51:01.476   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 19:51:02.116   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-17 19:51:02.197   874   885 I ActivityManager: Killing 2233:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 19:51:02.400   874  2736 D WifiService: setWifiEnabled: false pid=3777, uid=10000
,08-17 19:51:02.400   874  2736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:51:02.428  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 19:51:02.430   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 19:51:02.430   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 19:51:02.431   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:51:02.431   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:02.443   874  1923 D DhcpClient: Clearing IP address
,08-17 19:51:02.444   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:02.448   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:51:02.448   874  4046 D DhcpClient: Receive thread stopped
,08-17 19:51:02.449  1518  4086 V NativeCrypto: Read error: ssl=0x9ac33200: I/O error during system call, Connection timed out
,08-17 19:51:02.452  1518  4086 V NativeCrypto: SSL shutdown failed: ssl=0x9ac33200: I/O error during system call, Broken pipe
,08-17 19:51:02.462   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 19:51:02.462   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 19:51:02.469   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 19:51:02.470   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:51:02.472   371   872 D CommandListener: Clearing all IP addresses on wlan0
,08-17 19:51:02.473   399   399 E Parcel  : Reading a NULL string not supported here.
08-17 19:51:02.480   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 19:51:02.486   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:51:02.488  2149  2311 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 19:51:02.488  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:02.488  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:02.488  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:02.488  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:02.489  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:02.489  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:02.489  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:02.489  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:02.490   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 19:51:02.516   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:02.536   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:02.537   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 19:51:02.537   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:02.540   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-17 19:51:02.541  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:02.542  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:02.548  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:51:02.550  1738  1738 D SystemUpdateService: onCreate
,08-17 19:51:02.555  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:51:02.565  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 19:51:02.570  1738  2416 I iu.UploadsManager: num queued entries: 0
,08-17 19:51:02.573  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 19:51:02.574  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 19:51:02.577  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:02.580  3944  3944 D SprintDMHelper: simOperator: 
,08-17 19:51:02.580  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:51:02.588  1738  2416 I iu.UploadsManager: num updated entries: 0
,08-17 19:51:02.586  1738  4105 I SystemUpdateService: active receiver: enabled
,08-17 19:51:02.616  3070  4109 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 19:51:02.618   371   872 E Netd    : netlink response contains error (No such file or directory)
,08-17 19:51:02.619   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 19:51:02.622  1738  4105 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:51:02.623  1738  2416 I iu.SyncManager: NEXT; no task
,08-17 19:51:02.625  1738  4105 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 19:51:02.625  1738  4105 I SystemUpdateService: now status is 0 (complete)
08-17 19:51:02.625  1738  4105 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 19:51:02.625  1738  4105 I SystemUpdateService: file has been verified
08-17 19:51:02.625  1738  4105 I SystemUpdateService: OTA package size = 12249756
,08-17 19:51:02.629  1738  4105 I SystemUpdateService: showing system update notification
,08-17 19:51:02.637  1738  1738 D SystemUpdateService: onDestroy
,08-17 19:51:05.453   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7c6d936:true
,08-17 19:51:05.454  3929  3929 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 19:51:05.459  3929  3929 I bt_bluedroid: init
,08-17 19:51:05.459  3929  4114 I BluetoothAdapterState: Entering OffState
,08-17 19:51:05.465  3929  4115 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:51:05.465  3929  4115 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 19:51:05.466  3929  4115 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:51:05.466  3929  4115 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:51:05.468  3929  3929 I bt_bluedroid: get_profile_interface socket
,08-17 19:51:05.471  3929  3929 I bt_bluedroid: get_profile_interface sdp
,08-17 19:51:05.475  3929  3939 I bt_bluedroid: config_hci_snoop_log
,08-17 19:51:05.476  3929  4118 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 19:51:05.476   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:51:05.481  3929  4118 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:51:05.485  3929  4114 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 19:51:05.485  3929  4114 D BluetoothAdapterProperties: Setting state to 14
08-17 19:51:05.485  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 19:51:05.489  3929  4114 D BluetoothBondStateMachine: make
,08-17 19:51:05.493  3929  4119 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:51:05.498  3929  4114 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:05.499  3929  3929 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 19:51:05.503  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:05.504  3929  3929 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 19:51:05.505  3929  3929 D BtGatt.GattService: Received start request. Starting profile...
,08-17 19:51:05.505  3929  3929 D BtGatt.GattService: start()
08-17 19:51:05.505  3929  3929 I bt_bluedroid: get_profile_interface gatt
,08-17 19:51:05.506  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:05.507  3929  3929 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:51:05.513  3929  3929 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:05.513  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:05.513  3929  3929 V BluetoothAdapterState: isBleTurningOn()=true
08-17 19:51:05.513  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:05.514  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 19:51:05.515  3929  4114 I bt_bluedroid: enable
08-17 19:51:05.515  3929  4115 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 19:51:05.516  3929  4115 I bt_hci  : start_up
,08-17 19:51:05.525  3929  4115 I bt_vendor: alloc value 0xb3979189
,08-17 19:51:05.525  3929  4115 I bt_vendor: init
08-17 19:51:05.525  3929  4115 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 19:51:05.525  3929  4115 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 19:51:05.632  3929  4115 D bt_hci  : start_up starting async portion
08-17 19:51:05.632  3929  4122 I bt_hci  : event_finish_startup
08-17 19:51:05.632  3929  4122 I bt_hci_h4: hal_open
08-17 19:51:05.633  3929  4122 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 19:51:05.640  3929  4122 I bt_userial_vendor: device fd = 51 open
,08-17 19:51:05.675  3929  4122 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:51:05.706  3929  4122 D bt_hwcfg: Chipset BCM4354A2
08-17 19:51:05.707  3929  4122 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 19:51:05.707  3929  4122 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 19:51:05.735  4063  4085 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-17 19:51:06.376  3929  4122 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 19:51:06.378  3929  4122 D bt_hwcfg: Settlement delay -- 100 ms
08-17 19:51:06.378  3929  4122 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 19:51:06.495  3929  4122 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:51:06.496  3929  4122 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 19:51:06.525  3929  4122 I bt_hwcfg: vendor lib fwcfg completed
,08-17 19:51:06.526  3929  4122 I bt_vendor: firmware callback
08-17 19:51:06.526  3929  4122 I bt_hci  : firmware_config_callback
,08-17 19:51:06.537  3929  4126 I bt_btu  : btu_task pending for preload complete event
,08-17 19:51:06.537  3929  4126 I bt_btu_task: Bluetooth chip preload is complete
08-17 19:51:06.538  3929  4126 I bt_btu  : btu_task received preload complete event
,08-17 19:51:06.547  3929  4126 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:51:06.547  3929  4126 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 19:51:06.548  3929  4126 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 19:51:06.548  3929  4126 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:51:06.548  3929  4126 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 19:51:06.549  3929  4126 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:51:06.549  3929  4126 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:51:06.549  3929  4126 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:51:06.549  3929  4126 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 19:51:06.550  3929  4126 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 19:51:06.550  3929  4126 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:51:06.550  3929  4126 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:51:06.550  3929  4126 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 19:51:06.551  3929  4126 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:51:06.551  3929  4126 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 19:51:06.685  3929  4126 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-17 19:51:06.685  3929  4126 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-17 19:51:06.696  3929  4118 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 19:51:06.697  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 19:51:06.698  3929  4118 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 19:51:06.702  3929  4118 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:51:06.707  3929  4118 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:51:06.707  3929  4118 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:51:06.708  3929  4118 D bt_hci  : do_postload posting postload work item
08-17 19:51:06.708  3929  4122 I bt_hci  : event_postload
,08-17 19:51:06.708  3929  4122 I bt_vendor: sco_config_cb
08-17 19:51:06.709  3929  4122 I bt_hci  : sco_config_callback postload finished.
,08-17 19:51:06.713  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:06.718  3929  4118 D bt_bte_conf: Device ID record 1 : primary
,08-17 19:51:06.718  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:06.718  3929  4118 D bt_bte_conf:   vendorId            = 000f
08-17 19:51:06.719  3929  4118 D bt_bte_conf:   vendorIdSource      = 0001
08-17 19:51:06.719  3929  4118 D bt_bte_conf:   product             = 1200
08-17 19:51:06.719  3929  4118 D bt_bte_conf:   version             = 1436
08-17 19:51:06.719  3929  4118 D bt_bte_conf:   clientExecutableURL = 
08-17 19:51:06.719  3929  4118 D bt_bte_conf:   serviceDescription  = 
08-17 19:51:06.720  3929  4118 D bt_bte_conf:   documentationURL    = 
08-17 19:51:06.720  3929  4118 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 19:51:06.721  3929  4115 D bt_stack_manager: event_start_up_stack finished
08-17 19:51:06.723  3929  4122 I bt_vendor: low_power_mode_cb
,08-17 19:51:06.723  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 19:51:06.725  3929  4114 D BluetoothAdapterProperties: Setting state to 15
08-17 19:51:06.725  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 19:51:06.726  3929  4114 I BluetoothAdapterState: Entering BleOnState
,08-17 19:51:06.732  3929  4114 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 19:51:06.732  3929  4114 D BluetoothAdapterProperties: Setting state to 11
08-17 19:51:06.734  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 19:51:06.741  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:06.745  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:06.752  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.753  3929  3929 D HeadsetService: Received start request. Starting profile...
,08-17 19:51:06.755  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:06.757  3929  3929 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:51:06.757  3929  3929 D HeadsetStateMachine: make
,08-17 19:51:06.769  3929  4114 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:06.769  3929  3929 D HeadsetStateMachine: max_hf_connections = 1
08-17 19:51:06.769  3929  3929 I bt_bluedroid: get_profile_interface handsfree
08-17 19:51:06.770  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 19:51:06.770  3929  4118 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 19:51:06.775  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.776  3929  3929 D A2dpService: Received start request. Starting profile...
08-17 19:51:06.776  3929  3929 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 19:51:06.777  3929  3929 I bt_bluedroid: get_profile_interface avrcp
,08-17 19:51:06.783  3929  3929 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:51:06.783  3929  3929 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:51:06.783  3929  3929 D A2dpStateMachine: make
,08-17 19:51:06.785  3929  3929 I bt_bluedroid: get_profile_interface a2dp
,08-17 19:51:06.785  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 19:51:06.789  3929  4136 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:51:06.789  3929  3929 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:51:06.790  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.791  3848  3848 D BluetoothInputDevice: Proxy object connected
08-17 19:51:06.791  3929  3929 D HidService: Received start request. Starting profile...
08-17 19:51:06.792  3929  3929 I bt_bluedroid: get_profile_interface hidhost
,08-17 19:51:06.792  3929  4118 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
,08-17 19:51:06.792  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 19:51:06.792  3848  3848 D HidProfile: Bluetooth service connected
,08-17 19:51:06.792  3929  3929 D HidService: setHidService(): set to: null
08-17 19:51:06.793  3929  3929 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 19:51:06.793  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.794  3929  3929 D HealthService: Received start request. Starting profile...
08-17 19:51:06.796  3929  3929 I bt_bluedroid: get_profile_interface health
08-17 19:51:06.796  3929  3929 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:51:06.797  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.798  3848  3848 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:06.798  3929  3929 D PanService: Received start request. Starting profile...
08-17 19:51:06.799  3929  3929 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 19:51:06.799  3848  3848 D PanProfile: Bluetooth service connected
08-17 19:51:06.799  3929  3929 I bt_bluedroid: get_profile_interface pan
08-17 19:51:06.799  3929  4118 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:51:06.803  3929  3929 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:06.805  3929  3929 D BluetoothMapService: Received start request. Starting profile...
,08-17 19:51:06.805  3848  3848 D BluetoothMap: Proxy object connected
08-17 19:51:06.805  3929  3929 D BluetoothMapService: start()
08-17 19:51:06.805  3848  3848 D MapProfile: Bluetooth service connected
08-17 19:51:06.805  3848  3848 D BluetoothMap: getConnectedDevices()
08-17 19:51:06.806  3848  3848 D BluetoothMap: Bluetooth is Not enabled
,08-17 19:51:06.808  3929  3929 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 19:51:06.809  3929  3929 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 19:51:06.809  3929  3929 D BluetoothMapAppObserver: createReceiver()
,08-17 19:51:06.810  3929  3929 D BluetoothMapAppObserver: initObservers()
08-17 19:51:06.810  3929  3929 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 19:51:06.817  3929  3929 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:06.817  3929  3929 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:06.817  3929  4134 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 19:51:06.817  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:06.817  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:06.818  3929  3929 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:51:06.819  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:51:06.820  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:06.821  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-17 19:51:06.821  3929  4114 D BluetoothAdapterProperties: ScanMode =  20
,08-17 19:51:06.821  3929  4114 D BluetoothAdapterProperties: State =  11
08-17 19:51:06.821  3929  4114 D BluetoothAdapterProperties: Setting state to 12
08-17 19:51:06.822  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 19:51:06.822   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:06.822  1952  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:51:06.824  3929  4118 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:51:06.824  3929  4118 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:51:06.824  3929  4114 I BluetoothAdapterState: Entering OnState
08-17 19:51:06.825  3848  3861 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:51:06.826  1354  2055 D BluetoothPan: onBluetoothStateChange on: true
,08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:06.827  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:06.828  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:06.828  1354  1354 D PanProfile: Bluetooth service connected
08-17 19:51:06.828   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:06.829  1354  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:51:06.829  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:06.830   874   874 D BluetoothA2dp: Proxy object connected
08-17 19:51:06.832  1354  1354 D BluetoothMap: Proxy object connected
08-17 19:51:06.832  1354  1354 D MapProfile: Bluetooth service connected
08-17 19:51:06.832  1354  1354 D BluetoothMap: getConnectedDevices()
,08-17 19:51:06.833   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:06.833  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:06.833  3848  3859 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:51:06.835  1354  2056 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:06.835  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:06.837  3929  3929 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 19:51:06.837  1354  1354 D BluetoothA2dp: Proxy object connected
08-17 19:51:06.837  1354  1383 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:06.837  3929  3929 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 19:51:06.839   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:06.839  3929  3929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:51:06.839  1354  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:51:06.842  1354  1354 D BluetoothInputDevice: Proxy object connected
08-17 19:51:06.842  1354  1354 D HidProfile: Bluetooth service connected
,08-17 19:51:06.842  3929  3929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:51:06.842  3848  3861 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:51:06.842  3848  3859 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 19:51:06.843  3929  3929 D ObexServerSockets: Succeed to create listening sockets 
,08-17 19:51:06.843  3929  3929 D ObexServerSockets0: startAccept()
08-17 19:51:06.843  1354  2056 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:51:06.843  3929  3929 D ObexServerSockets0: prepareForNewConnect()
,08-17 19:51:06.845   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 19:51:06.848  3929  3929 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 19:51:06.848  3929  3929 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 19:51:06.848  3929  4141 D ObexServerSockets0: Accepting socket connection...
08-17 19:51:06.849  3929  3929 D BluetoothMapService: onReceive
08-17 19:51:06.849  3929  3929 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 19:51:06.849  3848  3848 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 19:51:06.849  3929  3929 D BluetoothMapService: STATE_ON
,08-17 19:51:06.850  3929  4143 D ObexServerSockets0: Accepting socket connection...
,08-17 19:51:06.850  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:06.852  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:06.854  3848  3848 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 19:51:06.860  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:06.862  3848  3848 D BluetoothA2dp: Proxy object connected
,08-17 19:51:06.866  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 19:51:06.868  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:06.876  3929  3929 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 19:51:06.876  1354  1354 D BluetoothPbap: Proxy object connected
08-17 19:51:06.876  3929  3929 D ObexServerSockets0: prepareForNewConnect()
08-17 19:51:06.876  1354  1354 D PbapServerProfile: Bluetooth service connected
08-17 19:51:06.877  3848  3848 D BluetoothPbap: Proxy object connected
,08-17 19:51:06.877  3848  3848 D PbapServerProfile: Bluetooth service connected
,08-17 19:51:06.887  3929  4148 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:06.913  3929  4152 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:06.914  3929  4152 I BtOppRfcommListener: Accept thread started.
,08-17 19:51:06.924   874   874 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.924  1354  1383 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.924  1354  1354 D HeadsetProfile: Bluetooth service connected
08-17 19:51:06.924   874   874 D BluetoothHeadset: Proxy object connected
08-17 19:51:06.925  1952  2203 D BluetoothHeadset: Proxy object connected
08-17 19:51:06.925   874   874 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.932   874   891 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.938  1354  2055 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.938  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:06.938   874   891 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.957  3848  3861 D BluetoothHeadset: Proxy object connected
,08-17 19:51:06.959  3848  3848 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:08.395   874  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-17 19:51:08.418  3929  4114 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 19:51:08.419  3929  4114 D BluetoothAdapterProperties: Setting state to 13
08-17 19:51:08.420  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 19:51:08.421  3929  4114 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 19:51:08.427  3929  4114 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:08.434  3929  3929 D BluetoothMapService: onReceive
,08-17 19:51:08.435  3929  3929 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:08.436  3929  3929 D BluetoothMapService: STATE_TURNING_OFF
08-17 19:51:08.436  3929  3929 D BluetoothMapService: MAP Service closeService in
08-17 19:51:08.436  3929  3929 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 19:51:08.437  3929  3929 D ObexServerSockets0: shutdown(block = true)
08-17 19:51:08.438  3929  3929 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:51:08.438  3929  3929 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 19:51:08.438  3929  4141 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 19:51:08.439  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:08.439  3929  4143 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:08.439  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:08.439  3929  4118 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:51:08.440  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 19:51:08.440  3929  4128 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 19:51:08.439  3929  3929 I BtOppRfcommListener: stopping Accept Thread
08-17 19:51:08.440  3929  4152 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 19:51:08.441  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:08.441  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:08.441  3929  4152 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 19:51:08.443  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 19:51:08.445  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:08.445  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 19:51:08.446  3777  3777 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 19:51:08.446  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:08.448  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:08.450  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:08.453  3929  3929 D HeadsetService: Received stop request...Stopping profile...
,08-17 19:51:08.462  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:08.462   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 19:51:08.463  1354  2055 D BluetoothHeadset: Proxy object disconnected
08-17 19:51:08.463  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-17 19:51:08.463   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 19:51:08.463  3848  3859 D BluetoothHeadset: Proxy object disconnected
,08-17 19:51:08.464  1952  2194 D BluetoothHeadset: Proxy object disconnected
08-17 19:51:08.464  3929  3929 D A2dpService: Received stop request...Stopping profile...
08-17 19:51:08.464   874   874 D BluetoothHeadset: Proxy object disconnected
08-17 19:51:08.464  3848  3848 D HeadsetProfile: Bluetooth service disconnected
08-17 19:51:08.464  3929  4136 D A2dpStateMachine: Exit Disconnected: -1
08-17 19:51:08.468  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-17 19:51:08.468  3848  3848 D BluetoothA2dp: Proxy object disconnected
08-17 19:51:08.469   874   874 D BluetoothA2dp: Proxy object disconnected
,08-17 19:51:08.470  3929  3929 D HidService: Received stop request...Stopping profile...
08-17 19:51:08.470  3929  3929 D HidService: Stopping Bluetooth HidService
,08-17 19:51:08.471  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-17 19:51:08.471  1354  1354 D HidProfile: Bluetooth service disconnected
08-17 19:51:08.471  3929  3929 D HealthService: Received stop request...Stopping profile...
,08-17 19:51:08.475  3929  3929 D PanService: Received stop request...Stopping profile...
,08-17 19:51:08.471  3848  3848 D BluetoothInputDevice: Proxy object disconnected
08-17 19:51:08.475  3848  3848 D HidProfile: Bluetooth service disconnected
,08-17 19:51:08.477  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:08.477  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:51:08.477  1354  1354 D PanProfile: Bluetooth service disconnected
,08-17 19:51:08.479  3929  3929 V BluetoothAdapterState: isTurningOff()=true
08-17 19:51:08.479  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.479  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:51:08.479  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:08.479  3848  3848 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 19:51:08.480  3848  3848 D PanProfile: Bluetooth service disconnected
,08-17 19:51:08.481  3929  3929 D BluetoothMapService: Received stop request...Stopping profile...
08-17 19:51:08.481  3929  3929 D BluetoothMapService: stop()
,08-17 19:51:08.482  3929  3929 D BluetoothMapAppObserver: deinitObservers()
,08-17 19:51:08.484  3929  3929 D BluetoothMapAppObserver: removeReceiver()
08-17 19:51:08.485  1354  1354 D BluetoothMap: Proxy object disconnected
,08-17 19:51:08.485  1354  1354 D MapProfile: Bluetooth service disconnected
,08-17 19:51:08.487  3848  3848 D BluetoothMap: Proxy object disconnected
08-17 19:51:08.487  3929  3929 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 19:51:08.487  3929  3929 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 19:51:08.487  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 19:51:08.487  3848  3848 D MapProfile: Bluetooth service disconnected
08-17 19:51:08.488  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:51:08.488  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:51:08.488  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:51:08.488  3929  4118 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-17 19:51:08.489  3929  3929 V BluetoothAdapterState: isTurningOff()=true
08-17 19:51:08.489  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.489  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.489  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:08.491  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:51:08.491  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 19:51:08.491  3929  4126 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:51:08.491  3929  4126 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:08.492  3929  4126 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 19:51:08.492  3929  4126 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 19:51:08.492  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-17 19:51:08.491  3929  3929 V BluetoothAdapterState: isTurningOff()=true
08-17 19:51:08.494  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.494  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.495  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:08.496  3929  3929 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 19:51:08.496  3929  3929 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 19:51:08.497  3929  4118 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 19:51:08.497  3929  3929 V BluetoothAdapterState: isTurningOff()=true
,08-17 19:51:08.498  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.498  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.499  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:08.499  3929  3929 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 19:51:08.500  3929  4118 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-17 19:51:08.500  3929  3929 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 19:51:08.504  1354  1354 D BluetoothPbap: Proxy object disconnected
,08-17 19:51:08.504  3848  3848 D BluetoothPbap: Proxy object disconnected
08-17 19:51:08.504  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-17 19:51:08.504  3848  3848 D PbapServerProfile: Bluetooth service disconnected
08-17 19:51:08.505  3929  3929 V BluetoothAdapterState: isTurningOff()=true
,08-17 19:51:08.506  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.506  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.507  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:08.508  3929  3929 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 19:51:08.508  3929  3929 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 19:51:08.510  3929  3929 D BluetoothMapService: MAP Service closeService in
08-17 19:51:08.510  3929  3929 V BluetoothAdapterState: isTurningOff()=true
08-17 19:51:08.511  3929  3929 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:08.511  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.511  3929  3929 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:08.511  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 19:51:08.511  3929  4114 D BluetoothAdapterProperties: Setting state to 15
08-17 19:51:08.512  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 19:51:08.512  3929  3929 D BluetoothMapService: cleanup()
08-17 19:51:08.512  3929  3929 D BluetoothMapService: MAP Service closeService in
08-17 19:51:08.512  3929  4114 I BluetoothAdapterState: Entering BleOnState
,08-17 19:51:08.513   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:51:08.514  3848  3859 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:51:08.515  1952  1965 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:51:08.515  3848  3861 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 19:51:08.520  1354  2055 D BluetoothPan: onBluetoothStateChange on: false
,08-17 19:51:08.521   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 19:51:08.521  1354  1382 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:51:08.522   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:51:08.522  3848  3859 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 19:51:08.522  3848  3861 D BluetoothPan: onBluetoothStateChange on: false
08-17 19:51:08.523  1354  2056 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 19:51:08.524  1354  1383 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 19:51:08.524   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 19:51:08.524  1354  2055 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 19:51:08.525  3848  3859 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 19:51:08.526  3848  3861 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 19:51:08.526  1354  1382 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 19:51:08.527  3929  4114 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 19:51:08.528  3929  4114 D BluetoothAdapterProperties: Setting state to 16
08-17 19:51:08.528  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 19:51:08.528  3929  4114 D BluetoothAdapterProperties: onBleDisable
,08-17 19:51:08.530  3929  4114 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:08.530  3929  4115 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 19:51:08.533  3929  4126 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 19:51:08.533  3929  4126 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 19:51:08.533  3929  4118 D BluetoothAdapterProperties: Scan Mode:20
08-17 19:51:08.535  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:08.535  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:08.537  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:08.539  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:08.540  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:08.544  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:08.547  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:08.733  3929  4118 I bt_hci  : shut_down
,08-17 19:51:08.734  3929  4122 D bt_hwcfg: hw_epilog_process
08-17 19:51:08.736  3929  4122 I bt_vendor: low_power_mode_cb
,08-17 19:51:08.756  3929  4122 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 19:51:08.757  3929  4122 I bt_vendor: epilog_cb
,08-17 19:51:08.757  3929  4122 I bt_hci  : epilog_finished_callback
,08-17 19:51:08.768  3929  4118 I bt_hci_h4: hal_close
,08-17 19:51:08.769  3929  4118 I bt_userial_vendor: device fd = 51 close
,08-17 19:51:08.890  3929  4115 D bt_stack_manager: event_shut_down_stack finished.
,08-17 19:51:08.891  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 19:51:08.897  3929  4114 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-17 19:51:08.897  3929  3929 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:51:08.899  3929  3929 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 19:51:08.899  3929  3929 D BtGatt.GattService: stop()
,08-17 19:51:08.899  3929  3929 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 19:51:08.908  3929  3929 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:08.908  3929  3929 V BluetoothAdapterState: isTurningOn()=false
,08-17 19:51:08.908  3929  3929 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:08.909  3929  3929 V BluetoothAdapterState: isBleTurningOff()=true
08-17 19:51:08.910  3929  4114 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 19:51:08.911  3929  4114 D BluetoothAdapterProperties: Setting state to 10
08-17 19:51:08.911  3929  4114 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 19:51:08.913  3929  4114 I BluetoothAdapterState: Entering OffState
08-17 19:51:08.914   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 19:51:08.938  3929  3929 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 19:51:08.939  3929  3929 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 19:51:08.939  3929  3929 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 19:51:08.945  3929  4115 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 19:51:08.956  3929  4115 D bt_stack_manager: event_clean_up_stack finished.
,08-17 19:51:08.963  3929  3929 I art     : System.exit called, status: 0
,08-17 19:51:08.963  3929  3929 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 19:51:09.023   874  1970 I ActivityManager: Process com.android.bluetooth (pid 3929) has died
,08-17 19:51:09.172   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 19:51:09.182  1873  1873 I Keyboard.Facilitator: onFinishInput()
,08-17 19:51:09.189   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 19:51:09.189   874   894 I Adreno  : Build Date                       : 10/20/15
08-17 19:51:09.189   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 19:51:09.189   874   894 I Adreno  : Local Branch                     : M14
08-17 19:51:09.189   874   894 I Adreno  : Remote Branch                    : 
08-17 19:51:09.189   874   894 I Adreno  : Remote Branch                    : 
08-17 19:51:09.189   874   894 I Adreno  : Reconstruct Branch               : 
,08-17 19:51:09.220   282   366 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (188 us)
,08-17 19:51:09.810  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:51:09.810  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 19:51:09.868   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 19:51:09.871  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ee9f0d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@71dfdb5, 16908290=android.view.AbsSavedState$1@71dfdb5}, android:focusedViewId=100}]}]
08-17 19:51:09.871  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-17 19:51:09.872  3777  3777 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 19:51:09.877  3777  3777 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 19:51:09.880   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 19:51:09.885   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-17 19:51:09.888   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-17 19:51:09.888   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 19:51:09.938   874   883 I art     : Background partial concurrent mark sweep GC freed 11485(854KB) AllocSpace objects, 5(184KB) LOS objects, 33% free, 29MB/43MB, paused 23.177ms total 150.605ms
,08-17 19:51:10.111   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 19:51:10.120   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 19:51:10.125   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,08-17 19:51:10.128   874   894 I DreamManagerService: Entering dreamland.
,08-17 19:51:10.130   874   894 I PowerManagerService: Dozing...
,08-17 19:51:10.132   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 19:51:10.185   375  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 19:51:10.185   375  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 19:51:10.196   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:51:10.199   874  1307 E native  : do suspend false
,08-17 19:51:10.202  1936  4164 D NfcService: Discovery configuration equal, not updating.
,08-17 19:51:10.234   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:51:10.238   874  1307 E native  : do suspend true
,08-17 19:51:10.322   375  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 19:51:10.322   375  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 19:51:10.822  3496  3609 D Finsky  : [294] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-17 19:51:10.841  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:10.856  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:10.861  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:10.909  1518  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-17 19:51:10.909  1518  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-17 19:51:10.910  1518  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:10.910  1518  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:10.952  3496  3609 D Finsky  : [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-17 19:51:11.414  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:51:11.415  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:14.421  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:14.421  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a105c4a added. We now have 6 listener(s)
,08-17 19:51:14.422  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:14.426  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:14.426  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5207bb added. We now have 7 listener(s)
08-17 19:51:14.426  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:14.427  3777  3830 I System.out: IsBluetoothEnabled
,08-17 19:51:14.438  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:14.475   874   891 I ActivityManager: Start proc 4174:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 19:51:14.483  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:14.518  1518  2082 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 19:51:14.518  1518  2082 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 19:51:14.518  1518  2082 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:14.518  1518  2082 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:14.545  3496  3496 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 19:51:14.545  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 19:51:14.546  3496  3496 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-17 19:51:14.579  4174  4174 D AdapterServiceConfig: Adding HeadsetService
,08-17 19:51:14.579  4174  4174 D AdapterServiceConfig: Adding A2dpService
08-17 19:51:14.580  4174  4174 D AdapterServiceConfig: Adding HidService
08-17 19:51:14.580  4174  4174 D AdapterServiceConfig: Adding HealthService
08-17 19:51:14.580  4174  4174 D AdapterServiceConfig: Adding PanService
,08-17 19:51:14.580  4174  4174 D AdapterServiceConfig: Adding GattService
08-17 19:51:14.580  4174  4174 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 19:51:14.593   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2b74cf:true
,08-17 19:51:14.593  4174  4174 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 19:51:14.596  4174  4174 I bt_bluedroid: init
,08-17 19:51:14.597  4174  4187 I BluetoothAdapterState: Entering OffState
,08-17 19:51:14.602  4174  4188 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 19:51:14.602  4174  4188 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 19:51:14.603  4174  4188 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 19:51:14.603  4174  4188 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 19:51:14.605  4174  4174 I bt_bluedroid: get_profile_interface socket
,08-17 19:51:14.609  4174  4174 I bt_bluedroid: get_profile_interface sdp
,08-17 19:51:14.609  4174  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 19:51:14.612  4174  4185 I bt_bluedroid: config_hci_snoop_log
,08-17 19:51:14.612  4174  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:51:14.613   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 19:51:14.619  4174  4187 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 19:51:14.619  4174  4187 D BluetoothAdapterProperties: Setting state to 14
,08-17 19:51:14.619  4174  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-17 19:51:14.620  4174  4187 D BluetoothBondStateMachine: make
,08-17 19:51:14.623  4174  4192 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 19:51:14.629  4174  4187 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:14.629  4174  4174 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 19:51:14.631  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:14.632  4174  4174 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 19:51:14.633  4174  4174 D BtGatt.GattService: Received start request. Starting profile...
,08-17 19:51:14.633  4174  4174 D BtGatt.GattService: start()
08-17 19:51:14.633  4174  4174 I bt_bluedroid: get_profile_interface gatt
08-17 19:51:14.634  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
08-17 19:51:14.634  4174  4174 D BtGatt.AdvertiseManager: advertise manager created
,08-17 19:51:14.644  4174  4174 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:14.644  4174  4174 V BluetoothAdapterState: isTurningOn()=false
08-17 19:51:14.644  4174  4174 V BluetoothAdapterState: isBleTurningOn()=true
08-17 19:51:14.645  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:14.645  4174  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 19:51:14.646  4174  4187 I bt_bluedroid: enable
08-17 19:51:14.646  4174  4188 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 19:51:14.647  4174  4188 I bt_hci  : start_up
,08-17 19:51:14.663  4174  4188 I bt_vendor: alloc value 0xb39e2189
,08-17 19:51:14.663  4174  4188 I bt_vendor: init
08-17 19:51:14.663  4174  4188 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 19:51:14.663  4174  4188 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 19:51:14.770  4174  4188 D bt_hci  : start_up starting async portion
,08-17 19:51:14.770  4174  4195 I bt_hci  : event_finish_startup
08-17 19:51:14.771  4174  4195 I bt_hci_h4: hal_open
,08-17 19:51:14.771  4174  4195 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 19:51:14.779  4174  4195 I bt_userial_vendor: device fd = 51 open
,08-17 19:51:14.811  4174  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:51:14.843  4174  4195 D bt_hwcfg: Chipset BCM4354A2
,08-17 19:51:14.844  4174  4195 D bt_hwcfg: Target name = [BCM4354A2]
08-17 19:51:14.844  4174  4195 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 19:51:15.504  4174  4195 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 19:51:15.506  4174  4195 D bt_hwcfg: Settlement delay -- 100 ms
08-17 19:51:15.506  4174  4195 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 19:51:15.623  4174  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 19:51:15.625  4174  4195 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 19:51:15.654  4174  4195 I bt_hwcfg: vendor lib fwcfg completed
,08-17 19:51:15.654  4174  4195 I bt_vendor: firmware callback
08-17 19:51:15.654  4174  4195 I bt_hci  : firmware_config_callback
,08-17 19:51:15.666  4174  4197 I bt_btu  : btu_task pending for preload complete event
,08-17 19:51:15.666  4174  4197 I bt_btu_task: Bluetooth chip preload is complete
,08-17 19:51:15.666  4174  4197 I bt_btu  : btu_task received preload complete event
,08-17 19:51:15.676  4174  4197 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 19:51:15.676  4174  4197 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 19:51:15.677  4174  4197 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 19:51:15.677  4174  4197 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 19:51:15.677  4174  4197 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 19:51:15.678  4174  4197 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 19:51:15.678  4174  4197 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 19:51:15.678  4174  4197 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 19:51:15.678  4174  4197 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 19:51:15.679  4174  4197 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 19:51:15.679  4174  4197 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 19:51:15.679  4174  4197 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 19:51:15.679  4174  4197 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 19:51:15.679  4174  4197 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 19:51:15.680  4174  4197 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 19:51:15.813  4174  4197 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395fd9d
,08-17 19:51:15.814  4174  4197 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395fd9d 
,08-17 19:51:15.826  4174  4191 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 19:51:15.829  4174  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 19:51:15.830  4174  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 19:51:15.833  4174  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 19:51:15.835  4174  4191 D BluetoothAdapterProperties: Scan Mode:20
,08-17 19:51:15.838  4174  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 19:51:15.838  4174  4191 D bt_hci  : do_postload posting postload work item
08-17 19:51:15.839  4174  4195 I bt_hci  : event_postload
08-17 19:51:15.839  4174  4195 I bt_vendor: sco_config_cb
08-17 19:51:15.839  4174  4195 I bt_hci  : sco_config_callback postload finished.
08-17 19:51:15.842  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:15.842  4174  4191 D bt_bte_conf: Device ID record 1 : primary
08-17 19:51:15.843  4174  4191 D bt_bte_conf:   vendorId            = 000f
08-17 19:51:15.843  4174  4191 D bt_bte_conf:   vendorIdSource      = 0001
08-17 19:51:15.843  4174  4191 D bt_bte_conf:   product             = 1200
08-17 19:51:15.843  4174  4191 D bt_bte_conf:   version             = 1436
,08-17 19:51:15.843  4174  4191 D bt_bte_conf:   clientExecutableURL = 
,08-17 19:51:15.844  4174  4191 D bt_bte_conf:   serviceDescription  = 
08-17 19:51:15.844  4174  4191 D bt_bte_conf:   documentationURL    = 
08-17 19:51:15.844  4174  4191 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 19:51:15.844  4174  4188 D bt_stack_manager: event_start_up_stack finished
08-17 19:51:15.845  4174  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 19:51:15.846  4174  4187 D BluetoothAdapterProperties: Setting state to 15
08-17 19:51:15.846  4174  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 19:51:15.846  4174  4195 I bt_vendor: low_power_mode_cb
,08-17 19:51:15.848  4174  4187 I BluetoothAdapterState: Entering BleOnState
,08-17 19:51:15.852  4174  4187 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 19:51:15.853  4174  4187 D BluetoothAdapterProperties: Setting state to 11
,08-17 19:51:15.853  4174  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 19:51:15.859  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:15.862  4174  4174 D HeadsetService: Received start request. Starting profile...
08-17 19:51:15.863  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:15.865  4174  4174 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 19:51:15.866  4174  4174 D HeadsetStateMachine: make
,08-17 19:51:15.879  4174  4174 D HeadsetStateMachine: max_hf_connections = 1
,08-17 19:51:15.879  4174  4174 I bt_bluedroid: get_profile_interface handsfree
,08-17 19:51:15.879  4174  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-17 19:51:15.880  4174  4191 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 19:51:15.884  4174  4187 I BluetoothAdapterState: Entering PendingCommandState
,08-17 19:51:15.885  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:15.886  4174  4174 D A2dpService: Received start request. Starting profile...
,08-17 19:51:15.887  4174  4174 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 19:51:15.887  4174  4174 I bt_bluedroid: get_profile_interface avrcp
,08-17 19:51:15.893  4174  4174 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 19:51:15.893  4174  4174 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 19:51:15.893  4174  4174 D A2dpStateMachine: make
,08-17 19:51:15.895  4174  4174 I bt_bluedroid: get_profile_interface a2dp
,08-17 19:51:15.895  4174  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048,
08-17 19:51:15.897  4174  4206 D A2dpStateMachine: Enter Disconnected: -2
,08-17 19:51:15.899  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:15.901  4174  4174 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 19:51:15.902  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:15.902  4174  4174 D HidService: Received start request. Starting profile...
,08-17 19:51:15.902  4174  4174 I bt_bluedroid: get_profile_interface hidhost
08-17 19:51:15.902  4174  4174 D HidService: setHidService(): set to: null
08-17 19:51:15.903  4174  4191 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39413e5
,08-17 19:51:15.903  4174  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 19:51:15.904  4174  4174 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 19:51:15.904  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
08-17 19:51:15.905  4174  4174 D HealthService: Received start request. Starting profile...
,08-17 19:51:15.906  4174  4174 I bt_bluedroid: get_profile_interface health
,08-17 19:51:15.907  4174  4174 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 19:51:15.907  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:15.908  4174  4174 D PanService: Received start request. Starting profile...
,08-17 19:51:15.908  4174  4174 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 19:51:15.908  4174  4174 I bt_bluedroid: get_profile_interface pan
,08-17 19:51:15.908  4174  4191 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 19:51:15.911  4174  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
08-17 19:51:15.911  4174  4174 D BluetoothMapService: Received start request. Starting profile...
08-17 19:51:15.911  4174  4174 D BluetoothMapService: start()
,08-17 19:51:15.914  4174  4174 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 19:51:15.914  4174  4174 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 19:51:15.914  4174  4174 D BluetoothMapAppObserver: createReceiver()
08-17 19:51:15.915  4174  4174 D BluetoothMapAppObserver: initObservers()
,08-17 19:51:15.915  4174  4174 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 19:51:15.921  4174  4203 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 19:51:15.922  4174  4174 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:15.922  4174  4174 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:15.922  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:15.922  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:15.923  4174  4174 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:15.923  4174  4174 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:51:15.923  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:15.923  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:15.927  4174  4174 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:15.927  4174  4174 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isTurningOff()=false
,08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isTurningOn()=true
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:15.928  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:15.929  4174  4174 V BluetoothAdapterState: isTurningOff()=false
08-17 19:51:15.929  4174  4174 V BluetoothAdapterState: isTurningOn()=true
,08-17 19:51:15.929  4174  4174 V BluetoothAdapterState: isBleTurningOn()=false
08-17 19:51:15.929  4174  4174 V BluetoothAdapterState: isBleTurningOff()=false
08-17 19:51:15.929  4174  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 19:51:15.929  4174  4187 D BluetoothAdapterProperties: ScanMode =  20
08-17 19:51:15.929  4174  4187 D BluetoothAdapterProperties: State =  11
08-17 19:51:15.930  4174  4191 D BluetoothAdapterProperties: Scan Mode:21
08-17 19:51:15.931  4174  4187 D BluetoothAdapterProperties: Setting state to 12
08-17 19:51:15.931  4174  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 19:51:15.931  4174  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 19:51:15.931   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:15.932  4174  4187 I BluetoothAdapterState: Entering OnState
08-17 19:51:15.932  3848  3859 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:15.935  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:15.935  1952  2194 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:51:15.936  3848  3859 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 19:51:15.936  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 19:51:15.937  1354  1383 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:51:15.938   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 19:51:15.939   874   874 D BluetoothA2dp: Proxy object connected
,08-17 19:51:15.939  1354  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-17 19:51:15.939  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 19:51:15.939  1354  1354 D PanProfile: Bluetooth service connected
08-17 19:51:15.940   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:15.940  3848  3861 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 19:51:15.941  3848  3859 D BluetoothPan: onBluetoothStateChange on: true
08-17 19:51:15.941  4174  4174 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 19:51:15.942  4174  4174 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 19:51:15.943  3848  3848 D BluetoothA2dp: Proxy object connected
,08-17 19:51:15.943  4174  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:51:15.943  1354  2055 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 19:51:15.945  1354  1354 D BluetoothA2dp: Proxy object connected
,08-17 19:51:15.945  1354  2056 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:15.946   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 19:51:15.946  1354  1382 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:51:15.947  4174  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 19:51:15.946  3848  3848 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 19:51:15.947  3848  3848 D PanProfile: Bluetooth service connected
,08-17 19:51:15.948  3848  3859 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 19:51:15.948  4174  4174 D ObexServerSockets: Succeed to create listening sockets 
08-17 19:51:15.948  4174  4174 D ObexServerSockets0: startAccept()
08-17 19:51:15.948  4174  4174 D ObexServerSockets0: prepareForNewConnect()
08-17 19:51:15.949  3848  3861 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 19:51:15.951  1354  2055 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 19:51:15.951  4174  4174 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 19:51:15.951  4174  4174 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 19:51:15.952  4174  4212 D ObexServerSockets0: Accepting socket connection...
08-17 19:51:15.952  4174  4213 D ObexServerSockets0: Accepting socket connection...
,08-17 19:51:15.952  1354  1354 D BluetoothMap: Proxy object connected
,08-17 19:51:15.953  1354  1354 D MapProfile: Bluetooth service connected
08-17 19:51:15.953  1354  1354 D BluetoothMap: getConnectedDevices()
08-17 19:51:15.953  3848  3848 D BluetoothMap: Proxy object connected
08-17 19:51:15.953  3848  3848 D MapProfile: Bluetooth service connected
08-17 19:51:15.953  3848  3848 D BluetoothMap: getConnectedDevices()
,08-17 19:51:15.954   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 19:51:15.957  1354  1354 D BluetoothInputDevice: Proxy object connected
08-17 19:51:15.957  1354  1354 D HidProfile: Bluetooth service connected
08-17 19:51:15.957  3848  3848 D BluetoothInputDevice: Proxy object connected
08-17 19:51:15.957  3848  3848 D HidProfile: Bluetooth service connected
08-17 19:51:15.958  4174  4174 D BluetoothMapService: onReceive
,08-17 19:51:15.958  4174  4174 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 19:51:15.958  4174  4174 D BluetoothMapService: STATE_ON
08-17 19:51:15.958  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:15.965  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 19:51:15.972  1518  1518 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 19:51:15.972  3848  3848 D DockEventReceiver: finishStartingService: stopping service
,08-17 19:51:15.981  3848  3848 D BluetoothPbap: Proxy object connected
,08-17 19:51:15.981  3848  3848 D PbapServerProfile: Bluetooth service connected
08-17 19:51:15.981  1354  1354 D BluetoothPbap: Proxy object connected
08-17 19:51:15.981  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-17 19:51:15.986  4174  4174 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 19:51:15.986  4174  4174 D ObexServerSockets0: prepareForNewConnect()
,08-17 19:51:15.988  4174  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:16.005  4174  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 19:51:16.006  4174  4222 I BtOppRfcommListener: Accept thread started.
,08-17 19:51:16.035   874   874 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.036  1952  1965 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.036  1354  2056 D BluetoothHeadset: Proxy object connected
08-17 19:51:16.036  1354  1354 D HeadsetProfile: Bluetooth service connected
08-17 19:51:16.036   874   874 D BluetoothHeadset: Proxy object connected
08-17 19:51:16.037  3848  4211 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.038  1952  1963 D BluetoothHeadset: Proxy object connected
08-17 19:51:16.038  3848  3848 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:16.039   874   874 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.041   874   891 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.042  3848  3859 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.042  3848  3848 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:16.046  1354  1382 D BluetoothHeadset: Proxy object connected
08-17 19:51:16.047  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-17 19:51:16.047   874   891 D BluetoothHeadset: Proxy object connected
,08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:16.460  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:16.468  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:16.472  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:16.472  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ea74d8 added. We now have 8 listener(s)
,08-17 19:51:16.472  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:16.480   874  2736 D WifiService: setWifiEnabled: false pid=3777, uid=10000
,08-17 19:51:16.480   874  2736 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:51:16.493  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:16.495   874  3913 D WifiService: setWifiEnabled: true pid=3777, uid=10000
,08-17 19:51:16.495   874  3913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 19:51:16.498  2149  2653 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 19:51:16.508   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 19:51:16.525  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 19:51:16.530  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 19:51:16.538   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-17 19:51:16.539   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 19:51:16.540   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 19:51:16.541   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 19:51:16.541   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 19:51:16.541   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 19:51:16.541   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 19:51:16.566   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 19:51:16.566   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.20 rxSuccessRate=0.22 delta 1000 -> 1000
08-17 19:51:16.567   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 19:51:16.568   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:16.569   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-17 19:51:16.569   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 19:51:16.578   874  1307 E native  : do suspend true
,08-17 19:51:16.587   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 19:51:16.592   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 19:51:16.592   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:16.592   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 19:51:16.606   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 19:51:16.656   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 19:51:16.679  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 19:51:17.118  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 19:51:17.158  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 19:51:17.159  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 19:51:17.168   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 19:51:17.178   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:51:17.178   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:17.179   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 19:51:17.195   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 19:51:17.204   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:17.206   874  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 19:51:17.212   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 19:51:17.224   874  4230 D DhcpClient: Receive thread started
,08-17 19:51:17.308   874  1307 E native  : do suspend false
,08-17 19:51:17.328   874  1923 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 19:51:17.343   874  4230 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-17 19:51:17.344   874  1923 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 19:51:17.350   874  1923 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 19:51:17.363   874  4230 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 19:51:17.364   874  1923 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 19:51:17.371   371   872 D CommandListener: Setting iface cfg
,08-17 19:51:17.382   874  1923 D DhcpClient: Scheduling renewal in 86399s
08-17 19:51:17.382   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 19:51:17.384   874  1307 E native  : do suspend true
,08-17 19:51:17.404   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 19:51:17.407   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 19:51:17.408   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 19:51:17.409   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 19:51:17.417   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 19:51:17.468   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 19:51:17.469   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 19:51:17.471   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102,
,08-17 19:51:17.473   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 19:51:17.476   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 19:51:17.491   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 19:51:17.502   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 19:51:17.502   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 19:51:17.502   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 19:51:17.503   874  1309 D ConnectivityService:    accepting network in place of null
,08-17 19:51:17.502   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 19:51:17.504   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 19:51:17.504   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:17.514  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:51:17.515   874  4229 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158560, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 19:51:17.516  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:17.520  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 19:51:17.520  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 19:51:17.523  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ee9f0d Bundle[{}]
,08-17 19:51:17.523  3777  3830 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 19:51:17.523  3777  3830 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 19:51:17.524  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 19:51:17.525  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 19:51:17.525  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 19:51:17.526  3777  3830 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 19:51:17.533  3777  3830 I System.out: Running OutgoingSocketThread
,08-17 19:51:17.534  3777  4236 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,08-17 19:51:17.535  3777  4236 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49071
,08-17 19:51:17.535  3777  4236 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 19:51:17.549   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:17.590   874  4228 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.174,2a00:1450:4001:816::200e
,08-17 19:51:17.605   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 19:51:17.611   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 19:51:17.611   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:17.618   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 19:51:17.619   874   891 D Tethering: MasterInitialState.processMessage what=3
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:17.635  3777  3777 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:51:17.639  3777  3777 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:17.649  1738  1738 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 19:51:17.659  1738  1738 D SystemUpdateService: onCreate
,08-17 19:51:17.661   874  4228 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:51:17 GMT], X-Android-Received-Millis=[1471456277660], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471456277633]}
08-17 19:51:17.662   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 19:51:17.663   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 19:51:17.663   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 19:51:17.666   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 19:51:17.667  1738  1738 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 19:51:17.685   874  1983 D ConnectivityService: reportNetworkConnectivity(102, false) by 10011
,08-17 19:51:17.686   874  4228 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10011
08-17 19:51:17.686   874  4228 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.174,2a00:1450:4001:816::200e
,08-17 19:51:17.689  1738  4243 I SystemUpdateService: active receiver: enabled
,08-17 19:51:17.699  1738  1738 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 19:51:17.700  1738  2416 I iu.UploadsManager: num queued entries: 0
08-17 19:51:17.700  1738  2416 I iu.UploadsManager: num updated entries: 0
,08-17 19:51:17.703  1738  4243 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 19:51:17.707  1738  2416 I iu.SyncManager: NEXT; no task
,08-17 19:51:17.709  1738  4243 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 19:51:17.709  1738  4243 I SystemUpdateService: now status is 0 (complete)
08-17 19:51:17.709  1738  4243 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 19:51:17.709  1738  4243 I SystemUpdateService: file has been verified
,08-17 19:51:17.711   874  4228 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 17:51:17 GMT], X-Android-Received-Millis=[1471456277711], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471456277687]}
,08-17 19:51:17.712   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 19:51:17.712   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 19:51:17.712  1738  1738 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 19:51:17.713  1738  1738 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 19:51:17.709  1738  4243 I SystemUpdateService: OTA package size = 12249756
,08-17 19:51:17.715  3944  3944 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 19:51:17.719  1738  4246 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 19:51:17.719  1738  4246 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 19:51:17.721  1738  4246 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 19:51:17.722  3944  3944 D SprintDMHelper: simOperator: 
08-17 19:51:17.722  3944  3944 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 19:51:17.755  1738  4243 I SystemUpdateService: showing system update notification
,08-17 19:51:17.784  1738  1738 D SystemUpdateService: onDestroy
,08-17 19:51:17.800  1518  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 19:51:17.801  1518  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 19:51:17.801  1518  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 19:51:17.801  1518  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 19:51:17.824  1738  4246 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-17 19:51:17.856  3070  4248 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 19:51:18.536  3777  3830 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,08-17 19:51:18.536  3777  3830 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-17 19:51:18.546  3777  3830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-17 19:51:18.548  3777  3830 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 19:51:18.548  3777  3830 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-17 19:51:18.553  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:18.553  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87dc031 added. We now have 2 listener(s)
,08-17 19:51:18.555  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.556  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.556  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.556  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:18.556  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fff316 added. We now have 9 listener(s)
,08-17 19:51:18.556  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.557  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:18.559  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:18.566  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:51:18.568  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:18.568  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:18.569  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:18.569  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe0684 added. We now have 3 listener(s)
08-17 19:51:18.571  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.571  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:18.571  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.571  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:18.571  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d2e6d added. We now have 10 listener(s)
08-17 19:51:18.571  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.572  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 19:51:18.572  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:18.572  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:51:18.572  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:18.572  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.572  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:18.572  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:18.572  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87dc031 removed from the list
08-17 19:51:18.572  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.572  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fff316 removed from the list
08-17 19:51:18.574  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.575  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:18.575  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.575  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.575  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.586  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:18.586  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.586  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.586  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4fff316 not in the list
08-17 19:51:18.587  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.587  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.588  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:18.590  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:18.590  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:18.590  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.591  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d2e6d removed from the list
08-17 19:51:18.591  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:18.592  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.592  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.592  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:18.592  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fe0684 removed from the list
,08-17 19:51:18.594  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:18.594  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b802aa2 added. We now have 2 listener(s)
,08-17 19:51:18.600  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.600  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.600  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.601  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:18.601  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddbb333 added. We now have 9 listener(s)
,08-17 19:51:18.602  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:18.603  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:18.606  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:18.611   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:18.612  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:51:18.615  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:18.615  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:18.615  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:18.615  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90b4469 added. We now have 3 listener(s)
,08-17 19:51:18.617  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.617  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.617  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:18.617  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:18.618  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ada4eee added. We now have 10 listener(s)
,08-17 19:51:18.618  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:18.618  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:51:18.618  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:18.618  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:51:18.618  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:18.618  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:51:18.620  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:18.622  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:51:18.622  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 19:51:18.625  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.628  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:51:18.629  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 19:51:18.629  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:18.635  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:51:18.635  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:51:18.635  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:51:18.637  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:51:18.642  4174  4184 D BtGatt.GattService: registerClient() - UUID=ea098422-9177-4baf-8f9e-8733423ffd17
,08-17 19:51:18.643  4174  4191 D BtGatt.GattService: onClientRegistered() - UUID=ea098422-9177-4baf-8f9e-8733423ffd17, clientIf=5
,08-17 19:51:18.644  3777  3941 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 19:51:18.646  4174  4204 D BtGatt.GattService: start scan with filters
,08-17 19:51:18.652  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:51:18.653  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:51:18.653  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:51:18.653  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:51:18.653  4174  4194 D BtGatt.ScanManager: handling starting scan
,08-17 19:51:18.656  4174  4194 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@deb66d1
,08-17 19:51:18.657  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:18.658  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:51:18.660  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:18.661  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:18.663  4174  4191 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:51:18.663  3777  3830 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 19:51:18.663  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.663  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:18.664  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 19:51:18.664  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.664  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 19:51:18.664  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 19:51:18.664  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:51:18.664  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:51:18.664  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:51:18.664  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 19:51:18.664  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:51:18.665  4174  4194 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:51:18.666  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:51:18.666  4174  4214 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:51:18.667  4174  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:51:18.667  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:51:18.668  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 19:51:18.668  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:51:18.668  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:51:18.668  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:51:18.669  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:18.669  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:51:18.669  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:51:18.669  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:51:18.670  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:18.675  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:18.675  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:18.675  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:18.675  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 19:51:18.675  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.676  4174  4194 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:51:18.676  4174  4194 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:51:18.679  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:51:18.679  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:18.679  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:51:18.680  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:18.681  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-17 19:51:18.681  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:18.681  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:18.681  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b802aa2 removed from the list
,08-17 19:51:18.682  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.682  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddbb333 removed from the list
,08-17 19:51:18.682  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:51:18.682  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.684  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.684  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.687  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.687  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:18.687  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.687  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddbb333 not in the list,
,08-17 19:51:18.687  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.687  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.689  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:18.689  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.689  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-17 19:51:18.689  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ada4eee removed from the list
,08-17 19:51:18.689  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:18.690  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.690  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.690  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:18.690  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90b4469 removed from the list
,08-17 19:51:18.692  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:18.693  4174  4191 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 19:51:18.694  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.694  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a06bfa added. We now have 2 listener(s)
,08-17 19:51:18.699  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.699  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.699  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:18.700  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:18.700  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79055ab added. We now have 9 listener(s)
,08-17 19:51:18.700  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:18.701  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:18.707  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 19:51:18.707  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.708  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:18.714  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:51:18.716  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:51:18.716  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.716  4174  4194 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:51:18.717  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:18.717  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:18.720  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:18.723  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:18.723  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:51:18.723  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.723  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dce17a1 added. We now have 3 listener(s)
08-17 19:51:18.723  4174  4194 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:51:18.725  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:51:18.725  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:18.725  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.725  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.725  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:18.725  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3794dc6 added. We now have 10 listener(s)
,08-17 19:51:18.725  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.725  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:18.727  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:18.727  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:18.727  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 19:51:18.728  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 19:51:18.728  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 19:51:18.729  4174  4191 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 19:51:18.729  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.733  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 19:51:18.733  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:51:18.737  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 19:51:18.737  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 19:51:18.738  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:18.741  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:51:18.741  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:51:18.741  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 19:51:18.741  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:51:18.743  4174  4214 D BtGatt.GattService: registerClient() - UUID=84c111d0-a12e-4256-bef1-775a049cf124
,08-17 19:51:18.743  4174  4191 D BtGatt.GattService: onClientRegistered() - UUID=84c111d0-a12e-4256-bef1-775a049cf124, clientIf=5
08-17 19:51:18.743  3777  3941 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:51:18.744  4174  4204 D BtGatt.GattService: start scan with filters
,08-17 19:51:18.746  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 19:51:18.746  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 19:51:18.746  4174  4194 D BtGatt.ScanManager: handling starting scan
,08-17 19:51:18.746  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 19:51:18.746  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:51:18.749  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:18.749  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:18.749  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 19:51:18.751  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:18.753  4174  4191 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:51:18.753  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.753  4174  4194 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 19:51:18.754  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 19:51:18.754  3777  3830 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 19:51:18.755  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 19:51:18.755  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:18.755  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:51:18.755  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:18.755  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.755  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-17 19:51:18.755  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:18.755  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a06bfa removed from the list
,08-17 19:51:18.755  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.755  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79055ab removed from the list
,08-17 19:51:18.756  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop,
,08-17 19:51:18.756  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:18.756  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.757  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 19:51:18.757  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.757  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:18.759  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.759  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.759  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.760  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 19:51:18.760  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79055ab not in the list
,08-17 19:51:18.760  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.760  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 19:51:18.760  4174  4194 D BtGatt.ScanManager: Starting BLE batch scan
08-17 19:51:18.760  4174  4194 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:51:18.760  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 19:51:18.760  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 19:51:18.760  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:51:18.760  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 19:51:18.761  3777  3830 D BluetoothAdapter: STATE_ON
08-17 19:51:18.762  4174  4184 D BtGatt.GattService: stopScan() - queue size =1
,08-17 19:51:18.762  4174  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 19:51:18.763  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 19:51:18.763  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:51:18.763  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 19:51:18.763  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 19:51:18.763  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 19:51:18.764  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 19:51:18.764  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 19:51:18.764  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 19:51:18.764  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:51:18.765  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.767  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.767  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 19:51:18.768  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:18.768  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:18.768  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:18.769  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.769  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3794dc6 removed from the list
,08-17 19:51:18.769  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:18.769  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.769  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.769  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:18.769  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dce17a1 removed from the list
08-17 19:51:18.770  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:18.770  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac8052 added. We now have 2 listener(s)
,08-17 19:51:18.771  4174  4191 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 19:51:18.771  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.772  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:51:18.772  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:18.772  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:18.772  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:18.772  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7cf23 added. We now have 9 listener(s)
08-17 19:51:18.772  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.773  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 19:51:18.775  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:18.775  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 19:51:18.775  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:18.778  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 19:51:18.779  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:18.780  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 19:51:18.780  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:18.780  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4119d9 added. We now have 3 listener(s)
,08-17 19:51:18.781  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:51:18.781  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 19:51:18.781  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.781  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 19:51:18.781  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86e4f9e added. We now have 10 listener(s)
08-17 19:51:18.781  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.781  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:18.781  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 19:51:18.781  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 19:51:18.781  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:18.781  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 19:51:18.782  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 19:51:18.782  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.782  4174  4194 D BtGatt.ScanManager: stopping BLe Batch
08-17 19:51:18.783  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.783  3777  3830 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 19:51:18.783  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 19:51:18.785  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 19:51:18.786  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 19:51:18.786  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 19:51:18.786  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 19:51:18.788  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 19:51:18.788  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 19:51:18.788  3777  3830 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 19:51:18.789  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:51:18.789  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.789  3777  3830 D BluetoothAdapter: STATE_ON
08-17 19:51:18.789  4174  4194 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:51:18.790  4174  4184 D BtGatt.GattService: registerClient() - UUID=23df6b4d-172a-47d6-9523-4c8977773145
08-17 19:51:18.790  4174  4191 D BtGatt.GattService: onClientRegistered() - UUID=23df6b4d-172a-47d6-9523-4c8977773145, clientIf=5
,08-17 19:51:18.790  3777  3789 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 19:51:18.791  4174  4204 D BtGatt.GattService: start scan with filters
,08-17 19:51:18.793  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 19:51:18.793  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 19:51:18.793  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 19:51:18.793  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 19:51:18.794  4174  4191 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 19:51:18.794  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.795  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 19:51:18.795  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 19:51:18.795  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 19:51:18.795  4174  4194 D BtGatt.ScanManager: handling starting scan
08-17 19:51:18.796  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 19:51:18.799  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:51:18.799  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:18.799  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 19:51:18.799  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:18.799  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.799  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 19:51:18.799  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 19:51:18.799  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ac8052 removed from the list
,08-17 19:51:18.799  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.799  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7cf23 removed from the list
,08-17 19:51:18.799  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 19:51:18.799  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:18.800  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 19:51:18.800  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 19:51:18.800  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.800  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 19:51:18.800  4174  4191 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 19:51:18.800  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.800  4174  4194 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.801  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7cf23 not in the list
,08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 19:51:18.801  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 19:51:18.801  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 19:51:18.801  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 19:51:18.801  3777  3830 D BluetoothAdapter: STATE_ON
,08-17 19:51:18.802  4174  4204 D BtGatt.GattService: stopScan() - queue size =1
08-17 19:51:18.802  4174  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 19:51:18.802  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 19:51:18.802  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 19:51:18.803  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-17 19:51:18.803  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 19:51:18.803  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 19:51:18.803  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 19:51:18.803  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 19:51:18.803  3777  3830 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 19:51:18.804  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 19:51:18.804  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.804  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.804  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 19:51:18.804  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 19:51:18.805  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 19:51:18.805  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@86e4f9e removed from the list,
,08-17 19:51:18.805  3777  3777 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 19:51:18.805  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 19:51:18.805  3777  3777 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-17 19:51:18.805  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.805  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 19:51:18.805  4174  4194 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 19:51:18.805  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.805  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-17 19:51:18.805  4174  4194 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 19:51:18.805  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:18.805  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4119d9 removed from the list
08-17 19:51:18.805  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 19:51:18.806  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebc7aa added. We now have 2 listener(s)
,08-17 19:51:18.806  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 19:51:18.807  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.807  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 19:51:18.807  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:18.807  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5ff9b added. We now have 9 listener(s)
,08-17 19:51:18.807  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 19:51:18.807  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 19:51:18.809  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 19:51:18.812  3777  3830 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 19:51:18.813  4174  4191 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 19:51:18.813  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.814  3777  3830 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 19:51:18.814  3777  3830 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 19:51:18.814  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 19:51:18.814  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b2b11 added. We now have 3 listener(s)
,08-17 19:51:18.816  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.816  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 19:51:18.816  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.816  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 19:51:18.816  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 19:51:18.817  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 19:51:18.817  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 19:51:18.817  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@816b476 added. We now have 10 listener(s)
,08-17 19:51:18.817  3777  3830 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 19:51:18.817  3777  3830 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 19:51:18.817  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 19:51:18.817  3777  3830 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 19:51:18.817  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 19:51:18.817  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.817  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 19:51:18.817  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:18.817  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebc7aa removed from the list
08-17 19:51:18.817  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.818  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5ff9b removed from the list
08-17 19:51:18.818  3777  3777 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 19:51:18.818  3777  3830 D io.jxcore.node.ConnectivityMonitor: stop
08-17 19:51:18.818  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.818  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.818  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.819  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.819  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.819  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.819  3777  3830 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5ff9b not in the list
,08-17 19:51:18.819  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.819  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 19:51:18.820  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 19:51:18.820  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 19:51:18.820  3777  3830 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 19:51:18.820  3777  3830 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@816b476 removed from the list
08-17 19:51:18.820  3777  3830 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 19:51:18.820  3777  3830 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 19:51:18.820  3777  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 19:51:18.820  3777  3830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 19:51:18.820  3777  3830 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b2b11 removed from the list
08-17 19:51:18.821  4174  4191 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 19:51:18.821  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.821  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 19:51:18.821  4174  4194 D BtGatt.ScanManager: stopping BLe Batch
,08-17 19:51:18.821  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 19:51:18.821  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-17 19:51:18.822  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 19:51:18.822  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 19:51:18.822  3777  3830 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 19:51:18.826  4174  4191 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 19:51:18.826  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 19:51:18.826  4174  4194 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 19:51:18.827  3777  4253 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
08-17 19:51:18.827  3777  4253 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
08-17 19:51:18.827  3777  4253 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 19:51:18.828  3777  4254 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
08-17 19:51:18.828  3777  4254 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
,08-17 19:51:18.828  3777  4254 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 19:51:18.830  3777  3830 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 19:51:18.830  3777  3830 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-17 19:51:18.830  3777  3830 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 19:51:18.830  3777  3830 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-17 19:51:18.830  3777  3830 D com.test.thalitest.ThaliTestRunner: Total duration: 22931 ms
08-17 19:51:18.831  4174  4191 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 19:51:18.831  4174  4191 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 19:51:18.831  3777  3830 I jxcore-log: Total number of executed tests:  80
08-17 19:51:18.831  3777  3830 I jxcore-log: 
08-17 19:51:18.832  3777  3830 I jxcore-log: Number of passed tests:  80
08-17 19:51:18.832  3777  3830 I jxcore-log: 
08-17 19:51:18.832  3777  3830 I jxcore-log: Number of failed tests:  0
08-17 19:51:18.832  3777  3830 I jxcore-log: 
,08-17 19:51:18.832  3777  3830 I jxcore-log: Number of ignored tests:  0
08-17 19:51:18.832  3777  3830 I jxcore-log: 
08-17 19:51:18.832  3777  3830 I jxcore-log: Total duration:  22931
08-17 19:51:18.832  3777  3830 I jxcore-log: 
,08-17 19:51:18.833  3777  3830 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 19:51:18.833  3777  3830 I jxcore-log: 
08-17 19:51:18.835  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.835  3777  3830 I jxcore-log: 
,08-17 19:51:18.837  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.837  3777  3830 I jxcore-log: 
08-17 19:51:18.838  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.838  3777  3830 I jxcore-log: 
08-17 19:51:18.839  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.839  3777  3830 I jxcore-log: 
08-17 19:51:18.840  3777  3777 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 19:51:18.840  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.840  3777  3830 I jxcore-log: 
08-17 19:51:18.841  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.841  3777  3830 I jxcore-log: 
08-17 19:51:18.843  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.843  3777  3830 I jxcore-log: 
08-17 19:51:18.845  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.845  3777  3830 I jxcore-log: 
08-17 19:51:18.845  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.845  3777  3830 I jxcore-log: 
08-17 19:51:18.846  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:18.846  3777  3830 I jxcore-log: 
08-17 19:51:18.847  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:51:18.847  3777  3830 I jxcore-log: 
08-17 19:51:18.848  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 19:51:18.848  3777  3830 I jxcore-log: 
08-17 19:51:18.849  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.849  3777  3830 I jxcore-log: 
08-17 19:51:18.849  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.849  3777  3830 I jxcore-log: 
08-17 19:51:18.850  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.850  3777  3830 I jxcore-log: 
08-17 19:51:18.850  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.850  3777  3830 I jxcore-log: 
08-17 19:51:18.851  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.851  3777  3830 I jxcore-log: 
08-17 19:51:18.852  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.852  3777  3830 I jxcore-log: 
08-17 19:51:18.852  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.852  3777  3830 I jxcore-log: 
08-17 19:51:18.853  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.853  3777  3830 I jxcore-log: 
08-17 19:51:18.854  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.854  3777  3830 I jxcore-log: 
08-17 19:51:18.854  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 19:51:18.854  3777  3830 I jxcore-log: 
08-17 19:51:18.855  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 19:51:18.855  3777  3830 I jxcore-log: 
08-17 19:51:18.855  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.855  3777  3830 I jxcore-log: 
08-17 19:51:18.856  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.856  3777  3830 I jxcore-log: 
08-17 19:51:18.856  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.856  3777  3830 I jxcore-log: 
08-17 19:51:18.857  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.857  3777  3830 I jxcore-log: 
08-17 19:51:18.857  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.857  3777  3830 I jxcore-log: 
08-17 19:51:18.858  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.858  3777  3830 I jxcore-log: 
08-17 19:51:18.858  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 19:51:18.858  3777  3830 I jxcore-log: 
,08-17 19:51:19.176  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:51:19.177  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:19.177  3777  3830 I jxcore-log: 
,08-17 19:51:19.269  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:51:19.270  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:19.270  3777  3830 I jxcore-log: 
,08-17 19:51:19.305  3777  3777 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 19:51:19.309  3777  3830 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 19:51:19.309  3777  3830 I jxcore-log: 
,08-17 19:51:19.493  4255  4255 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 19:51:19.498  4255  4255 D AndroidRuntime: CheckJNI is OFF
,08-17 19:51:19.518  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 19:51:19.539  4255  4255 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 19:51:19.575  4255  4255 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 19:51:19.596  4255  4255 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 19:51:19.604   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 19:51:19.605   874   887 I ActivityManager: Killing 3777:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 19:51:19.711   874  1308 D WifiService: Client connection lost with reason: 4
,08-17 19:51:19.711   874  3913 D GraphicsStats: Buffer count: 2
08-17 19:51:19.713   874  1390 I WindowState: WIN DEATH: Window{e55519d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 19:51:19.726   874   897 W PackageSettings: Skipping PackageSetting{64d6d3a com.example.hello/10273} due to missing metadata
,08-17 19:51:19.769   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-17 19:51:19.769   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-17 19:51:19.770   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-17 19:51:19.770   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 19:51:19.770   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:19.770   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:19.770   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:51:19.770   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 19:51:19.770   874   887 I ActivityManager:   Force finishing activity ActivityRecord{e3d35e4 u0 com.test.thalitest/.MainActivity t2}
,08-17 19:51:19.774   874  1890 W ActivityManager: Spurious death for ProcessRecord{762512d 0:com.test.thalitest/u0a0}, curProc for 3777: null
,08-17 19:51:19.777   874   897 I art     : Starting a blocking GC Explicit
,08-17 19:51:19.818   874   897 I art     : Explicit concurrent mark sweep GC freed 18451(1167KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 704us total 40.586ms
,08-17 19:51:19.834  1518  4267 I VacuumService: Vacuum at: now=1471456279834 tag=VacuumService
,08-17 19:51:19.847   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 19:51:19.851  4255  4255 I art     : System.exit called, status: 0
,08-17 19:51:19.851  4255  4255 I AndroidRuntime: VM exiting with result code 0.
,08-17 19:51:19.874   874   897 I ActivityManager: Start proc 4272:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-17 19:51:19.876   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 19:51:19.902   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 19:51:19.920  4174  4174 D BluetoothMapAppObserver: onReceive
,08-17 19:51:19.921  4174  4174 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-17 19:51:19.923   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 19:51:19.931  3648  3648 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 19:51:19.938  2149  2296 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 19:51:19.942  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 19:51:19.945  1873  4287 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 19:51:19.947  1873  4287 I Decoder : createOrResetDecoder
,08-17 19:51:19.968  1952  1952 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 19:51:19.983   874  2736 I ActivityManager: Start proc 4290:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 19:51:20.005   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 19:51:20.006  1518  1518 I ConfigService: onCreate
,08-17 19:51:20.016   874  1390 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3777 uid 10000
,08-17 19:51:20.017  1873  1873 I Keyboard.Facilitator: onFinishInput()
08-17 19:51:20.021  1518  4268 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
08-17 19:51:20.022  1518  4268 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 19:51:20.036  1873  4287 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 19:51:20.041  1518  4268 W Uploader:  no longer exists, so no auth token.
,08-17 19:51:20.045  1518  4271 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: disk I/O error (code 3850)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at com.google.android.gms.phenotype.service.a.c.a(SourceFile:60)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at com.google.android.gms.phenotype.service.a.a.a(SourceFile:25)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 19:51:20.046  1518  4271 E PhenotypeIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-17 19:51:20.046  1518  4268 E Uploader: Failed to get server token: Status{statusCode=INTERNAL_ERROR, resolution=null}
,08-17 19:51:20.055  4290  4290 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 19:51:20.065  1967  2046 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 19:51:20.066   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 19:51:20.066   874   886 E PackageManager: Failed to write settings, restoring backup
08-17 19:51:20.066   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 19:51:20.066   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 19:51:20.066   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 19:51:20.066   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 19:51:20.066   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 19:51:20.066   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.066   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.066   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.070   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-17 19:51:20.070   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 19:51:20.070   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:51:20.070   874   887 E DropBoxManagerService: 	... 13 more
,08-17 19:51:20.077   874  4265 I ActivityManager: Start proc 4304:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-17 19:51:20.078  1967  2046 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 19:51:20.078  1967  2046 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1967
08-17 19:51:20.078  1967  2046 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.078  1967  2046 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.080   874  1970 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 19:51:20.080   874  4309 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:51:20.080   874  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:51:20.080   874  4309 E DropBoxManagerService: 	... 5 more
,08-17 19:51:20.083  1967  2046 I Process : Sending signal. PID: 1967 SIG: 9
,08-17 19:51:20.094  1873  4287 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 19:51:20.096  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 19:51:20.096  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 19:51:20.098  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 19:51:20.099  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 19:51:20.099  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 19:51:20.099  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-17 19:51:20.100  1873  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-17 19:51:20.100  1873  4287 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 19:51:20.100  1873  4287 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 19:51:20.100  1873  4287 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 19:51:20.100  1873  4287 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-17 19:51:20.100  1873  4287 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 19:51:20.155  4290  4290 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 19:51:20.181  4290  4327 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 19:51:20.183   874  4265 I ActivityManager: Start proc 4325:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 19:51:20.187   874  1297 W InputDispatcher: channel 'fd864b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-17 19:51:20.187   874  1297 E InputDispatcher: channel 'fd864b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-17 19:51:20.188   874   884 I WindowState: WIN DEATH: Window{fd864b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-17 19:51:20.188   874   884 W InputDispatcher: Attempted to unregister already unregistered input channel 'fd864b com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-17 19:51:20.191   874  3913 D GraphicsStats: Buffer count: 1
,08-17 19:51:20.198   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1967) has died
,08-17 19:51:20.199   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-17 19:51:20.200   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 19:51:20.220   874   887 I ActivityManager: Start proc 4338:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 19:51:20.250  4325  4325 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 19:51:20.266  1518  1518 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-17 19:51:20.267  1518  1518 D AndroidRuntime: Shutting down VM
,08-17 19:51:20.267  1518  1518 E AndroidRuntime: FATAL EXCEPTION: main
08-17 19:51:20.267  1518  1518 E AndroidRuntime: Process: com.google.process.gapps, PID: 1518
08-17 19:51:20.267  1518  1518 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 19:51:20.267  1518  1518 E AndroidRuntime: 	... 8 more
,08-17 19:51:20.272   874  4353 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:51:20.272   874  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:51:20.272   874  4353 E DropBoxManagerService: 	... 5 more
,08-17 19:51:20.273  1518  1518 I Process : Sending signal. PID: 1518 SIG: 9
,08-17 19:51:20.278  4290  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.278  4290  4320 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.283  4338  4338 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:51:20.283  4338  4338 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 19:51:20.283  4338  4338 D AndroidRuntime: Shutting down VM
08-17 19:51:20.284   874  3913 I ActivityManager: Killing 3701:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.287  4290  4320 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.303   874  1308 D WifiService: Client connection lost with reason: 4
,08-17 19:51:20.305  1738  4348 E BulkCursor: Unable to get window because the remote process is dead
,08-17 19:51:20.305  1738  4348 W BulkCursor: Remote process exception when closing
,08-17 19:51:20.322  4290  4320 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-17 19:51:20.327  4290  4327 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.327  4290  4327 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.327  4290  4327 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 19:51:20.327  4290  4327 E AndroidRuntime: Process: android.process.acore, PID: 4290
08-17 19:51:20.327  4290  4327 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.327  4290  4327 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 19:51:20.329  4290  4320 I Process : Sending signal. PID: 4290 SIG: 9
,08-17 19:51:20.336   874  1392 I ActivityManager: Process com.google.process.gapps (pid 1518) has died
08-17 19:51:20.337   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.uploader.UploaderService in 1000ms
08-17 19:51:20.337   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 1000ms
08-17 19:51:20.337   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-17 19:51:20.337   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-17 19:51:20.338   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-17 19:51:20.338   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
08-17 19:51:20.338   874  1392 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.phenotype.service.PhenotypeIntentService in 40999ms
08-17 19:51:20.338   874  1392 I ActivityManager: Killing 1738:com.google.android.gms/u0a11 (adj 1): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
,08-17 19:51:20.371   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-17 19:51:20.372   874  3913 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@deb21ef)
,08-17 19:51:20.373  4304  4323 W GmsClient: service died
,08-17 19:51:20.373   874  1309 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 19:51:20.374   874  1309 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 19:51:20.375  4304  4304 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
,08-17 19:51:20.382   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 30955ms
,08-17 19:51:20.382   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 40955ms
08-17 19:51:20.382   874  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 50955ms
,08-17 19:51:20.384   874  4356 I ActivityManager: Process android.process.acore (pid 4290) has died
08-17 19:51:20.384   874  4356 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 50953ms
,08-17 19:51:20.387  4338  4338 E AndroidRuntime: FATAL EXCEPTION: main
08-17 19:51:20.387  4338  4338 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4338
08-17 19:51:20.387  4338  4338 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 19:51:20.387  4338  4338 E AndroidRuntime: 	... 10 more
,08-17 19:51:20.400   874   887 I ActivityManager: Start proc 4359:com.google.android.gms/u0a11 for broadcast com.google.android.gms/.photos.autobackup.PhotosAppUninstalledReceiver
,08-17 19:51:20.403   874  4368 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:51:20.403   874  4368 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:51:20.403   874  4368 E DropBoxManagerService: 	... 5 more
,08-17 19:51:20.405   874  3913 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 19:51:20.410   874  4370 E DropBoxManagerService: Can't write: system_app_crash
08-17 19:51:20.410   874  4370 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 19:51:20.410   874  4370 E DropBoxManagerService: 	... 5 more
,08-17 19:51:20.418   874  4358 I ActivityManager: Start proc 4373:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-17 19:51:20.418  4338  4338 I Process : Sending signal. PID: 4338 SIG: 9
,08-17 19:51:20.430   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
