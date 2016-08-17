#### Test 81634701f6c81fd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-17 16:35:36.383   872  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-17 16:35:37.185  3952  3952 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 16:35:37.191  3952  3952 D AndroidRuntime: CheckJNI is OFF
08-17 16:35:37.228  3952  3952 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 16:35:37.278  3952  3952 I Radio-JNI: register_android_hardware_Radio DONE
08-17 16:35:37.304  3952  3952 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 16:35:37.310   872  1372 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 16:35:37.349  1964  1976 W SearchService: Abort, client detached.
08-17 16:35:37.361  3952  3952 D AndroidRuntime: Shutting down VM
08-17 16:35:37.364  1964  2278 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d618851
08-17 16:35:37.366  1964  2301 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 16:35:37.366  1964  1964 I HotwordDetector: Closing mic
08-17 16:35:37.370   872  1695 I ActivityManager: Start proc 3961:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 16:35:37.412   375  2306 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 16:35:37.412   375  2306 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 16:35:37.419   375  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 16:35:37.422  1964  2286 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 16:35:37.423  1964  2300 I MicroRecognitionRnrImpl: Detection finished
08-17 16:35:37.447  1964  2035 I SearchBackgroundTaskFac: Checking for language pack updates
08-17 16:35:37.459  3961  3961 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 16:35:37.460  1964  3978 I GservicesUpdateTask: Updating Gservices keys
08-17 16:35:37.491  3961  3961 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 16:35:37.499  3961  3961 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4005-4008)
08-17 16:35:37.499  3961  3961 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 16:35:37.512  3961  3961 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d9f13a}
08-17 16:35:37.512  3961  3961 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 16:35:37.513  3961  3961 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:35:37.517  1964  2117 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:35:37.519  1964  2109 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 16:35:37.519  3961  3961 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 16:35:37.521  3961  3961 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 16:35:37.537  3961  3961 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:35:37.540  1964  2075 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 16:35:37.540  1964  2095 E VelvetNetworkClient: Failed to get auth token
08-17 16:35:37.546  3961  3961 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 16:35:37.546  3961  3961 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 16:35:37.546  3961  3961 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 16:35:37.546  3961  3961 I Adreno  : Build Date                       : 10/20/15
08-17 16:35:37.546  3961  3961 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 16:35:37.546  3961  3961 I Adreno  : Local Branch                     : M14
08-17 16:35:37.546  3961  3961 I Adreno  : Remote Branch                    : 
08-17 16:35:37.546  3961  3961 I Adreno  : Remote Branch                    : 
08-17 16:35:37.546  3961  3961 I Adreno  : Reconstruct Branch               : 
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:35:37.569  1964  2133 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-17 16:35:37.569  1964  2027 E VelvetNetworkClient: Failed to get auth token
,08-17 16:35:37.585   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cdb86b5:true
,08-17 16:35:37.617  3961  3961 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 16:35:37.628  3961  3961 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 16:35:37.664  3961  4016 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-17 16:35:37.673  3961  4002 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-17 16:35:37.705  3961  4016 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 16:35:37.759   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +404ms
08-17 16:35:37.762  1845  1845 I Keyboard.Facilitator: onFinishInput()
08-17 16:35:37.817  3961  3961 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3961
08-17 16:35:37.919  3961  3961 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-17 16:35:38.083  3961  4018 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1684801232
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 16:35:38.101  3961  4018 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a27c5d9 added. We now have 1 listener(s)
08-17 16:35:38.104  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-17 16:35:38.105  3961  4018 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 16:35:38.105  3961  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:35:38.106  3961  4018 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 16:35:38.109  3961  4018 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@563664c added. We now have 1 listener(s)
08-17 16:35:38.109  3961  4018 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:35:38.115   872  1302 D WifiService: New client listening to asynchronous messages
08-17 16:35:38.115  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 16:35:38.116  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 16:35:38.116  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 16:35:38.116  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 16:35:38.116  3961  4018 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 16:35:38.118  3961  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:35:38.118  3961  4018 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-17 16:35:38.125  3961  4018 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:38.125  3961  4018 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:35:38.125  3961  4018 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 16:35:38.126  3961  4018 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:35:38.126  3961  4018 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 16:35:38.128  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:38.130  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:38.171  3961  3961 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-17 16:35:38.673  3961  3970 I art     : Background sticky concurrent mark sweep GC freed 69899(6MB) AllocSpace objects, 17(1116KB) LOS objects, 28% free, 23MB/32MB, paused 540us total 102.811ms
,08-17 16:35:39.528   872  2198 I ActivityManager: Killing 3558:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-17 16:35:39.850  3961  4025 W jxcore-log: Initializing JXcore engine
,08-17 16:35:39.851  3961  4025 W jxcore-log: JXcore engine is ready
,08-17 16:35:39.888  4025  4025 W Thread-365: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 16:35:39.888  4025  4025 W Thread-365: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10971]" dev="sockfs" ino=10971 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 16:35:39.888  4025  4025 W Thread-365: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 16:35:39.888  4025  4025 W Thread-365: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24188]" dev="sockfs" ino=24188 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 16:35:39.906  3961  4025 W jxcore-log: Starting JXcore engine
,08-17 16:35:39.991  3961  4025 W jxcore-log: Platform android
08-17 16:35:39.991  3961  4025 W jxcore-log: 
,08-17 16:35:39.991  3961  4025 W jxcore-log: Process ARCH arm
08-17 16:35:39.991  3961  4025 W jxcore-log: 
,08-17 16:35:40.271  3961  4025 I jxcore-log: JXcore Cordova bridge is ready!
08-17 16:35:40.271  3961  4025 I jxcore-log: 
,08-17 16:35:40.272  3961  4025 W jxcore-log: JXcore engine is started
,08-17 16:35:40.288  3961  4018 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 16:35:40.294  3961  3961 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 16:35:42.603   872  1995 I ActivityManager: Killing 3355:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 16:35:43.108  3178  4034 V KeepSync: Connecting to GoogleApiClient
,08-17 16:35:43.109   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011,
,08-17 16:35:43.167  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:35:43.170  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:35:43.206  1519  2063 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 16:35:43.207  1519  2063 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 16:35:43.207  1519  2063 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:35:43.207  1519  2063 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:35:43.225  1745  4035 V BaseAuthAsyncOperation: access token request failed
,08-17 16:35:43.226  3178  4034 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 16:35:43.322  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 16:35:43.322  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 16:35:43.323  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:35:43.323  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:35:43.352  3178  4034 E KeepSync: IOException
08-17 16:35:43.352  3178  4034 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 16:35:43.352  3178  4034 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 16:35:43.352  3178  4034 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 16:35:43.352  3178  4034 E KeepSync: 	... 10 more
08-17 16:35:43.352  3178  4034 W KeepSync: Sync result 2
,08-17 16:35:43.363   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 129527, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-17 16:35:47.591  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:35:47.618  1519  3118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 16:35:47.618  1519  3118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 16:35:47.618  1519  3118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:35:47.618  1519  3118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:35:47.634  3675  3675 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 16:35:47.634  3675  3675 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 16:35:47.634  3675  3675 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-17 16:35:47.688   872  1863 D NetlinkSocketObserver: NeighborEvent{elapsedMs=134196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 16:35:56.926  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 16:35:56.926  3961  4025 I jxcore-log: 
,08-17 16:35:56.928  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 16:35:56.928  3961  4025 I jxcore-log: 
,08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:56.940  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:35:56.943  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:35:56.945  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 16:35:56.945  3961  4025 I jxcore-log: 
,08-17 16:35:56.947  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 16:35:56.947  3961  4025 I jxcore-log: 
,08-17 16:35:57.289  3961  4025 D ExecuteNativeTests: Running unit tests
,08-17 16:35:57.348  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 16:35:57.348  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b added. We now have 2 listener(s)
08-17 16:35:57.349  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 16:35:57.349  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:35:57.349  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:35:57.349  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:35:57.349  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 added. We now have 2 listener(s)
08-17 16:35:57.349  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:35:57.350  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 16:35:57.356  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.365  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:35:57.368  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:35:57.368  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:35:57.370  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 16:35:57.372  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 16:35:57.372  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 16:35:57.374  3961  4025 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 16:35:57.374  3961  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 16:35:57.374  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 16:35:57.374  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 16:35:57.374  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 16:35:57.375  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.375  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.375  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.376  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.376  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 16:35:57.376  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.376  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:35:57.376  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 16:35:57.376  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b removed from the list
08-17 16:35:57.376  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.376  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 removed from the list
08-17 16:35:57.381  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.382  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.383  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.386  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.387  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.391  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:35:57.391  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.392  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:35:57.392  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
,08-17 16:35:57.396  3961  4025 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 16:35:57.398  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 16:35:57.399  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.399  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 16:35:57.399  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.399  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.400  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.400  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
,08-17 16:35:57.400  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.400  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
,08-17 16:35:57.401  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.401  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.401  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.401  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.402  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.404  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:35:57.404  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.405  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.405  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
,08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 16:35:57.415  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 16:35:57.416  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 16:35:57.417  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 16:35:57.417  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 16:35:57.417  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 16:35:57.417  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-17 16:35:57.417  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.417  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.417  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.417  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.417  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.417  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.417  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.417  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.417  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.417  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.418  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.418  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.418  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.418  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.419  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:35:57.419  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.419  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.419  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.420  3961  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 16:35:57.421  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.426  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:35:57.427  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.428  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:35:57.428  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 16:35:57.428  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 16:35:57.428  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 16:35:57.428  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:35:57.428  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 16:35:57.429  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.437  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.438  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 16:35:57.438  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 16:35:57.444  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 16:35:57.446  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 16:35:57.447  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:35:57.449  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 16:35:57.451  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-17 16:35:57.452  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 16:35:57.452  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 16:35:57.453  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 16:35:57.454  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:35:57.459  2608  2748 D BtGatt.GattService: registerClient() - UUID=587fce8b-f38f-426d-84ec-6bea731bc1a5
,08-17 16:35:57.460  2608  2630 D BtGatt.GattService: onClientRegistered() - UUID=587fce8b-f38f-426d-84ec-6bea731bc1a5, clientIf=5
,08-17 16:35:57.461  3961  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 16:35:57.463  2608  2619 D BtGatt.GattService: start scan with filters
,08-17 16:35:57.468  2608  2636 D BtGatt.ScanManager: handling starting scan
,08-17 16:35:57.468  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 16:35:57.469  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 16:35:57.469  2608  2636 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:35:57.469  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 16:35:57.470  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:35:57.477  2608  2630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 16:35:57.477  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.478  2608  2636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 16:35:57.479  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:35:57.480  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 16:35:57.480  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:35:57.485  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 16:35:57.486  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.486  2608  2636 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:35:57.486  2608  2636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 16:35:57.487  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 16:35:57.494  3961  4025 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 16:35:57.498  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 16:35:57.498  3961  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 16:35:57.498  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:35:57.498  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 16:35:57.498  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.498  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 16:35:57.498  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 16:35:57.498  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 16:35:57.498  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 16:35:57.498  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 16:35:57.499  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:35:57.499  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 16:35:57.500  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:35:57.500  2608  2620 D BtGatt.GattService: stopScan() - queue size =1
08-17 16:35:57.501  2608  2748 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 16:35:57.501  2608  2630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 16:35:57.502  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.503  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 16:35:57.504  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 16:35:57.504  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 16:35:57.505  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 16:35:57.505  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 16:35:57.507  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:35:57.507  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 16:35:57.507  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 16:35:57.508  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 16:35:57.509  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.510  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 16:35:57.510  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.512  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.512  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 16:35:57.512  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:35:57.512  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.513  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.513  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.513  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
,08-17 16:35:57.513  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.513  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.513  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.513  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.514  3961  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 16:35:57.517  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:35:57.519  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:35:57.520  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.520  2608  2636 D BtGatt.ScanManager: stopping BLe Batch
,08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.525  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:35:57.528  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 16:35:57.528  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.528  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:35:57.528  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:35:57.528  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 16:35:57.528  2608  2636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 16:35:57.528  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 16:35:57.528  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 16:35:57.529  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:35:57.529  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 16:35:57.532  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.534  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 16:35:57.534  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 16:35:57.535  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.537  2608  2630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 16:35:57.537  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.539  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 16:35:57.540  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 16:35:57.540  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:35:57.545  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 16:35:57.545  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 16:35:57.545  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 16:35:57.546  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:35:57.550  2608  2619 D BtGatt.GattService: registerClient() - UUID=f3edc65d-d5f7-405d-bf65-facd258998b3
,08-17 16:35:57.551  2608  2630 D BtGatt.GattService: onClientRegistered() - UUID=f3edc65d-d5f7-405d-bf65-facd258998b3, clientIf=5
,08-17 16:35:57.551  3961  3973 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 16:35:57.552  2608  2748 D BtGatt.GattService: start scan with filters
,08-17 16:35:57.556  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 16:35:57.556  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 16:35:57.556  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 16:35:57.556  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:35:57.556  2608  2636 D BtGatt.ScanManager: handling starting scan
,08-17 16:35:57.561  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:35:57.562  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:35:57.562  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 16:35:57.565  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 16:35:57.565  2608  2630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 16:35:57.565  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.565  2608  2636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 16:35:57.568  3961  4025 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 16:35:57.572  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 16:35:57.572  3961  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 16:35:57.572  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:35:57.572  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 16:35:57.572  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.572  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 16:35:57.572  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 16:35:57.573  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 16:35:57.573  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 16:35:57.573  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 16:35:57.573  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:35:57.573  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 16:35:57.574  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 16:35:57.574  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.574  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:35:57.574  2608  2636 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:35:57.575  2608  2636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 16:35:57.575  2608  2748 D BtGatt.GattService: stopScan() - queue size =1
,08-17 16:35:57.577  2608  2619 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 16:35:57.577  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 16:35:57.577  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 16:35:57.578  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 16:35:57.578  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 16:35:57.578  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 16:35:57.580  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:35:57.580  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 16:35:57.580  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 16:35:57.580  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 16:35:57.581  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.582  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.583  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.583  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:35:57.583  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.583  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.583  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.584  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
,08-17 16:35:57.584  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.584  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.585  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.585  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.586  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.586  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.588  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.588  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.588  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:35:57.588  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.589  3961  4025 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 16:35:57.591  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:35:57.596  2608  2630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 16:35:57.596  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.599  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:35:57.602  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.602  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 16:35:57.604  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 16:35:57.604  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.605  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.606  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 16:35:57.606  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 16:35:57.607  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.606  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 16:35:57.607  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:35:57.607  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 16:35:57.611  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 16:35:57.611  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 16:35:57.613  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:35:57.614  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.614  2608  2636 D BtGatt.ScanManager: stopping BLe Batch
,08-17 16:35:57.616  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 16:35:57.617  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 16:35:57.617  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:35:57.621  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 16:35:57.621  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 16:35:57.621  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 16:35:57.621  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 16:35:57.621  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.622  2608  2636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 16:35:57.622  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:35:57.624  2608  2620 D BtGatt.GattService: registerClient() - UUID=8f332f4e-26a8-4334-8c2e-6cec523434d9
,08-17 16:35:57.625  2608  2630 D BtGatt.GattService: onClientRegistered() - UUID=8f332f4e-26a8-4334-8c2e-6cec523434d9, clientIf=5
08-17 16:35:57.625  3961  3973 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 16:35:57.625  2608  2748 D BtGatt.GattService: start scan with filters
,08-17 16:35:57.628  2608  2630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 16:35:57.628  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:35:57.628  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 16:35:57.628  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 16:35:57.629  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 16:35:57.629  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:35:57.631  2608  2636 D BtGatt.ScanManager: handling starting scan
08-17 16:35:57.631  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:35:57.631  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:35:57.632  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 16:35:57.639  2608  2630 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 16:35:57.639  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.639  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 16:35:57.639  2608  2636 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 16:35:57.643  3961  4025 I io.jxcore.node.ConnectionHelper: start: OK
08-17 16:35:57.643  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 16:35:57.643  3961  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 16:35:57.644  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:35:57.644  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 16:35:57.644  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.644  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 16:35:57.644  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 16:35:57.644  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 16:35:57.644  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 16:35:57.644  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 16:35:57.644  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:35:57.644  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 16:35:57.645  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:35:57.646  2608  2619 D BtGatt.GattService: stopScan() - queue size =1
08-17 16:35:57.647  2608  2620 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 16:35:57.647  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 16:35:57.647  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 16:35:57.647  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 16:35:57.647  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 16:35:57.647  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 16:35:57.648  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 16:35:57.647  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.648  2608  2636 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:35:57.648  2608  2636 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 16:35:57.649  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:35:57.649  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 16:35:57.649  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 16:35:57.649  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 16:35:57.650  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.651  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.651  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.651  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:35:57.652  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.652  3961  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 16:35:57.652  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.652  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.652  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.652  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.653  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:35:57.653  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
,08-17 16:35:57.653  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.653  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.653  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.653  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.654  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.654  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.655  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.655  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 16:35:57.655  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.655  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.655  3961  4025 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 16:35:57.656  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.656  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.656  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.656  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 16:35:57.657  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.657  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.657  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.657  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:35:57.657  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.657  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.657  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.657  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.657  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.658  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:35:57.658  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:35:57.658  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 16:35:57.659  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:35:57.659  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
,08-17 16:35:57.660  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 16:35:57.660  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.660  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:35:57.660  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.660  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 16:35:57.660  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.661  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.661  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.661  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.661  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.661  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.661  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 16:35:57.661  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.661  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.661  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.661  2608  2630 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 16:35:57.662  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.663  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.663  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.663  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.663  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.663  3961  4025 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 16:35:57.664  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.664  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.666  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.667  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.667  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.667  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.667  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.667  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.667  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.667  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.667  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.667  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.667  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:35:57.668  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.668  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.669  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.669  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.669  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.669  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 16:35:57.670  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.670  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.670  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.670  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.670  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.670  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.671  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.671  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.671  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.671  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.671  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.671  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.671  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.671  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 16:35:57.672  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.672  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.673  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:35:57.673  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.673  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.673  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.674  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 16:35:57.676  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 16:35:57.676  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 16:35:57.676  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 16:35:57.676  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 16:35:57.676  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 16:35:57.676  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.676  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.676  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.677  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.677  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.677  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.677  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.677  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.677  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.677  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.677  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.677  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.677  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.677  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.678  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.678  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.678  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.678  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.679  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 16:35:57.679  3961  4025 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 16:35:57.679  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 16:35:57.682  2608  2630 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:35:57.682  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.682  2608  2636 D BtGatt.ScanManager: stopping BLe Batch
08-17 16:35:57.683  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 16:35:57.683  3961  4025 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 16:35:57.683  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 16:35:57.683  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 16:35:57.684  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 16:35:57.685  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 16:35:57.686  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 16:35:57.686  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 16:35:57.686  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 16:35:57.686  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 16:35:57.686  3961  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 16:35:57.686  3961  4025 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 16:35:57.686  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 16:35:57.686  3961  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 16:35:57.687  3961  4025 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 16:35:57.687  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 16:35:57.687  3961  4025 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 16:35:57.687  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 16:35:57.689  2608  2630 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 16:35:57.689  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.689  2608  2636 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 16:35:57.696  2608  2630 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 16:35:57.696  2608  2630 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:35:57.696  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 16:35:57.697  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 16:35:57.697  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 16:35:57.697  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 16:35:57.697  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 16:35:57.697  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 16:35:57.698  3961  4025 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 16:35:57.698  3961  4025 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 16:35:57.698  3961  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
08-17 16:35:57.698  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.698  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.698  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.699  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.699  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.699  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.699  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 16:35:57.700  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.700  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.700  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.700  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.700  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.700  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.700  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.700  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.700  3961  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 16:35:57.701  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.701  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.701  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.701  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.702  3961  4025 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 16:35:57.702  3961  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
08-17 16:35:57.703  3961  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 429)
08-17 16:35:57.703  3961  4040 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 429)
08-17 16:35:57.703  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.703  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.703  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.704  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.704  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.704  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.704  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.704  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.704  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.704  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.704  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.704  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.704  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.704  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.704  3961  4039 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
08-17 16:35:57.705  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.705  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.705  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.705  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.706  3961  4025 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 16:35:57.706  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.706  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.706  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.706  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.706  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.707  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.707  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Connec,tionManager@64f8c7b not in the list
08-17 16:35:57.707  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.707  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.707  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.707  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.707  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.707  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.707  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.708  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.708  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.708  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.708  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.708  3961  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 16:35:57.708  3961  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 16:35:57.709  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 16:35:57.709  3961  4025 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 16:35:57.709  3961  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 16:35:57.709  3961  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 16:35:57.709  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 16:35:57.709  3961  4025 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 16:35:57.709  3961  4025 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 16:35:57.709  3961  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 16:35:57.709  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 16:35:57.709  3961  4025 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 16:35:57.709  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.709  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.709  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.710  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.710  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.710  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.710  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.710  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.710  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.710  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.710  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.710  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.710  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.710  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.712  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.712  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.712  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.712  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.712  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.712  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.712  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.712  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.712  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.712  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.713  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.713  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.713  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.713  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.713  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.713  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.713  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.713  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.713  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.713  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.713  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.713  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.713  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.714  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.714  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.714  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.714  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.714  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.714  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.714  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.714  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.714  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.714  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.715  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.715  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.715  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.715  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.716  3961  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 16:35:57.716  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:35:57.717  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 16:35:57.718  3961  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 16:35:57.718  3961  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 16:35:57.718  3961  3961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 16:35:57.718  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 16:35:57.718  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 16:35:57.719  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.719  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 16:35:57.719  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 16:35:57.719  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 16:35:57.719  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.719  3961  4025 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 16:35:57.719  3961  3961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 16:35:57.719  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.719  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.719  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 16:35:57.719  3961  4041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 16:35:57.719  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 16:35:57.719  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 16:35:57.720  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.720  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.720  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:35:57.721  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.721  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:35:57.721  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:35:57.721  3961  4041 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 16:35:57.721  3961  4041 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 16:35:57.721  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.721  3961  4041 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 16:35:57.721  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.721  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.721  3961  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 16:35:57.721  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.722  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.722  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.722  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.722  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.722  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.722  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.722  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.722  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.722  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.722  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.722  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.723  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.723  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.723  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.723  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.724  3961  4025 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 16:35:57.724  3961  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 16:35:57.724  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 16:35:57.724  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 16:35:57.725  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.725  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.725  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.725  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.725  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.725  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.725  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.725  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.725  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.725  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.725  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.725  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.725  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.725  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.726  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.727  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.727  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.727  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.731  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.731  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.731  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.731  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.731  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.731  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.731  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.731  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.731  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.731  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.732  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.732  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.732  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.732  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.733  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.733  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.733  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.733  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.734  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:35:57.734  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:35:57.734  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:35:57.734  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:35:57.734  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.734  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.734  3961  4025 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64f8c7b not in the list
08-17 16:35:57.734  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.734  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.734  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:35:57.734  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.734  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.734  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:35:57.735  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:35:57.735  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:35:57.735  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:35:57.736  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:35:57.736  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ece7a98 not in the list
08-17 16:35:57.736  3961  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 16:35:57.737  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 16:35:57.737  3961  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 16:35:57.737  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 16:35:57.737  3961  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 16:35:57.737  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 16:35:57.739  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 16:35:57.739  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 16:35:57.739  3961  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 16:35:57.739  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 16:35:57.740  3961  4025 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 16:35:57.740  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 16:35:57.740  3961  4025 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 16:35:57.740  3961  4025 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 16:35:57.740  3961  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 16:35:57.740  3961  4025 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 16:35:57.741  3961  4025 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 16:35:57.741  3961  4025 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 16:35:57.741  3961  4025 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 16:35:57.741  3961  4025 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 16:35:57.742  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:35:57.742  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc97bba added. We now have 2 listener(s)
08-17 16:35:57.742  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:35:57.744  3961  4025 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 16:35:57.744   872   882 D WifiService: setWifiEnabled: true pid=3961, uid=10000
08-17 16:35:57.744   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 16:35:57.745  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:35:57.745  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1588a6b added. We now have 3 listener(s)
08-17 16:35:57.745  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:35:57.752  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:35:57.753  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a1b9c8 added. We now have 4 listener(s)
08-17 16:35:57.753  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:35:57.755  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:35:57.755  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2273a61 added. We now have 5 listener(s)
08-17 16:35:57.755  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:35:57.757   872  1697 D WifiService: setWifiEnabled: false pid=3961, uid=10000
08-17 16:35:57.757   872  1697 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 16:35:57.762  2608  2625 D BluetoothAdapterState: Current state: ON, message: 23
08-17 16:35:57.762  2608  2625 D BluetoothAdapterProperties: Setting state to 13
08-17 16:35:57.762  2608  2625 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 16:35:57.762  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:35:57.763  2608  2625 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 16:35:57.764  2608  2625 I BluetoothAdapterState: Entering PendingCommandState
08-17 16:35:57.765  2608  2630 D BluetoothAdapterProperties: Scan Mode:20
08-17 16:35:57.765  2608  2625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 16:35:57.766  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.766  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:35:57.767  2608  2608 D BluetoothMapService: onReceive
08-17 16:35:57.767  2608  2608 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 16:35:57.767  2608  2608 D BluetoothMapService: STATE_TURNING_OFF
08-17 16:35:57.767  2608  2608 D BluetoothMapService: MAP Service closeService in
08-17 16:35:57.767  2608  2608 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 16:35:57.767  2608  2608 D ObexServerSockets0: shutdown(block = true)
08-17 16:35:57.768  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.768  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.768  2608  2608 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 16:35:57.768  2608  2608 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 16:35:57.768  2608  2761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 16:35:57.768  2608  2762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 16:35:57.769  2608  2608 I BtOppRfcommListener: stopping Accept Thread
08-17 16:35:57.769  2608  3553 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 16:35:57.769  2608  2745 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 16:35:57.769  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:35:57.771  2608  3553 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 16:35:57.771  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.774  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.775  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 16:35:57.776   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 16:35:57.776   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 16:35:57.777   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 16:35:57.777   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 16:35:57.777  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:35:57.777  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:35:57.777  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.777  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:35:57.780  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.782  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.783  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.792   872   885 I ActivityManager: Start proc 4044:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 16:35:57.794  2608  2608 D HeadsetService: Received stop request...Stopping profile...
08-17 16:35:57.796   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:35:57.796   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:35:57.796  1899  2273 D BluetoothHeadset: Proxy object disconnected
08-17 16:35:57.797  1358  1383 D BluetoothHeadset: Proxy object disconnected
08-17 16:35:57.798   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:35:57.798  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-17 16:35:57.800  2608  2608 D A2dpService: Received stop request...Stopping profile...
08-17 16:35:57.800   872  1865 D DhcpClient: Clearing IP address
08-17 16:35:57.800  2608  2752 D A2dpStateMachine: Exit Disconnected: -1
08-17 16:35:57.800   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-17 16:35:57.802  1358  1358 D BluetoothA2dp: Proxy object disconnected
,08-17 16:35:57.802   872   872 D BluetoothA2dp: Proxy object disconnected
,08-17 16:35:57.802   371   870 D CommandListener: Setting iface cfg
,08-17 16:35:57.803  2608  2608 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:35:57.803  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:57.803  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:35:57.803  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:35:57.804  2608  2608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 16:35:57.804  1519  2190 V NativeCrypto: Read error: ssl=0xaeb2ac00: I/O error during system call, Connection timed out
,08-17 16:35:57.805  2608  2630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 16:35:57.805  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:35:57.805  2608  2608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 16:35:57.805  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 16:35:57.805  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 16:35:57.805  2608  2630 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-17 16:35:57.806  2608  2608 D HidService: Received stop request...Stopping profile...
,08-17 16:35:57.806  2608  2608 D HidService: Stopping Bluetooth HidService
08-17 16:35:57.807  1358  1358 D BluetoothInputDevice: Proxy object disconnected
,08-17 16:35:57.807  1358  1358 D HidProfile: Bluetooth service disconnected
,08-17 16:35:57.808  2608  2608 D HealthService: Received stop request...Stopping profile...
,08-17 16:35:57.811  2608  2608 D PanService: Received stop request...Stopping profile...
08-17 16:35:57.812  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 16:35:57.812  1358  1358 D PanProfile: Bluetooth service disconnected
08-17 16:35:57.813  2608  2608 D BluetoothMapService: Received stop request...Stopping profile...
08-17 16:35:57.813  2608  2608 D BluetoothMapService: stop()
08-17 16:35:57.813  2608  2608 D BluetoothMapAppObserver: deinitObservers()
08-17 16:35:57.814  2608  2608 D BluetoothMapAppObserver: removeReceiver()
08-17 16:35:57.814  1519  2190 V NativeCrypto: SSL shutdown failed: ssl=0xaeb2ac00: I/O error during system call, Broken pipe
,08-17 16:35:57.816  1358  1358 D BluetoothMap: Proxy object disconnected
08-17 16:35:57.816  1358  1358 D MapProfile: Bluetooth service disconnected
08-17 16:35:57.817  2608  2608 V BluetoothAdapterState: isTurningOff()=true
08-17 16:35:57.817  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:57.817  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:35:57.817  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:35:57.817   872  3114 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-17 16:35:57.818   872  1858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-17 16:35:57.818  2608  2630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 16:35:57.818  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:35:57.818  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:35:57.818  2608  2721 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 16:35:57.818  2608  2721 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 16:35:57.818  2608  2721 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 16:35:57.818  2608  2721 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 16:35:57.818  2608  2608 V BluetoothAdapterState: isTurningOff()=true
08-17 16:35:57.818  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:57.818  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:35:57.818  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:35:57.819  2608  2608 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 16:35:57.819  2608  2630 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 16:35:57.819  2608  2608 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 16:35:57.819  2608  2608 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:35:57.820  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:57.820  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:35:57.820  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:35:57.820  2608  2608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 16:35:57.820  2608  2630 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 16:35:57.821  2608  2608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 16:35:57.822  2608  2608 V BluetoothAdapterState: isTurningOff()=true
08-17 16:35:57.822  2608  2608 V BluetoothAdapterState: isTurningOn()=false
,08-17 16:35:57.822  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:35:57.822  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:35:57.822  2608  2608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 16:35:57.822   872  1858 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 16:35:57.823  2608  2608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 16:35:57.823   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-17 16:35:57.824   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-17 16:35:57.824  2608  2608 D BluetoothMapService: MAP Service closeService in
08-17 16:35:57.824  2608  2608 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:35:57.825   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 16:35:57.824  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:57.829  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:35:57.829   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 16:35:57.830   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 16:35:57.831   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 16:35:57.831   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 16:35:57.831   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 16:35:57.832   394   394 E Parcel  : Reading a NULL string not supported here.
08-17 16:35:57.829  2608  2608 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:35:57.833  2608  2625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-17 16:35:57.833  2608  2625 D BluetoothAdapterProperties: Setting state to 15
08-17 16:35:57.833  2608  2625 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 16:35:57.834   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:35:57.834  1358  1383 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 16:35:57.834   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 16:35:57.834  1899  2273 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 16:35:57.834  1358  1385 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 16:35:57.835  2608  2625 I BluetoothAdapterState: Entering BleOnState
08-17 16:35:57.836  1358  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 16:35:57.837   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:35:57.837  2608  2608 D BluetoothMapService: cleanup()
08-17 16:35:57.837  1358  1370 D BluetoothPan: onBluetoothStateChange on: false
08-17 16:35:57.837  2608  2608 D BluetoothMapService: MAP Service closeService in
08-17 16:35:57.838  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 16:35:57.838   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 16:35:57.839   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 16:35:57.839  1358  1370 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 16:35:57.840  2608  2625 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 16:35:57.840  2608  2625 D BluetoothAdapterProperties: Setting state to 16
08-17 16:35:57.840  2608  2625 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 16:35:57.841  2608  2625 D BluetoothAdapterProperties: onBleDisable
08-17 16:35:57.841  2608  2625 I BluetoothAdapterState: Entering PendingCommandState
08-17 16:35:57.841  2608  2627 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 16:35:57.843  2608  2721 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 16:35:57.843  2608  2721 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:35:57.844  2608  2630 D BluetoothAdapterProperties: Scan Mode:20
08-17 16:35:57.845   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 16:35:57.850  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:35:57.850  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:35:57.850  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.850  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 16:35:57.851   872  1872 D DhcpClient: Receive thread stopped
08-17 16:35:57.852  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:35:57.852  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:35:57.853  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:35:57.853  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17, 16:35:57.854  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.855  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.856  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.856  2150  2354 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 16:35:57.856  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.872   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 16:35:57.873   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:35:57.886  4044  4044 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 16:35:57.889   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:35:57.890   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 16:35:57.890   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:35:57.892   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 16:35:57.895  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:35:57.896  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:35:57.896  3575  3575 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d8b9e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 16:35:57.905  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 16:35:57.909   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41c95c2:true
,08-17 16:35:57.911  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 16:35:57.925   872  1697 I ActivityManager: Start proc 4065:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 16:35:57.934  4044  4044 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 16:35:57.934   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-17 16:35:57.935   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 16:35:57.937  4044  4044 D BluetoothMap: Create BluetoothMap proxy object
,08-17 16:35:57.943  4044  4044 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 16:35:57.954  4065  4065 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-17 16:35:57.957  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-17 16:35:57.964   872  2056 I ActivityManager: Killing 3119:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 16:35:58.046  2608  2630 I bt_hci  : shut_down
,08-17 16:35:58.046  2608  2637 D bt_hwcfg: hw_epilog_process
,08-17 16:35:58.050  2608  2637 I bt_vendor: low_power_mode_cb
,08-17 16:35:58.072  2608  2637 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 16:35:58.072  2608  2637 I bt_vendor: epilog_cb
08-17 16:35:58.073  2608  2637 I bt_hci  : epilog_finished_callback
,08-17 16:35:58.076  2608  2630 I bt_hci_h4: hal_close
,08-17 16:35:58.077  2608  2630 I bt_userial_vendor: device fd = 51 close
,08-17 16:35:58.164  4065  4065 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.164  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 16:35:58.165  4065  4065 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.165  4065  4065 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.165  4065  4065 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.165  4065  4065 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.165  4065  4065 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.165  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.166  4065  4065 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.166  4065  4065 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:35:58.166  4065  4065 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:35:58.181  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 16:35:58.196  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 16:35:58.202  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-17 16:35:58.213  2608  2627 D bt_stack_manager: event_shut_down_stack finished.
08-17 16:35:58.213  2608  2625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-17 16:35:58.221  3961  3961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 16:35:58.230   872  1695 I ActivityManager: Start proc 4097:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-17 16:35:58.231   872  1695 I ActivityManager: Killing 3575:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 16:35:58.339  4065  4090 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 16:35:58.347  2608  2608 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 16:35:58.348  2608  2625 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 16:35:58.352  2608  2608 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 16:35:58.352  2608  2608 D BtGatt.GattService: stop()
,08-17 16:35:58.353  2608  2608 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 16:35:58.372  2608  2608 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:35:58.373  2608  2608 V BluetoothAdapterState: isTurningOn()=false
08-17 16:35:58.373  2608  2608 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:35:58.373  2608  2608 V BluetoothAdapterState: isBleTurningOff()=true
08-17 16:35:58.374  2608  2625 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 16:35:58.375  2608  2625 D BluetoothAdapterProperties: Setting state to 10
08-17 16:35:58.375  2608  2625 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 16:35:58.376  2608  2625 I BluetoothAdapterState: Entering OffState
08-17 16:35:58.378   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 16:35:58.392  4097  4097 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 16:35:58.395  2608  2608 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 16:35:58.395  2608  2608 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 16:35:58.395  2608  2608 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 16:35:58.397  2608  2627 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-17 16:35:58.399  2608  2627 D bt_stack_manager: event_clean_up_stack finished.
,08-17 16:35:58.416  2608  2608 I art     : System.exit called, status: 0
,08-17 16:35:58.416  2608  2608 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 16:35:58.430   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f691504:true
,08-17 16:35:58.478   872  1372 I ActivityManager: Process com.android.bluetooth (pid 2608) has died
,08-17 16:35:58.504  4097  4097 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 16:35:58.519  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 16:35:58.526  1745  1745 D SystemUpdateService: onCreate
,08-17 16:35:58.531  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 16:35:58.533  1745  4125 I SystemUpdateService: active receiver: enabled
,08-17 16:35:58.536  1745  4125 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 16:35:58.542  1745  4125 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-17 16:35:58.542  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 16:35:58.542  1745  4125 I SystemUpdateService: now status is 0 (complete)
08-17 16:35:58.542  1745  4125 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 16:35:58.542  1745  4125 I SystemUpdateService: file has been verified
08-17 16:35:58.543  1745  4125 I SystemUpdateService: OTA package size = 12249756
,08-17 16:35:58.543  1745  2410 I iu.UploadsManager: num queued entries: 0
,08-17 16:35:58.546  1745  2410 I iu.UploadsManager: num updated entries: 0
,08-17 16:35:58.552  1745  2410 I iu.SyncManager: NEXT; no task
,08-17 16:35:58.556  1745  4125 I SystemUpdateService: showing system update notification
,08-17 16:35:58.557  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 16:35:58.559  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 16:35:58.580   872  3114 I ActivityManager: Start proc 4127:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 16:35:58.582  1745  1745 D SystemUpdateService: onDestroy
,08-17 16:35:58.619  4127  4127 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 16:35:58.622  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:35:58.627  4127  4127 D SprintDMHelper: simOperator: 
,08-17 16:35:58.627  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 16:35:58.648   872  3114 I ActivityManager: Start proc 4139:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 16:35:58.652   872  3114 I ActivityManager: Killing 3763:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-17 16:35:58.780   872  1695 I ActivityManager: Start proc 4154:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 16:35:58.783  3650  4153 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
08-17 16:35:58.785   872  1372 I ActivityManager: Killing 3614:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 16:35:58.864  4154  4154 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 16:35:58.927  4154  4154 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 16:35:58.927  4154  4154 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 16:35:58.927  4154  4154 I GAv4    :   adb logcat -s GAv4
,08-17 16:35:58.942  4154  4154 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 16:35:58.950  4154  4154 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 16:35:58.979  4154  4171 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 16:35:59.088  4154  4154 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 16:35:59.133  4154  4154 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 16:35:59.144  4154  4154 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5650-5652)
,08-17 16:35:59.144  4154  4154 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 16:35:59.154  4154  4154 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f02184e}
08-17 16:35:59.155  4154  4154 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 16:35:59.155  4154  4154 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 16:35:59.168  4154  4154 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 16:35:59.169  4154  4154 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 16:35:59.184  4154  4154 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 16:35:59.201  4154  4154 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 16:35:59.201  4154  4154 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 16:35:59.201  4154  4154 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 16:35:59.201  4154  4154 I Adreno  : Build Date                       : 10/20/15
08-17 16:35:59.201  4154  4154 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 16:35:59.201  4154  4154 I Adreno  : Local Branch                     : M14
08-17 16:35:59.201  4154  4154 I Adreno  : Remote Branch                    : 
08-17 16:35:59.201  4154  4154 I Adreno  : Remote Branch                    : 
08-17 16:35:59.201  4154  4154 I Adreno  : Reconstruct Branch               : 
,08-17 16:35:59.274  4154  4154 I NSApplication: Starting up...
,08-17 16:35:59.300  4154  4200 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 16:35:59.304   872  1372 I ActivityManager: Start proc 4205:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 16:35:59.305   872  1372 I ActivityManager: Killing 3802:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-17 16:35:59.381  4205  4205 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 16:35:59.559   872  1372 I ActivityManager: Killing 1699:android.process.acore/u0a5 (adj 15): empty #17
,08-17 16:36:00.774   872   882 D WifiService: setWifiEnabled: true pid=3961, uid=10000
,08-17 16:36:00.775   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 16:36:00.795   872  1301 D WifiConfigStore: Loading config and enabling all networks 
08-17 16:36:00.800  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:00.800  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:00.801  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:00.801  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:00.804  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:00.805  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:00.805  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:00.805  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:00.843   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-17 16:36:00.845   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 16:36:00.846   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 16:36:00.848   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 16:36:00.848   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 16:36:00.848   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 16:36:00.848   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 16:36:00.870   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 16:36:00.873   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:00.873   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.94 rxSuccessRate=7.56 delta 1000 -> 1000
,08-17 16:36:00.875   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 16:36:00.876   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 16:36:00.883   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 16:36:00.884   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 16:36:00.894   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 16:36:00.894   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:00.924   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 16:36:01.000   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 16:36:01.005  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 16:36:01.427  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 16:36:01.472  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 16:36:01.473  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 16:36:01.485   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 16:36:01.500   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 16:36:01.501   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 16:36:01.501   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 16:36:01.534   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:01.559   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:01.561   872  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 16:36:01.583   872  1303 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 16:36:01.588   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 16:36:01.609   872  4228 D DhcpClient: Receive thread started
,08-17 16:36:01.692   872  1301 E native  : do suspend false
,08-17 16:36:01.713   872  1865 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 16:36:01.730   872  4228 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172675, domain null
,08-17 16:36:01.731   872  1865 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172675 seconds
,08-17 16:36:01.736   872  1865 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 16:36:01.749   872  4228 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 16:36:01.750   872  1865 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 16:36:01.757   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:01.768   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 16:36:01.769   872  1865 D DhcpClient: Scheduling renewal in 86399s
,08-17 16:36:01.787   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 16:36:01.790   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:01.791   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 16:36:01.792   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 16:36:01.796   872  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 16:36:01.807   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 16:36:01.860   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 16:36:01.860   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
08-17 16:36:01.861   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 16:36:01.862   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 16:36:01.863   872  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 16:36:01.878   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:01.882   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 16:36:01.882   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:01.882   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:01.882   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 16:36:01.882   872  1303 D ConnectivityService:    accepting network in place of null
,08-17 16:36:01.883   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 16:36:01.883   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 16:36:01.889   872  4227 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148398, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 16:36:01.928   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:01.960   872  4226 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:815::200e
,08-17 16:36:01.963   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:01.971   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 16:36:01.971   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:01.978   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:01.982   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 16:36:01.988  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:01.988  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:36:01.989  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:01.989  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:01.992  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:01.993  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:01.993  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:01.993  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:02.008  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 16:36:02.011  1745  1745 D SystemUpdateService: onCreate
,08-17 16:36:02.014  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 16:36:02.017  1745  4239 I SystemUpdateService: active receiver: enabled
,08-17 16:36:02.023  1745  4239 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 16:36:02.028  1745  4239 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 16:36:02.028  1745  4239 I SystemUpdateService: now status is 0 (complete)
,08-17 16:36:02.028  1745  4239 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 16:36:02.029  1745  4239 I SystemUpdateService: file has been verified
08-17 16:36:02.029  1745  4239 I SystemUpdateService: OTA package size = 12249756
,08-17 16:36:02.035   872  4226 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 14:36:02 GMT], X-Android-Received-Millis=[1471444562035], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471444562011]}
,08-17 16:36:02.036   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 16:36:02.037   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-17 16:36:02.037   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 16:36:02.037  1745  4239 I SystemUpdateService: showing system update notification
,08-17 16:36:02.038   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 16:36:02.042  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 16:36:02.044  1745  2410 I iu.UploadsManager: num queued entries: 0
08-17 16:36:02.045  1745  2410 I iu.UploadsManager: num updated entries: 0
,08-17 16:36:02.047  1745  2410 I iu.SyncManager: NEXT; no task
,08-17 16:36:02.052  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 16:36:02.053  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 16:36:02.053  1745  1745 D SystemUpdateService: onDestroy
08-17 16:36:02.053  1745  4243 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-17 16:36:02.054  1745  4243 W BaseAppContext: Using Auth Proxy for data requests.
08-17 16:36:02.055  1745  4243 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 16:36:02.066   872   884 I ActivityManager: Start proc 4246:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-17 16:36:02.070  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:02.076  4127  4127 D SprintDMHelper: simOperator: 
,08-17 16:36:02.076  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 16:36:02.076  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 16:36:02.078  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:02.105  4246  4246 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-17 16:36:02.113  1519  2063 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-17 16:36:02.113  1519  2063 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 16:36:02.113  1519  2063 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:36:02.113  1519  2063 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:02.128  1745  4243 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-17 16:36:02.187  4246  4246 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-17 16:36:02.193  1519  3118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 16:36:02.193  1519  3118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 16:36:02.194  1519  3118 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 16:36:02.194  1519  3118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:02.196  4246  4246 I BooksApp: Created application version: 3.6.9 (30609)
,08-17 16:36:02.204  3718  4260 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 16:36:02.204  3718  4260 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jdm.a(PG:82)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jcs.o(PG:406)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jcn.a(PG:1379)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jcs.i(PG:143)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at blb.a(PG:3937)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at czp.a(PG:18188)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at czp.a(PG:9081)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at czq.run(PG:1686)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:36:02.204  3718  4260 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jdj.a(PG:4091)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jdj.a(PG:1125)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jdm.a(PG:77)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	... 12 more
08-17 16:36:02.204  3718  4260 E HttpOperation: Caused by: faj: BadAuthentication
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at fal.a(PG:38)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	at jdj.a(PG:4089)
08-17 16:36:02.204  3718  4260 E HttpOperation: 	... 14 more
,08-17 16:36:02.222  3650  4259 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 16:36:02.230  1519  3118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 16:36:02.230  1519  3118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 16:36:02.230  1519  3118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:36:02.230  1519  3118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:02.250  3718  4260 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 16:36:02.250  3718  4260 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jdm.a(PG:82)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jcs.o(PG:406)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jcn.a(PG:1379)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jcs.i(PG:143)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at hec.a(PG:42)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at hee.a(PG:102)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at czr.a(PG:65)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at kka.a(PG:108)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at czp.a(PG:19176)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at czp.a(PG:9081)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at czq.run(PG:1686)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:36:02.250  3718  4260 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jdj.a(PG:4091)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jdj.a(PG:1125)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jdm.a(PG:77)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	... 15 more
08-17 16:36:02.250  3718  4260 E HttpOperation: Caused by: faj: BadAuthentication
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at fal.a(PG:38)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	at jdj.a(PG:4089)
08-17 16:36:02.250  3718  4260 E HttpOperation: 	... 17 more
,08-17 16:36:02.250  3718  4260 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 16:36:02.250  3718  4260 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at hec.a(PG:42)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at hee.a(PG:102)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at czr.a(PG:65)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at kka.a(PG:108)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	... 15 more
08-17 16:36:02.250  3718  4260 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at fal.a(PG:38)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 16:36:02.250  3718  4260 E ExperimentLoader: 	... 17 more
,08-17 16:36:02.273  4246  4272 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 16:36:02.337   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130155, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-17 16:36:02.417  4246  4280 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 16:36:02.486  1519  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 16:36:02.486  1519  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 16:36:02.486  1519  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 16:36:02.486  1519  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:02.549  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 16:36:02.549  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 16:36:02.549  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:36:02.549  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:02.567  4246  4280 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 16:36:02.569  4246  4272 E BooksSync: Soft error
08-17 16:36:02.569  4246  4272 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 16:36:02.569  4246  4272 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 16:36:02.569  4246  4272 E BooksSync: Sync error
08-17 16:36:02.569  4246  4272 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 16:36:02.569  4246  4272 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 16:36:02.569  4246  4272 I BooksSync: Finished books sync
,08-17 16:36:02.580   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130472, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 16:36:02.586   872   883 I ActivityManager: Killing 3839:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 16:36:02.970   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 16:36:03.338   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 16:36:03.350  1845  1845 I Keyboard.Facilitator: onFinishInput()
,08-17 16:36:03.362   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 16:36:03.362   872   892 I Adreno  : Build Date                       : 10/20/15
08-17 16:36:03.362   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 16:36:03.362   872   892 I Adreno  : Local Branch                     : M14
08-17 16:36:03.362   872   892 I Adreno  : Remote Branch                    : 
08-17 16:36:03.362   872   892 I Adreno  : Remote Branch                    : 
08-17 16:36:03.362   872   892 I Adreno  : Reconstruct Branch               : 
,08-17 16:36:03.405   280   294 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (200 us)
,08-17 16:36:03.482   872  2198 I ActivityManager: Killing 3856:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 16:36:03.783   872  1695 D WifiService: setWifiEnabled: false pid=3961, uid=10000
,08-17 16:36:03.787   872  1695 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 16:36:03.819  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 16:36:03.823   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 16:36:03.823   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 16:36:03.823   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 16:36:03.823   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:03.838   872  1865 D DhcpClient: Clearing IP address
08-17 16:36:03.839   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 16:36:03.842   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:03.850  1519  4267 V NativeCrypto: Read error: ssl=0x9a227400: I/O error during system call, Connection timed out
,08-17 16:36:03.853  1519  4267 V NativeCrypto: SSL shutdown failed: ssl=0x9a227400: I/O error during system call, Broken pipe
,08-17 16:36:03.859   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 16:36:03.859   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-17 16:36:03.860   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-17 16:36:03.861   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 16:36:03.864   394   394 E Parcel  : Reading a NULL string not supported here.
,08-17 16:36:03.865   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 16:36:03.876   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 16:36:03.878   872  4228 D DhcpClient: Receive thread stopped
,08-17 16:36:03.881   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 16:36:03.885   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 16:36:03.894  2150  2354 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 16:36:03.895  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:03.895  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:03.895  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:03.895  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 16:36:03.896  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:03.896  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:03.896  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:03.896  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:03.908   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:03.934   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:03.937   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 16:36:03.937   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:03.939   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 16:36:03.943  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:03.945  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:03.962  3961  3961 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 16:36:03.962  3961  3961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 16:36:03.990   872   892 W ProcessCpuTracker: Skipping unknown process pid 4292
,08-17 16:36:03.991   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 16:36:03.995  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 16:36:03.999   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 16:36:04.000  3961  3961 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@667db60 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2736247, 16908290=android.view.AbsSavedState$1@2736247}, android:focusedViewId=100}]}]
08-17 16:36:04.000  3961  3961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 16:36:04.001  3961  3961 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 16:36:04.001  3961  3961 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 16:36:04.003   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-17 16:36:04.003   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-17 16:36:04.003   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 16:36:04.024   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-17 16:36:04.024   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 16:36:04.025  1745  1745 D SystemUpdateService: onCreate
,08-17 16:36:04.027  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 16:36:04.028   872   881 I art     : Background partial concurrent mark sweep GC freed 64466(3MB) AllocSpace objects, 10(288KB) LOS objects, 33% free, 29MB/43MB, paused 7.396ms total 73.044ms
,08-17 16:36:04.030  1745  4295 I SystemUpdateService: active receiver: enabled
,08-17 16:36:04.035  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 16:36:04.041  1745  2410 I iu.UploadsManager: num queued entries: 0
,08-17 16:36:04.043  1745  4295 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 16:36:04.045  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 16:36:04.046  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 16:36:04.047  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:04.049  1745  2410 I iu.UploadsManager: num updated entries: 0
,08-17 16:36:04.050  1745  4295 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 16:36:04.050  1745  4295 I SystemUpdateService: now status is 0 (complete)
,08-17 16:36:04.050  1745  4295 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 16:36:04.050  1745  4295 I SystemUpdateService: file has been verified
,08-17 16:36:04.051  4127  4127 D SprintDMHelper: simOperator: 
,08-17 16:36:04.052  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 16:36:04.058  1745  4295 I SystemUpdateService: OTA package size = 12249756
,08-17 16:36:04.070  3650  4298 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 16:36:04.074  1745  2410 I iu.SyncManager: NEXT; no task
,08-17 16:36:04.080  1745  4295 I SystemUpdateService: showing system update notification
,08-17 16:36:04.089  1745  1745 D SystemUpdateService: onDestroy
,08-17 16:36:04.229   280   336 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 16:36:04.231   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 16:36:04.236   872  1327 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
,08-17 16:36:04.238   872   892 I DreamManagerService: Entering dreamland.
,08-17 16:36:04.240   872   892 I PowerManagerService: Dozing...
,08-17 16:36:04.241   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 16:36:04.299   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 16:36:04.300   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 16:36:04.305   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 16:36:04.312   872  1301 E native  : do suspend false
,08-17 16:36:04.326  1891  4301 D NfcService: Discovery configuration equal, not updating.
,08-17 16:36:04.351   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 16:36:04.358   872  1301 E native  : do suspend true
,08-17 16:36:04.436   375  1309 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 16:36:04.436   375  1309 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 16:36:06.844   872   889 I ActivityManager: Start proc 4305:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 16:36:06.973  4305  4305 D AdapterServiceConfig: Adding HeadsetService
,08-17 16:36:06.974  4305  4305 D AdapterServiceConfig: Adding A2dpService
08-17 16:36:06.974  4305  4305 D AdapterServiceConfig: Adding HidService
,08-17 16:36:06.974  4305  4305 D AdapterServiceConfig: Adding HealthService
08-17 16:36:06.974  4305  4305 D AdapterServiceConfig: Adding PanService
08-17 16:36:06.974  4305  4305 D AdapterServiceConfig: Adding GattService
,08-17 16:36:06.975  4305  4305 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 16:36:06.991   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@868174d:true
08-17 16:36:06.991  4305  4305 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 16:36:06.996  4305  4305 I bt_bluedroid: init
,08-17 16:36:06.997  4305  4317 I BluetoothAdapterState: Entering OffState
,08-17 16:36:07.002  4305  4318 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 16:36:07.003  4305  4318 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 16:36:07.004  4305  4318 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 16:36:07.004  4305  4318 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 16:36:07.006  4305  4305 I bt_bluedroid: get_profile_interface socket
,08-17 16:36:07.012  4305  4305 I bt_bluedroid: get_profile_interface sdp
,08-17 16:36:07.012  4305  4321 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 16:36:07.015  4305  4321 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 16:36:07.019  4305  4316 I bt_bluedroid: config_hci_snoop_log
,08-17 16:36:07.023   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 16:36:07.033  4305  4317 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 16:36:07.033  4305  4317 D BluetoothAdapterProperties: Setting state to 14
08-17 16:36:07.034  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 16:36:07.038  4305  4317 D BluetoothBondStateMachine: make
,08-17 16:36:07.042  4305  4322 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 16:36:07.050  4305  4305 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 16:36:07.051  4305  4317 I BluetoothAdapterState: Entering PendingCommandState
,08-17 16:36:07.053  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:07.054  4305  4305 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 16:36:07.054  4305  4305 D BtGatt.GattService: Received start request. Starting profile...
08-17 16:36:07.055  4305  4305 D BtGatt.GattService: start()
,08-17 16:36:07.055  4305  4305 I bt_bluedroid: get_profile_interface gatt
08-17 16:36:07.056  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:36:07.056  4305  4305 D BtGatt.AdvertiseManager: advertise manager created
,08-17 16:36:07.063  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:07.063  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:07.063  4305  4305 V BluetoothAdapterState: isBleTurningOn()=true
08-17 16:36:07.063  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:07.064  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 16:36:07.064  4305  4317 I bt_bluedroid: enable
08-17 16:36:07.064  4305  4318 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 16:36:07.065  4305  4318 I bt_hci  : start_up
,08-17 16:36:07.085  4305  4318 I bt_vendor: alloc value 0xb399f189
,08-17 16:36:07.085  4305  4318 I bt_vendor: init
,08-17 16:36:07.085  4305  4318 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 16:36:07.086  4305  4318 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 16:36:07.193  4305  4318 D bt_hci  : start_up starting async portion
,08-17 16:36:07.194  4305  4325 I bt_hci  : event_finish_startup
08-17 16:36:07.194  4305  4325 I bt_hci_h4: hal_open
08-17 16:36:07.194  4305  4325 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 16:36:07.197  4246  4269 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-17 16:36:07.201  4305  4325 I bt_userial_vendor: device fd = 51 open
,08-17 16:36:07.234  4305  4325 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 16:36:07.267  4305  4325 D bt_hwcfg: Chipset BCM4354A2
,08-17 16:36:07.267  4305  4325 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 16:36:07.268  4305  4325 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 16:36:07.905  4305  4325 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 16:36:07.906  4305  4325 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 16:36:07.907  4305  4325 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 16:36:08.023  4305  4325 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 16:36:08.025  4305  4325 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 16:36:08.055  4305  4325 I bt_hwcfg: vendor lib fwcfg completed
,08-17 16:36:08.055  4305  4325 I bt_vendor: firmware callback
,08-17 16:36:08.055  4305  4325 I bt_hci  : firmware_config_callback
,08-17 16:36:08.066  4305  4329 I bt_btu  : btu_task pending for preload complete event
,08-17 16:36:08.067  4305  4329 I bt_btu_task: Bluetooth chip preload is complete
,08-17 16:36:08.067  4305  4329 I bt_btu  : btu_task received preload complete event
,08-17 16:36:08.079  4305  4329 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 16:36:08.080  4305  4329 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 16:36:08.080  4305  4329 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 16:36:08.080  4305  4329 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 16:36:08.081  4305  4329 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 16:36:08.081  4305  4329 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 16:36:08.081  4305  4329 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 16:36:08.081  4305  4329 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 16:36:08.082  4305  4329 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 16:36:08.082  4305  4329 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 16:36:08.082  4305  4329 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 16:36:08.083  4305  4329 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 16:36:08.083  4305  4329 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 16:36:08.083  4305  4329 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 16:36:08.083  4305  4329 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 16:36:08.217  4305  4329 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391cd9d
,08-17 16:36:08.217  4305  4329 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391cd9d 
,08-17 16:36:08.241  4305  4321 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-17 16:36:08.242  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 16:36:08.243  4305  4321 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 16:36:08.251  4305  4321 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 16:36:08.259  4305  4321 D BluetoothAdapterProperties: Scan Mode:20
,08-17 16:36:08.259  4305  4321 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 16:36:08.260  4305  4321 D bt_hci  : do_postload posting postload work item
,08-17 16:36:08.260  4305  4325 I bt_hci  : event_postload
08-17 16:36:08.260  4305  4325 I bt_vendor: sco_config_cb
08-17 16:36:08.260  4305  4325 I bt_hci  : sco_config_callback postload finished.
08-17 16:36:08.262  4305  4325 I bt_vendor: low_power_mode_cb
08-17 16:36:08.262  4305  4321 D bt_bte_conf: Device ID record 1 : primary
08-17 16:36:08.262  4305  4321 D bt_bte_conf:   vendorId            = 000f
,08-17 16:36:08.262  4305  4321 D bt_bte_conf:   vendorIdSource      = 0001
08-17 16:36:08.262  4305  4321 D bt_bte_conf:   product             = 1200
08-17 16:36:08.262  4305  4321 D bt_bte_conf:   version             = 1436
,08-17 16:36:08.263  4305  4321 D bt_bte_conf:   clientExecutableURL = 
08-17 16:36:08.263  4305  4321 D bt_bte_conf:   serviceDescription  = 
08-17 16:36:08.263  4305  4321 D bt_bte_conf:   documentationURL    = 
,08-17 16:36:08.263  4305  4321 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 16:36:08.263  4305  4318 D bt_stack_manager: event_start_up_stack finished
08-17 16:36:08.264  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 16:36:08.264  4305  4317 D BluetoothAdapterProperties: Setting state to 15
,08-17 16:36:08.264  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 16:36:08.268  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:08.268  4305  4317 I BluetoothAdapterState: Entering BleOnState
,08-17 16:36:08.280  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:08.280  4305  4317 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 16:36:08.280  4305  4317 D BluetoothAdapterProperties: Setting state to 11
08-17 16:36:08.281  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 16:36:08.287  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:08.289  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:08.290  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:08.291  4305  4305 D HeadsetService: Received start request. Starting profile...
,08-17 16:36:08.294  4305  4305 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 16:36:08.295  4305  4305 D HeadsetStateMachine: make
,08-17 16:36:08.301  4305  4317 I BluetoothAdapterState: Entering PendingCommandState
,08-17 16:36:08.303  4305  4305 D HeadsetStateMachine: max_hf_connections = 1
,08-17 16:36:08.303  4305  4305 I bt_bluedroid: get_profile_interface handsfree
,08-17 16:36:08.303  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 16:36:08.304  4305  4321 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 16:36:08.310  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:08.310  4305  4305 D A2dpService: Received start request. Starting profile...
08-17 16:36:08.310  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 16:36:08.311  4305  4305 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 16:36:08.311  4305  4305 I bt_bluedroid: get_profile_interface avrcp
,08-17 16:36:08.318  4305  4305 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 16:36:08.318  4305  4305 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 16:36:08.318  4305  4305 D A2dpStateMachine: make
,08-17 16:36:08.320  4305  4305 I bt_bluedroid: get_profile_interface a2dp
,08-17 16:36:08.321  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 16:36:08.324  4305  4338 D A2dpStateMachine: Enter Disconnected: -2
,08-17 16:36:08.325  4305  4305 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 16:36:08.326  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:08.327  4305  4305 D HidService: Received start request. Starting profile...
,08-17 16:36:08.327  4044  4044 D BluetoothInputDevice: Proxy object connected
08-17 16:36:08.327  4305  4305 I bt_bluedroid: get_profile_interface hidhost
08-17 16:36:08.328  4305  4321 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fe3e5
08-17 16:36:08.328  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 16:36:08.328  4305  4305 D HidService: setHidService(): set to: null
08-17 16:36:08.328  4305  4305 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 16:36:08.329  4044  4044 D HidProfile: Bluetooth service connected
,08-17 16:36:08.329  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:36:08.330  4305  4305 D HealthService: Received start request. Starting profile...
,08-17 16:36:08.332  4305  4305 I bt_bluedroid: get_profile_interface health
,08-17 16:36:08.333  4305  4305 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 16:36:08.334  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:08.335  4305  4305 D PanService: Received start request. Starting profile...
,08-17 16:36:08.335  4305  4305 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 16:36:08.335  4305  4305 I bt_bluedroid: get_profile_interface pan,
,08-17 16:36:08.336  4044  4044 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 16:36:08.336  4305  4321 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 16:36:08.337  4044  4044 D PanProfile: Bluetooth service connected
08-17 16:36:08.339  4305  4305 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:08.341  4305  4305 D BluetoothMapService: Received start request. Starting profile...
,08-17 16:36:08.341  4305  4305 D BluetoothMapService: start()
,08-17 16:36:08.341  4044  4044 D BluetoothMap: Proxy object connected
08-17 16:36:08.342  4044  4044 D MapProfile: Bluetooth service connected
,08-17 16:36:08.342  4044  4044 D BluetoothMap: getConnectedDevices()
,08-17 16:36:08.343  4044  4044 D BluetoothMap: Bluetooth is Not enabled
08-17 16:36:08.343  4305  4305 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-17 16:36:08.344  4305  4305 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 16:36:08.344  4305  4305 D BluetoothMapAppObserver: createReceiver()
08-17 16:36:08.345  4305  4305 D BluetoothMapAppObserver: initObservers()
08-17 16:36:08.345  4305  4305 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 16:36:08.354  4305  4305 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:36:08.354  4305  4305 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:08.354  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:08.354  4305  4336 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 16:36:08.354  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:08.359  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:08.359  4305  4305 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:08.359  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:08.359  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:08.360  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isTurningOn()=true
,08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:08.361  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:08.362  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 16:36:08.362  4305  4317 D BluetoothAdapterProperties: ScanMode =  20
08-17 16:36:08.362  4305  4317 D BluetoothAdapterProperties: State =  11
,08-17 16:36:08.385  4305  4321 D BluetoothAdapterProperties: Scan Mode:21
,08-17 16:36:08.385  4305  4321 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 16:36:08.386  4305  4317 D BluetoothAdapterProperties: Setting state to 12
,08-17 16:36:08.386  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 16:36:08.387  4044  4054 D BluetoothPan: onBluetoothStateChange on: true
08-17 16:36:08.387   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:08.387  1358  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:08.388  4305  4317 I BluetoothAdapterState: Entering OnState
08-17 16:36:08.389   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:08.389  1899  2273 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:08.390  4044  4056 D BluetoothMap: onBluetoothStateChange: up=true
08-17 16:36:08.391  1358  1370 D BluetoothMap: onBluetoothStateChange: up=true
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:08.391  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:08.394  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:08.398  1358  1385 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 16:36:08.398  1358  1358 D BluetoothMap: Proxy object connected
08-17 16:36:08.398  1358  1358 D MapProfile: Bluetooth service connected
08-17 16:36:08.398  1358  1358 D BluetoothMap: getConnectedDevices()
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:08.399  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 16:36:08.400   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:08.400  4044  4054 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 16:36:08.401  1358  1370 D BluetoothPan: onBluetoothStateChange on: true
,08-17 16:36:08.402  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 16:36:08.402  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 16:36:08.402  1358  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 16:36:08.402  1358  1358 D PanProfile: Bluetooth service connected
,08-17 16:36:08.404   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 16:36:08.405  1358  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 16:36:08.405   872   872 D BluetoothA2dp: Proxy object connected
,08-17 16:36:08.405  1358  1358 D BluetoothA2dp: Proxy object connected
08-17 16:36:08.407  1358  1358 D BluetoothInputDevice: Proxy object connected
08-17 16:36:08.407  1358  1358 D HidProfile: Bluetooth service connected
08-17 16:36:08.407  4044  4056 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 16:36:08.409   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 16:36:08.411  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:08.413  4305  4305 D BluetoothMapService: onReceive
08-17 16:36:08.413  4305  4305 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 16:36:08.413  4305  4305 D BluetoothMapService: STATE_ON
08-17 16:36:08.413  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:08.413  4044  4044 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 16:36:08.417  4044  4044 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 16:36:08.422  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 16:36:08.425  4044  4044 D BluetoothA2dp: Proxy object connected,
,08-17 16:36:08.428  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 16:36:08.437  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-17 16:36:08.438  1358  1358 D BluetoothPbap: Proxy object connected
,08-17 16:36:08.438  1358  1358 D PbapServerProfile: Bluetooth service connected
,08-17 16:36:08.440  4044  4044 D BluetoothPbap: Proxy object connected
,08-17 16:36:08.440  4044  4044 D PbapServerProfile: Bluetooth service connected
,08-17 16:36:08.445  4305  4305 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 16:36:08.445  4305  4305 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-17 16:36:08.448  4305  4305 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 16:36:08.451  4305  4305 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 16:36:08.452  4305  4305 D ObexServerSockets: Succeed to create listening sockets 
,08-17 16:36:08.453  4305  4305 D ObexServerSockets0: startAccept()
08-17 16:36:08.453  4305  4305 D ObexServerSockets0: prepareForNewConnect()
,08-17 16:36:08.455  4305  4305 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 16:36:08.455  4305  4305 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 16:36:08.455  4305  4348 D ObexServerSockets0: Accepting socket connection...
08-17 16:36:08.456  4305  4349 D ObexServerSockets0: Accepting socket connection...
08-17 16:36:08.457  4305  4350 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 16:36:08.472  4305  4354 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 16:36:08.473  4305  4354 I BtOppRfcommListener: Accept thread started.
,08-17 16:36:08.489   872   872 D BluetoothHeadset: Proxy object connected
,08-17 16:36:08.489   872   872 D BluetoothHeadset: Proxy object connected
08-17 16:36:08.489   872   889 D BluetoothHeadset: Proxy object connected
08-17 16:36:08.490  1899  1916 D BluetoothHeadset: Proxy object connected
08-17 16:36:08.490  1899  1911 D BluetoothHeadset: Proxy object connected
08-17 16:36:08.490  1358  1385 D BluetoothHeadset: Proxy object connected
,08-17 16:36:08.490  1358  1358 D HeadsetProfile: Bluetooth service connected
08-17 16:36:08.491   872   872 D BluetoothHeadset: Proxy object connected
,08-17 16:36:08.500   872   889 D BluetoothHeadset: Proxy object connected
,08-17 16:36:08.520  4044  4054 D BluetoothHeadset: Proxy object connected
,08-17 16:36:08.521  4044  4044 D HeadsetProfile: Bluetooth service connected
,08-17 16:36:08.524  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:08.540  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 16:36:08.543  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:08.569  1519  2321 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 16:36:08.570  1519  2321 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 16:36:08.570  1519  2321 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 16:36:08.570  1519  2321 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:08.587  3675  3675 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 16:36:08.588  3675  3675 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 16:36:08.588  3675  3675 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 16:36:09.804  4305  4317 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 16:36:09.804  4305  4317 D BluetoothAdapterProperties: Setting state to 13
08-17 16:36:09.804  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 16:36:09.806  4305  4317 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 16:36:09.811  4305  4317 I BluetoothAdapterState: Entering PendingCommandState
,08-17 16:36:09.819  4305  4305 D BluetoothMapService: onReceive
,08-17 16:36:09.819  4305  4305 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 16:36:09.820  4305  4305 D BluetoothMapService: STATE_TURNING_OFF
,08-17 16:36:09.820  4305  4305 D BluetoothMapService: MAP Service closeService in
,08-17 16:36:09.821  4305  4305 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 16:36:09.821  4305  4305 D ObexServerSockets0: shutdown(block = true)
08-17 16:36:09.822  4305  4348 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 16:36:09.823  4305  4305 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 16:36:09.823  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:09.824  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 16:36:09.824  4305  4349 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 16:36:09.826  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:09.827  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:09.827  4305  4332 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 16:36:09.826  4305  4305 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 16:36:09.830  4305  4321 D BluetoothAdapterProperties: Scan Mode:20
,08-17 16:36:09.831  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 16:36:09.833  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:09.833  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 16:36:09.834  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 16:36:09.834  3961  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 16:36:09.834  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 16:36:09.830  4305  4305 I BtOppRfcommListener: stopping Accept Thread
08-17 16:36:09.835  4305  4354 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 16:36:09.836  4305  4354 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 16:36:09.836  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:09.838  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:09.840  4305  4305 D HeadsetService: Received stop request...Stopping profile...
08-17 16:36:09.841  4044  4044 D DockEventReceiver: finishStartingService: stopping service
08-17 16:36:09.843   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.843   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.844  4044  4056 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.844  4305  4305 D A2dpService: Received stop request...Stopping profile...
08-17 16:36:09.845  4305  4338 D A2dpStateMachine: Exit Disconnected: -1
08-17 16:36:09.845  1899  1990 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.845  1358  1383 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.846  1358  1358 D HeadsetProfile: Bluetooth service disconnected
08-17 16:36:09.846   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 16:36:09.846  4044  4044 D HeadsetProfile: Bluetooth service disconnected
08-17 16:36:09.847   872   872 D BluetoothA2dp: Proxy object disconnected
08-17 16:36:09.847  4044  4044 D BluetoothA2dp: Proxy object disconnected
08-17 16:36:09.847  1358  1358 D BluetoothA2dp: Proxy object disconnected
08-17 16:36:09.848  4305  4305 D HidService: Received stop request...Stopping profile...
08-17 16:36:09.848  4305  4305 D HidService: Stopping Bluetooth HidService
,08-17 16:36:09.849  4044  4044 D BluetoothInputDevice: Proxy object disconnected
08-17 16:36:09.849  1358  1358 D BluetoothInputDevice: Proxy object disconnected
08-17 16:36:09.849  1358  1358 D HidProfile: Bluetooth service disconnected
08-17 16:36:09.849  4044  4044 D HidProfile: Bluetooth service disconnected
,08-17 16:36:09.851  4305  4305 D HealthService: Received stop request...Stopping profile...
,08-17 16:36:09.854  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 16:36:09.854  4305  4305 D PanService: Received stop request...Stopping profile...
,08-17 16:36:09.856  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 16:36:09.856  1358  1358 D PanProfile: Bluetooth service disconnected
08-17 16:36:09.857  4044  4044 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 16:36:09.857  4044  4044 D PanProfile: Bluetooth service disconnected
08-17 16:36:09.857  4305  4305 V BluetoothAdapterState: isTurningOff()=true
08-17 16:36:09.857  4305  4305 V BluetoothAdapterState: isTurningOn()=false
,08-17 16:36:09.857  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:09.857  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:09.858  4305  4305 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 16:36:09.858  4305  4305 D BluetoothMapService: stop()
08-17 16:36:09.858  4305  4305 D BluetoothMapAppObserver: deinitObservers()
08-17 16:36:09.858  4305  4305 D BluetoothMapAppObserver: removeReceiver()
,08-17 16:36:09.859  4044  4044 D BluetoothMap: Proxy object disconnected
08-17 16:36:09.859  1358  1358 D BluetoothMap: Proxy object disconnected
,08-17 16:36:09.859  1358  1358 D MapProfile: Bluetooth service disconnected
08-17 16:36:09.859  4044  4044 D MapProfile: Bluetooth service disconnected
,08-17 16:36:09.861  4305  4305 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 16:36:09.861  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 16:36:09.861  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:36:09.861  4305  4305 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 16:36:09.861  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 16:36:09.861  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:36:09.862  4305  4321 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-17 16:36:09.862  4305  4305 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:36:09.862  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:09.862  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:09.862  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:09.863  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-17 16:36:09.863  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:36:09.864  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 16:36:09.864  4305  4329 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 16:36:09.864  4305  4329 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 16:36:09.864  4305  4329 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 16:36:09.864  4305  4305 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:36:09.864  4305  4329 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 16:36:09.864  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:09.864  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:09.864  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:09.865  4305  4305 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-17 16:36:09.865  4305  4321 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 16:36:09.865  4305  4305 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 16:36:09.865  4305  4305 V BluetoothAdapterState: isTurningOff()=true
08-17 16:36:09.866  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:09.866  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:09.866  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:09.866  4305  4305 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 16:36:09.866  4305  4321 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 16:36:09.866  4305  4305 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 16:36:09.868  1358  1358 D BluetoothPbap: Proxy object disconnected
08-17 16:36:09.868  4044  4044 D BluetoothPbap: Proxy object disconnected
08-17 16:36:09.868  1358  1358 D PbapServerProfile: Bluetooth service disconnected
08-17 16:36:09.869  4044  4044 D PbapServerProfile: Bluetooth service disconnected
08-17 16:36:09.869  4305  4305 V BluetoothAdapterState: isTurningOff()=true
,08-17 16:36:09.869  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:09.869  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:09.869  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:09.872  4305  4305 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 16:36:09.872  4305  4305 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 16:36:09.872  4305  4305 D BluetoothMapService: MAP Service closeService in
,08-17 16:36:09.872  4305  4305 V BluetoothAdapterState: isTurningOff()=true
08-17 16:36:09.872  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:09.873  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:09.873  4305  4305 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:09.873  4305  4305 D BluetoothMapService: cleanup()
08-17 16:36:09.873  4305  4305 D BluetoothMapService: MAP Service closeService in
08-17 16:36:09.873  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-17 16:36:09.873  4305  4317 D BluetoothAdapterProperties: Setting state to 15
,08-17 16:36:09.873  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 16:36:09.874  4305  4317 I BluetoothAdapterState: Entering BleOnState
,08-17 16:36:09.875  4044  4056 D BluetoothPan: onBluetoothStateChange on: false
08-17 16:36:09.876   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:36:09.876  4044  4054 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:36:09.877  1358  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:36:09.877   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:36:09.877  1899  2202 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 16:36:09.877  4044  4056 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 16:36:09.878  1358  1370 D BluetoothMap: onBluetoothStateChange: up=false
08-17 16:36:09.879  1358  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 16:36:09.879   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 16:36:09.879  4044  4054 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 16:36:09.880  1358  1385 D BluetoothPan: onBluetoothStateChange on: false
08-17 16:36:09.880  1358  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 16:36:09.881   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 16:36:09.881  1358  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 16:36:09.882  4044  4056 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 16:36:09.883  4044  4054 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 16:36:09.883  4305  4317 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-17 16:36:09.883  4305  4317 D BluetoothAdapterProperties: Setting state to 16
08-17 16:36:09.883  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 16:36:09.884  4305  4317 D BluetoothAdapterProperties: onBleDisable,
08-17 16:36:09.884  4305  4317 I BluetoothAdapterState: Entering PendingCommandState
08-17 16:36:09.884  4305  4318 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 16:36:09.886  4305  4329 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms,
,08-17 16:36:09.886  4305  4329 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 16:36:09.886  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:09.887  4305  4321 D BluetoothAdapterProperties: Scan Mode:20
,08-17 16:36:09.887   872  1303 D ConnectivityService: handlePromptUnvalidated 101
08-17 16:36:09.888  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:09.889  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 16:36:09.889  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 16:36:09.890  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:09.894  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 16:36:09.904  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,08-17 16:36:10.087  4305  4321 I bt_hci  : shut_down
,08-17 16:36:10.105  4305  4325 I bt_vendor: low_power_mode_cb
,08-17 16:36:10.109  4305  4325 D bt_hwcfg: hw_epilog_process
,08-17 16:36:10.123  4305  4325 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 16:36:10.123  4305  4325 I bt_vendor: epilog_cb
,08-17 16:36:10.123  4305  4325 I bt_hci  : epilog_finished_callback
,08-17 16:36:10.131  4305  4321 I bt_hci_h4: hal_close
,08-17 16:36:10.132  4305  4321 I bt_userial_vendor: device fd = 51 close
,08-17 16:36:10.269  4305  4318 D bt_stack_manager: event_shut_down_stack finished.
,08-17 16:36:10.270  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 16:36:10.276  4305  4305 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 16:36:10.277  4305  4317 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 16:36:10.278  4305  4305 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 16:36:10.278  4305  4305 D BtGatt.GattService: stop()
08-17 16:36:10.278  4305  4305 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 16:36:10.283  4305  4305 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:10.283  4305  4305 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:10.283  4305  4305 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:10.284  4305  4305 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 16:36:10.284  4305  4317 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 16:36:10.285  4305  4317 D BluetoothAdapterProperties: Setting state to 10
08-17 16:36:10.286  4305  4317 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 16:36:10.288  4305  4317 I BluetoothAdapterState: Entering OffState
,08-17 16:36:10.293   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 16:36:10.315  4305  4305 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 16:36:10.315  4305  4305 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 16:36:10.315  4305  4318 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 16:36:10.319  4305  4318 D bt_stack_manager: event_clean_up_stack finished.
,08-17 16:36:10.319  4305  4305 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 16:36:10.322  4305  4305 I art     : System.exit called, status: 0
,08-17 16:36:10.322  4305  4305 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 16:36:10.358   872  1995 I ActivityManager: Process com.android.bluetooth (pid 4305) has died
,08-17 16:36:12.273  3675  3686 D Finsky  : [309] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-17 16:36:12.289  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:12.341  1519  2359 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-17 16:36:12.341  1519  2359 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-17 16:36:12.342  1519  2359 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:36:12.342  1519  2359 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:12.380  3675  3686 D Finsky  : [309] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-17 16:36:12.685  2150  2806 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 16:36:12.800  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 16:36:12.800  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:15.808  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:15.808  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cfcaa74 added. We now have 6 listener(s)
,08-17 16:36:15.809  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:15.813  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:15.814  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3c1b9d added. We now have 7 listener(s)
,08-17 16:36:15.815  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:15.816  3961  4025 I System.out: IsBluetoothEnabled
,08-17 16:36:15.828  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:15.866   872   889 I ActivityManager: Start proc 4366:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 16:36:15.977  4366  4366 D AdapterServiceConfig: Adding HeadsetService
,08-17 16:36:15.977  4366  4366 D AdapterServiceConfig: Adding A2dpService
,08-17 16:36:15.978  4366  4366 D AdapterServiceConfig: Adding HidService
08-17 16:36:15.978  4366  4366 D AdapterServiceConfig: Adding HealthService
,08-17 16:36:15.978  4366  4366 D AdapterServiceConfig: Adding PanService
08-17 16:36:15.978  4366  4366 D AdapterServiceConfig: Adding GattService
,08-17 16:36:15.978  4366  4366 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 16:36:15.996  4366  4366 D BluetoothAdapterState: make() - Creating AdapterState
08-17 16:36:15.996   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f68c17:true
,08-17 16:36:16.001  4366  4366 I bt_bluedroid: init
,08-17 16:36:16.002  4366  4378 I BluetoothAdapterState: Entering OffState
,08-17 16:36:16.008  4366  4379 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 16:36:16.009  4366  4379 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 16:36:16.009  4366  4379 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 16:36:16.009  4366  4379 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 16:36:16.011  4366  4366 I bt_bluedroid: get_profile_interface socket
,08-17 16:36:16.014  4366  4366 I bt_bluedroid: get_profile_interface sdp
,08-17 16:36:16.016  4366  4382 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 16:36:16.020  4366  4382 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 16:36:16.021  4366  4377 I bt_bluedroid: config_hci_snoop_log
,08-17 16:36:16.024   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 16:36:16.029  4366  4378 D BluetoothAdapterState: Current state: OFF, message: 0
08-17 16:36:16.030  4366  4378 D BluetoothAdapterProperties: Setting state to 14
08-17 16:36:16.030  4366  4378 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 16:36:16.035  4366  4378 D BluetoothBondStateMachine: make
,08-17 16:36:16.040  4366  4383 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 16:36:16.050  4366  4378 I BluetoothAdapterState: Entering PendingCommandState
,08-17 16:36:16.054  4366  4366 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 16:36:16.063  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:16.065  4366  4366 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 16:36:16.066  4366  4366 D BtGatt.GattService: Received start request. Starting profile...
,08-17 16:36:16.067  4366  4366 D BtGatt.GattService: start()
08-17 16:36:16.067  4366  4366 I bt_bluedroid: get_profile_interface gatt
,08-17 16:36:16.069  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:16.069  4366  4366 D BtGatt.AdvertiseManager: advertise manager created
,08-17 16:36:16.084  4366  4366 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:36:16.085  4366  4366 V BluetoothAdapterState: isTurningOn()=false
08-17 16:36:16.085  4366  4366 V BluetoothAdapterState: isBleTurningOn()=true
08-17 16:36:16.086  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:16.087  4366  4378 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 16:36:16.087  4366  4378 I bt_bluedroid: enable
08-17 16:36:16.088  4366  4379 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 16:36:16.089  4366  4379 I bt_hci  : start_up
,08-17 16:36:16.109  4366  4379 I bt_vendor: alloc value 0xb399f189
08-17 16:36:16.109  4366  4379 I bt_vendor: init
,08-17 16:36:16.110  4366  4379 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 16:36:16.110  4366  4379 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 16:36:16.220  4366  4379 D bt_hci  : start_up starting async portion
,08-17 16:36:16.221  4366  4386 I bt_hci  : event_finish_startup
08-17 16:36:16.221  4366  4386 I bt_hci_h4: hal_open
08-17 16:36:16.221  4366  4386 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 16:36:16.231  4366  4386 I bt_userial_vendor: device fd = 51 open
,08-17 16:36:16.262  4366  4386 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 16:36:16.294  4366  4386 D bt_hwcfg: Chipset BCM4354A2
,08-17 16:36:16.294  4366  4386 D bt_hwcfg: Target name = [BCM4354A2]
08-17 16:36:16.295  4366  4386 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 16:36:16.965  4366  4386 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 16:36:16.966  4366  4386 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 16:36:16.967  4366  4386 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 16:36:17.083  4366  4386 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 16:36:17.085  4366  4386 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 16:36:17.114  4366  4386 I bt_hwcfg: vendor lib fwcfg completed
,08-17 16:36:17.114  4366  4386 I bt_vendor: firmware callback
08-17 16:36:17.115  4366  4386 I bt_hci  : firmware_config_callback
,08-17 16:36:17.128  4366  4388 I bt_btu  : btu_task pending for preload complete event
,08-17 16:36:17.129  4366  4388 I bt_btu_task: Bluetooth chip preload is complete
,08-17 16:36:17.129  4366  4388 I bt_btu  : btu_task received preload complete event
,08-17 16:36:17.139  4366  4388 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 16:36:17.139  4366  4388 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 16:36:17.140  4366  4388 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 16:36:17.140  4366  4388 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 16:36:17.140  4366  4388 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 16:36:17.141  4366  4388 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 16:36:17.141  4366  4388 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 16:36:17.141  4366  4388 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 16:36:17.141  4366  4388 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 16:36:17.142  4366  4388 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 16:36:17.142  4366  4388 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 16:36:17.142  4366  4388 I         : BTE_InitTraceLevels -- TRC_GATT,
08-17 16:36:17.142  4366  4388 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 16:36:17.143  4366  4388 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 16:36:17.143  4366  4388 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 16:36:17.277  4366  4388 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391cd9d
,08-17 16:36:17.278  4366  4388 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391cd9d 
,08-17 16:36:17.301  4366  4382 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 16:36:17.302  4366  4382 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 16:36:17.303  4366  4382 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 16:36:17.306  4366  4382 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 16:36:17.310  4366  4382 D BluetoothAdapterProperties: Scan Mode:20
,08-17 16:36:17.310  4366  4382 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 16:36:17.310  4366  4382 D bt_hci  : do_postload posting postload work item
,08-17 16:36:17.311  4366  4386 I bt_hci  : event_postload
08-17 16:36:17.311  4366  4386 I bt_vendor: sco_config_cb
08-17 16:36:17.312  4366  4386 I bt_hci  : sco_config_callback postload finished.
08-17 16:36:17.315  4366  4382 D bt_bte_conf: Device ID record 1 : primary
08-17 16:36:17.315  4366  4382 D bt_bte_conf:   vendorId            = 000f
08-17 16:36:17.315  4366  4382 D bt_bte_conf:   vendorIdSource      = 0001
08-17 16:36:17.316  4366  4382 D bt_bte_conf:   product             = 1200
08-17 16:36:17.316  4366  4382 D bt_bte_conf:   version             = 1436
,08-17 16:36:17.316  4366  4382 D bt_bte_conf:   clientExecutableURL = 
08-17 16:36:17.316  4366  4382 D bt_bte_conf:   serviceDescription  = 
08-17 16:36:17.317  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:17.317  4366  4382 D bt_bte_conf:   documentationURL    = 
08-17 16:36:17.317  4366  4382 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 16:36:17.318  4366  4379 D bt_stack_manager: event_start_up_stack finished
08-17 16:36:17.320  4366  4378 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 16:36:17.321  4366  4378 D BluetoothAdapterProperties: Setting state to 15
08-17 16:36:17.321  4366  4378 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 16:36:17.325  4366  4378 I BluetoothAdapterState: Entering BleOnState
,08-17 16:36:17.328  4366  4378 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 16:36:17.328  4366  4378 D BluetoothAdapterProperties: Setting state to 11
08-17 16:36:17.328  4366  4378 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 16:36:17.331  4366  4386 I bt_vendor: low_power_mode_cb
,08-17 16:36:17.335  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:17.336  4366  4366 D HeadsetService: Received start request. Starting profile...
,08-17 16:36:17.339  4366  4366 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 16:36:17.339  4366  4366 D HeadsetStateMachine: make
,08-17 16:36:17.342  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:17.357  4366  4378 I BluetoothAdapterState: Entering PendingCommandState
,08-17 16:36:17.357  4366  4366 D HeadsetStateMachine: max_hf_connections = 1
,08-17 16:36:17.358  4366  4366 I bt_bluedroid: get_profile_interface handsfree
,08-17 16:36:17.358  4366  4382 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 16:36:17.358  4366  4382 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-17 16:36:17.361  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:36:17.361  4366  4366 D A2dpService: Received start request. Starting profile...
,08-17 16:36:17.362  4366  4366 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 16:36:17.362  4366  4366 I bt_bluedroid: get_profile_interface avrcp
,08-17 16:36:17.367  4366  4366 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 16:36:17.368  4366  4366 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 16:36:17.368  4366  4366 D A2dpStateMachine: make
,08-17 16:36:17.369  4366  4366 I bt_bluedroid: get_profile_interface a2dp
,08-17 16:36:17.369  4366  4382 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 16:36:17.370  4366  4397 D A2dpStateMachine: Enter Disconnected: -2
,08-17 16:36:17.372  4366  4366 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 16:36:17.373  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:36:17.373  4366  4366 D HidService: Received start request. Starting profile...
08-17 16:36:17.373  4366  4366 I bt_bluedroid: get_profile_interface hidhost
08-17 16:36:17.373  4366  4382 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fe3e5
08-17 16:36:17.374  4366  4382 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 16:36:17.374  4366  4366 D HidService: setHidService(): set to: null
08-17 16:36:17.375  4366  4366 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 16:36:17.375  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 16:36:17.375  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:17.376  4366  4366 D HealthService: Received start request. Starting profile...
08-17 16:36:17.378  4366  4366 I bt_bluedroid: get_profile_interface health
,08-17 16:36:17.378  4366  4366 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 16:36:17.379  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
08-17 16:36:17.379  4366  4366 D PanService: Received start request. Starting profile...
,08-17 16:36:17.379  4366  4366 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 16:36:17.379  4366  4366 I bt_bluedroid: get_profile_interface pan
08-17 16:36:17.380  4366  4382 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 16:36:17.384  4366  4366 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:17.385  4366  4366 D BluetoothMapService: Received start request. Starting profile...
,08-17 16:36:17.385  4366  4366 D BluetoothMapService: start()
,08-17 16:36:17.387  4366  4366 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 16:36:17.388  4366  4366 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 16:36:17.388  4366  4366 D BluetoothMapAppObserver: createReceiver()
08-17 16:36:17.391  4366  4366 D BluetoothMapAppObserver: initObservers()
,08-17 16:36:17.391  4366  4366 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 16:36:17.397  4366  4366 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:36:17.397  4366  4366 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:17.397  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:17.397  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isTurningOn()=true
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:17.399  4366  4394 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isTurningOn()=true
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:17.399  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOff()=false
,08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOff()=false
08-17 16:36:17.401  4366  4366 V BluetoothAdapterState: isTurningOn()=true
08-17 16:36:17.402  4366  4366 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 16:36:17.402  4366  4366 V BluetoothAdapterState: isBleTurningOff()=false
08-17 16:36:17.402  4366  4378 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-17 16:36:17.402  4366  4378 D BluetoothAdapterProperties: ScanMode =  20
08-17 16:36:17.402  4366  4378 D BluetoothAdapterProperties: State =  11
08-17 16:36:17.402  4366  4378 D BluetoothAdapterProperties: Setting state to 12
,08-17 16:36:17.402  4366  4378 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 16:36:17.403  4366  4378 I BluetoothAdapterState: Entering OnState
08-17 16:36:17.403  4044  4054 D BluetoothPan: onBluetoothStateChange on: true
08-17 16:36:17.403  4366  4382 D BluetoothAdapterProperties: Scan Mode:21
08-17 16:36:17.403  4366  4382 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 16:36:17.405   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 16:36:17.405  4044  4056 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:17.406  1358  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:17.406  4044  4044 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 16:36:17.406  4044  4044 D PanProfile: Bluetooth service connected
08-17 16:36:17.406   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:17.406  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 16:36:17.406  1899  1911 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:17.407  4044  4054 D BluetoothMap: onBluetoothStateChange: up=true
08-17 16:36:17.408  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 16:36:17.409  1358  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-17 16:36:17.410  4044  4044 D BluetoothMap: Proxy object connected
08-17 16:36:17.410  4044  4044 D MapProfile: Bluetooth service connected
,08-17 16:36:17.410  4044  4044 D BluetoothMap: getConnectedDevices()
08-17 16:36:17.410  1358  1358 D BluetoothMap: Proxy object connected
08-17 16:36:17.410  1358  1358 D MapProfile: Bluetooth service connected
08-17 16:36:17.410  1358  1370 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 16:36:17.410  1358  1358 D BluetoothMap: getConnectedDevices()
,08-17 16:36:17.412   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 16:36:17.412  4044  4054 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 16:36:17.414  1358  1385 D BluetoothPan: onBluetoothStateChange on: true
08-17 16:36:17.416  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 16:36:17.416  1358  1358 D PanProfile: Bluetooth service connected
08-17 16:36:17.416  1358  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 16:36:17.417  4366  4366 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 16:36:17.417  4044  4044 D BluetoothInputDevice: Proxy object connected
08-17 16:36:17.417  4366  4366 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 16:36:17.418  4044  4044 D HidProfile: Bluetooth service connected
08-17 16:36:17.418   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 16:36:17.419  1358  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 16:36:17.419  4366  4366 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 16:36:17.420  1358  1358 D BluetoothInputDevice: Proxy object connected
08-17 16:36:17.420  1358  1358 D HidProfile: Bluetooth service connected
08-17 16:36:17.421  4044  4056 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 16:36:17.422  4366  4366 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 16:36:17.422  4366  4366 D ObexServerSockets: Succeed to create listening sockets 
,08-17 16:36:17.423  4366  4366 D ObexServerSockets0: startAccept()
08-17 16:36:17.423  4366  4366 D ObexServerSockets0: prepareForNewConnect()
08-17 16:36:17.423  4044  4054 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 16:36:17.424  4366  4366 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 16:36:17.424  4366  4366 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 16:36:17.425   872   872 D BluetoothA2dp: Proxy object connected
08-17 16:36:17.426  4366  4403 D ObexServerSockets0: Accepting socket connection...
,08-17 16:36:17.426  1358  1358 D BluetoothA2dp: Proxy object connected
08-17 16:36:17.426  4044  4044 D BluetoothA2dp: Proxy object connected
08-17 16:36:17.427  4366  4366 D BluetoothMapService: onReceive
08-17 16:36:17.427  4366  4366 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 16:36:17.428  4366  4366 D BluetoothMapService: STATE_ON
08-17 16:36:17.428  4366  4404 D ObexServerSockets0: Accepting socket connection...
08-17 16:36:17.429   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 16:36:17.430  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:17.435  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 16:36:17.441  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 16:36:17.441  4044  4044 D DockEventReceiver: finishStartingService: stopping service
08-17 16:36:17.447  4044  4044 D BluetoothPbap: Proxy object connected
08-17 16:36:17.447  4044  4044 D PbapServerProfile: Bluetooth service connected
08-17 16:36:17.452  1358  1358 D BluetoothPbap: Proxy object connected
08-17 16:36:17.452  1358  1358 D PbapServerProfile: Bluetooth service connected
08-17 16:36:17.455  4366  4366 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 16:36:17.455  4366  4366 D ObexServerSockets0: prepareForNewConnect()
08-17 16:36:17.456  4366  4409 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 16:36:17.466  4366  4413 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 16:36:17.468  4366  4413 I BtOppRfcommListener: Accept thread started.
,08-17 16:36:17.506   872   872 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.506   872   872 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.506  4044  4054 D BluetoothHeadset: Proxy object connected
08-17 16:36:17.507  4044  4044 D HeadsetProfile: Bluetooth service connected
,08-17 16:36:17.507  1899  1916 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.507  1358  1383 D BluetoothHeadset: Proxy object connected
08-17 16:36:17.507   872   872 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.507  1358  1385 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.507  1358  1358 D HeadsetProfile: Bluetooth service connected
08-17 16:36:17.508   872   889 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.509  1899  1990 D BluetoothHeadset: Proxy object connected
08-17 16:36:17.514   872   889 D BluetoothHeadset: Proxy object connected
,08-17 16:36:17.518  1358  1358 D HeadsetProfile: Bluetooth service connected
,08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:17.848  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 16:36:17.855  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:17.861  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:17.861  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6fc812 added. We now have 8 listener(s)
,08-17 16:36:17.862  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:17.869   872  1697 D WifiService: setWifiEnabled: false pid=3961, uid=10000
,08-17 16:36:17.869   872  1697 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 16:36:17.883  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:17.885   872   882 D WifiService: setWifiEnabled: true pid=3961, uid=10000
08-17 16:36:17.885   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 16:36:17.900   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 16:36:17.920  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 16:36:17.921   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-17 16:36:17.922   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 16:36:17.924  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 16:36:17.925   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 16:36:17.928   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 16:36:17.929   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2,
08-17 16:36:17.929   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 16:36:17.930   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 16:36:17.946   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.28 delta 1000 -> 1000
,08-17 16:36:17.946   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-17 16:36:17.946   872  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 16:36:17.948   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:17.955   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 16:36:17.955   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 16:36:17.956   872  1301 E native  : do suspend true
,08-17 16:36:17.970   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 16:36:17.971   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:17.978   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 16:36:18.022   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 16:36:18.024  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 16:36:18.038   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 16:36:18.038   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 16:36:18.444  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 16:36:18.491  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 16:36:18.493  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 16:36:18.501   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 16:36:18.512   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 16:36:18.513   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:18.513   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 16:36:18.536   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 16:36:18.547   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:18.551   872  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 16:36:18.555   872  4421 D DhcpClient: Receive thread started
,08-17 16:36:18.559   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 16:36:18.650   872  1301 E native  : do suspend false
,08-17 16:36:18.674   872  1865 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 16:36:18.688   872  4421 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-17 16:36:18.689   872  1865 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 16:36:18.693   872  1865 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 16:36:18.706   872  4421 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 16:36:18.707   872  1865 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 16:36:18.712   371   870 D CommandListener: Setting iface cfg
,08-17 16:36:18.725   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-17 16:36:18.726   872  1865 D DhcpClient: Scheduling renewal in 86399s
,08-17 16:36:18.727   872  1301 E native  : do suspend true
,08-17 16:36:18.742   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 16:36:18.745   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 16:36:18.746   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 16:36:18.748   872  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 16:36:18.756   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 16:36:18.821   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 16:36:18.821   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 16:36:18.823   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 16:36:18.825   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 16:36:18.827   872  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 16:36:18.841   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 16:36:18.848   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 16:36:18.849   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-17 16:36:18.849   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 16:36:18.849   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 16:36:18.849   872  1303 D ConnectivityService:    accepting network in place of null
,08-17 16:36:18.850   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 16:36:18.850   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 16:36:18.857   872  4420 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165366, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 16:36:18.907   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:18.913  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:18.919  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:18.930  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 16:36:18.930   872  4419 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
,08-17 16:36:18.931  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 16:36:18.933  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@667db60 Bundle[{}]
,08-17 16:36:18.934  3961  4025 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 16:36:18.934  3961  4025 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 16:36:18.935  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 16:36:18.935  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 16:36:18.936  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 16:36:18.936  3961  4025 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 16:36:18.940  3961  4025 I System.out: Running OutgoingSocketThread
08-17 16:36:18.942  3961  4429 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 460)
08-17 16:36:18.943  3961  4429 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47552
08-17 16:36:18.943  3961  4429 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 16:36:18.956   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 16:36:18.963   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 16:36:18.964   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:18.971   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 16:36:18.972   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:18.979  3961  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:36:18.982  3961  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:18.994  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 16:36:19.003  1745  1745 D SystemUpdateService: onCreate
,08-17 16:36:19.007  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 16:36:19.013   872  4419 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 14:36:19 GMT], X-Android-Received-Millis=[1471444579012], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471444578983]}
,08-17 16:36:19.015   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 16:36:19.016   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 16:36:19.016   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 16:36:19.017   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 16:36:19.038  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 16:36:19.040  1745  2410 I iu.UploadsManager: num queued entries: 0
,08-17 16:36:19.047  1745  4431 I SystemUpdateService: active receiver: enabled
,08-17 16:36:19.050  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 16:36:19.052  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 16:36:19.054  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 16:36:19.060  1745  4434 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 16:36:19.060  1745  4434 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 16:36:19.061  4127  4127 D SprintDMHelper: simOperator: 
,08-17 16:36:19.061  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 16:36:19.067  1745  4434 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 16:36:19.076  1745  2410 I iu.UploadsManager: num updated entries: 0
,08-17 16:36:19.077  1745  4431 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-17 16:36:19.077  1745  2410 I iu.SyncManager: NEXT; no task
,08-17 16:36:19.087  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:19.088  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 16:36:19.092  1745  4431 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 16:36:19.093  1745  4431 I SystemUpdateService: now status is 0 (complete)
08-17 16:36:19.093  1745  4431 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 16:36:19.093  1745  4431 I SystemUpdateService: file has been verified
08-17 16:36:19.093  1745  4431 I SystemUpdateService: OTA package size = 12249756
,08-17 16:36:19.105  1745  4431 I SystemUpdateService: showing system update notification
,08-17 16:36:19.182  1745  1745 D SystemUpdateService: onDestroy
,08-17 16:36:19.185  1519  2359 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 16:36:19.185  1519  2359 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 16:36:19.185  1519  2359 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 16:36:19.185  1519  2359 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 16:36:19.190  3650  4437 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 16:36:19.207  1745  4434 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-17 16:36:19.944  3961  4025 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 461)
,08-17 16:36:19.944  3961  4025 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 461)
,08-17 16:36:19.954  3961  4025 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 466)
,08-17 16:36:19.956  3961  4025 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 16:36:19.956  3961  4025 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 467)
,08-17 16:36:19.963  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 16:36:19.963  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d79dbe3 added. We now have 2 listener(s)
,08-17 16:36:19.963   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-17 16:36:19.965  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 16:36:19.965  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:19.965  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:19.965  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:19.965  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@273f9e0 added. We now have 9 listener(s)
08-17 16:36:19.966  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:19.966  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 16:36:19.974  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:19.984  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:19.989  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:19.990  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 16:36:19.990  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:19.991  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97e535e added. We now have 3 listener(s)
,08-17 16:36:19.996  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:19.997  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:19.997  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:19.997  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:19.998  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:19.998  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4533f added. We now have 10 listener(s)
,08-17 16:36:19.998  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:19.999  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 16:36:19.999  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:36:19.999  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:36:20.000  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.000  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.000  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 16:36:20.000  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.001  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d79dbe3 removed from the list
08-17 16:36:20.001  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.001  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@273f9e0 removed from the list
,08-17 16:36:20.003  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:20.003  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:36:20.004  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.005  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.005  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.008  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:36:20.008  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.008  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.008  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@273f9e0 not in the list
08-17 16:36:20.008  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.009  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.011  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 16:36:20.011  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.011  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.011  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e4533f removed from the list
08-17 16:36:20.011  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.012  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.012  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.012  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 16:36:20.012  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97e535e removed from the list
,08-17 16:36:20.014  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:20.014  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44ed40c added. We now have 2 listener(s)
,08-17 16:36:20.018  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.019  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.019  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:20.019  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:20.019  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7742155 added. We now have 9 listener(s)
08-17 16:36:20.020  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:20.021  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 16:36:20.026  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:20.034  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:20.037  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:20.038  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 16:36:20.038  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 16:36:20.038  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54e45b added. We now have 3 listener(s)
,08-17 16:36:20.041  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.041  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 16:36:20.041  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 16:36:20.042  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:20.042  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1b24f8 added. We now have 10 listener(s)
,08-17 16:36:20.042  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:20.042  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 16:36:20.042  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 16:36:20.042  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 16:36:20.043  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:36:20.043  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 16:36:20.043  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:20.049  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 16:36:20.049  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 16:36:20.050  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:20.056  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 16:36:20.057  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 16:36:20.057  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:36:20.063  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 16:36:20.064  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 16:36:20.064  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 16:36:20.064  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:36:20.069  4366  4395 D BtGatt.GattService: registerClient() - UUID=d65c6870-2ae4-45cc-af3e-20ca7dc7ab60
,08-17 16:36:20.071  4366  4382 D BtGatt.GattService: onClientRegistered() - UUID=d65c6870-2ae4-45cc-af3e-20ca7dc7ab60, clientIf=5
,08-17 16:36:20.072  3961  4124 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 16:36:20.074  4366  4376 D BtGatt.GattService: start scan with filters
,08-17 16:36:20.080  4366  4385 D BtGatt.ScanManager: handling starting scan
,08-17 16:36:20.080  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 16:36:20.081  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 16:36:20.081  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 16:36:20.081  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:36:20.084  4366  4385 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4ed73f4
,08-17 16:36:20.088  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:36:20.088  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 16:36:20.089  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:36:20.091  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 16:36:20.091  4366  4382 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 16:36:20.091  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.093  4366  4385 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 16:36:20.095  3961  4025 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 16:36:20.095  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 16:36:20.095  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 16:36:20.095  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.095  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 16:36:20.095  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 16:36:20.096  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 16:36:20.096  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 16:36:20.096  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 16:36:20.096  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:36:20.097  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 16:36:20.098  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:36:20.099  4366  4376 D BtGatt.GattService: stopScan() - queue size =1
08-17 16:36:20.101  4366  4377 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 16:36:20.101  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 16:36:20.101  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 16:36:20.101  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 16:36:20.101  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 16:36:20.101  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 16:36:20.103  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:36:20.103  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 16:36:20.103  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 16:36:20.103  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 16:36:20.104  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 16:36:20.107  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 16:36:20.107  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:36:20.107  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.108  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:36:20.108  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:36:20.108  4366  4385 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:36:20.109  4366  4385 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 16:36:20.112  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:36:20.112  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:36:20.113  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:36:20.113  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.113  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.113  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:36:20.113  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.113  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44ed40c removed from the list
08-17 16:36:20.114  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.114  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7742155 removed from the list
08-17 16:36:20.114  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:36:20.114  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.115  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.115  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.117  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 16:36:20.117  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 16:36:20.117  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.117  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7742155 not in the list
08-17 16:36:20.118  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.118  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.119  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 16:36:20.120  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.120  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.120  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1b24f8 removed from the list
08-17 16:36:20.120  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 16:36:20.120  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.120  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.121  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 16:36:20.121  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54e45b removed from the list
08-17 16:36:20.122  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 16:36:20.123  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85998a4 added. We now have 2 listener(s)
,08-17 16:36:20.127  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.127  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.127  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 16:36:20.128  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:20.128  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d80260d added. We now have 9 listener(s)
,08-17 16:36:20.128  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:20.129  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 16:36:20.133  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:36:20.138  4366  4382 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 16:36:20.138  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:20.141  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:20.144  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:20.145  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 16:36:20.145  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:20.145  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28983d3 added. We now have 3 listener(s)
,08-17 16:36:20.149  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:20.150  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.150  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.150  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:20.151  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 16:36:20.151  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e99b10 added. We now have 10 listener(s)
08-17 16:36:20.151  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:20.151  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 16:36:20.153  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 16:36:20.153  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 16:36:20.153  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 16:36:20.153  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:36:20.153  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 16:36:20.154  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 16:36:20.154  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.154  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 16:36:20.159  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 16:36:20.159  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 16:36:20.168  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 16:36:20.169  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:36:20.169  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.169  4366  4385 D BtGatt.ScanManager: stopping BLe Batch
,08-17 16:36:20.169  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 16:36:20.169  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:36:20.174  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 16:36:20.174  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 16:36:20.174  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 16:36:20.175  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:36:20.178  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 16:36:20.178  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.178  4366  4385 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 16:36:20.179  4366  4376 D BtGatt.GattService: registerClient() - UUID=cc4dc7ef-1730-49a7-a641-bdf653b4f6df
,08-17 16:36:20.180  4366  4382 D BtGatt.GattService: onClientRegistered() - UUID=cc4dc7ef-1730-49a7-a641-bdf653b4f6df, clientIf=5
,08-17 16:36:20.181  3961  3973 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 16:36:20.181  4366  4405 D BtGatt.GattService: start scan with filters
,08-17 16:36:20.184  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 16:36:20.184  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 16:36:20.184  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 16:36:20.184  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:36:20.187  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 16:36:20.187  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 16:36:20.187  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:36:20.187  4366  4382 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 16:36:20.187  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.189  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 16:36:20.190  4366  4385 D BtGatt.ScanManager: handling starting scan
,08-17 16:36:20.191  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 16:36:20.192  3961  4025 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 16:36:20.192  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:36:20.192  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:36:20.192  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 16:36:20.192  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.192  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.192  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 16:36:20.192  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.192  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85998a4 removed from the list
08-17 16:36:20.193  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.193  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d80260d removed from the list
,08-17 16:36:20.193  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:36:20.193  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 16:36:20.193  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.193  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 16:36:20.193  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.193  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.195  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d80260d not in the list
08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 16:36:20.195  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 16:36:20.195  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:36:20.195  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 16:36:20.196  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:36:20.197  4366  4395 D BtGatt.GattService: stopScan() - queue size =1
,08-17 16:36:20.197  4366  4405 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 16:36:20.198  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 16:36:20.198  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 16:36:20.198  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 16:36:20.198  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 16:36:20.198  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 16:36:20.199  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:36:20.199  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 16:36:20.199  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 16:36:20.200  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 16:36:20.200  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.200  4366  4382 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 16:36:20.201  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.201  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.201  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.201  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.201  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e99b10 removed from the list
08-17 16:36:20.201  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 16:36:20.201  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.202  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.202  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.201  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:36:20.202  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28983d3 removed from the list
,08-17 16:36:20.202  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:36:20.202  4366  4385 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 16:36:20.202  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 16:36:20.203  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:20.203  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35583c added. We now have 2 listener(s)
,08-17 16:36:20.205  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.205  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.205  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:20.205  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:20.205  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80109c5 added. We now have 9 listener(s)
08-17 16:36:20.205  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 16:36:20.206  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 16:36:20.208  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 16:36:20.212  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 16:36:20.212  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.212  4366  4385 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:36:20.212  4366  4385 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:20.212  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 16:36:20.216  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 16:36:20.216  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 16:36:20.217  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:20.217  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d39a4b added. We now have 3 listener(s)
,08-17 16:36:20.220  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:20.220  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.221  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 16:36:20.221  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 16:36:20.221  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:20.221  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81dbc28 added. We now have 10 listener(s)
08-17 16:36:20.222  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:20.222  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 16:36:20.222  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 16:36:20.222  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 16:36:20.222  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:36:20.222  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 16:36:20.224  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:20.225  4366  4382 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 16:36:20.225  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.226  3961  4025 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 16:36:20.226  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 16:36:20.229  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 16:36:20.230  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 16:36:20.230  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 16:36:20.231  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 16:36:20.231  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.234  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 16:36:20.234  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 16:36:20.234  3961  4025 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 16:36:20.235  3961  4025 D BluetoothAdapter: STATE_ON
,08-17 16:36:20.237  4366  4377 D BtGatt.GattService: registerClient() - UUID=e4c2f7f3-8df9-4aa5-9db2-8147e31669e1
,08-17 16:36:20.238  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:36:20.238  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.238  4366  4385 D BtGatt.ScanManager: stopping BLe Batch
08-17 16:36:20.238  4366  4382 D BtGatt.GattService: onClientRegistered() - UUID=e4c2f7f3-8df9-4aa5-9db2-8147e31669e1, clientIf=5
08-17 16:36:20.238  3961  3972 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 16:36:20.239  4366  4405 D BtGatt.GattService: start scan with filters
,08-17 16:36:20.241  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 16:36:20.242  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 16:36:20.242  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 16:36:20.242  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 16:36:20.244  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 16:36:20.244  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.244  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:36:20.244  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 16:36:20.244  4366  4385 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 16:36:20.244  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 16:36:20.246  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 16:36:20.249  4366  4382 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 16:36:20.250  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.250  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:36:20.250  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:36:20.250  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:36:20.250  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 16:36:20.250  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.250  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 16:36:20.250  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.250  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35583c removed from the list
,08-17 16:36:20.250  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.250  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80109c5 removed from the list
,08-17 16:36:20.250  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:36:20.250  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:36:20.251  4366  4385 D BtGatt.ScanManager: handling starting scan
08-17 16:36:20.251  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.251  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 16:36:20.251  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.251  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 16:36:20.252  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80109c5 not in the list
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 16:36:20.252  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 16:36:20.252  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 16:36:20.252  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 16:36:20.253  3961  4025 D BluetoothAdapter: STATE_ON
08-17 16:36:20.253  4366  4405 D BtGatt.GattService: stopScan() - queue size =1
08-17 16:36:20.254  4366  4395 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 16:36:20.254  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 16:36:20.254  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 16:36:20.254  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 16:36:20.254  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 16:36:20.254  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 16:36:20.255  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:36:20.255  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 16:36:20.255  3961  4025 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 16:36:20.255  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 16:36:20.256  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.256  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.256  4366  4382 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 16:36:20.257  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.257  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.257  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.257  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 16:36:20.257  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81dbc28 removed from the list
08-17 16:36:20.257  4366  4385 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 16:36:20.257  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.257  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.257  3961  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 16:36:20.257  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.257  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.257  3961  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 16:36:20.257  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d39a4b removed from the list
08-17 16:36:20.258  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 16:36:20.258  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a672d4 added. We now have 2 listener(s)
08-17 16:36:20.259  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 16:36:20.259  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.259  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 16:36:20.259  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:20.260  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3ac7d added. We now have 9 listener(s)
08-17 16:36:20.260  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:20.260  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 16:36:20.262  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 16:36:20.262  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 16:36:20.262  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.263  4366  4385 D BtGatt.ScanManager: Starting BLE batch scan
08-17 16:36:20.263  4366  4385 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 16:36:20.265  3961  4025 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 16:36:20.266  3961  4025 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 16:36:20.266  3961  4025 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 16:36:20.267  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 16:36:20.267  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78b07c3 added. We now have 3 listener(s)
,08-17 16:36:20.268  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 16:36:20.268  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 16:36:20.268  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 16:36:20.269  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 16:36:20.269  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@661e840 added. We now have 10 listener(s)
08-17 16:36:20.269  3961  4025 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 16:36:20.269  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 16:36:20.269  3961  4025 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 16:36:20.269  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 16:36:20.269  3961  4025 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 16:36:20.269  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.269  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 16:36:20.269  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 16:36:20.269  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 16:36:20.269  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a672d4 removed from the list
08-17 16:36:20.269  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.270  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3ac7d removed from the list
08-17 16:36:20.272  3961  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 16:36:20.272  3961  4025 D io.jxcore.node.ConnectivityMonitor: stop
08-17 16:36:20.272  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.272  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.272  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 16:36:20.273  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.274  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 16:36:20.274  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.274  3961  4025 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d3ac7d not in the list
08-17 16:36:20.274  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.274  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.274  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 16:36:20.274  4366  4382 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 16:36:20.275  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 16:36:20.275  3961  4025 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 16:36:20.275  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.275  3961  4025 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@661e840 removed from the list
08-17 16:36:20.275  3961  4025 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 16:36:20.275  3961  4025 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 16:36:20.275  3961  4025 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 16:36:20.275  3961  4025 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 16:36:20.275  3961  4025 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78b07c3 removed from the list
08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 16:36:20.276  3961  4025 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 16:36:20.280  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 16:36:20.280  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 16:36:20.282  3961  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: My test thread name)
,08-17 16:36:20.282  3961  4443 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 474, thread name: My test thread name)
08-17 16:36:20.282  3961  4443 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 474, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 16:36:20.283  3961  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 476, name: My test thread name)
08-17 16:36:20.284  3961  4444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 476, thread name: My test thread name)
08-17 16:36:20.284  3961  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 476, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 16:36:20.286  3961  4025 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 16:36:20.286  3961  4025 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 16:36:20.286  3961  4025 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 16:36:20.286  3961  4025 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-17 16:36:20.286  3961  4025 D com.test.thalitest.ThaliTestRunner: Total duration: 22939 ms
08-17 16:36:20.286  4366  4382 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 16:36:20.286  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.286  4366  4385 D BtGatt.ScanManager: stopping BLe Batch
,08-17 16:36:20.288  3961  4025 I jxcore-log: Total number of executed tests:  80
08-17 16:36:20.288  3961  4025 I jxcore-log: 
,08-17 16:36:20.288  3961  4025 I jxcore-log: Number of passed tests:  80
08-17 16:36:20.288  3961  4025 I jxcore-log: 
08-17 16:36:20.289  3961  4025 I jxcore-log: Number of failed tests:  0
08-17 16:36:20.289  3961  4025 I jxcore-log: 
08-17 16:36:20.289  3961  4025 I jxcore-log: Number of ignored tests:  0
08-17 16:36:20.289  3961  4025 I jxcore-log: 
08-17 16:36:20.289  3961  4025 I jxcore-log: Total duration:  22939
08-17 16:36:20.289  3961  4025 I jxcore-log: 
,08-17 16:36:20.289  3961  4025 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 16:36:20.289  3961  4025 I jxcore-log: 
,08-17 16:36:20.293  4366  4382 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 16:36:20.293  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.293  4366  4385 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 16:36:20.294  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.294  3961  4025 I jxcore-log: 
08-17 16:36:20.297  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.297  3961  4025 I jxcore-log: 
08-17 16:36:20.298  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.298  3961  4025 I jxcore-log: 
08-17 16:36:20.299  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.299  3961  4025 I jxcore-log: 
08-17 16:36:20.300  4366  4382 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 16:36:20.300  4366  4382 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 16:36:20.301  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.301  3961  4025 I jxcore-log: 
08-17 16:36:20.302  3961  3961 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-17 16:36:20.302  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.302  3961  4025 I jxcore-log: 
08-17 16:36:20.304  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.304  3961  4025 I jxcore-log: 
,08-17 16:36:20.306  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.306  3961  4025 I jxcore-log: 
,08-17 16:36:20.306  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.306  3961  4025 I jxcore-log: 
,08-17 16:36:20.307  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 16:36:20.307  3961  4025 I jxcore-log: 
,08-17 16:36:20.308  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 16:36:20.308  3961  4025 I jxcore-log: 
,08-17 16:36:20.309  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 16:36:20.309  3961  4025 I jxcore-log: 
08-17 16:36:20.310  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-17 16:36:20.310  3961  4025 I jxcore-log: 
08-17 16:36:20.310  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.310  3961  4025 I jxcore-log: 
,08-17 16:36:20.311  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.311  3961  4025 I jxcore-log: 
,08-17 16:36:20.312  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.312  3961  4025 I jxcore-log: 
08-17 16:36:20.312  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.312  3961  4025 I jxcore-log: 
,08-17 16:36:20.313  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.313  3961  4025 I jxcore-log: 
,08-17 16:36:20.314  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.314  3961  4025 I jxcore-log: 
,08-17 16:36:20.314  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.314  3961  4025 I jxcore-log: 
,08-17 16:36:20.315  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.315  3961  4025 I jxcore-log: 
,08-17 16:36:20.315  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 16:36:20.315  3961  4025 I jxcore-log: 
08-17 16:36:20.316  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 16:36:20.316  3961  4025 I jxcore-log: 
,08-17 16:36:20.316  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.316  3961  4025 I jxcore-log: 
08-17 16:36:20.317  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.317  3961  4025 I jxcore-log: 
,08-17 16:36:20.318  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.318  3961  4025 I jxcore-log: 
08-17 16:36:20.318  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.318  3961  4025 I jxcore-log: 
,08-17 16:36:20.319  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.319  3961  4025 I jxcore-log: 
08-17 16:36:20.320  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.320  3961  4025 I jxcore-log: 
,08-17 16:36:20.320  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 16:36:20.320  3961  4025 I jxcore-log: 
,08-17 16:36:20.609  3961  3961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 16:36:20.612  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 16:36:20.612  3961  4025 I jxcore-log: 
,08-17 16:36:20.703  3961  3961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 16:36:20.706  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 16:36:20.706  3961  4025 I jxcore-log: 
,08-17 16:36:20.758  3961  3961 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 16:36:20.760  3961  4025 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 16:36:20.760  3961  4025 I jxcore-log: 
,08-17 16:36:21.037  4445  4445 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 16:36:21.041  4445  4445 D AndroidRuntime: CheckJNI is OFF
,08-17 16:36:21.086  4445  4445 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 16:36:21.132  4445  4445 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 16:36:21.155  4445  4445 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 16:36:21.168   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 16:36:21.169   872   885 I ActivityManager: Killing 3961:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 16:36:21.276   872  1302 D WifiService: Client connection lost with reason: 4
08-17 16:36:21.277   872  1995 I WindowState: WIN DEATH: Window{83c8725 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 16:36:21.278   872  2198 D GraphicsStats: Buffer count: 2
,08-17 16:36:21.300   872   895 W PackageSettings: Skipping PackageSetting{6e95cf1 com.example.hello/10273} due to missing metadata
,08-17 16:36:21.338   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 16:36:21.339   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-17 16:36:21.339   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-17 16:36:21.339   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 16:36:21.339   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.339   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.339   872   885 E ActivityManager: ,	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 16:36:21.339   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 16:36:21.340   872   885 I ActivityManager:   Force finishing activity ActivityRecord{50ba519 u0 com.test.thalitest/.MainActivity t2}
08-17 16:36:21.345   872   895 I art     : Starting a blocking GC Explicit
08-17 16:36:21.346   872  1372 W ActivityManager: Spurious death for ProcessRecord{a1050c0 0:com.test.thalitest/u0a0}, curProc for 3961: null
,08-17 16:36:21.406   872   895 I art     : Explicit concurrent mark sweep GC freed 48052(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.180ms total 60.644ms
,08-17 16:36:21.438   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 16:36:21.443  4445  4445 I art     : System.exit called, status: 0
,08-17 16:36:21.443  4445  4445 I AndroidRuntime: VM exiting with result code 0.
,08-17 16:36:21.455   872   895 I ActivityManager: Start proc 4456:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-17 16:36:21.456   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 16:36:21.474   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null),
08-17 16:36:21.481  4366  4366 D BluetoothMapAppObserver: onReceive
08-17 16:36:21.481  4366  4366 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-17 16:36:21.486  2150  2325 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 16:36:21.497   872  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 16:36:21.512  3825  3825 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 16:36:21.531  1899  1899 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-17 16:36:21.537   872  3114 I ActivityManager: Killing 2242:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
08-17 16:36:21.538  1845  1845 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 16:36:21.557  1845  4471 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 16:36:21.557  1845  4471 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-17 16:36:21.557  1845  4471 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-17 16:36:21.561  1845  4471 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-17 16:36:21.562  1845  4471 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-17 16:36:21.562  1845  4471 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-17 16:36:21.562  1845  4471 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-17 16:36:21.563  1845  4471 I Decoder : createOrResetDecoder
,08-17 16:36:21.563   872  2056 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3961 uid 10000
08-17 16:36:21.564  1845  1845 I Keyboard.Facilitator: onFinishInput()
,08-17 16:36:21.569   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 16:36:21.591  1519  1519 I ConfigService: onCreate
,08-17 16:36:21.594  1519  4472 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 16:36:21.594  1519  4472 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 16:36:21.594  1519  4472 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 16:36:21.596  1519  4472 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-17 16:36:21.602   872  3114 I ActivityManager: Start proc 4473:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 16:36:21.609  1845  4471 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 16:36:21.617  1918  2026 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 16:36:21.617   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 16:36:21.620   872   884 E PackageManager: Failed to write settings, restoring backup
08-17 16:36:21.620   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 16:36:21.620   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 16:36:21.620   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 16:36:21.620   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 16:36:21.620   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 16:36:21.620   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.620   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.620   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 16:36:21.626   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-17 16:36:21.626   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 16:36:21.626   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 16:36:21.626   872   885 E DropBoxManagerService: 	... 13 more
,08-17 16:36:21.632   872  1697 I ActivityManager: Start proc 4485:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-17 16:36:21.633  1918  2026 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 16:36:21.633  1918  2026 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1918
08-17 16:36:21.633  1918  2026 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.633  1918  2026 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 16:36:21.638   872  1695 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 16:36:21.638   872  4494 E DropBoxManagerService: Can't write: system_app_crash
08-17 16:36:21.638   872  4494 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 16:36:21.638   872  4494 E DropBoxManagerService: 	... 5 more
,08-17 16:36:21.704  1918  2026 I Process : Sending signal. PID: 1918 SIG: 9
,08-17 16:36:21.731  4473  4473 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 16:36:21.758  1845  4471 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 16:36:21.760  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 16:36:21.760  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 16:36:21.765  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 16:36:21.765  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-17 16:36:21.773  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-17 16:36:21.773  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-17 16:36:21.780  1845  4471 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-17 16:36:21.780  1845  4471 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 16:36:21.780  1845  4471 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-17 16:36:21.784  1845  4471 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 16:36:21.784  1845  4471 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 16:36:21.784  1845  4471 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 16:36:21.805   872  1695 I WindowState: WIN DEATH: Window{50c8fd5 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 16:36:21.805   872  1377 D GraphicsStats: Buffer count: 1
,08-17 16:36:21.817   872  1697 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1918) has died
08-17 16:36:21.817   872  1697 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-17 16:36:21.819   872  1697 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.839  4473  4503 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.839  4473  4503 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 16:36:21.842   872   885 I ActivityManager: Start proc 4505:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 16:36:21.853  4473  4473 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-17 16:36:21.854  1745  4501 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-17 16:36:21.855  1745  4501 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-17 16:36:21.864   872  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
08-17 16:36:21.870   872  1377 I ActivityManager: Start proc 4517:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-17 16:36:21.876  4473  4519 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 16:36:21.906  4517  4517 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:36:21.914  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:36:21.915  4505  4505 D AndroidRuntime: Shutting down VM
,08-17 16:36:21.927  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-17 16:36:21.928  1519  1519 D AndroidRuntime: Shutting down VM
08-17 16:36:21.931  4505  4505 E AndroidRuntime: FATAL EXCEPTION: main
08-17 16:36:21.931  4505  4505 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4505
08-17 16:36:21.931  4505  4505 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 16:36:21.931  4505  4505 E AndroidRuntime: 	... 10 more
08-17 16:36:21.934  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
08-17 16:36:21.934  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
08-17 16:36:21.934  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 16:36:21.934  1519  1519 E AndroidRuntime: 	... 8 more
08-17 16:36:21.938   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 16:36:21.940   872  4534 E DropBoxManagerService: Can't write: system_app_crash
08-17 16:36:21.940   872  4534 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 16:36:21.940   872  4534 E DropBoxManagerService: 	... 5 more
08-17 16:36:21.940   872  4533 E DropBoxManagerService: Can't write: system_app_crash
08-17 16:36:21.940   872  4533 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 16:36:21.940   872  4533 E DropBoxManagerService: 	... 5 more

```
