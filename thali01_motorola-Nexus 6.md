#### Test 80912877691b6a3_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-24 12:45:10.147   876  2088 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-24 12:45:10.812  3912  3912 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 12:45:10.817  3912  3912 D AndroidRuntime: CheckJNI is OFF
08-24 12:45:10.854  3912  3912 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 12:45:10.897  3912  3912 I Radio-JNI: register_android_hardware_Radio DONE
08-24 12:45:10.917  3912  3912 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 12:45:10.923   876  1952 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 12:45:10.967  2026  2040 W SearchService: Abort, client detached.
08-24 12:45:10.977  2026  2026 I HotwordDetector: Closing mic
08-24 12:45:10.977  2026  2336 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e5f5d4
08-24 12:45:10.978  2026  2348 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 12:45:10.994  3912  3912 D AndroidRuntime: Shutting down VM
08-24 12:45:11.008   876   886 I ActivityManager: Start proc 3922:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 12:45:11.046   376  2351 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 12:45:11.047   376  2351 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 12:45:11.052   376  1281 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 12:45:11.053  2026  2344 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 12:45:11.053  2026  2347 I MicroRecognitionRnrImpl: Detection finished
08-24 12:45:11.087  3922  3922 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 12:45:11.087  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 12:45:11.089  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 12:45:11.106  1499  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-24 12:45:11.106  1499  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-24 12:45:11.106  1499  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:11.106  1499  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 12:45:11.110  3922  3922 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:45:11.116  2026  2209 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-24 12:45:11.117  2026  2200 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 12:45:11.117  3922  3922 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1552-1554)
08-24 12:45:11.118  3922  3922 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 12:45:11.131  3922  3922 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {612a60d}
08-24 12:45:11.131  3922  3922 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 12:45:11.131  3922  3922 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 12:45:11.141  3922  3922 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 12:45:11.142  3922  3922 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 12:45:11.151  2026  2200 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 12:45:11.153  3922  3922 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 12:45:11.157  2026  2200 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1591-1593)
08-24 12:45:11.157  2026  2200 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 12:45:11.162  3922  3922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 12:45:11.162  3922  3922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 12:45:11.163  3922  3922 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 12:45:11.163  3922  3922 I Adreno  : Build Date                       : 10/20/15
08-24 12:45:11.163  3922  3922 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 12:45:11.163  3922  3922 I Adreno  : Local Branch                     : M14
08-24 12:45:11.163  3922  3922 I Adreno  : Remote Branch                    : 
08-24 12:45:11.163  3922  3922 I Adreno  : Remote Branch                    : 
08-24 12:45:11.163  3922  3922 I Adreno  : Reconstruct Branch               : 
08-24 12:45:11.196   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f96bff:true
08-24 12:45:11.229  3922  3922 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 12:45:11.240  3922  3922 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 12:45:11.313  3922  3973 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 12:45:11.321  3922  3954 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 12:45:11.362  3922  3973 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 12:45:11.409   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +415ms
,08-24 12:45:11.418  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-24 12:45:11.460  3922  3922 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3922
,08-24 12:45:11.646  3922  3922 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 12:45:11.795   876  1968 I ActivityManager: Killing 2258:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 12:45:11.810  3922  3978 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1701967568
,08-24 12:45:11.822  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 12:45:11.822  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 12:45:11.822  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 12:45:11.822  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 12:45:11.822  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 12:45:11.823  3922  3978 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50d5301 added. We now have 1 listener(s)
,08-24 12:45:11.825  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-24 12:45:11.828  3922  3978 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:11.828  3922  3978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 12:45:11.829  3922  3978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 12:45:11.832  3922  3978 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e19394 added. We now have 1 listener(s)
08-24 12:45:11.832  3922  3978 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:11.843   876  1312 D WifiService: New client listening to asynchronous messages
,08-24 12:45:11.844  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 12:45:11.844  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 12:45:11.844  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 12:45:11.844  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 12:45:11.844  3922  3978 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 12:45:11.851   876  1968 I ActivityManager: Killing 3074:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-24 12:45:11.894  3922  3978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:11.895  3922  3978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 12:45:11.906  3922  3978 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:11.907  3922  3978 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:11.908  3922  3978 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 12:45:11.908  3922  3978 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:11.910  3922  3978 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 12:45:12.042  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:12.045  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:12.049  3922  3922 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 12:45:13.225   876  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-24 12:45:13.284  3922  3986 W jxcore-log: Initializing JXcore engine
,08-24 12:45:13.284  3922  3986 W jxcore-log: JXcore engine is ready
,08-24 12:45:13.317  3986  3986 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 12:45:13.317  3986  3986 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9882]" dev="sockfs" ino=9882 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 12:45:13.317  3986  3986 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 12:45:13.317  3986  3986 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24320]" dev="sockfs" ino=24320 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 12:45:13.333  3922  3986 W jxcore-log: Starting JXcore engine
,08-24 12:45:13.410  3922  3986 W jxcore-log: Platform android
08-24 12:45:13.410  3922  3986 W jxcore-log: 
,08-24 12:45:13.410  3922  3986 W jxcore-log: Process ARCH arm
08-24 12:45:13.410  3922  3986 W jxcore-log: 
,08-24 12:45:13.595  3922  3986 I jxcore-log: JXcore Cordova bridge is ready!
08-24 12:45:13.595  3922  3986 I jxcore-log: 
,08-24 12:45:13.595  3922  3986 W jxcore-log: JXcore engine is started
,08-24 12:45:13.604  3922  3978 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 12:45:13.610  3922  3922 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 12:45:13.640   876  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 12:45:16.264   876  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-24 12:45:16.333   876  2088 D NetlinkSocketObserver: NeighborEvent{elapsedMs=126770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 12:45:21.190  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:21.191  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:21.200  3703  3998 V GoogleAuthProtoRequest: [299] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 12:45:21.259  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 12:45:21.260  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 12:45:21.260  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:21.260  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: [299] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: [299] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 12:45:21.282  3703  3998 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 12:45:21.299  1499  4000 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-24 12:45:21.300  1499  4000 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 12:45:21.324  1499  4000 W Uploader:  no longer exists, so no auth token.
,08-24 12:45:21.378  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:21.401  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 12:45:21.401  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 12:45:21.401  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:21.401  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:21.416  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 12:45:21.417  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 12:45:21.417  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-24 12:45:22.427  1499  4000 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 12:45:22.428  1499  4000 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 12:45:22.428  1499  4000 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:45:22.428  1499  4000 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:22.467  1499  4000 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 12:45:22.467  1499  4000 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 12:45:22.467  1499  4000 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 12:45:22.829  1499  4000 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 12:45:22.829  1499  4000 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 12:45:22.831  1499  4000 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:45:22.831  1499  4000 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:22.874  1499  4000 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 12:45:22.874  1499  4000 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 12:45:22.874  1499  4000 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 12:45:23.477  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 12:45:23.477  3922  3986 I jxcore-log: 
,08-24 12:45:23.478  1499  4000 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 12:45:23.478  1499  4000 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 12:45:23.478  1499  4000 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:23.479  1499  4000 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:23.479  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 12:45:23.479  3922  3986 I jxcore-log: 
,08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:23.492  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:23.504  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:23.506  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 12:45:23.506  3922  3986 I jxcore-log: 
08-24 12:45:23.508  1499  4000 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 12:45:23.508  1499  4000 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 12:45:23.508  1499  4000 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
08-24 12:45:23.509  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 12:45:23.509  3922  3986 I jxcore-log: 
,08-24 12:45:23.642  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:45:23.642  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:45:23.642  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:23.642  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:23.657  3090  4012 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 12:45:23.657  3090  4012 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at blb.a(PG:3937)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at czp.a(PG:18188)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,08-24 12:45:23.657  3090  4012 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:45:23.657  3090  4012 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	... 12 more
08-24 12:45:23.657  3090  4012 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at fal.a(PG:38)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:45:23.657  3090  4012 E HttpOperation: 	... 14 more
,08-24 12:45:23.692  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:45:23.692  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 12:45:23.692  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:45:23.692  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:23.698  1499  4000 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-24 12:45:23.699  1499  4000 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-24 12:45:23.699  1499  4000 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:23.699  1499  4000 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:23.704  3090  4012 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 12:45:23.704  3090  4012 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at hec.a(PG:42)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at hee.a(PG:102)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at czr.a(PG:65)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at kka.a(PG:108)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at czp.a(PG:19176)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:45:23.704  3090  4012 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	... 15 more
08-24 12:45:23.704  3090  4012 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at fal.a(PG:38)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:45:23.704  3090  4012 E HttpOperation: 	... 17 more
,08-24 12:45:23.704  3090  4012 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 12:45:23.704  3090  4012 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at hec.a(PG:42)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at hee.a(PG:102)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at czr.a(PG:65)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at kka.a(PG:108)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	... 15 more
08-24 12:45:23.704  3090  4012 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at fal.a(PG:38)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 12:45:23.704  3090  4012 E ExperimentLoader: 	... 17 more
,08-24 12:45:23.711  1499  4000 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 12:45:23.711  1499  4000 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 12:45:23.711  1499  4000 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 12:45:23.842   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 133868, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:45:24.079  3922  3986 D ExecuteNativeTests: Running unit tests
,08-24 12:45:24.138  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:24.138  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 added. We now have 2 listener(s)
,08-24 12:45:24.139  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 12:45:24.139  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:24.139  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:24.139  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:24.139  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 added. We now have 2 listener(s)
,08-24 12:45:24.139  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:24.140  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 12:45:24.143  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.158  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:24.165  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:24.165  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 12:45:24.171  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.176  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 12:45:24.177  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.181  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 12:45:24.181  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 12:45:24.190  3922  3986 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-24 12:45:24.191  3922  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-24 12:45:24.191  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 12:45:24.192  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 12:45:24.192  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 12:45:24.192  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.192  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:24.193  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.193  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.194  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.194  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.194  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:24.194  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 removed from the list
08-24 12:45:24.194  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.194  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 removed from the list
,08-24 12:45:24.194  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.194  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.196  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.196  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-24 12:45:24.199  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.199  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.200  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.200  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.204  3922  3986 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-24 12:45:24.207  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:24.207  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.207  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.207  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.208  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.208  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.208  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.209  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.209  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.209  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.209  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.210  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.210  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.210  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.213  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.213  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.213  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.214  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.224  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 12:45:24.224  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 12:45:24.225  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 12:45:24.226  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-24 12:45:24.226  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 12:45:24.226  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 12:45:24.227  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 12:45:24.228  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 12:45:24.228  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-24 12:45:24.228  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.228  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.228  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.228  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.228  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.228  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.228  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.228  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.228  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.228  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.229  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.229  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.229  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.229  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.232  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.232  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.232  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.232  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.235  3922  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 12:45:24.240  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.247  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:24.250  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:24.250  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:24.251  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 12:45:24.253  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 12:45:24.253  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 12:45:24.253  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:24.253  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 12:45:24.256  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.258  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 12:45:24.258  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 12:45:24.264  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.264  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 12:45:24.266  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 12:45:24.267  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 12:45:24.270  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-24 12:45:24.277  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-24 12:45:24.277  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-24 12:45:24.277  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:24.278  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 12:45:24.278  3922  3986 D BluetoothAdapter: STATE_ON,
,08-24 12:45:24.286  2814  2827 D BtGatt.GattService: registerClient() - UUID=fe8bfedc-af6c-48f1-9f85-72d171baf18f
,08-24 12:45:24.287  2814  2865 D BtGatt.GattService: onClientRegistered() - UUID=fe8bfedc-af6c-48f1-9f85-72d171baf18f, clientIf=5
08-24 12:45:24.288  3922  3934 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 12:45:24.290  2814  3010 D BtGatt.GattService: start scan with filters
,08-24 12:45:24.296  2814  2870 D BtGatt.ScanManager: handling starting scan
,08-24 12:45:24.296  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 12:45:24.297  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 12:45:24.297  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 12:45:24.298  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-24 12:45:24.298  2814  2870 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f,
,08-24 12:45:24.302  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:24.302  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 12:45:24.302  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 12:45:24.303  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 12:45:24.308  3922  3986 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 12:45:24.310  2814  2865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 12:45:24.310  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.311  2814  2870 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 12:45:24.312  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.312  3922  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 12:45:24.313  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
08-24 12:45:24.313  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 12:45:24.313  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.313  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:24.313  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 12:45:24.313  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:24.314  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 12:45:24.314  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 12:45:24.314  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:24.315  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-24 12:45:24.316  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:24.317  2814  2830 D BtGatt.GattService: stopScan() - queue size =1
,08-24 12:45:24.318  2814  2827 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 12:45:24.319  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-24 12:45:24.319  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 12:45:24.320  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 12:45:24.320  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 12:45:24.320  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 12:45:24.322  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.323  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 12:45:24.323  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 12:45:24.324  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 12:45:24.325  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.325  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-24 12:45:24.325  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.325  2814  2870 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 12:45:24.325  2814  2870 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 12:45:24.327  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 12:45:24.327  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.327  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.328  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.328  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.328  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.328  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.329  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.329  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.329  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.329  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.330  3922  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 12:45:24.333  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.341  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:24.341  2814  2865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:24.341  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.343  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:24.343  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:24.343  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:24.343  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 12:45:24.343  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 12:45:24.343  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:24.343  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 12:45:24.345  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.347  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.349  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 12:45:24.349  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.350  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 12:45:24.350  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 12:45:24.353  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 12:45:24.354  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 12:45:24.354  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 12:45:24.357  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 12:45:24.357  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:24.357  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 12:45:24.358  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:24.359  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 12:45:24.359  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.360  2814  2870 D BtGatt.ScanManager: stopping BLe Batch
,08-24 12:45:24.361  2814  3010 D BtGatt.GattService: registerClient() - UUID=a939ef54-bb2a-452c-99d8-fe6e94adff4b
,08-24 12:45:24.362  2814  2865 D BtGatt.GattService: onClientRegistered() - UUID=a939ef54-bb2a-452c-99d8-fe6e94adff4b, clientIf=5
,08-24 12:45:24.364  3922  3933 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 12:45:24.364  2814  2830 D BtGatt.GattService: start scan with filters
,08-24 12:45:24.366  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-24 12:45:24.366  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.366  2814  2870 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 12:45:24.366  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 12:45:24.368  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 12:45:24.369  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-24 12:45:24.370  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 12:45:24.371  2814  2865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 12:45:24.371  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.373  2814  2870 D BtGatt.ScanManager: handling starting scan
,08-24 12:45:24.378  2814  2865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 12:45:24.378  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.378  2814  2870 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 12:45:24.381  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:24.382  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:24.382  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 12:45:24.383  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 12:45:24.383  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.384  2814  2870 D BtGatt.ScanManager: Starting BLE batch scan
08-24 12:45:24.384  2814  2870 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 12:45:24.384  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 12:45:24.386  3922  3986 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 12:45:24.388  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:24.388  3922  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 12:45:24.388  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.388  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 12:45:24.388  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.389  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:24.389  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-24 12:45:24.389  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:24.389  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 12:45:24.389  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 12:45:24.389  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:24.389  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 12:45:24.390  3922  3986 D BluetoothAdapter: STATE_ON
08-24 12:45:24.390  2814  2827 D BtGatt.GattService: stopScan() - queue size =1
,08-24 12:45:24.391  2814  2830 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 12:45:24.391  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 12:45:24.391  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 12:45:24.391  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 12:45:24.391  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-24 12:45:24.391  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 12:45:24.392  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:24.392  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 12:45:24.393  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 12:45:24.393  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-24 12:45:24.393  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.393  2814  2865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:24.393  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.394  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.394  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.394  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.394  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.395  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.395  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.395  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.395  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.395  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.395  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.395  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.395  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.395  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.396  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.396  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.396  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.396  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.397  3922  3986 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-24 12:45:24.398  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:24.398  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 12:45:24.399  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.402  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:24.404  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:24.404  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:24.404  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 12:45:24.405  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.405  2814  2870 D BtGatt.ScanManager: stopping BLe Batch
,08-24 12:45:24.405  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 12:45:24.405  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 12:45:24.406  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-24 12:45:24.406  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:24.406  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 12:45:24.406  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.408  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.410  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 12:45:24.410  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 12:45:24.411  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 12:45:24.411  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.411  2814  2870 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 12:45:24.414  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 12:45:24.414  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 12:45:24.414  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 12:45:24.416  2814  2865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 12:45:24.416  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:24.417  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 12:45:24.417  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:24.417  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 12:45:24.418  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:24.419  2814  2827 D BtGatt.GattService: registerClient() - UUID=12387b1f-9f44-4fdc-b922-303935ae6ce3
,08-24 12:45:24.420  2814  2865 D BtGatt.GattService: onClientRegistered() - UUID=12387b1f-9f44-4fdc-b922-303935ae6ce3, clientIf=5
,08-24 12:45:24.420  3922  3934 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 12:45:24.420  2814  3010 D BtGatt.GattService: start scan with filters
,08-24 12:45:24.423  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-24 12:45:24.423  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-24 12:45:24.423  2814  2870 D BtGatt.ScanManager: handling starting scan
08-24 12:45:24.423  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 12:45:24.423  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 12:45:24.426  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:24.426  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 12:45:24.426  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 12:45:24.428  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 12:45:24.430  2814  2865 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 12:45:24.430  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.430  2814  2870 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 12:45:24.431  3922  3986 I io.jxcore.node.ConnectionHelper: start: OK
,08-24 12:45:24.431  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.431  3922  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 12:45:24.431  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:24.432  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 12:45:24.432  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.432  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:24.432  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 12:45:24.432  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:24.432  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 12:45:24.432  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 12:45:24.432  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:24.432  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 12:45:24.433  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:24.434  2814  2830 D BtGatt.GattService: stopScan() - queue size =1
08-24 12:45:24.434  2814  2827 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-24 12:45:24.435  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 12:45:24.435  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-24 12:45:24.435  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 12:45:24.436  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.435  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 12:45:24.436  2814  2870 D BtGatt.ScanManager: Starting BLE batch scan
,08-24 12:45:24.436  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 12:45:24.436  2814  2870 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 12:45:24.436  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 12:45:24.437  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.437  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 12:45:24.437  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 12:45:24.437  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 12:45:24.438  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 12:45:24.439  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 12:45:24.439  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.439  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:24.439  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.439  3922  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 12:45:24.440  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.440  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:24.440  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.440  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.440  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:24.440  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.440  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.440  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.440  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.440  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.441  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.441  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.442  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.442  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.443  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.443  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.444  3922  3986 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-24 12:45:24.444  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.444  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.444  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:24.445  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.445  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.445  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.445  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.445  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.445  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.445  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.445  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.448  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.449  2814  2865 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:24.449  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.448  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.449  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.450  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.450  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.450  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.450  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.451  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 12:45:24.452  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:24.452  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.452  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.452  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.452  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.452  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.452  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.452  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.452  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.452  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.453  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.453  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.453  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.453  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.454  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.454  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.454  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.454  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.455  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 12:45:24.455  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.455  3922  3986 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-24 12:45:24.455  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.456  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.456  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.456  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.456  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.456  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.456  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.456  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.457  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.457  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.457  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.457  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.457  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.457  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.458  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.458  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.458  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.458  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.459  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-24 12:45:24.459  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.459  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.459  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:24.460  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.460  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.460  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.460  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.460  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.461  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.461  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.461  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.461  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.461  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.461  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.461  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.461  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.461  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.461  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.462  2814  2865 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 12:45:24.462  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.462  2814  2870 D BtGatt.ScanManager: stopping BLe Batch
08-24 12:45:24.462  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 12:45:24.465  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 12:45:24.465  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-24 12:45:24.465  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-24 12:45:24.465  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-24 12:45:24.465  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-24 12:45:24.465  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.465  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.465  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.466  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.466  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.466  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.466  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.466  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.466  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.466  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.466  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.466  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.466  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.466  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.467  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.467  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 12:45:24.467  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.467  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.467  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 12:45:24.468  3922  3986 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 12:45:24.468  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-24 12:45:24.468  2814  2865 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 12:45:24.468  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.468  2814  2870 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 12:45:24.470  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-24 12:45:24.470  3922  3986 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-24 12:45:24.471  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-24 12:45:24.472  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-24 12:45:24.472  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-24 12:45:24.473  3922  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 12:45:24.473  3922  3986 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-24 12:45:24.473  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 12:45:24.473  3922  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 12:45:24.473  3922  3986 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-24 12:45:24.473  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 12:45:24.473  3922  3986 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-24 12:45:24.473  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-24 12:45:24.475  2814  2865 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 12:45:24.475  2814  2865 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:24.477  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-24 12:45:24.478  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-24 12:45:24.478  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-24 12:45:24.478  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-24 12:45:24.479  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-24 12:45:24.479  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,08-24 12:45:24.479  3922  3986 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-24 12:45:24.479  3922  3986 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-24 12:45:24.479  3922  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 401)
08-24 12:45:24.480  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.480  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.480  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.480  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.480  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.480  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.480  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-24 12:45:24.481  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.481  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.481  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.481  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.481  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.481  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.481  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.481  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.481  3922  4014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 12:45:24.481  3922  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 401
08-24 12:45:24.481  3922  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 401)
08-24 12:45:24.482  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.482  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.482  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.482  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.483  3922  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 401)
,08-24 12:45:24.482  3922  4015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 401)
08-24 12:45:24.486  3922  3986 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-24 12:45:24.487  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.487  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:24.487  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.487  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.487  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.487  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.487  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.487  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.487  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.487  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.487  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.487  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.487  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.487  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.488  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.488  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.488  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.488  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.489  3922  3986 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-24 12:45:24.489  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.489  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.489  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.489  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.489  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.489  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.489  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.489  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.489  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.489  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.489  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.489  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.490  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.490  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.490  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.490  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.490  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.490  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-24 12:45:24.491  3922  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 12:45:24.491  3922  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 12:45:24.491  3922  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 12:45:24.491  3922  3986 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-24 12:45:24.491  3922  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-24 12:45:24.491  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 12:45:24.491  3922  3986 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-24 12:45:24.491  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.491  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:24.492  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.492  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.492  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.492  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.492  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.492  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.492  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.492  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.492  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.492  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.492  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.492  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.493  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.493  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.493  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.493  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.493  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.493  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.493  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.493  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.493  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.493  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.493  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.494  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.494  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.494  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.494  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.494  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.494  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.494  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.494  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.494  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.494  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.494  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.494  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.494  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.494  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.494  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.494  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.495  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.495  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.495  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.495  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.495  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.495  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.495  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.495  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.495  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.495  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.496  3922  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-24 12:45:24.496  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:24.497  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-24 12:45:24.498  3922  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-24 12:45:24.498  3922  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-24 12:45:24.498  3922  3922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-24 12:45:24.498  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-24 12:45:24.498  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 12:45:24.498  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.498  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-24 12:45:24.498  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-24 12:45:24.498  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-24 12:45:24.498  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.498  3922  3986 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-24 12:45:24.499  3922  3922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-24 12:45:24.499  3922  4016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 12:45:24.499  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.499  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.499  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-24 12:45:24.499  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 12:45:24.499  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 12:45:24.499  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.499  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.500  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.500  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.500  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:24.500  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:24.500  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.500  3922  4016 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-24 12:45:24.500  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:24.500  3922  4016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-24 12:45:24.500  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:24.500  3922  4016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-24 12:45:24.501  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.501  3922  3922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-24 12:45:24.501  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.501  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.501  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.501  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.501  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.501  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.501  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:24.501  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.501  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.501  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.501  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.502  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.502  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.502  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.502  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.503  3922  3986 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-24 12:45:24.503  3922  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-24 12:45:24.503  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-24 12:45:24.504  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-24 12:45:24.504  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:24.504  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.504  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.504  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.504  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.504  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.504  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.504  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.504  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.504  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.504  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.504  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.504  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.504  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.505  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.505  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.505  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.505  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
,08-24 12:45:24.508  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.508  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.508  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:24.508  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:24.508  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:24.508  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.508  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
,08-24 12:45:24.508  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:24.509  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.509  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.509  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.509  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.509  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.509  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.509  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:24.509  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.509  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.509  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.510  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:24.510  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:24.510  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:24.510  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:24.510  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.510  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.511  3922  3986 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57be791 not in the list
08-24 12:45:24.511  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.511  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.511  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:24.511  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.511  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:24.511  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:24.511  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:24.511  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:24.511  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:24.512  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:24.512  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@175f6f6 not in the list
08-24 12:45:24.512  3922  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-24 12:45:24.512  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 12:45:24.512  3922  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-24 12:45:24.512  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-24 12:45:24.512  3922  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-24 12:45:24.513  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-24 12:45:24.514  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-24 12:45:24.514  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-24 12:45:24.514  3922  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-24 12:45:24.514  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 12:45:24.515  3922  3986 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-24 12:45:24.515  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-24 12:45:24.515  3922  3986 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-24 12:45:24.515  3922  3986 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-24 12:45:24.515  3922  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-24 12:45:24.515  3922  3986 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-24 12:45:24.515  3922  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-24 12:45:24.516  3922  3986 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-24 12:45:24.516  3922  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-24 12:45:24.516  3922  3986 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-24 12:45:24.516  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:24.516  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48764e8 added. We now have 2 listener(s)
08-24 12:45:24.516  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:24.518  3922  3986 D BluetoothAdapter: enable(): BT is already enabled..!
08-24 12:45:24.518   876  1968 D WifiService: setWifiEnabled: true pid=3922, uid=10000
08-24 12:45:24.518   876  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 12:45:24.518  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:24.518  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d4d701 added. We now have 3 listener(s)
08-24 12:45:24.519  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:24.522  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:24.522  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce809a6 added. We now have 4 listener(s)
08-24 12:45:24.522  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:24.523  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:24.523  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e20dfe7 added. We now have 5 listener(s)
08-24 12:45:24.523  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:24.524   876  1697 D WifiService: setWifiEnabled: false pid=3922, uid=10000
08-24 12:45:24.524   876  1697 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-24 12:45:24.529  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:24.529  2814  2861 D BluetoothAdapterState: Current state: ON, message: 23
08-24 12:45:24.529  2814  2861 D BluetoothAdapterProperties: Setting state to 13
08-24 12:45:24.529  2814  2861 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-24 12:45:24.530  2814  2861 D BluetoothAdapterProperties: onBluetoothDisable()
08-24 12:45:24.530  2814  2861 I BluetoothAdapterState: Entering PendingCommandState
08-24 12:45:24.531  2814  2865 D BluetoothAdapterProperties: Scan Mode:20
08-24 12:45:24.531  2814  2861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-24 12:45:24.532  2814  2814 D HeadsetService: Received stop request...Stopping profile...
08-24 12:45:24.535  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.535  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:24.536  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.536  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.536  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:24.538  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.540  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.542  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-24 12:45:24.543  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:24.543  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:24.543  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.543  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:24.544   876  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-24 12:45:24.544   876  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 12:45:24.545   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 12:45:24.545   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 12:45:24.547  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.549  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.551  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.554   876   889 I ActivityManager: Start proc 4019:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-24 12:45:24.557  1354  2083 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:24.557  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-24 12:45:24.557   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:24.557   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:24.558   876  2091 D DhcpClient: Clearing IP address
08-24 12:45:24.558   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:24.558   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-24 12:45:24.559  1955  2252 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:24.560  2814  2814 D A2dpService: Received stop request...Stopping profile...
08-24 12:45:24.560  2814  2994 D A2dpStateMachine: Exit Disconnected: -1
08-24 12:45:24.561   372   874 D CommandListener: Setting iface cfg
08-24 12:45:24.561   876   876 D BluetoothA2dp: Proxy object disconnected
08-24 12:45:24.562  2814  2814 D BluetoothMapService: onReceive
08-24 12:45:24.562  2814  2814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 12:45:24.562  2814  2814 D BluetoothMapService: STATE_TURNING_OFF
08-24 12:45:24.562  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-24 12:45:24.562   876  2102 D DhcpClient: Receive thread stopped
08-24 12:45:24.562  2814  2814 D HidService: Received stop request...Stopping profile...
08-24 12:45:24.563  2814  2814 D HidService: Stopping Bluetooth HidService
08-24 12:45:24.563  1499  2543 V NativeCrypto: Read error: ssl=0x9b723400: I/O error during system call, Connection timed out
08-24 12:45:24.564  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.564  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.564  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.564  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.564  1499  2543 V NativeCrypto: SSL shutdown failed: ssl=0x9b723400: I/O error during system call, Broken pipe
08-24 12:45:24.565  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-24 12:45:24.565  1354  1354 D HidProfile: Bluetooth service disconnected
08-24 12:45:24.566   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 12:45:24.566   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-24 12:45:24.568   876  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
08-24 12:45:24.569   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 12:45:24.570   396   396 E Parcel  : Reading a NULL string not supported here.
08-24 12:45:24.566  2814  2814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-24 12:45:24.572  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.572  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.572  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.572  2814  2865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 12:45:24.573  2814  2865 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-24 12:45:24.576   372   874 D CommandListener: Clearing all IP addresses on wlan0
08-24 12:45:24.576  2814  2814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-24 12:45:24.577  2814  2814 D HealthService: Received stop request...Stopping profile...
08-24 12:45:24.581   876  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-24 12:45:24.584  2814  2814 D PanService: Received stop request...Stopping profile...
08-24 12:45:24.585  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.585  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.585  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.585  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.586  2814  2814 D BluetoothMapService: Received stop request...Stopping profile...
08-24 12:45:24.586  2814  2814 D BluetoothMapService: stop()
08-24 12:45:24.587   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 12:45:24.587  2814  2814 D BluetoothMapAppObserver: deinitObservers()
08-24 12:45:24.587  2814  2814 D BluetoothMapAppObserver: removeReceiver()
08-24 12:45:24.589  2814  2865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-24 12:45:24.589  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.590  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.590  2814  2982 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 12:45:24.590  2814  2982 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 12:45:24.590  2814  2982 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 12:45:24.590  2814  2982 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 12:45:24.590  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:24.590  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:24.590  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.590  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:24.592  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:24.592  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:24.593  1855  2299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 12:45:24.593  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:24.593  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:24.594  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 12:45:24.594  1354  1354 D PanProfile: Bluetooth service disconnected
08-24 12:45:24.594  1354  1354 D BluetoothMap: Proxy object disconnected
08-24 12:45:24.594  2814  2814 I BtOppRfcommListener: stopping Accept Thread
08-24 12:45:24.594  1354  1354 D MapProfile: Bluetooth service disconnected
08-24 12:45:24.594  2814  3544 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 12:45:24.594  2814  3544 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-24 12:45:24.595  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.595  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.595  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.595  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.595  2814  2814 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 12:45:24.595  2814  2814 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.596  2814  2814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-24 12:45:24.596  2814  2814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 12:45:24.596  2814  2865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 12:45:24.596  2814  2865 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.596   876  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.596  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.597  2814  2814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-24 12:45:24.597  2814  2814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 12:45:24.598  2814  2814 D BluetoothMapService: MAP Service closeService in
08-24 12:45:24.598  2814  2814 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 12:45:24.598  2814  2814 D ObexServerSockets0: shutdown(block = true)
08-24 12:45:24.598  2814  2814 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 12:45:24.598  2814  3012 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 12:45:24.598  2814  2814 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 12:45:24.598  2814  2988 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 12:45:24.599  2814  3011 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 12:45:24.599  2814  2814 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:24.599  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:24.599  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:24.599  2814  2814 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:24.599  2814  2861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 12:45:24.599  2814  2861 D BluetoothAdapterProperties: Setting state to 15
08-24 12:45:24.599  2814  2861 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 12:45:24.600  2814  2814 D BluetoothMapService: cleanup()
08-24 12:45:24.600  2814  2861 I BluetoothAdapterState: Entering BleOnState
08-24 12:45:24.600  2814  2814 D BluetoothMapService: MAP Service closeService in
08-24 12:45:24.600   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:24.600   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 12:45:24.600  1354  1366 D BluetoothMap: onBluetoothStateChange: up=false
08-24 12:45:24.601   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:24.601  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:24.601   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:24.601  1354  3921 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 12:45:24.602  1354  2083 D BluetoothPan: onBluetoothStateChange on: false
08-24 12:45:24.603  1955  2252 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:24.603  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 12:45:24.604  1354  3921 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 12:45:24.605  2814  2861 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 12:45:24.605  2814  2861 D BluetoothAdapterProperties: Setting state to 16
08-24 12:45:24.605  2814  2861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 12:45:24.606  2814  2861 D BluetoothAdapterProperties: onBleDisable
08-24 12:45:24.606  2814  2861 I BluetoothAdapterState: Entering PendingCommandState
08-24 12:45:24.607  2814  2862 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-24 12:45:24.607  2814  2865 D BluetoothAdapterProperties: Scan Mode:20
08-24 12:45:24.607  2814  2982 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-24 12:45:24.607  2814  2982 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:24.608  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.609  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.610  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.613  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:24.625   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:24.636  4019  4019 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-24 12:45:24.642   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:24.643   876  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-24 12:45:24.643   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:24.644   876   893 D Tethering: MasterInitialState.processMessage what=3
08-24 12:45:24.647  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.647  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:24.648  3514  3514 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@73ffdef and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-24 12:45:24.648  2026  2026 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-24 12:45:24.658  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 12:45:24.662  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:24.665   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1dfb68:true
,08-24 12:45:24.674   876   886 I ActivityManager: Start proc 4038:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-24 12:45:24.682  4019  4019 D LocalBluetoothProfileManager: Adding local MAP profile
,08-24 12:45:24.685  4019  4019 D BluetoothMap: Create BluetoothMap proxy object
,08-24 12:45:24.687   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-24 12:45:24.688   876  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-24 12:45:24.694  4019  4019 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-24 12:45:24.705  4038  4038 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-24 12:45:24.706  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:24.715   876  1968 I ActivityManager: Killing 3514:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 12:45:24.807  2814  2865 I bt_hci  : shut_down
08-24 12:45:24.808  2814  2871 D bt_hwcfg: hw_epilog_process
,08-24 12:45:24.815  2814  2871 I bt_vendor: low_power_mode_cb
,08-24 12:45:24.839  2814  2871 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 12:45:24.839  2814  2871 I bt_vendor: epilog_cb
08-24 12:45:24.839  2814  2871 I bt_hci  : epilog_finished_callback
,08-24 12:45:24.845  2814  2865 I bt_hci_h4: hal_close
,08-24 12:45:24.846  2814  2865 I bt_userial_vendor: device fd = 51 close
,08-24 12:45:24.909  4038  4038 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.909  4038  4038 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.909  4038  4038 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.909  4038  4038 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.909  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.921  4038  4038 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.k.d(PG:583)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.e.b(PG:170)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.921  4038  4038 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 12:45:24.921  4038  4038 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.io.File.exists(File.java:361)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.921,  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.921  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.922  4038  4038 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 12:45:24.922  4038  4038 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-24 12:45:24.955   876  1394 I ActivityManager: Start proc 4069:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-24 12:45:24.958   876  1394 I ActivityManager: Killing 3582:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-24 12:45:25.001  3922  3922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 12:45:25.014  2814  2862 D bt_stack_manager: event_shut_down_stack finished.
,08-24 12:45:25.015  2814  2861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 12:45:25.018  2814  2814 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 12:45:25.018  2814  2861 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-24 12:45:25.019  2814  2814 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 12:45:25.019  2814  2814 D BtGatt.GattService: stop()
08-24 12:45:25.019  2814  2814 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 12:45:25.029  2814  2814 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:25.029  2814  2814 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:25.029  2814  2814 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:25.029  2814  2814 V BluetoothAdapterState: isBleTurningOff()=true
08-24 12:45:25.029  2814  2861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-24 12:45:25.030  2814  2861 D BluetoothAdapterProperties: Setting state to 10
08-24 12:45:25.030  2814  2861 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 12:45:25.031  2814  2861 I BluetoothAdapterState: Entering OffState
,08-24 12:45:25.033   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-24 12:45:25.046  2814  2814 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 12:45:25.046  2814  2814 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 12:45:25.046  2814  2814 I BluetoothServiceJni: cleanupNative: return from cleanup
08-24 12:45:25.047  2814  2862 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-24 12:45:25.051  4069  4069 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-24 12:45:25.054  2814  2862 D bt_stack_manager: event_clean_up_stack finished.
,08-24 12:45:25.060  2814  2814 I art     : System.exit called, status: 0
,08-24 12:45:25.060  2814  2814 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 12:45:25.133   876   887 I ActivityManager: Process com.android.bluetooth (pid 2814) has died
,08-24 12:45:25.282  4069  4088 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-24 12:45:25.283  4069  4088 I Babel_SMS: MmsConfig.loadMmsSettings
08-24 12:45:25.284  4069  4088 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-24 12:45:25.284  4069  4088 I Babel_SMS: MmsConfig.loadFromDatabase
,08-24 12:45:25.378  4069  4088 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-24 12:45:25.378  4069  4088 I Babel_SMS: MmsConfig.loadFromResources
08-24 12:45:25.380  4069  4088 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-24 12:45:25.380  4069  4088 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-24 12:45:25.413  4069  4069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 12:45:25.429  4069  4069 I Babel_Crash: startup - clean
,08-24 12:45:25.465  4069  4069 I Babel_telephony: TeleModule.launchCompleted
,08-24 12:45:25.475   876  1394 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 12:45:25.482  4069  4069 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-24 12:45:25.489  4069  4069 W Babel   : BAM#gBA: invalid account id: -1
,08-24 12:45:25.498  4038  4058 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-24 12:45:25.489  4069  4069 W Babel   : BAM#gBA: invalid account id: -1
,08-24 12:45:25.500  4069  4069 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-24 12:45:25.503  4069  4094 I Babel   : deleted: false for 0
,08-24 12:45:25.511   876  2003 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-24 12:45:25.554  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 12:45:25.587   876  2003 I ActivityManager: Start proc 4098:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-24 12:45:25.596  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:25.612  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 12:45:25.677  4069  4069 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-24 12:45:25.690  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 12:45:25.692  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 12:45:25.717  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 12:45:25.735  4069  4069 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-24 12:45:25.753  4069  4069 I vclib   : onServiceConnected
,08-24 12:45:25.771  4098  4098 D AdapterServiceConfig: Adding HeadsetService
,08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding A2dpService
08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding HidService
08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding HealthService
,08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding PanService
08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding GattService
,08-24 12:45:25.772  4098  4098 D AdapterServiceConfig: Adding BluetoothMapService
08-24 12:45:25.775   876  1394 I ActivityManager: Killing 3117:android.process.acore/u0a5 (adj 15): empty #17
,08-24 12:45:25.782   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@766875e:true
,08-24 12:45:25.871  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:25.896  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 12:45:25.907  1706  1706 D SystemUpdateService: onCreate
,08-24 12:45:25.914  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 12:45:25.926  1706  4110 I SystemUpdateService: active receiver: enabled
,08-24 12:45:25.931  1706  4110 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 12:45:25.933  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 12:45:25.935  1706  2520 I iu.UploadsManager: num queued entries: 0
,08-24 12:45:25.935  1706  2520 I iu.UploadsManager: num updated entries: 0
08-24 12:45:25.937  1706  2520 I iu.SyncManager: NEXT; no task
,08-24 12:45:25.937  1706  4110 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 12:45:25.938  1706  4110 I SystemUpdateService: now status is 0 (complete)
08-24 12:45:25.938  1706  4110 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 12:45:25.939  1706  4110 I SystemUpdateService: file has been verified
,08-24 12:45:25.939  1706  4110 I SystemUpdateService: OTA package size = 12249756
,08-24 12:45:25.942  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 12:45:25.944  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 12:45:25.946  1706  4110 I SystemUpdateService: showing system update notification
,08-24 12:45:25.958  1706  1706 D SystemUpdateService: onDestroy
,08-24 12:45:25.973   876  1951 I ActivityManager: Start proc 4112:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-24 12:45:26.011  4112  4112 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-24 12:45:26.013  4112  4112 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:26.018  4112  4112 D SprintDMHelper: simOperator: 
08-24 12:45:26.018  4112  4112 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 12:45:26.034   876  1962 I ActivityManager: Start proc 4124:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-24 12:45:26.035   876  1962 I ActivityManager: Killing 3773:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-24 12:45:26.161   876  1952 I ActivityManager: Start proc 4139:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-24 12:45:26.165  4069  4138 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-24 12:45:26.168   876  1381 I ActivityManager: Killing 3789:com.android.musicfx/u0a18 (adj 15): empty #17
,08-24 12:45:26.231  4139  4139 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-24 12:45:26.279  4139  4139 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-24 12:45:26.279  4139  4139 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-24 12:45:26.279  4139  4139 I GAv4    :   adb logcat -s GAv4
,08-24 12:45:26.293  4139  4139 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-24 12:45:26.302  4139  4139 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-24 12:45:26.338  4139  4157 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-24 12:45:26.447  4139  4139 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-24 12:45:26.485  4139  4139 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-24 12:45:26.498  4139  4139 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 6927-6935)
,08-24 12:45:26.499  4139  4139 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 12:45:26.509  4139  4139 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0ffe71}
,08-24 12:45:26.509  4139  4139 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-24 12:45:26.510  4139  4139 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-24 12:45:26.518  4139  4139 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-24 12:45:26.520  4139  4139 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-24 12:45:26.539  4139  4139 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-24 12:45:26.557  4139  4139 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-24 12:45:26.557  4139  4139 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 12:45:26.557  4139  4139 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 12:45:26.557  4139  4139 I Adreno  : Build Date                       : 10/20/15
08-24 12:45:26.557  4139  4139 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 12:45:26.557  4139  4139 I Adreno  : Local Branch                     : M14
08-24 12:45:26.557  4139  4139 I Adreno  : Remote Branch                    : 
08-24 12:45:26.557  4139  4139 I Adreno  : Remote Branch                    : 
08-24 12:45:26.557  4139  4139 I Adreno  : Reconstruct Branch               : 
,08-24 12:45:26.623  4139  4139 I NSApplication: Starting up...
,08-24 12:45:26.633  4139  4186 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-24 12:45:26.672   876  3181 I ActivityManager: Start proc 4191:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-24 12:45:26.674   876  3181 I ActivityManager: Killing 3561:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-24 12:45:26.793  4191  4191 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-24 12:45:26.985   876  1381 I ActivityManager: Killing 3811:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-24 12:45:27.539   876  1951 D WifiService: setWifiEnabled: true pid=3922, uid=10000
08-24 12:45:27.540   876  1951 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 12:45:27.552   876  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-24 12:45:27.560  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:27.560  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:27.561  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:27.561  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:27.564  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:27.565  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:27.565  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:27.565  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:27.593   876  1311 D WifiConfigStore: loaded 0 passpoint configs
,08-24 12:45:27.594   876  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 12:45:27.595   876  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 12:45:27.596   876  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-24 12:45:27.596   876  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 12:45:27.596   876  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 12:45:27.596   876  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 12:45:27.615   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-24 12:45:27.617   372   874 D CommandListener: Setting iface cfg
08-24 12:45:27.618   876  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-24 12:45:27.618   876  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 12:45:27.623   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 12:45:27.634   876  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 12:45:27.634   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 12:45:27.635   876  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 12:45:29.179   876  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.89 rxSuccessRate=2.09 delta 1000 -> 1000
08-24 12:45:29.181   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 12:45:29.181   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:29.196   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 12:45:29.242   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 12:45:29.247  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 12:45:29.666  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 12:45:29.708  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 12:45:29.708  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 12:45:29.714   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 12:45:29.727   876  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 12:45:29.728   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-24 12:45:29.728   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:29.755   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:29.769   372   874 D CommandListener: Setting iface cfg
08-24 12:45:29.769   876  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,08-24 12:45:29.783   876  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-24 12:45:29.784   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 12:45:29.797   876  4215 D DhcpClient: Receive thread started
,08-24 12:45:29.875   876  1311 E native  : do suspend false
,08-24 12:45:29.894   876  2091 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 12:45:29.910   876  4215 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172683, domain null
08-24 12:45:29.911   876  2091 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172683 seconds
,08-24 12:45:29.914   876  2091 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 12:45:29.928   876  4215 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 12:45:29.928   876  2091 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 12:45:29.934   372   874 D CommandListener: Setting iface cfg
,08-24 12:45:29.939   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 12:45:29.943   876  2091 D DhcpClient: Scheduling renewal in 86399s
,08-24 12:45:29.950   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 12:45:29.951   876  1311 D WifiConfigStore: No blacklist allowed without epno enabled
08-24 12:45:29.953   876  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 12:45:29.953   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 12:45:29.954   876  1313 D ConnectivityService: Adding iface wlan0 to network 101
08-24 12:45:29.957   876  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 12:45:30.005   876  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-24 12:45:30.006   876  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-24 12:45:30.007   876  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-24 12:45:30.009   876  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-24 12:45:30.010   876  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-24 12:45:30.017   876  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-24 12:45:30.022   876  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-24 12:45:30.023   876  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-24 12:45:30.023   876  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-24 12:45:30.023   876  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-24 12:45:30.023   876  1313 D ConnectivityService:    accepting network in place of null
08-24 12:45:30.024   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 12:45:30.024   876  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 12:45:30.035   876  4214 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140472, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 12:45:30.052   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:30.091   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:30.096   876  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 12:45:30.096   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 12:45:30.098   876  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-24 12:45:30.101   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-24 12:45:30.103   876  4213 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:81b::200e
08-24 12:45:30.114  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:30.114  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:30.114  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.115  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:30.119  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:30.119  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:30.119  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.119  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:30.125  2026  2026 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-24 12:45:30.125  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 12:45:30.128  1706  1706 D SystemUpdateService: onCreate
,08-24 12:45:30.132  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 12:45:30.135  1706  4225 I SystemUpdateService: active receiver: enabled
,08-24 12:45:30.138  1706  4225 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 12:45:30.142  1706  4225 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 12:45:30.143  1706  4225 I SystemUpdateService: now status is 0 (complete)
08-24 12:45:30.143  1706  4225 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 12:45:30.143  1706  4225 I SystemUpdateService: file has been verified
08-24 12:45:30.143  1706  4225 I SystemUpdateService: OTA package size = 12249756
,08-24 12:45:30.151  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 12:45:30.155  1706  4228 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 12:45:30.155  1706  4228 W BaseAppContext: Using Auth Proxy for data requests.
08-24 12:45:30.155  1706  2520 I iu.UploadsManager: num queued entries: 0
08-24 12:45:30.156  1706  2520 I iu.UploadsManager: num updated entries: 0
08-24 12:45:30.156  1706  4228 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 12:45:30.158  1706  4225 I SystemUpdateService: showing system update notification
,08-24 12:45:30.159  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-24 12:45:30.157  1706  2520 I iu.SyncManager: NEXT; no task
,08-24 12:45:30.160  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 12:45:30.163  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:30.164  4112  4112 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:30.164  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:30.168  4112  4112 D SprintDMHelper: simOperator: 
,08-24 12:45:30.168  4112  4112 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 12:45:30.175   876  4213 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 10:45:30 GMT], X-Android-Received-Millis=[1472035530174], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472035530151]}
,08-24 12:45:30.175   876  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-24 12:45:30.176   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-24 12:45:30.176   876  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-24 12:45:30.176   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 12:45:30.180  1706  1706 D SystemUpdateService: onDestroy
,08-24 12:45:30.198  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-24 12:45:30.198  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 12:45:30.198  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:30.198  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:30.210  1706  4228 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-24 12:45:30.211  4069  4069 I art     : Waiting for a blocking GC DisableMovingGc
,08-24 12:45:30.214  4069  4069 I art     : Starting a blocking GC DisableMovingGc
,08-24 12:45:30.339  4069  4231 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 12:45:30.454   876  1697 I ActivityManager: Killing 3737:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-24 12:45:30.547   876  1697 D WifiService: setWifiEnabled: false pid=3922, uid=10000
,08-24 12:45:30.548   876  1697 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 12:45:30.559  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-24 12:45:30.563   876  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-24 12:45:30.563   876  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-24 12:45:30.563   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 12:45:30.564   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:30.579   876  2091 D DhcpClient: Clearing IP address
08-24 12:45:30.579   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-24 12:45:30.582   372   874 D CommandListener: Setting iface cfg
,08-24 12:45:30.591  1499  4235 V NativeCrypto: Read error: ssl=0x99cff200: I/O error during system call, Connection timed out
,08-24 12:45:30.593  1499  4235 V NativeCrypto: SSL shutdown failed: ssl=0x99cff200: I/O error during system call, Broken pipe
,08-24 12:45:30.600   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-24 12:45:30.600   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-24 12:45:30.603   396   396 E Parcel  : Reading a NULL string not supported here.
08-24 12:45:30.605   876  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
08-24 12:45:30.608   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-24 12:45:30.617   876  4215 D DhcpClient: Receive thread stopped
08-24 12:45:30.618   372   874 D CommandListener: Clearing all IP addresses on wlan0
,08-24 12:45:30.628   876  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-24 12:45:30.632   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
08-24 12:45:30.635  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:30.635  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:30.635  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.635  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:30.635  1855  2299 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 12:45:30.636  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:30.636  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:30.636  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:30.636  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:30.637   876  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-24 12:45:30.676   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:30.703   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:30.704   876  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-24 12:45:30.704   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-24 12:45:30.711   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-24 12:45:30.713  2026  2026 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-24 12:45:30.713  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:30.715  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:30.726  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 12:45:30.731  1706  1706 D SystemUpdateService: onCreate
,08-24 12:45:30.741  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 12:45:30.761  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-24 12:45:30.763  1706  2520 I iu.UploadsManager: num queued entries: 0
,08-24 12:45:30.764  1706  4246 I SystemUpdateService: active receiver: enabled
,08-24 12:45:30.767  1706  2520 I iu.UploadsManager: num updated entries: 0
,08-24 12:45:30.767  1706  2520 I iu.SyncManager: NEXT; no task
,08-24 12:45:30.770  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 12:45:30.771  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 12:45:30.772  4112  4112 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:30.776  4112  4112 D SprintDMHelper: simOperator: 
,08-24 12:45:30.776  4112  4112 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 12:45:30.813  1706  4246 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 12:45:30.813  4069  4249 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-24 12:45:30.814   372   874 E Netd    : netlink response contains error (No such file or directory)
,08-24 12:45:30.816   876  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-24 12:45:30.820  1706  4246 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-24 12:45:30.821  1706  4246 I SystemUpdateService: now status is 0 (complete)
08-24 12:45:30.821  1706  4246 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-24 12:45:30.821  1706  4246 I SystemUpdateService: file has been verified
08-24 12:45:30.821  1706  4246 I SystemUpdateService: OTA package size = 12249756
,08-24 12:45:30.830  1706  4246 I SystemUpdateService: showing system update notification
,08-24 12:45:30.845  1706  1706 D SystemUpdateService: onDestroy
,08-24 12:45:31.097   876  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-24 12:45:33.605   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb46539:true
08-24 12:45:33.605  4098  4098 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 12:45:33.611  4098  4098 I bt_bluedroid: init
,08-24 12:45:33.612  4098  4252 I BluetoothAdapterState: Entering OffState
,08-24 12:45:33.617  4098  4253 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-24 12:45:33.617  4098  4253 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-24 12:45:33.617  4098  4253 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 12:45:33.618  4098  4253 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 12:45:33.620  4098  4098 I bt_bluedroid: get_profile_interface socket
,08-24 12:45:33.622  4098  4098 I bt_bluedroid: get_profile_interface sdp
08-24 12:45:33.626  4098  4108 I bt_bluedroid: config_hci_snoop_log
08-24 12:45:33.628   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-24 12:45:33.628  4098  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 12:45:33.633  4098  4256 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 12:45:33.634  4098  4252 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 12:45:33.636  4098  4252 D BluetoothAdapterProperties: Setting state to 14
,08-24 12:45:33.636  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 12:45:33.642  4098  4252 D BluetoothBondStateMachine: make
,08-24 12:45:33.647  4098  4257 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 12:45:33.654  4098  4252 I BluetoothAdapterState: Entering PendingCommandState
,08-24 12:45:33.656  4098  4098 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-24 12:45:33.659  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:33.660  4098  4098 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 12:45:33.661  4098  4098 D BtGatt.GattService: Received start request. Starting profile...
08-24 12:45:33.661  4098  4098 D BtGatt.GattService: start()
,08-24 12:45:33.661  4098  4098 I bt_bluedroid: get_profile_interface gatt
,08-24 12:45:33.663  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:33.663  4098  4098 D BtGatt.AdvertiseManager: advertise manager created
,08-24 12:45:33.671  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:33.671  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:33.672  4098  4098 V BluetoothAdapterState: isBleTurningOn()=true
08-24 12:45:33.672  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:33.672  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-24 12:45:33.673  4098  4252 I bt_bluedroid: enable
,08-24 12:45:33.675  4098  4253 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 12:45:33.675  4098  4253 I bt_hci  : start_up
,08-24 12:45:33.682  4098  4253 I bt_vendor: alloc value 0xb39f9189
,08-24 12:45:33.682  4098  4253 I bt_vendor: init
08-24 12:45:33.682  4098  4253 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 12:45:33.682  4098  4253 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 12:45:33.791  4098  4253 D bt_hci  : start_up starting async portion
,08-24 12:45:33.792  4098  4260 I bt_hci  : event_finish_startup
,08-24 12:45:33.792  4098  4260 I bt_hci_h4: hal_open
08-24 12:45:33.792  4098  4260 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-24 12:45:33.799  4098  4260 I bt_userial_vendor: device fd = 51 open
,08-24 12:45:33.832  4098  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 12:45:33.865  4098  4260 D bt_hwcfg: Chipset BCM4354A2
08-24 12:45:33.865  4098  4260 D bt_hwcfg: Target name = [BCM4354A2]
08-24 12:45:33.865  4098  4260 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 12:45:34.511  4098  4260 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 12:45:34.513  4098  4260 D bt_hwcfg: Settlement delay -- 100 ms
08-24 12:45:34.513  4098  4260 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 12:45:34.630  4098  4260 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 12:45:34.631  4098  4260 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 12:45:34.661  4098  4260 I bt_hwcfg: vendor lib fwcfg completed
,08-24 12:45:34.661  4098  4260 I bt_vendor: firmware callback
08-24 12:45:34.661  4098  4260 I bt_hci  : firmware_config_callback
,08-24 12:45:34.673  4098  4264 I bt_btu  : btu_task pending for preload complete event
,08-24 12:45:34.673  4098  4264 I bt_btu_task: Bluetooth chip preload is complete
,08-24 12:45:34.674  4098  4264 I bt_btu  : btu_task received preload complete event
,08-24 12:45:34.684  4098  4264 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 12:45:34.684  4098  4264 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 12:45:34.684  4098  4264 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 12:45:34.684  4098  4264 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 12:45:34.685  4098  4264 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 12:45:34.685  4098  4264 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 12:45:34.685  4098  4264 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 12:45:34.685  4098  4264 I         : BTE_InitTraceLevels -- TRC_BTM
08-24 12:45:34.686  4098  4264 I         : BTE_InitTraceLevels -- TRC_GAP
,08-24 12:45:34.686  4098  4264 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 12:45:34.686  4098  4264 I         : BTE_InitTraceLevels -- TRC_SDP
08-24 12:45:34.686  4098  4264 I         : BTE_InitTraceLevels -- TRC_GATT
,08-24 12:45:34.687  4098  4264 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 12:45:34.687  4098  4264 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-24 12:45:34.687  4098  4264 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 12:45:34.819  4098  4264 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-24 12:45:34.819  4098  4264 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-24 12:45:34.839  4098  4256 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 12:45:34.842  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 12:45:34.843  4098  4256 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 12:45:34.846  4098  4256 D BluetoothAdapterProperties: Name is: Nexus 6
08-24 12:45:34.850  4098  4256 D BluetoothAdapterProperties: Scan Mode:20
,08-24 12:45:34.851  4098  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 12:45:34.851  4098  4256 D bt_hci  : do_postload posting postload work item
08-24 12:45:34.851  4098  4260 I bt_hci  : event_postload
08-24 12:45:34.851  4098  4260 I bt_vendor: sco_config_cb
,08-24 12:45:34.851  4098  4260 I bt_hci  : sco_config_callback postload finished.
08-24 12:45:34.854  4098  4256 D bt_bte_conf: Device ID record 1 : primary
08-24 12:45:34.854  4098  4256 D bt_bte_conf:   vendorId            = 000f
,08-24 12:45:34.855  4098  4256 D bt_bte_conf:   vendorIdSource      = 0001
08-24 12:45:34.855  4098  4256 D bt_bte_conf:   product             = 1200
08-24 12:45:34.855  4098  4256 D bt_bte_conf:   version             = 1436
08-24 12:45:34.855  4098  4256 D bt_bte_conf:   clientExecutableURL = 
08-24 12:45:34.855  4098  4256 D bt_bte_conf:   serviceDescription  = 
08-24 12:45:34.855  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:34.856  4098  4256 D bt_bte_conf:   documentationURL    = 
,08-24 12:45:34.856  4098  4256 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-24 12:45:34.856  4098  4253 D bt_stack_manager: event_start_up_stack finished
08-24 12:45:34.858  4098  4260 I bt_vendor: low_power_mode_cb
08-24 12:45:34.859  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 12:45:34.859  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:34.860  4098  4252 D BluetoothAdapterProperties: Setting state to 15
08-24 12:45:34.860  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-24 12:45:34.860  4098  4252 I BluetoothAdapterState: Entering BleOnState
,08-24 12:45:34.866  4098  4252 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 12:45:34.867  4098  4252 D BluetoothAdapterProperties: Setting state to 11
,08-24 12:45:34.867  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 12:45:34.877  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:34.877  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:34.878  4098  4098 D HeadsetService: Received start request. Starting profile...
,08-24 12:45:34.880  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:34.881  4098  4098 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-24 12:45:34.881  4098  4098 D HeadsetStateMachine: make
,08-24 12:45:34.891  4098  4252 I BluetoothAdapterState: Entering PendingCommandState
,08-24 12:45:34.892  4098  4098 D HeadsetStateMachine: max_hf_connections = 1
,08-24 12:45:34.892  4098  4098 I bt_bluedroid: get_profile_interface handsfree
08-24 12:45:34.893  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-24 12:45:34.893  4098  4256 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 12:45:34.898  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:34.899  4098  4098 D A2dpService: Received start request. Starting profile...
,08-24 12:45:34.899  4098  4098 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 12:45:34.899  4098  4098 I bt_bluedroid: get_profile_interface avrcp
,08-24 12:45:34.906  4098  4098 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 12:45:34.906  4098  4098 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 12:45:34.906  4098  4098 D A2dpStateMachine: make
,08-24 12:45:34.907  4098  4098 I bt_bluedroid: get_profile_interface a2dp
,08-24 12:45:34.908  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 12:45:34.911  4098  4273 D A2dpStateMachine: Enter Disconnected: -2
,08-24 12:45:34.911  4098  4098 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 12:45:34.912  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:34.913  4019  4019 D BluetoothInputDevice: Proxy object connected
,08-24 12:45:34.913  4098  4098 D HidService: Received start request. Starting profile...
08-24 12:45:34.913  4098  4098 I bt_bluedroid: get_profile_interface hidhost
08-24 12:45:34.913  4098  4256 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-24 12:45:34.913  4019  4019 D HidProfile: Bluetooth service connected
,08-24 12:45:34.913  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 12:45:34.914  4098  4098 D HidService: setHidService(): set to: null
08-24 12:45:34.914  4098  4098 I BluetoothHealthServiceJni: classInitNative: succeeds
08-24 12:45:34.915  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:34.915  4098  4098 D HealthService: Received start request. Starting profile...
,08-24 12:45:34.917  4098  4098 I bt_bluedroid: get_profile_interface health
,08-24 12:45:34.918  4098  4098 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 12:45:34.918  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:34.919  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:34.921  4019  4019 D BluetoothPan: BluetoothPAN Proxy object connected
,08-24 12:45:34.921  4098  4098 D PanService: Received start request. Starting profile...
08-24 12:45:34.921  4098  4098 D BluetoothPanServiceJni: initializeNative(L110): pan
08-24 12:45:34.921  4098  4098 I bt_bluedroid: get_profile_interface pan
08-24 12:45:34.921  4019  4019 D PanProfile: Bluetooth service connected
,08-24 12:45:34.922  4098  4256 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 12:45:34.925  4098  4098 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:34.927  4019  4019 D BluetoothMap: Proxy object connected
08-24 12:45:34.927  4098  4098 D BluetoothMapService: Received start request. Starting profile...
08-24 12:45:34.927  4098  4098 D BluetoothMapService: start()
,08-24 12:45:34.928  4019  4019 D MapProfile: Bluetooth service connected
,08-24 12:45:34.928  4019  4019 D BluetoothMap: getConnectedDevices()
,08-24 12:45:34.929  4019  4019 D BluetoothMap: Bluetooth is Not enabled
08-24 12:45:34.930  4098  4098 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 12:45:34.931  4098  4098 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-24 12:45:34.931  4098  4098 D BluetoothMapAppObserver: createReceiver()
,08-24 12:45:34.932  4098  4098 D BluetoothMapAppObserver: initObservers()
,08-24 12:45:34.932  4098  4098 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 12:45:34.939  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:34.939  4098  4098 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:34.939  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:34.939  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:34.941  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:34.941  4098  4098 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:34.941  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:34.941  4098  4271 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 12:45:34.941  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isTurningOn()=true
,08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isTurningOn()=true
,08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 12:45:34.942  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:34.944  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:34.944  4098  4098 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:34.945  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:34.945  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-24 12:45:34.945  4098  4252 D BluetoothAdapterProperties: ScanMode =  20
,08-24 12:45:34.945  4098  4252 D BluetoothAdapterProperties: State =  11
,08-24 12:45:34.946  4098  4252 D BluetoothAdapterProperties: Setting state to 12
08-24 12:45:34.946  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 12:45:34.946   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:34.947   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-24 12:45:34.947  4098  4252 I BluetoothAdapterState: Entering OnState
,08-24 12:45:34.948  4098  4256 D BluetoothAdapterProperties: Scan Mode:21
08-24 12:45:34.948  4098  4256 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 12:45:34.949  1354  2083 D BluetoothMap: onBluetoothStateChange: up=true
08-24 12:45:34.950   876   876 D BluetoothA2dp: Proxy object connected
08-24 12:45:34.952  1354  1354 D BluetoothMap: Proxy object connected
08-24 12:45:34.952  1354  1354 D MapProfile: Bluetooth service connected
08-24 12:45:34.952  1354  1354 D BluetoothMap: getConnectedDevices()
,08-24 12:45:34.954   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:34.954  4019  4030 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 12:45:34.955  1354  1366 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:34.955  4019  4031 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:34.956  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-24 12:45:34.957   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:34.957  4019  4030 D BluetoothMap: onBluetoothStateChange: up=true
08-24 12:45:34.958  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 12:45:34.958  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:34.960  1354  1354 D BluetoothInputDevice: Proxy object connected
,08-24 12:45:34.960  1354  1354 D HidProfile: Bluetooth service connected
08-24 12:45:34.960  1354  3921 D BluetoothPan: onBluetoothStateChange on: true
08-24 12:45:34.961  4098  4098 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 12:45:34.962  4019  4031 D BluetoothPan: onBluetoothStateChange on: true
08-24 12:45:34.962  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 12:45:34.962  1354  1354 D PanProfile: Bluetooth service connected
,08-24 12:45:34.962  4098  4098 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-24 12:45:34.963  1955  2252 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:34.962  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:34.963  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 12:45:34.964  4098  4098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 12:45:34.965  1354  3921 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 12:45:34.967  4098  4098 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 12:45:34.967  1354  1354 D BluetoothA2dp: Proxy object connected
,08-24 12:45:34.968  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:34.969   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-24 12:45:34.971  4098  4098 D ObexServerSockets: Succeed to create listening sockets 
,08-24 12:45:34.971  4098  4098 D ObexServerSockets0: startAccept()
08-24 12:45:34.973  4098  4098 D ObexServerSockets0: prepareForNewConnect()
08-24 12:45:34.973  4019  4019 D LocalBluetoothProfileManager: Adding local A2DP profile
08-24 12:45:34.973  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:34.974  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:34.978  4098  4280 D ObexServerSockets0: Accepting socket connection...
,08-24 12:45:34.978  4098  4098 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-24 12:45:34.978  4098  4098 D BluetoothSdpJni: SDP Create record success - handle: 0
08-24 12:45:34.979  4098  4098 D BluetoothMapService: onReceive
08-24 12:45:34.979  4098  4098 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 12:45:34.979  4098  4098 D BluetoothMapService: STATE_ON
08-24 12:45:34.979  4098  4281 D ObexServerSockets0: Accepting socket connection...
,08-24 12:45:34.981  4019  4019 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-24 12:45:34.988  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 12:45:34.992  4019  4019 D BluetoothA2dp: Proxy object connected
,08-24 12:45:34.995  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:35.001  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:35.004  4019  4019 D BluetoothPbap: Proxy object connected
,08-24 12:45:35.004  1354  1354 D BluetoothPbap: Proxy object connected
08-24 12:45:35.004  1354  1354 D PbapServerProfile: Bluetooth service connected
08-24 12:45:35.005  4098  4098 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 12:45:35.005  4019  4019 D PbapServerProfile: Bluetooth service connected
08-24 12:45:35.005  4098  4098 D ObexServerSockets0: prepareForNewConnect()
,08-24 12:45:35.012  4098  4285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 12:45:35.033  4098  4289 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 12:45:35.035  4098  4289 I BtOppRfcommListener: Accept thread started.
,08-24 12:45:35.048  1354  1366 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.048  1354  1354 D HeadsetProfile: Bluetooth service connected
08-24 12:45:35.048   876   876 D BluetoothHeadset: Proxy object connected
08-24 12:45:35.048   876   876 D BluetoothHeadset: Proxy object connected
08-24 12:45:35.048   876   876 D BluetoothHeadset: Proxy object connected
08-24 12:45:35.049  1955  1982 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.054   876   893 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.056  1354  1365 D BluetoothHeadset: Proxy object connected
08-24 12:45:35.056  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-24 12:45:35.058   876   893 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.063  1955  1976 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.085  4019  4031 D BluetoothHeadset: Proxy object connected
,08-24 12:45:35.086  4019  4019 D HeadsetProfile: Bluetooth service connected
,08-24 12:45:36.564  4098  4252 D BluetoothAdapterState: Current state: ON, message: 23
08-24 12:45:36.565  4098  4252 D BluetoothAdapterProperties: Setting state to 13
,08-24 12:45:36.565  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-24 12:45:36.567  4098  4252 D BluetoothAdapterProperties: onBluetoothDisable()
,08-24 12:45:36.571  4098  4252 I BluetoothAdapterState: Entering PendingCommandState
,08-24 12:45:36.574  4098  4256 D BluetoothAdapterProperties: Scan Mode:20
,08-24 12:45:36.574  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-24 12:45:36.582  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:36.582  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:36.585  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-24 12:45:36.586  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:36.590  4098  4098 D HeadsetService: Received stop request...Stopping profile...
,08-24 12:45:36.594  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:36.594  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:36.596  3922  3922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-24 12:45:36.596  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-24 12:45:36.598  4098  4098 D BluetoothMapService: onReceive
08-24 12:45:36.598  4098  4098 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 12:45:36.598  4098  4098 D BluetoothMapService: STATE_TURNING_OFF
08-24 12:45:36.599  1354  2083 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.599  4098  4098 D A2dpService: Received stop request...Stopping profile...
08-24 12:45:36.600  4098  4273 D A2dpStateMachine: Exit Disconnected: -1
08-24 12:45:36.601  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:36.603  4019  4030 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.604  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:36.604  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-24 12:45:36.604  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-24 12:45:36.604   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.604   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.605   876   876 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.606  1955  1982 D BluetoothHeadset: Proxy object disconnected
08-24 12:45:36.607   876   876 D BluetoothA2dp: Proxy object disconnected
08-24 12:45:36.607  4098  4098 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:36.608  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:36.608  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.608  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:36.611  4098  4098 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-24 12:45:36.611  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-24 12:45:36.611  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.611  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.611  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.611  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-24 12:45:36.611  4098  4256 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 12:45:36.611  4098  4098 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-24 12:45:36.614  4098  4098 D HidService: Received stop request...Stopping profile...
08-24 12:45:36.614  4098  4098 D HidService: Stopping Bluetooth HidService
,08-24 12:45:36.618  4019  4019 D HeadsetProfile: Bluetooth service disconnected
,08-24 12:45:36.618  4098  4098 D BluetoothMapService: MAP Service closeService in
08-24 12:45:36.619  4098  4098 D BluetoothMapMasInstance0: MAP Service shutdown
08-24 12:45:36.619  4098  4098 D ObexServerSockets0: shutdown(block = true)
08-24 12:45:36.619  4098  4280 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-24 12:45:36.620  4098  4098 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-24 12:45:36.620  4098  4098 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-24 12:45:36.620  4098  4281 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-24 12:45:36.620  4098  4267 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-24 12:45:36.620  4019  4019 D BluetoothA2dp: Proxy object disconnected
08-24 12:45:36.621  4098  4098 I BtOppRfcommListener: stopping Accept Thread
,08-24 12:45:36.621  4098  4289 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-24 12:45:36.621  4098  4289 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-24 12:45:36.624  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:36.624  4098  4098 D HealthService: Received stop request...Stopping profile...
08-24 12:45:36.625  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-24 12:45:36.625  1354  1354 D HidProfile: Bluetooth service disconnected
08-24 12:45:36.626  4019  4019 D BluetoothInputDevice: Proxy object disconnected
08-24 12:45:36.626  4019  4019 D HidProfile: Bluetooth service disconnected
,08-24 12:45:36.627  4098  4098 D PanService: Received stop request...Stopping profile...
,08-24 12:45:36.629  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 12:45:36.629  1354  1354 D PanProfile: Bluetooth service disconnected
,08-24 12:45:36.630  4019  4019 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-24 12:45:36.630  4019  4019 D PanProfile: Bluetooth service disconnected
,08-24 12:45:36.631  4098  4098 D BluetoothMapService: Received stop request...Stopping profile...
08-24 12:45:36.631  4098  4098 D BluetoothMapService: stop()
,08-24 12:45:36.633  4098  4098 D BluetoothMapAppObserver: deinitObservers()
,08-24 12:45:36.633  4098  4098 D BluetoothMapAppObserver: removeReceiver()
,08-24 12:45:36.635  1354  1354 D BluetoothMap: Proxy object disconnected
,08-24 12:45:36.635  1354  1354 D MapProfile: Bluetooth service disconnected
08-24 12:45:36.635  4019  4019 D BluetoothMap: Proxy object disconnected
08-24 12:45:36.635  4098  4098 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:36.636  4019  4019 D MapProfile: Bluetooth service disconnected
08-24 12:45:36.636  4098  4098 V BluetoothAdapterState: isTurningOn()=false
,08-24 12:45:36.636  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.636  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:36.637  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-24 12:45:36.637  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.638  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.638  4098  4264 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 12:45:36.638  4098  4264 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 12:45:36.638  4098  4098 V BluetoothAdapterState: isTurningOff()=true
,08-24 12:45:36.638  4098  4264 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-24 12:45:36.638  4098  4264 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-24 12:45:36.638  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:36.638  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.638  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:36.639  4098  4098 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-24 12:45:36.639  4098  4256 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-24 12:45:36.640  4098  4098 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-24 12:45:36.644  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:36.646  4098  4098 V BluetoothAdapterState: isTurningOff()=true
,08-24 12:45:36.646  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:36.647  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.647  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:36.647  4098  4098 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-24 12:45:36.647  4098  4256 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-24 12:45:36.648  4098  4098 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-24 12:45:36.649  4098  4098 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:36.649  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:36.649  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.649  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:36.650  4098  4098 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-24 12:45:36.651  4098  4098 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-24 12:45:36.652  4098  4098 D BluetoothMapService: MAP Service closeService in
08-24 12:45:36.653  4098  4098 V BluetoothAdapterState: isTurningOff()=true
08-24 12:45:36.653  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:36.653  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:36.653  4098  4098 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:36.654  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-24 12:45:36.654  4098  4252 D BluetoothAdapterProperties: Setting state to 15
08-24 12:45:36.654  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-24 12:45:36.654  4098  4098 D BluetoothMapService: cleanup()
08-24 12:45:36.654  4098  4252 I BluetoothAdapterState: Entering BleOnState
08-24 12:45:36.654  4098  4098 D BluetoothMapService: MAP Service closeService in
08-24 12:45:36.654  4019  4031 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 12:45:36.655   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:36.655   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
08-24 12:45:36.655  4019  4030 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:36.657  1354  3921 D BluetoothMap: onBluetoothStateChange: up=false
08-24 12:45:36.657  1354  1354 D BluetoothPbap: Proxy object disconnected
08-24 12:45:36.657  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-24 12:45:36.658   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:36.658  4019  4030 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-24 12:45:36.659  1354  2083 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:36.659  4019  4292 D BluetoothPbap: onBluetoothStateChange: up=false
08-24 12:45:36.661  4019  4019 D BluetoothPbap: Proxy object disconnected
,08-24 12:45:36.661   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
08-24 12:45:36.662  4019  4031 D BluetoothMap: onBluetoothStateChange: up=false
,08-24 12:45:36.661  4019  4019 D PbapServerProfile: Bluetooth service disconnected
,08-24 12:45:36.665  1354  1366 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-24 12:45:36.665  1354  3921 D BluetoothPan: onBluetoothStateChange on: false
08-24 12:45:36.666  4019  4030 D BluetoothPan: onBluetoothStateChange on: false
,08-24 12:45:36.666  1955  1976 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-24 12:45:36.667  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=false
,08-24 12:45:36.668  1354  2083 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-24 12:45:36.668  4098  4252 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-24 12:45:36.669  4098  4252 D BluetoothAdapterProperties: Setting state to 16
08-24 12:45:36.669  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-24 12:45:36.670  4098  4252 D BluetoothAdapterProperties: onBleDisable
08-24 12:45:36.670  4098  4252 I BluetoothAdapterState: Entering PendingCommandState
08-24 12:45:36.671  4098  4253 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-24 12:45:36.672  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:36.673  4098  4264 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-24 12:45:36.673  4098  4264 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-24 12:45:36.674  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:36.674  4098  4256 D BluetoothAdapterProperties: Scan Mode:20
,08-24 12:45:36.675  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 12:45:36.677  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:36.678  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:36.682  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:36.686  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:36.874  4098  4256 I bt_hci  : shut_down
,08-24 12:45:36.875  4098  4260 D bt_hwcfg: hw_epilog_process
08-24 12:45:36.878  4098  4260 I bt_vendor: low_power_mode_cb
,08-24 12:45:36.904  4098  4260 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-24 12:45:36.904  4098  4260 I bt_vendor: epilog_cb
08-24 12:45:36.905  4098  4260 I bt_hci  : epilog_finished_callback
,08-24 12:45:36.915  4098  4256 I bt_hci_h4: hal_close
,08-24 12:45:36.919  4098  4256 I bt_userial_vendor: device fd = 51 close
,08-24 12:45:37.042  4098  4253 D bt_stack_manager: event_shut_down_stack finished.
,08-24 12:45:37.043  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-24 12:45:37.049  4098  4252 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-24 12:45:37.049  4098  4098 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-24 12:45:37.051  4098  4098 D BtGatt.GattService: Received stop request...Stopping profile...
08-24 12:45:37.051  4098  4098 D BtGatt.GattService: stop()
08-24 12:45:37.051  4098  4098 D BtGatt.AdvertiseManager: advertise clients cleared
,08-24 12:45:37.058  4098  4098 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:37.058  4098  4098 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:37.059  4098  4098 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:37.059  4098  4098 V BluetoothAdapterState: isBleTurningOff()=true
08-24 12:45:37.060  4098  4252 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-24 12:45:37.061  4098  4252 D BluetoothAdapterProperties: Setting state to 10
08-24 12:45:37.061  4098  4252 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-24 12:45:37.062  4098  4252 I BluetoothAdapterState: Entering OffState
,08-24 12:45:37.065   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-24 12:45:37.088  4098  4098 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-24 12:45:37.089  4098  4098 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-24 12:45:37.090  4098  4253 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-24 12:45:37.091  4098  4098 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-24 12:45:37.101  4098  4253 D bt_stack_manager: event_clean_up_stack finished.
,08-24 12:45:37.108  4098  4098 I art     : System.exit called, status: 0
,08-24 12:45:37.109  4098  4098 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-24 12:45:37.167   876  2003 I ActivityManager: Process com.android.bluetooth (pid 4098) has died
,08-24 12:45:38.029   876  1313 D ConnectivityService: handlePromptUnvalidated 101
,08-24 12:45:39.561  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:39.562  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:42.569  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 12:45:42.570  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@436e23d added. We now have 6 listener(s)
08-24 12:45:42.570  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:42.573  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 12:45:42.574  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7b1a32 added. We now have 7 listener(s)
08-24 12:45:42.574  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:42.575  3922  3986 I System.out: IsBluetoothEnabled
,08-24 12:45:42.588  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:42.625   876   893 I ActivityManager: Start proc 4301:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-24 12:45:42.639  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:42.652  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:42.657  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:45:42.693  1499  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 12:45:42.693  1499  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 12:45:42.693  1499  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:42.693  1499  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:42.711  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 12:45:42.711  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 12:45:42.712  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-24 12:45:42.734  4301  4301 D AdapterServiceConfig: Adding HeadsetService
,08-24 12:45:42.734  4301  4301 D AdapterServiceConfig: Adding A2dpService
08-24 12:45:42.734  4301  4301 D AdapterServiceConfig: Adding HidService
,08-24 12:45:42.734  4301  4301 D AdapterServiceConfig: Adding HealthService
08-24 12:45:42.735  4301  4301 D AdapterServiceConfig: Adding PanService
08-24 12:45:42.735  4301  4301 D AdapterServiceConfig: Adding GattService
,08-24 12:45:42.735  4301  4301 D AdapterServiceConfig: Adding BluetoothMapService
,08-24 12:45:42.746   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bc36e84:true
,08-24 12:45:42.746  4301  4301 D BluetoothAdapterState: make() - Creating AdapterState
,08-24 12:45:42.749  4301  4301 I bt_bluedroid: init
,08-24 12:45:42.749  4301  4313 I BluetoothAdapterState: Entering OffState
,08-24 12:45:42.751  4301  4314 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-24 12:45:42.751  4301  4314 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-24 12:45:42.751  4301  4314 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-24 12:45:42.751  4301  4314 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-24 12:45:42.751  4301  4301 I bt_bluedroid: get_profile_interface socket
,08-24 12:45:42.753  4301  4317 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 12:45:42.755  4301  4317 D BluetoothAdapterProperties: Name is: Nexus 6
,08-24 12:45:42.755  4301  4301 I bt_bluedroid: get_profile_interface sdp
,08-24 12:45:42.758  4301  4311 I bt_bluedroid: config_hci_snoop_log
,08-24 12:45:42.759   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-24 12:45:42.762  4301  4313 D BluetoothAdapterState: Current state: OFF, message: 0
,08-24 12:45:42.762  4301  4313 D BluetoothAdapterProperties: Setting state to 14
08-24 12:45:42.762  4301  4313 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-24 12:45:42.763  4301  4313 D BluetoothBondStateMachine: make
,08-24 12:45:42.765  4301  4318 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-24 12:45:42.769  4301  4313 I BluetoothAdapterState: Entering PendingCommandState
08-24 12:45:42.770  4301  4301 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-24 12:45:42.773  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:42.773  4301  4301 D BtGatt.DebugUtils: handleDebugAction() action=null
08-24 12:45:42.774  4301  4301 D BtGatt.GattService: Received start request. Starting profile...
08-24 12:45:42.774  4301  4301 D BtGatt.GattService: start()
08-24 12:45:42.774  4301  4301 I bt_bluedroid: get_profile_interface gatt
08-24 12:45:42.775  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:42.775  4301  4301 D BtGatt.AdvertiseManager: advertise manager created
08-24 12:45:42.780  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:42.780  4301  4301 V BluetoothAdapterState: isTurningOn()=false
08-24 12:45:42.780  4301  4301 V BluetoothAdapterState: isBleTurningOn()=true
08-24 12:45:42.780  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:42.781  4301  4313 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-24 12:45:42.781  4301  4313 I bt_bluedroid: enable
08-24 12:45:42.781  4301  4314 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-24 12:45:42.781  4301  4314 I bt_hci  : start_up
08-24 12:45:42.786  4301  4314 I bt_vendor: alloc value 0xb3a68189
08-24 12:45:42.786  4301  4314 I bt_vendor: init
08-24 12:45:42.786  4301  4314 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-24 12:45:42.786  4301  4314 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-24 12:45:42.876   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 12:45:42.884  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-24 12:45:42.896  4301  4314 D bt_hci  : start_up starting async portion
,08-24 12:45:42.896  4301  4321 I bt_hci  : event_finish_startup
08-24 12:45:42.897  4301  4321 I bt_hci_h4: hal_open
,08-24 12:45:42.897  4301  4321 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-24 12:45:42.903   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 12:45:42.903   876   896 I Adreno  : Build Date                       : 10/20/15
08-24 12:45:42.903   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 12:45:42.903   876   896 I Adreno  : Local Branch                     : M14
08-24 12:45:42.903   876   896 I Adreno  : Remote Branch                    : 
08-24 12:45:42.903   876   896 I Adreno  : Remote Branch                    : 
08-24 12:45:42.903   876   896 I Adreno  : Reconstruct Branch               : 
,08-24 12:45:42.908  4301  4321 I bt_userial_vendor: device fd = 51 open
,08-24 12:45:42.936  4301  4321 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 12:45:42.953   280   371 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (291 us)
,08-24 12:45:42.968  4301  4321 D bt_hwcfg: Chipset BCM4354A2
,08-24 12:45:42.971  4301  4321 D bt_hwcfg: Target name = [BCM4354A2]
08-24 12:45:42.972  4301  4321 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-24 12:45:43.609  3922  3922 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,08-24 12:45:43.610  3922  3922 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 12:45:43.648   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-24 12:45:43.649  3922  3922 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@63a1a4b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7119383, 16908290=android.view.AbsSavedState$1@7119383}, android:focusedViewId=100}]}]
,08-24 12:45:43.649  3922  3922 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 12:45:43.650  3922  3922 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 12:45:43.650  3922  3922 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 12:45:43.665   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 12:45:43.669   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 12:45:43.670   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-24 12:45:43.670   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 12:45:43.715  4301  4321 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-24 12:45:43.715  4301  4321 D bt_hwcfg: Settlement delay -- 100 ms
08-24 12:45:43.715  4301  4321 I bt_hwcfg: Setting fw settlement delay to 100 
,08-24 12:45:43.831  4301  4321 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-24 12:45:43.832  4301  4321 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-24 12:45:43.864  4301  4321 I bt_hwcfg: vendor lib fwcfg completed
,08-24 12:45:43.864  4301  4321 I bt_vendor: firmware callback
08-24 12:45:43.865  4301  4321 I bt_hci  : firmware_config_callback
,08-24 12:45:43.878  4301  4325 I bt_btu  : btu_task pending for preload complete event
,08-24 12:45:43.878  4301  4325 I bt_btu_task: Bluetooth chip preload is complete
08-24 12:45:43.878  4301  4325 I bt_btu  : btu_task received preload complete event
,08-24 12:45:43.891  4301  4325 I         : BTE_InitTraceLevels -- TRC_HCI
,08-24 12:45:43.891  4301  4325 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-24 12:45:43.891  4301  4325 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-24 12:45:43.892  4301  4325 I         : BTE_InitTraceLevels -- TRC_AVDT
08-24 12:45:43.892  4301  4325 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-24 12:45:43.892  4301  4325 I         : BTE_InitTraceLevels -- TRC_A2D
08-24 12:45:43.892  4301  4325 I         : BTE_InitTraceLevels -- TRC_BNEP
08-24 12:45:43.893  4301  4325 I         : BTE_InitTraceLevels -- TRC_BTM
,08-24 12:45:43.893  4301  4325 I         : BTE_InitTraceLevels -- TRC_GAP
08-24 12:45:43.893  4301  4325 I         : BTE_InitTraceLevels -- TRC_PAN
08-24 12:45:43.894  4301  4325 I         : BTE_InitTraceLevels -- TRC_SDP
,08-24 12:45:43.894  4301  4325 I         : BTE_InitTraceLevels -- TRC_GATT
08-24 12:45:43.894  4301  4325 I         : BTE_InitTraceLevels -- TRC_SMP
08-24 12:45:43.894  4301  4325 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-24 12:45:43.894  4301  4325 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-24 12:45:43.911   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 12:45:43.913   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-24 12:45:43.914   876  1335 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
,08-24 12:45:43.921   876   896 I DreamManagerService: Entering dreamland.
,08-24 12:45:43.924   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 12:45:43.926   876   896 I PowerManagerService: Dozing...
,08-24 12:45:43.981   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-24 12:45:43.982   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 12:45:43.989   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 12:45:43.994   876  1311 E native  : do suspend false
,08-24 12:45:44.004  1939  4328 D NfcService: Discovery configuration equal, not updating.
,08-24 12:45:44.036  4301  4325 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e5d9d
,08-24 12:45:44.036  4301  4325 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e5d9d 
,08-24 12:45:44.038   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 12:45:44.047  4301  4317 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-24 12:45:44.048  4301  4317 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-24 12:45:44.049   876  1311 E native  : do suspend true
,08-24 12:45:44.049  4301  4317 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-24 12:45:44.051  4301  4317 D BluetoothAdapterProperties: Name is: Nexus 6
08-24 12:45:44.054  4301  4317 D BluetoothAdapterProperties: Scan Mode:20
08-24 12:45:44.054  4301  4317 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-24 12:45:44.056  4301  4317 D bt_hci  : do_postload posting postload work item
08-24 12:45:44.057  4301  4321 I bt_hci  : event_postload
,08-24 12:45:44.057  4301  4321 I bt_vendor: sco_config_cb
,08-24 12:45:44.057  4301  4321 I bt_hci  : sco_config_callback postload finished.
08-24 12:45:44.058  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:44.061  4301  4317 D bt_bte_conf: Device ID record 1 : primary
08-24 12:45:44.061  4301  4317 D bt_bte_conf:   vendorId            = 000f
08-24 12:45:44.061  4301  4317 D bt_bte_conf:   vendorIdSource      = 0001
08-24 12:45:44.062  4301  4317 D bt_bte_conf:   product             = 1200
,08-24 12:45:44.062  4301  4317 D bt_bte_conf:   version             = 1436
08-24 12:45:44.062  4301  4317 D bt_bte_conf:   clientExecutableURL = 
08-24 12:45:44.062  4301  4317 D bt_bte_conf:   serviceDescription  = 
08-24 12:45:44.062  4301  4317 D bt_bte_conf:   documentationURL    = 
08-24 12:45:44.063  4301  4317 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-24 12:45:44.063  4301  4314 D bt_stack_manager: event_start_up_stack finished
08-24 12:45:44.064  4301  4321 I bt_vendor: low_power_mode_cb
08-24 12:45:44.065  4301  4313 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-24 12:45:44.066  4301  4313 D BluetoothAdapterProperties: Setting state to 15
,08-24 12:45:44.066  4301  4313 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-24 12:45:44.070  4301  4313 I BluetoothAdapterState: Entering BleOnState
,08-24 12:45:44.121   376  1477 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-24 12:45:44.122   376  1477 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-24 12:45:44.127  4301  4313 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-24 12:45:44.127  4301  4313 D BluetoothAdapterProperties: Setting state to 11
,08-24 12:45:44.127  4301  4313 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-24 12:45:44.143  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:44.146  4301  4301 D HeadsetService: Received start request. Starting profile...
,08-24 12:45:44.151  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:44.155  4301  4301 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-24 12:45:44.157  4301  4301 D HeadsetStateMachine: make
,08-24 12:45:44.172  4301  4313 I BluetoothAdapterState: Entering PendingCommandState,
,08-24 12:45:44.173  4301  4301 D HeadsetStateMachine: max_hf_connections = 1
,08-24 12:45:44.173  4301  4301 I bt_bluedroid: get_profile_interface handsfree
,08-24 12:45:44.174  4301  4317 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-24 12:45:44.175  4301  4317 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-24 12:45:44.184  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:44.186  4301  4301 D A2dpService: Received start request. Starting profile...
,08-24 12:45:44.192  4301  4301 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-24 12:45:44.197  4301  4301 I bt_bluedroid: get_profile_interface avrcp
,08-24 12:45:44.205  4301  4301 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-24 12:45:44.205  4301  4301 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-24 12:45:44.205  4301  4301 D A2dpStateMachine: make
,08-24 12:45:44.207  4301  4301 I bt_bluedroid: get_profile_interface a2dp
,08-24 12:45:44.207  4301  4317 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-24 12:45:44.210  4301  4301 I BluetoothHidServiceJni: classInitNative: succeeds
,08-24 12:45:44.211  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:44.211  4301  4339 D A2dpStateMachine: Enter Disconnected: -2
,08-24 12:45:44.211  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:44.211  4301  4301 D HidService: Received start request. Starting profile...
08-24 12:45:44.212  4301  4301 I bt_bluedroid: get_profile_interface hidhost
,08-24 12:45:44.212  4301  4317 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c73e5
,08-24 12:45:44.212  4301  4317 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-24 12:45:44.213  4301  4301 D HidService: setHidService(): set to: null
,08-24 12:45:44.213  4301  4301 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-24 12:45:44.214  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:44.214  4301  4301 D HealthService: Received start request. Starting profile...
,08-24 12:45:44.216  4301  4301 I bt_bluedroid: get_profile_interface health
,08-24 12:45:44.217  4301  4301 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-24 12:45:44.218  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:44.218  4301  4301 D PanService: Received start request. Starting profile...
08-24 12:45:44.218  4301  4301 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-24 12:45:44.219  4301  4301 I bt_bluedroid: get_profile_interface pan
08-24 12:45:44.219  4301  4317 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-24 12:45:44.222  4301  4301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
,08-24 12:45:44.222  4301  4301 D BluetoothMapService: Received start request. Starting profile...
,08-24 12:45:44.222  4301  4301 D BluetoothMapService: start()
,08-24 12:45:44.224  4301  4301 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-24 12:45:44.225  4301  4301 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-24 12:45:44.225  4301  4301 D BluetoothMapAppObserver: createReceiver()
,08-24 12:45:44.226  4301  4301 D BluetoothMapAppObserver: initObservers()
08-24 12:45:44.226  4301  4301 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-24 12:45:44.233  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:44.233  4301  4301 V BluetoothAdapterState: isTurningOn()=true
,08-24 12:45:44.233  4301  4334 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-24 12:45:44.233  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
,08-24 12:45:44.233  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:44.234  4301  4301 V BluetoothAdapterState: isTurningOff()=false
,08-24 12:45:44.234  4301  4301 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isTurningOn()=true
,08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:44.235  4301  4301 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
,08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isTurningOff()=false
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isTurningOn()=true
08-24 12:45:44.236  4301  4301 V BluetoothAdapterState: isBleTurningOn()=false
08-24 12:45:44.237  4301  4301 V BluetoothAdapterState: isBleTurningOff()=false
08-24 12:45:44.237  4301  4313 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-24 12:45:44.237  4301  4313 D BluetoothAdapterProperties: ScanMode =  20
08-24 12:45:44.237  4301  4313 D BluetoothAdapterProperties: State =  11
,08-24 12:45:44.242  4301  4317 D BluetoothAdapterProperties: Scan Mode:21
08-24 12:45:44.242  4301  4313 D BluetoothAdapterProperties: Setting state to 12
,08-24 12:45:44.242  4301  4313 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-24 12:45:44.242  4301  4317 D BluetoothAdapterProperties: Discoverable Timeout:120
08-24 12:45:44.243  4019  4292 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 12:45:44.243  4301  4313 I BluetoothAdapterState: Entering OnState
,08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:44.245  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:44.246   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 12:45:44.247   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 12:45:44.247   876   876 D BluetoothA2dp: Proxy object connected
08-24 12:45:44.247  4019  4030 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:44.248  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:44.248  4019  4019 D BluetoothA2dp: Proxy object connected
08-24 12:45:44.248  1354  3921 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 12:45:44.249   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 12:45:44.250  4019  4292 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 12:45:44.250  1354  1354 D BluetoothMap: Proxy object connected
,08-24 12:45:44.250  1354  1354 D MapProfile: Bluetooth service connected
08-24 12:45:44.250  1354  1354 D BluetoothMap: getConnectedDevices()
,08-24 12:45:44.252  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:44.252  4301  4301 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-24 12:45:44.252  4019  4031 D BluetoothPbap: onBluetoothStateChange: up=true
08-24 12:45:44.253  4301  4301 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-24 12:45:44.254  4301  4301 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 12:45:44.254   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-24 12:45:44.254  4019  4030 D BluetoothMap: onBluetoothStateChange: up=true
,08-24 12:45:44.256  4301  4301 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-24 12:45:44.256  4301  4301 D ObexServerSockets: Succeed to create listening sockets 
08-24 12:45:44.257  4301  4301 D ObexServerSockets0: startAccept()
08-24 12:45:44.257  4301  4301 D ObexServerSockets0: prepareForNewConnect()
08-24 12:45:44.257  1354  2083 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-24 12:45:44.257  4019  4019 D BluetoothMap: Proxy object connected
,08-24 12:45:44.258  4019  4019 D MapProfile: Bluetooth service connected
,08-24 12:45:44.258  4301  4301 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-24 12:45:44.258  4019  4019 D BluetoothMap: getConnectedDevices()
08-24 12:45:44.258  4301  4301 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-24 12:45:44.259  4301  4345 D ObexServerSockets0: Accepting socket connection...
,08-24 12:45:44.259  1354  1354 D BluetoothInputDevice: Proxy object connected
,08-24 12:45:44.259  1354  1354 D HidProfile: Bluetooth service connected
,08-24 12:45:44.260  1354  1365 D BluetoothPan: onBluetoothStateChange on: true
,08-24 12:45:44.260  4301  4346 D ObexServerSockets0: Accepting socket connection...
08-24 12:45:44.261  4019  4019 D BluetoothInputDevice: Proxy object connected
08-24 12:45:44.261  4019  4019 D HidProfile: Bluetooth service connected
08-24 12:45:44.261  4019  4292 D BluetoothPan: onBluetoothStateChange on: true
,08-24 12:45:44.262  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 12:45:44.262  1354  1354 D PanProfile: Bluetooth service connected
08-24 12:45:44.263  1955  2082 D BluetoothHeadset: onBluetoothStateChange: up=true
08-24 12:45:44.263  1354  2083 D BluetoothPbap: onBluetoothStateChange: up=true
,08-24 12:45:44.264  4019  4019 D BluetoothPan: BluetoothPAN Proxy object connected
08-24 12:45:44.264  4019  4019 D PanProfile: Bluetooth service connected
08-24 12:45:44.264  1354  3921 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-24 12:45:44.266  1354  1354 D BluetoothA2dp: Proxy object connected
08-24 12:45:44.267   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
08-24 12:45:44.268  4301  4301 D BluetoothMapService: onReceive
08-24 12:45:44.268  4301  4301 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-24 12:45:44.268  4301  4301 D BluetoothMapService: STATE_ON
,08-24 12:45:44.269  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:44.274  4019  4019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-24 12:45:44.280  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-24 12:45:44.280  4019  4019 D DockEventReceiver: finishStartingService: stopping service
,08-24 12:45:44.289  4019  4019 D BluetoothPbap: Proxy object connected
,08-24 12:45:44.289  4019  4019 D PbapServerProfile: Bluetooth service connected,
,08-24 12:45:44.291  1354  1354 D BluetoothPbap: Proxy object connected
08-24 12:45:44.291  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-24 12:45:44.295  4301  4301 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-24 12:45:44.295  4301  4301 D ObexServerSockets0: prepareForNewConnect()
,08-24 12:45:44.297  4301  4352 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 12:45:44.317  4301  4356 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-24 12:45:44.319  4301  4356 I BtOppRfcommListener: Accept thread started.
,08-24 12:45:44.349  1354  2083 D BluetoothHeadset: Proxy object connected
,08-24 12:45:44.349   876   893 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.350  1354  1354 D HeadsetProfile: Bluetooth service connected
08-24 12:45:44.350  4019  4031 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.350   876   876 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.350   876   876 D BluetoothHeadset: Proxy object connected
,08-24 12:45:44.350  4019  4019 D HeadsetProfile: Bluetooth service connected
08-24 12:45:44.351   876   876 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.351  1955  1982 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.354  1354  3921 D BluetoothHeadset: Proxy object connected
08-24 12:45:44.354   876   893 D BluetoothHeadset: Proxy object connected
,08-24 12:45:44.357  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-24 12:45:44.365  1955  1976 D BluetoothHeadset: Proxy object connected
,08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:44.620  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:44.626  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:44.630  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 12:45:44.630  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bfe900 added. We now have 8 listener(s)
,08-24 12:45:44.630  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:44.637   876  2003 D WifiService: setWifiEnabled: false pid=3922, uid=10000
,08-24 12:45:44.638   876  2003 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 12:45:44.653  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:44.654   876  1394 D WifiService: setWifiEnabled: true pid=3922, uid=10000
08-24 12:45:44.654   876  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-24 12:45:44.667   876  1311 D WifiConfigStore: Loading config and enabling all networks 
,08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:44.685  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:44.691  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:44.699   876  1311 D WifiConfigStore: loaded 0 passpoint configs
08-24 12:45:44.700   876  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-24 12:45:44.701   876  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-24 12:45:44.702   876  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-24 12:45:44.702   876  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-24 12:45:44.702   876  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-24 12:45:44.702   876  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-24 12:45:44.724   372   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-24 12:45:44.724   876  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.29 rxSuccessRate=0.31 delta 1000 -> 1000
,08-24 12:45:44.724   876  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-24 12:45:44.725   372   874 D CommandListener: Setting iface cfg
,08-24 12:45:44.775   876  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-24 12:45:44.775   876  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-24 12:45:44.780   876  1311 E native  : do suspend true
,08-24 12:45:44.791   876  1309 D WifiNative-HAL: p2pGetDeviceAddress
,08-24 12:45:44.791   876  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-24 12:45:44.805   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-24 12:45:44.806   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:44.844   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-24 12:45:44.928   876  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-24 12:45:44.932  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-24 12:45:45.367  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-24 12:45:45.418  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-24 12:45:45.420  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-24 12:45:45.423   876  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 12:45:45.435   876  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-24 12:45:45.436   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-24 12:45:45.436   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-24 12:45:45.460   876  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-24 12:45:45.471   372   874 D CommandListener: Setting iface cfg
,08-24 12:45:45.473   876  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,08-24 12:45:45.480   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-24 12:45:45.508   876  4365 D DhcpClient: Receive thread started
,08-24 12:45:45.593   876  1311 E native  : do suspend false
,08-24 12:45:45.613   876  2091 D DhcpClient: Broadcasting DHCPDISCOVER
,08-24 12:45:45.631   876  4365 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172785, domain null
,08-24 12:45:45.632   876  2091 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172785 seconds
,08-24 12:45:45.635   876  2091 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-24 12:45:45.648   876  4365 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-24 12:45:45.649   876  2091 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-24 12:45:45.654   372   874 D CommandListener: Setting iface cfg
,08-24 12:45:45.664   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-24 12:45:45.666   876  2091 D DhcpClient: Scheduling renewal in 86399s
,08-24 12:45:45.669   876  1311 E native  : do suspend true
,08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-24 12:45:45.680  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-24 12:45:45.688   876  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-24 12:45:45.688  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-24 12:45:45.690   876  1311 D WifiConfigStore: No blacklist allowed without epno enabled
08-24 12:45:45.690   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-24 12:45:45.691   876  1313 D ConnectivityService: Adding iface wlan0 to network 102
08-24 12:45:45.693   876  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-24 12:45:45.701  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-24 12:45:45.702  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-24 12:45:45.704  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@63a1a4b Bundle[{}]
,08-24 12:45:45.705  3922  3986 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 12:45:45.705  3922  3986 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 12:45:45.706  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-24 12:45:45.706  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 12:45:45.707  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 12:45:45.707  3922  3986 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-24 12:45:45.712  3922  3986 I System.out: Running OutgoingSocketThread
,08-24 12:45:45.713  3922  4367 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
08-24 12:45:45.714  3922  4367 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42720
08-24 12:45:45.714  3922  4367 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-24 12:45:45.730   876  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-24 12:45:45.731   876  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-24 12:45:45.732   876  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-24 12:45:45.734   876  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-24 12:45:45.735   876  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-24 12:45:45.743   876  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-24 12:45:45.748   876  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-24 12:45:45.748   876  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-24 12:45:45.748   876  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-24 12:45:45.748   876  1313 D ConnectivityService:    accepting network in place of null
08-24 12:45:45.748   876  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-24 12:45:45.750   876  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-24 12:45:45.750   876  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-24 12:45:45.754   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156191, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 12:45:45.777   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:45.813   372   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-24 12:45:45.818   876  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-24 12:45:45.818   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:45.820   876  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-24 12:45:45.821   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-24 12:45:45.830   876  4363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:816::200e
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:45.831  3922  3922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:45.834  3922  3922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:45.843  2026  2026 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-24 12:45:45.851  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-24 12:45:45.861  1706  1706 D SystemUpdateService: onCreate
,08-24 12:45:45.865  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-24 12:45:45.872  1706  4375 I SystemUpdateService: active receiver: enabled
,08-24 12:45:45.879  1706  4375 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-24 12:45:45.883  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-24 12:45:45.886  1706  2520 I iu.UploadsManager: num queued entries: 0
,08-24 12:45:45.886  1706  2520 I iu.UploadsManager: num updated entries: 0
,08-24 12:45:45.889  1706  4375 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-24 12:45:45.893  1706  4375 I SystemUpdateService: now status is 0 (complete)
08-24 12:45:45.893  1706  4375 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-24 12:45:45.893  1706  4375 I SystemUpdateService: file has been verified
08-24 12:45:45.893  1706  4375 I SystemUpdateService: OTA package size = 12249756
,08-24 12:45:45.895  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-24 12:45:45.896  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-24 12:45:45.898  4112  4112 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-24 12:45:45.903  1706  4378 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-24 12:45:45.903  1706  4378 W BaseAppContext: Using Auth Proxy for data requests.
,08-24 12:45:45.905  1706  4378 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 12:45:45.905  4112  4112 D SprintDMHelper: simOperator: 
08-24 12:45:45.905  4112  4112 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-24 12:45:45.909   876  4363 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 24 Aug 2016 10:45:45 GMT], X-Android-Received-Millis=[1472035545908], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472035545879]}
,08-24 12:45:45.913   876  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-24 12:45:45.914   876  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-24 12:45:45.914   876  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-24 12:45:45.915   876  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-24 12:45:45.948  1706  2520 I iu.SyncManager: NEXT; no task
,08-24 12:45:45.950  1706  4375 I SystemUpdateService: showing system update notification
,08-24 12:45:45.993  1706  1706 D SystemUpdateService: onDestroy
,08-24 12:45:46.007  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-24 12:45:46.008  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-24 12:45:46.008  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:45:46.008  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:45:46.020  1706  4378 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-24 12:45:46.070  4069  4381 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-24 12:45:46.714  3922  3986 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,08-24 12:45:46.715  3922  3986 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,08-24 12:45:46.723  3922  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-24 12:45:46.725  3922  3986 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-24 12:45:46.725  3922  3986 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,08-24 12:45:46.733  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 12:45:46.733  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb46539 added. We now have 2 listener(s)
,08-24 12:45:46.740  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.740  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.740  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.740  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.740  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bca77e added. We now have 9 listener(s)
08-24 12:45:46.741  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.741  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 12:45:46.744  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:46.749  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:46.751  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.751  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 12:45:46.751  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.752  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ba952c added. We now have 3 listener(s)
,08-24 12:45:46.753  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:46.753  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 12:45:46.754  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.754  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 12:45:46.754  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.754  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed1bf5 added. We now have 10 listener(s)
,08-24 12:45:46.755  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:46.755  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-24 12:45:46.755  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:46.755  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:46.755  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:46.755  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 12:45:46.755  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-24 12:45:46.755  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.756  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.756  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bb46539 removed from the list
08-24 12:45:46.756  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.756  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bca77e removed from the list
08-24 12:45:46.756  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:46.756  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.757  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.757  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.757  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.757  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.757  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.758  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bca77e not in the list
08-24 12:45:46.758  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.758  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:46.759  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 12:45:46.759  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:46.759  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:46.759  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ed1bf5 removed from the list,
08-24 12:45:46.759  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-24 12:45:46.759  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.759  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.759  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.759  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ba952c removed from the list,
08-24 12:45:46.760  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.760  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff7bd8a added. We now have 2 listener(s)
08-24 12:45:46.762  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 12:45:46.762  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.762  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.762  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 12:45:46.762  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7effb added. We now have 9 listener(s)
08-24 12:45:46.763  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.763  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 12:45:46.765  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:46.773  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 12:45:46.775  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.775  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 12:45:46.775  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.775  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc08271 added. We now have 3 listener(s)
08-24 12:45:46.777  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:46.777  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.777  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.777  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 12:45:46.778  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.778  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c2856 added. We now have 10 listener(s)
08-24 12:45:46.778  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:46.778  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:46.778  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 12:45:46.778  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
,08-24 12:45:46.778  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:46.778  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 12:45:46.780  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:46.781  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 12:45:46.781  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-24 12:45:46.785  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 12:45:46.785  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 12:45:46.786  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-24 12:45:46.788  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 12:45:46.788  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:46.788  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-24 12:45:46.789  3922  3986 D BluetoothAdapter: STATE_ON
08-24 12:45:46.791  4301  4344 D BtGatt.GattService: registerClient() - UUID=2b9a6c1d-209f-42d9-a74a-d976e6658536
08-24 12:45:46.791  4301  4317 D BtGatt.GattService: onClientRegistered() - UUID=2b9a6c1d-209f-42d9-a74a-d976e6658536, clientIf=5
08-24 12:45:46.792  3922  3933 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-24 12:45:46.793  4301  4348 D BtGatt.GattService: start scan with filters
08-24 12:45:46.795  4301  4320 D BtGatt.ScanManager: handling starting scan
08-24 12:45:46.795  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 12:45:46.795  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 12:45:46.796  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 12:45:46.796  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 12:45:46.796  4301  4320 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add0a2f
08-24 12:45:46.798  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:46.799  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-24 12:45:46.799  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-24 12:45:46.800  4301  4317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 12:45:46.800  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:46.800  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-24 12:45:46.801  4301  4320 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 12:45:46.803  3922  3986 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-24 12:45:46.803  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:46.804  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-24 12:45:46.804  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:46.804  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:46.804  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-24 12:45:46.804  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:46.804  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 12:45:46.804  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 12:45:46.804  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:46.804  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 12:45:46.806  3922  3986 D BluetoothAdapter: STATE_ON
08-24 12:45:46.806  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 12:45:46.807  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.807  4301  4312 D BtGatt.GattService: stopScan() - queue size =1
08-24 12:45:46.807  4301  4320 D BtGatt.ScanManager: Starting BLE batch scan
08-24 12:45:46.807  4301  4320 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 12:45:46.807  4301  4344 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 12:45:46.808  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 12:45:46.808  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 12:45:46.808  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 12:45:46.808  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 12:45:46.808  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-24 12:45:46.809  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:46.809  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 12:45:46.809  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-24 12:45:46.809  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 12:45:46.810  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 12:45:46.811  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:46.811  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:46.811  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:46.812  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-24 12:45:46.813  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:46.813  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:46.813  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.813  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.813  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.813  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.813  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff7bd8a removed from the list
08-24 12:45:46.813  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.813  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7effb removed from the list
,08-24 12:45:46.813  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:46.813  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.814  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.814  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.814  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:46.815  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 12:45:46.815  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:46.815  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af7effb not in the list
08-24 12:45:46.815  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.815  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:46.816  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.816  4301  4317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:46.816  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:46.816  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.816  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:46.816  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c2856 removed from the list
08-24 12:45:46.816  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.816  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.816  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.816  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.816  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc08271 removed from the list
,08-24 12:45:46.817  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.817  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a73e2 added. We now have 2 listener(s)
08-24 12:45:46.819  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.819  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.819  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.819  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.819  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce6373 added. We now have 9 listener(s)
08-24 12:45:46.819  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.820  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 12:45:46.820  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 12:45:46.820  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.822  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:46.826  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 12:45:46.826  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.826  4301  4320 D BtGatt.ScanManager: stopping BLe Batch
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:46.827  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:46.828  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:46.829  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 12:45:46.831  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.831  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:46.831  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1c0ea9 added. We now have 3 listener(s)
08-24 12:45:46.831  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 12:45:46.831  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.831  4301  4320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-24 12:45:46.832  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.833  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.833  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.833  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:46.833  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.833  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1fec2e added. We now have 10 listener(s)
,08-24 12:45:46.833  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.833  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:46.834  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:46.834  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-24 12:45:46.835  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 12:45:46.835  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:46.835  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-24 12:45:46.836  4301  4317 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 12:45:46.836  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.838  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-24 12:45:46.838  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 12:45:46.842  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-24 12:45:46.843  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-24 12:45:46.843  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 12:45:46.845  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 12:45:46.845  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:46.846  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 12:45:46.846  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:46.848  4301  4347 D BtGatt.GattService: registerClient() - UUID=e4b563ea-a26a-4c8f-823a-1bbe5a74e83a
,08-24 12:45:46.848  4301  4317 D BtGatt.GattService: onClientRegistered() - UUID=e4b563ea-a26a-4c8f-823a-1bbe5a74e83a, clientIf=5
08-24 12:45:46.848  3922  3934 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 12:45:46.848  4301  4311 D BtGatt.GattService: start scan with filters
,08-24 12:45:46.850  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 12:45:46.850  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 12:45:46.850  4301  4320 D BtGatt.ScanManager: handling starting scan
08-24 12:45:46.850  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 12:45:46.850  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 12:45:46.852  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:46.853  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 12:45:46.853  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:46.853  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 12:45:46.855  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-24 12:45:46.855  3922  3986 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-24 12:45:46.855  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:46.855  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:46.855  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:46.856  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.856  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.856  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:46.856  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.856  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a73e2 removed from the list
08-24 12:45:46.856  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-24 12:45:46.856  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce6373 removed from the list
08-24 12:45:46.856  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:46.856  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.857  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.857  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 12:45:46.857  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.857  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.857  4301  4317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-24 12:45:46.857  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.857  4301  4320 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.858  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ce6373 not in the list
08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:46.858  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-24 12:45:46.858  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:46.858  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 12:45:46.858  3922  3986 D BluetoothAdapter: STATE_ON
,08-24 12:45:46.859  4301  4347 D BtGatt.GattService: stopScan() - queue size =1
08-24 12:45:46.859  4301  4311 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 12:45:46.860  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 12:45:46.860  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-24 12:45:46.860  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 12:45:46.861  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 12:45:46.861  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.861  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 12:45:46.862  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.862  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.862  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1fec2e removed from the list
08-24 12:45:46.862  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:46.862  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.862  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.862  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.862  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:46.862  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-24 12:45:46.862  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1c0ea9 removed from the list
08-24 12:45:46.862  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:46.862  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 12:45:46.862  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.862  4301  4320 D BtGatt.ScanManager: Starting BLE batch scan
08-24 12:45:46.862  4301  4320 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-24 12:45:46.863  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 12:45:46.863  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c29d3a added. We now have 2 listener(s)
08-24 12:45:46.864  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.864  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.864  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.864  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.864  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a0cdeb added. We now have 9 listener(s)
08-24 12:45:46.864  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.864  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 12:45:46.866  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:46.869  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:46.871  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:46.871  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:46.871  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.871  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65e9e1 added. We now have 3 listener(s)
08-24 12:45:46.872  4301  4317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:46.872  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:46.872  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.872  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 12:45:46.872  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.873  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.873  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad5306 added. We now have 10 listener(s)
08-24 12:45:46.873  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 12:45:46.873  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:46.873  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-24 12:45:46.873  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-24 12:45:46.873  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 12:45:46.873  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-24 12:45:46.874  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 12:45:46.875  3922  3986 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-24 12:45:46.875  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-24 12:45:46.877  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-24 12:45:46.877  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:46.879  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-24 12:45:46.879  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:46.880  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-24 12:45:46.880  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-24 12:45:46.882  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-24 12:45:46.882  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-24 12:45:46.882  3922  3986 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-24 12:45:46.883  3922  3986 D BluetoothAdapter: STATE_ON
08-24 12:45:46.883  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-24 12:45:46.883  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.884  4301  4320 D BtGatt.ScanManager: stopping BLe Batch
,08-24 12:45:46.884  4301  4347 D BtGatt.GattService: registerClient() - UUID=90b11832-af4e-445c-a744-12a575a72282
,08-24 12:45:46.885  4301  4317 D BtGatt.GattService: onClientRegistered() - UUID=90b11832-af4e-445c-a744-12a575a72282, clientIf=5
08-24 12:45:46.885  3922  3934 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-24 12:45:46.886  4301  4348 D BtGatt.GattService: start scan with filters
,08-24 12:45:46.888  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-24 12:45:46.888  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 12:45:46.889  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.889  4301  4320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 12:45:46.888  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-24 12:45:46.889  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-24 12:45:46.889  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-24 12:45:46.891  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:46.891  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-24 12:45:46.891  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-24 12:45:46.892  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-24 12:45:46.894  4301  4317 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-24 12:45:46.894  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.895  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:46.895  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:46.895  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-24 12:45:46.895  4301  4320 D BtGatt.ScanManager: handling starting scan
,08-24 12:45:46.896  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.896  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.896  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-24 12:45:46.896  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.896  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c29d3a removed from the list
08-24 12:45:46.896  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.896  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a0cdeb removed from the list
,08-24 12:45:46.896  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
08-24 12:45:46.896  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.896  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.896  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-24 12:45:46.896  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.896  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-24 12:45:46.897  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-24 12:45:46.897  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.897  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.897  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a0cdeb not in the list
08-24 12:45:46.897  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-24 12:45:46.897  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-24 12:45:46.897  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-24 12:45:46.897  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-24 12:45:46.898  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-24 12:45:46.898  3922  3986 D BluetoothAdapter: STATE_ON
08-24 12:45:46.898  4301  4335 D BtGatt.GattService: stopScan() - queue size =1
08-24 12:45:46.899  4301  4312 D BtGatt.GattService: unregisterClient() - clientIf=5
08-24 12:45:46.899  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-24 12:45:46.899  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-24 12:45:46.899  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-24 12:45:46.899  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-24 12:45:46.899  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-24 12:45:46.900  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-24 12:45:46.900  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-24 12:45:46.900  3922  3986 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-24 12:45:46.900  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-24 12:45:46.901  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.901  4301  4317 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-24 12:45:46.901  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.901  4301  4320 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-24 12:45:46.902  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-24 12:45:46.902  3922  3922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-24 12:45:46.902  3922  3922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-24 12:45:46.902  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.902  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.902  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.902  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ad5306 removed from the list
08-24 12:45:46.902  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.902  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:46.902  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.902  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.903  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65e9e1 removed from the list
08-24 12:45:46.903  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-24 12:45:46.903  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b9992 added. We now have 2 listener(s)
,08-24 12:45:46.904  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-24 12:45:46.905  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.905  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.905  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-24 12:45:46.905  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6170f63 added. We now have 9 listener(s)
08-24 12:45:46.905  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.905  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 12:45:46.906  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-24 12:45:46.906  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.906  4301  4320 D BtGatt.ScanManager: Starting BLE batch scan
08-24 12:45:46.906  4301  4320 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-24 12:45:46.908  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 12:45:46.911  3922  3986 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 12:45:46.912  3922  3986 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 12:45:46.912  3922  3986 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 12:45:46.913  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-24 12:45:46.913  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@538f419 added. We now have 3 listener(s)
08-24 12:45:46.914  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:46.915  3922  3922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 12:45:46.916  4301  4317 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-24 12:45:46.916  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.916  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 12:45:46.916  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 12:45:46.916  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 12:45:46.917  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-24 12:45:46.917  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f5bcde added. We now have 10 listener(s)
,08-24 12:45:46.917  3922  3986 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 12:45:46.917  3922  3986 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-24 12:45:46.917  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:46.917  3922  3986 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-24 12:45:46.917  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.917  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:46.917  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-24 12:45:46.917  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.917  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b9992 removed from the list
08-24 12:45:46.917  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.917  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6170f63 removed from the list
08-24 12:45:46.918  3922  3986 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 12:45:46.918  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.918  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.918  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.918  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.919  3922  3986 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6170f63 not in the list
08-24 12:45:46.919  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-24 12:45:46.919  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 12:45:46.919  3922  3986 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f5bcde removed from the list
08-24 12:45:46.919  3922  3986 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 12:45:46.920  3922  3986 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 12:45:46.920  3922  3986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 12:45:46.920  3922  3986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 12:45:46.920  3922  3986 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@538f419 removed from the list
,08-24 12:45:46.920  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-24 12:45:46.920  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-24 12:45:46.920  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-24 12:45:46.920  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:46.921  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-24 12:45:46.921  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-24 12:45:46.921  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.921  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-24 12:45:46.926  3922  4387 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
,08-24 12:45:46.926  3922  4387 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
08-24 12:45:46.927  3922  4387 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-24 12:45:46.927  4301  4317 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-24 12:45:46.927  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.927  4301  4320 D BtGatt.ScanManager: stopping BLe Batch
,08-24 12:45:46.930  3922  4388 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
,08-24 12:45:46.930  3922  4388 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
08-24 12:45:46.930  3922  4388 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-24 12:45:46.932  3922  3986 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-24 12:45:46.932  4301  4317 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-24 12:45:46.932  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-24 12:45:46.932  3922  3986 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-24 12:45:46.932  4301  4320 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-24 12:45:46.933  3922  3986 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-24 12:45:46.933  3922  3986 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-24 12:45:46.933  3922  3986 D com.test.thalitest.ThaliTestRunner: Total duration: 22797 ms
,08-24 12:45:46.935  3922  3986 I jxcore-log: Total number of executed tests:  80
08-24 12:45:46.935  3922  3986 I jxcore-log: 
,08-24 12:45:46.935  3922  3986 I jxcore-log: Number of passed tests:  80
08-24 12:45:46.935  3922  3986 I jxcore-log: 
08-24 12:45:46.935  3922  3986 I jxcore-log: Number of failed tests:  0
08-24 12:45:46.935  3922  3986 I jxcore-log: 
,08-24 12:45:46.936  3922  3986 I jxcore-log: Number of ignored tests:  0
08-24 12:45:46.936  3922  3986 I jxcore-log: 
,08-24 12:45:46.937  3922  3986 I jxcore-log: Total duration:  22797
08-24 12:45:46.937  3922  3986 I jxcore-log: 
08-24 12:45:46.937  4301  4317 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-24 12:45:46.937  4301  4317 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-24 12:45:46.939  3922  3986 I jxcore-log: Unit Test app is loaded
08-24 12:45:46.939  3922  3986 I jxcore-log: 
,08-24 12:45:46.945  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.945  3922  3986 I jxcore-log: 
,08-24 12:45:46.948  3922  3922 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 12:45:46.948  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.948  3922  3986 I jxcore-log: 
,08-24 12:45:46.949  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.949  3922  3986 I jxcore-log: 
08-24 12:45:46.949  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.949  3922  3986 I jxcore-log: 
,08-24 12:45:46.950  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.950  3922  3986 I jxcore-log: 
,08-24 12:45:46.951  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.951  3922  3986 I jxcore-log: 
,08-24 12:45:46.952  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.952  3922  3986 I jxcore-log: 
,08-24 12:45:46.953  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.953  3922  3986 I jxcore-log: 
,08-24 12:45:46.954  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.954  3922  3986 I jxcore-log: 
08-24 12:45:46.955  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 12:45:46.955  3922  3986 I jxcore-log: 
,08-24 12:45:46.955  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 12:45:46.955  3922  3986 I jxcore-log: 
,08-24 12:45:46.956  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-24 12:45:46.956  3922  3986 I jxcore-log: 
08-24 12:45:46.956  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.956  3922  3986 I jxcore-log: 
,08-24 12:45:46.957  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.957  3922  3986 I jxcore-log: 
08-24 12:45:46.957  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.957  3922  3986 I jxcore-log: 
,08-24 12:45:46.958  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.958  3922  3986 I jxcore-log: 
08-24 12:45:46.958  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.958  3922  3986 I jxcore-log: 
,08-24 12:45:46.959  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.959  3922  3986 I jxcore-log: 
08-24 12:45:46.959  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.959  3922  3986 I jxcore-log: 
,08-24 12:45:46.960  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.960  3922  3986 I jxcore-log: 
08-24 12:45:46.960  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.960  3922  3986 I jxcore-log: 
,08-24 12:45:46.961  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-24 12:45:46.961  3922  3986 I jxcore-log: 
08-24 12:45:46.961  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 12:45:46.961  3922  3986 I jxcore-log: 
,08-24 12:45:46.962  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-24 12:45:46.962  3922  3986 I jxcore-log: 
08-24 12:45:46.962  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.962  3922  3986 I jxcore-log: 
,08-24 12:45:46.963  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.963  3922  3986 I jxcore-log: 
08-24 12:45:46.963  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.963  3922  3986 I jxcore-log: 
08-24 12:45:46.964  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.964  3922  3986 I jxcore-log: 
,08-24 12:45:46.964  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.964  3922  3986 I jxcore-log: 
08-24 12:45:46.964  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 12:45:46.964  3922  3986 I jxcore-log: 
,08-24 12:45:46.968  3922  3986 I jxcore-log: My device name is: motorola-Nexus 6
08-24 12:45:46.968  3922  3986 I jxcore-log: 
,08-24 12:45:47.312  3922  3922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 12:45:47.362  3922  3922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 12:45:47.402  3922  3922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-24 12:45:48.815  1855  2675 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 12:45:50.007   876  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-24 12:45:51.024  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 12:45:51.024  3922  3986 I jxcore-log: 
,08-24 12:45:51.995  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 12:45:51.995  3922  3986 I jxcore-log: 
,08-24 12:45:52.021  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 12:45:52.021  3922  3986 I jxcore-log: 
,08-24 12:45:52.026  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 12:45:52.026  3922  3986 I jxcore-log: 
,08-24 12:45:52.042  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 12:45:52.042  3922  3986 I jxcore-log: 
,08-24 12:45:52.047  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 12:45:52.047  3922  3986 I jxcore-log: 
,08-24 12:45:53.756   876  1313 D ConnectivityService: handlePromptUnvalidated 102
,08-24 12:45:55.211  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 12:45:55.211  3922  3986 I jxcore-log: 
,08-24 12:45:55.224  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 12:45:55.224  3922  3986 I jxcore-log: 
,08-24 12:45:55.247  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
08-24 12:45:55.247  3922  3986 I jxcore-log: 
,08-24 12:45:55.424  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 12:45:55.424  3922  3986 I jxcore-log: 
,08-24 12:45:56.273  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 12:45:56.273  3922  3986 I jxcore-log: 
,08-24 12:45:56.554  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 12:45:56.554  3922  3986 I jxcore-log: 
,08-24 12:45:56.563  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 12:45:56.563  3922  3986 I jxcore-log: 
,08-24 12:45:56.758  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 12:45:56.758  3922  3986 I jxcore-log: 
,08-24 12:45:56.779  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 12:45:56.779  3922  3986 I jxcore-log: 
,08-24 12:45:56.784  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 12:45:56.784  3922  3986 I jxcore-log: 
,08-24 12:45:56.790  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 12:45:56.790  3922  3986 I jxcore-log: 
,08-24 12:45:56.805  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 12:45:56.805  3922  3986 I jxcore-log: 
,08-24 12:45:56.824  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 12:45:56.824  3922  3986 I jxcore-log: 
,08-24 12:45:56.905  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 12:45:56.905  3922  3986 I jxcore-log: 
,08-24 12:45:56.911  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 12:45:56.911  3922  3986 I jxcore-log: 
,08-24 12:45:56.937  3922  3986 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 12:45:56.937  3922  3986 I jxcore-log: 
,08-24 12:45:56.950  3922  3986 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 12:45:56.951  3922  3986 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 12:45:56.951  3922  3986 I jxcore-log: 
,08-24 12:45:57.003  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 12:45:57.003  3922  3986 I jxcore-log: 
08-24 12:45:57.004  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 12:45:57.004  3922  3986 I jxcore-log: 
08-24 12:45:57.004  3922  3986 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-24 12:45:57.004  3922  3986 I jxcore-log: 
08-24 12:45:57.004  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-24 12:45:57.005  3922  3986 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-24 12:45:57.005  3922  3986 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-24 12:45:57.005  3922  3986 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-24 12:46:14.379  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:14.388  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:14.392  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:14.434  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 12:46:14.434  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 12:46:14.435  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:14.435  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:14.472  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 12:46:14.472  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 12:46:14.472  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-24 12:46:15.886  3875  4391 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 12:46:15.922  3875  4393 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 12:46:15.964  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 12:46:15.965  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 12:46:15.965  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:15.965  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:15.974  3134  4392 V KeepSync: Connecting to GoogleApiClient
08-24 12:46:15.974   876  1968 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 12:46:16.044  1499  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 12:46:16.044  1499  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 12:46:16.044  1499  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:16.044  1499  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:16.068  3875  4393 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 12:46:16.069  3875  4391 E BooksSync: Soft error
08-24 12:46:16.069  3875  4391 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:46:16.069  3875  4391 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:46:16.069  3875  4391 E BooksSync: Sync error
08-24 12:46:16.069  3875  4391 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:46:16.069  3875  4391 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:46:16.069  3875  4391 I BooksSync: Finished books sync
,08-24 12:46:16.076   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162815, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:46:16.083  1499  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 12:46:16.083  1499  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 12:46:16.083  1499  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:16.083  1499  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:16.099  1706  4394 V BaseAuthAsyncOperation: access token request failed
08-24 12:46:16.100  3134  4392 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 12:46:16.153  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 12:46:16.154  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 12:46:16.154  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:46:16.154  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:16.184  3134  4392 E KeepSync: IOException
08-24 12:46:16.184  3134  4392 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 12:46:16.184  3134  4392 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:46:16.184  3134  4392 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 12:46:16.184  3134  4392 E KeepSync: 	... 10 more
08-24 12:46:16.184  3134  4392 W KeepSync: Sync result 2
,08-24 12:46:16.189   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 163090, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:46:25.634   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196070, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:46:34.769  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:34.785  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:34.787  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:34.850  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 12:46:34.850  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 12:46:34.851  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:34.851  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:34.902  3630  3630 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 12:46:34.903  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 12:46:34.903  3630  3630 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-24 12:46:42.925  1887  1937 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-24 12:46:42.925  1887  1937 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-24 12:46:42.970  1499  1499 I ConfigService: onCreate
,08-24 12:46:46.670  3134  4397 V KeepSync: Connecting to GoogleApiClient
,08-24 12:46:46.670   876  1394 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 12:46:46.716  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:46.718  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:46:46.742  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 12:46:46.742  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 12:46:46.742  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:46.743  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:46.762  1706  4398 V BaseAuthAsyncOperation: access token request failed
,08-24 12:46:46.764  3134  4397 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 12:46:46.819  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 12:46:46.819  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-24 12:46:46.819  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:46:46.819  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:46:46.853  3134  4397 E KeepSync: IOException
08-24 12:46:46.853  3134  4397 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 12:46:46.853  3134  4397 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:46:46.853  3134  4397 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 12:46:46.853  3134  4397 E KeepSync: 	... 10 more
,08-24 12:46:46.853  3134  4397 W KeepSync: Sync result 2
,08-24 12:46:46.878   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 216979, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:46:48.042  1499  1499 I ConfigService: onDestroy
,08-24 12:47:17.035  3875  4401 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 12:47:17.059  3875  4402 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 12:47:17.086  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:17.092  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:17.154  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 12:47:17.155  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 12:47:17.155  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:17.155  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:17.201  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:17.207  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:17.257  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 12:47:17.257  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 12:47:17.257  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:17.258  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:17.292  3875  4402 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 12:47:17.293  3875  4401 E BooksSync: Soft error
08-24 12:47:17.293  3875  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:47:17.293  3875  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 12:47:17.294  3875  4401 E BooksSync: Sync error
08-24 12:47:17.294  3875  4401 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:47:17.294  3875  4401 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:47:17.294  3875  4401 I BooksSync: Finished books sync
,08-24 12:47:17.310   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 218804, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:47:21.358  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:21.360  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:21.374  3703  4404 V GoogleAuthProtoRequest: [301] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 12:47:21.401  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 12:47:21.402  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 12:47:21.402  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:21.402  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: [301] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: [301] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 12:47:21.419  3703  4404 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 12:47:38.935   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=269371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:47:47.662   876   885 I art     : Background partial concurrent mark sweep GC freed 35509(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.187ms total 110.068ms
,08-24 12:47:47.755  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:47.757  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:47:47.786  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:47:47.786  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:47:47.786  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:47.786  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:47.807  3090  4407 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 12:47:47.807  3090  4407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at blb.a(PG:3937)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at czp.a(PG:18188)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:47:47.807  3090  4407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	... 12 more
08-24 12:47:47.807  3090  4407 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at fal.a(PG:38)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:47:47.807  3090  4407 E HttpOperation: 	... 14 more
,08-24 12:47:47.845  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 12:47:47.845  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:47:47.845  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:47.845  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:47.861  3090  4407 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 12:47:47.861  3090  4407 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at hec.a(PG:42)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at hee.a(PG:102)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at czr.a(PG:65)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at kka.a(PG:108)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at czp.a(PG:19176)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:47:47.861  3090  4407 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	... 15 more
08-24 12:47:47.861  3090  4407 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at fal.a(PG:38)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:47:47.861  3090  4407 E HttpOperation: 	... 17 more
,08-24 12:47:47.862  3090  4407 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 12:47:47.862  3090  4407 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at hec.a(PG:42)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at hee.a(PG:102)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at czr.a(PG:65)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at kka.a(PG:108)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	... 15 more
08-24 12:47:47.862  3090  4407 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at fal.a(PG:38)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 12:47:47.862  3090  4407 E ExperimentLoader: 	... 17 more
,08-24 12:47:48.000   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 264235, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:47:48.053  3134  4409 V KeepSync: Connecting to GoogleApiClient
,08-24 12:47:48.053   876  1951 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 12:47:48.102  1499  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 12:47:48.102  1499  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 12:47:48.102  1499  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:48.102  1499  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:48.125  1706  4410 V BaseAuthAsyncOperation: access token request failed
,08-24 12:47:48.126  3134  4409 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 12:47:48.169  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 12:47:48.169  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 12:47:48.169  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:47:48.169  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:47:48.183  3134  4409 E KeepSync: IOException
08-24 12:47:48.183  3134  4409 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 12:47:48.183  3134  4409 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:47:48.183  3134  4409 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 12:47:48.183  3134  4409 E KeepSync: 	... 10 more
,08-24 12:47:48.183  3134  4409 W KeepSync: Sync result 2
,08-24 12:47:48.190   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 278021, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:48:18.307   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:48:19.675  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:19.677  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:19.710  1499  2050 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:48:19.710  1499  2050 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:48:19.710  1499  2050 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:48:19.710  1499  2050 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:48:19.732  3090  4418 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 12:48:19.732  3090  4418 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at blb.a(PG:3937)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at czp.a(PG:18188)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:48:19.732  3090  4418 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	... 12 more
08-24 12:48:19.732  3090  4418 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at fal.a(PG:38)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:48:19.732  3090  4418 E HttpOperation: 	... 14 more
,08-24 12:48:19.790  1499  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 12:48:19.790  1499  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 12:48:19.790  1499  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:48:19.790  1499  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:48:19.806  3090  4418 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 12:48:19.806  3090  4418 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at hec.a(PG:42)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at hee.a(PG:102)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at czr.a(PG:65)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at kka.a(PG:108)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at czp.a(PG:19176)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:48:19.806  3090  4418 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	... 15 more
08-24 12:48:19.806  3090  4418 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at fal.a(PG:38)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:48:19.806  3090  4418 E HttpOperation: 	... 17 more
,08-24 12:48:19.807  3090  4418 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 12:48:19.807  3090  4418 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at hec.a(PG:42)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at hee.a(PG:102)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at czr.a(PG:65)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at kka.a(PG:108)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	... 15 more
08-24 12:48:19.807  3090  4418 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at fal.a(PG:38)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 12:48:19.807  3090  4418 E ExperimentLoader: 	... 17 more
,08-24 12:48:19.929   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 309793, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:48:36.161   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=326597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:48:50.044  3875  4421 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 12:48:50.095  3875  4422 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 12:48:50.133  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:50.139  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:50.201  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 12:48:50.202  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 12:48:50.202  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:48:50.202  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:48:50.250  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:50.252  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:50.291  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 12:48:50.291  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 12:48:50.291  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:48:50.291  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:48:50.315  3875  4422 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 12:48:50.316  3875  4421 E BooksSync: Soft error
08-24 12:48:50.316  3875  4421 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:48:50.316  3875  4421 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:48:50.316  3875  4421 E BooksSync: Sync error
08-24 12:48:50.316  3875  4421 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:48:50.316  3875  4421 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 12:48:50.316  3875  4421 I BooksSync: Finished books sync
,08-24 12:48:50.330   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 312329, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:48:54.421  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:54.434  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:54.439  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:48:54.499  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-24 12:48:54.500  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-24 12:48:54.500  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:48:54.500  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:48:54.536  1499  2306 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-24 12:48:54.536  1499  2306 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 12:48:54.549  3630  3661 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 12:48:54.549  3630  3661 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-24 12:48:54.549  3630  3661 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-24 12:48:54.549  3630  3661 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-24 12:48:54.549  3630  3661 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-24 12:48:54.549  3630  3661 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-24 12:48:54.549  3630  3661 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 12:49:23.011  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:49:23.013  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:49:23.067  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:49:23.067  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:49:23.067  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:49:23.067  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:49:23.092  3090  4428 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 12:49:23.092  3090  4428 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at blb.a(PG:3937)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at czp.a(PG:18188)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:49:23.092  3090  4428 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	... 12 more
08-24 12:49:23.092  3090  4428 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at fal.a(PG:38)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:49:23.092  3090  4428 E HttpOperation: 	... 14 more
,08-24 12:49:23.143  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:49:23.143  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:49:23.143  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:49:23.143  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:49:23.156  3090  4428 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 12:49:23.156  3090  4428 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at hec.a(PG:42)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at hee.a(PG:102)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at czr.a(PG:65)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at kka.a(PG:108)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at czp.a(PG:19176)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:49:23.156  3090  4428 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	... 15 more
08-24 12:49:23.156  3090  4428 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at fal.a(PG:38)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:49:23.156  3090  4428 E HttpOperation: 	... 17 more
,08-24 12:49:23.156  3090  4428 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 12:49:23.156  3090  4428 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jcs.i(PG:143)
,08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at hec.a(PG:42)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at hee.a(PG:102)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at czr.a(PG:65)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at kka.a(PG:108)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	... 15 more
08-24 12:49:23.156  3090  4428 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at fal.a(PG:38)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 12:49:23.156  3090  4428 E ExperimentLoader: 	... 17 more
,08-24 12:49:23.294   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 373080, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:49:34.254   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:49:48.157  1499  2270 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 12:49:51.161   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=401597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:49:53.571  3134  4431 V KeepSync: Connecting to GoogleApiClient
,08-24 12:49:53.571   876  2004 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 12:49:53.615  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:49:53.617  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:49:53.647  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 12:49:53.647  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 12:49:53.648  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:49:53.648  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:49:53.671  1706  4432 V BaseAuthAsyncOperation: access token request failed
,08-24 12:49:53.672  3134  4431 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 12:49:53.748  1499  3087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 12:49:53.748  1499  3087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 12:49:53.748  1499  3087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:49:53.748  1499  3087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:49:53.770  3134  4431 E KeepSync: IOException
08-24 12:49:53.770  3134  4431 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 12:49:53.770  3134  4431 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 12:49:53.770  3134  4431 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 12:49:53.770  3134  4431 E KeepSync: 	... 10 more
,08-24 12:49:53.770  3134  4431 W KeepSync: Sync result 2
,08-24 12:49:53.791   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 400039, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:50:30.574   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=441011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:50:50.921   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=461357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:50:59.538  3875  4436 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 12:50:59.576  3875  4437 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 12:50:59.592  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:50:59.594  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:50:59.624  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 12:50:59.624  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 12:50:59.624  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:50:59.624  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:50:59.656  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:50:59.659  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:50:59.688  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 12:50:59.688  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-24 12:50:59.688  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 12:50:59.688  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:50:59.718  3875  4437 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 12:50:59.721  3875  4436 E BooksSync: Soft error
08-24 12:50:59.721  3875  4436 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:50:59.721  3875  4436 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:50:59.722  3875  4436 E BooksSync: Sync error
08-24 12:50:59.722  3875  4436 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 12:50:59.722  3875  4436 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 12:50:59.722  3875  4436 I BooksSync: Finished books sync
,08-24 12:50:59.733   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 469931, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:51:21.552  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:51:21.554  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:51:21.564  3703  4440 V GoogleAuthProtoRequest: [302] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 12:51:21.604  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 12:51:21.604  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 12:51:21.604  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-24 12:51:21.604  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: [302] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: [302] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 12:51:21.622  3703  4440 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 12:51:30.058  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:51:30.061  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 12:51:30.092  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:51:30.092  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 12:51:30.092  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 12:51:30.092  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 12:51:30.108  3090  4442 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 12:51:30.108  3090  4442 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at blb.a(PG:3937)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at czp.a(PG:18188)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:51:30.108  3090  4442 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	... 12 more
08-24 12:51:30.108  3090  4442 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at fal.a(PG:38)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:51:30.108  3090  4442 E HttpOperation: 	... 14 more
,08-24 12:51:30.177  1499  3107 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 12:51:30.177  1499  3107 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 12:51:30.177  1499  3107 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-24 12:51:30.177  1499  3107 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-24 12:51:30.199  3090  4442 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 12:51:30.199  3090  4442 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jdm.a(PG:82)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jcs.o(PG:406)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jcn.a(PG:1379)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jcs.i(PG:143)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at hec.a(PG:42)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at hee.a(PG:102)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at czr.a(PG:65)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at kka.a(PG:108)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at czp.a(PG:19176)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at czp.a(PG:9081)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at czq.run(PG:1686)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:51:30.199  3090  4442 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jdj.a(PG:4091)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jdj.a(PG:1125)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jdm.a(PG:77)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	... 15 more
08-24 12:51:30.199  3090  4442 E HttpOperation: Caused by: faj: BadAuthentication
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at fal.a(PG:38)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	at jdj.a(PG:4089)
08-24 12:51:30.199  3090  4442 E HttpOperation: 	... 17 more
,08-24 12:51:30.199  3090  4442 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 12:51:30.199  3090  4442 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at hec.a(PG:42)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at hee.a(PG:102)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at czr.a(PG:65)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at kka.a(PG:108)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	... 15 more
08-24 12:51:30.199  3090  4442 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at fal.a(PG:38)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 12:51:30.199  3090  4442 E ExperimentLoader: 	... 17 more
,08-24 12:51:30.307   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=500743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE},
,08-24 12:51:30.322   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 499159, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 12:51:51.641   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=522077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:52:31.000   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=561437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:53:00.094   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=590531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:53:39.481   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=629917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 12:53:59.947   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=650384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 12:54:39.320   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=689757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:00:46.275  1706  4474 I EventLogService: Opted in for usage reporting
08-24 13:00:46.276  1706  4474 I EventLogService: Aggregate from 1472034593311 (log), 1472034593311 (data)
,08-24 13:00:46.315  1706  4474 W EventLogAggregator: Unknown tag: snet_gcore
,08-24 13:00:46.315  1706  4474 W EventLogAggregator: Unknown tag: snet_launch_service
,08-24 13:00:46.383  1706  4474 I ServiceDumpSys: dumping service [account]
,08-24 13:00:46.444  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:00:46.445  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:00:46.454  3703  4477 V GoogleAuthProtoRequest: [303] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:00:46.482  1499  2306 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 13:00:46.483  1499  2306 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-24 13:00:46.483  1499  2306 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 13:00:46.483  1499  2306 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:00:46.496  3703  4477 W ExperimentUpdateService: [303] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: [303] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:00:46.497  3703  4477 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:00:51.427   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1061864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 13:01:08.867   876  4364 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1079303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:03:28.589   876   888 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-24 13:08:41.896  4496  4496 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 13:08:41.901  4496  4496 D AndroidRuntime: CheckJNI is OFF
08-24 13:08:41.943  4496  4496 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 13:08:41.993  4496  4496 I Radio-JNI: register_android_hardware_Radio DONE
08-24 13:08:42.018  4496  4496 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 13:08:42.033   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 13:08:42.034   876   889 I ActivityManager: Killing 3922:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-24 13:08:42.149   876  3181 D GraphicsStats: Buffer count: 2
08-24 13:08:42.149   876  2004 I WindowState: WIN DEATH: Window{c760001 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:08:42.150   876  1312 D WifiService: Client connection lost with reason: 4
08-24 13:08:42.181   876   899 W PackageSettings: Skipping PackageSetting{a796a60 com.example.hello/10273} due to missing metadata
08-24 13:08:42.213   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-24 13:08:42.214   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-24 13:08:42.214   876   889 E ActivityManager: Failure starting process com.test.thalitest
08-24 13:08:42.214   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 13:08:42.214   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.214   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.214   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.214   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 13:08:42.215   876   889 I ActivityManager:   Force finishing activity ActivityRecord{a4621be u0 com.test.thalitest/.MainActivity t2}
08-24 13:08:42.215   876   899 I art     : Starting a blocking GC Explicit
08-24 13:08:42.225   876  3181 W ActivityManager: Spurious death for ProcessRecord{d7a93b5 0:com.test.thalitest/u0a0}, curProc for 3922: null
08-24 13:08:42.276   876   899 I art     : Explicit concurrent mark sweep GC freed 44107(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 928us total 61.011ms
08-24 13:08:42.316   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-24 13:08:42.318  4496  4496 I art     : System.exit called, status: 0
08-24 13:08:42.318  4496  4496 I AndroidRuntime: VM exiting with result code 0.
08-24 13:08:42.338   876   899 I ActivityManager: Start proc 4506:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-24 13:08:42.338   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-24 13:08:42.358   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-24 13:08:42.364  4301  4301 D BluetoothMapAppObserver: onReceive
08-24 13:08:42.364  4301  4301 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 13:08:42.367   876  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 13:08:42.368  1855  2273 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 13:08:42.371  3759  3759 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-24 13:08:42.371  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 13:08:42.377  1887  4518 I Keyboard.Facilitator.DecoderInitializer: run()
08-24 13:08:42.393  1887  4518 I Decoder : createOrResetDecoder
08-24 13:08:42.396  1955  1955 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 13:08:42.440   876   887 I ActivityManager: Start proc 4523:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-24 13:08:42.448   876  1962 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3922 uid 10000
08-24 13:08:42.448   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 13:08:42.450  1887  1887 I Keyboard.Facilitator: onFinishInput()
08-24 13:08:42.454  1499  1499 I ConfigService: onCreate
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 13:08:42.463  1499  4529 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-24 13:08:42.484  1499  4529 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:08:42.486  1499  4529 W SQLiteOpenHelper: Opened config.db in read-only mode
08-24 13:08:42.496  1887  4518 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-24 13:08:42.501  4523  4523 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-24 13:08:42.528  1887  4518 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 13:08:42.530  1971  2055 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-24 13:08:42.530   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 13:08:42.531   876   888 E PackageManager: Failed to write settings, restoring backup
08-24 13:08:42.531   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 13:08:42.531   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 13:08:42.531   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 13:08:42.531   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 13:08:42.531   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 13:08:42.531   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.531   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.531   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.530  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 13:08:42.533  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-24 13:08:42.535   876   889 E DropBoxManagerService: Can't write: system_server_wtf
08-24 13:08:42.535   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 13:08:42.535   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:08:42.535   876   889 E DropBoxManagerService: 	... 13 more
08-24 13:08:42.543   876  2002 I ActivityManager: Start proc 4538:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-24 13:08:42.543  1971  2055 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 13:08:42.543  1971  2055 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1971
08-24 13:08:42.543  1971  2055 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.543  1971  2055 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.546   876  2004 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 13:08:42.547   876  4547 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:08:42.547   876  4547 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:08:42.547   876  4547 E DropBoxManagerService: 	... 5 more
08-24 13:08:42.550  1971  2055 I Process : Sending signal. PID: 1971 SIG: 9
08-24 13:08:42.553  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 13:08:42.553  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 13:08:42.553  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 13:08:42.553  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 13:08:42.554  1887  4518 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 13:08:42.554  1887  4518 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-24 13:08:42.554  1887  4518 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 13:08:42.554  1887  4518 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 13:08:42.554  1887  4518 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 13:08:42.554  1887  4518 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-24 13:08:42.585  4523  4523 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-24 13:08:42.606   876  1381 I ActivityManager: Start proc 4557:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-24 13:08:42.613  4523  4555 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 13:08:42.627   876  1951 D GraphicsStats: Buffer count: 1
08-24 13:08:42.627   876   887 I WindowState: WIN DEATH: Window{bf7b804 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-24 13:08:42.639   876  2004 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1971) has died
08-24 13:08:42.640   876  2004 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-24 13:08:42.641   876  2004 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 13:08:42.659   876  1968 I ActivityManager: Start proc 4570:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 13:08:42.685  4557  4557 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 13:08:42.708  4570  4570 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 13:08:42.709  4570  4570 D AndroidRuntime: Shutting down VM
08-24 13:08:42.711  1706  4581 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 13:08:42.712  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 13:08:42.713  1499  1499 D AndroidRuntime: Shutting down VM
08-24 13:08:42.714  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
08-24 13:08:42.714  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
08-24 13:08:42.714  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 13:08:42.714  1499  1499 E AndroidRuntime: 	... 8 more
08-24 13:08:42.717  4570  4570 E AndroidRuntime: FATAL EXCEPTION: main
08-24 13:08:42.717  4570  4570 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4570
08-24 13:08:42.717  4570  4570 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 13:08:42.717  4570  4570 E AndroidRuntime: 	... 10 more
08-24 13:08:42.719   876  1381 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 13:08:42.719   876  4586 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:08:42.719   876  4586 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:08:42.719   876  4586 E DropBoxManagerService: 	... 5 more
08-24 13:08:42.720  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
08-24 13:08:42.720   876  4587 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:08:42.720   876  4587 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:08:42.720   876  4587 E DropBoxManagerService: 	... 5 more
08-24 13:08:42.721  4570  4570 I Process : Sending signal. PID: 4570 SIG: 9
08-24 13:08:42.721  1706  4581 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 13:08:42.732  1706  4581 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-24 13:08:42.733  1706  4581 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.738  4523  4552 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.740   876  1962 I ActivityManager: Killing 2026:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:08:42.750  4523  4552 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:08:42.751   876  1312 D WifiService: Client connection lost with reason: 4
08-24 13:08:42.774   876  1312 D WifiService: Client connection lost with reason: 4
08-24 13:08:42.780   876  1381 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4570) has died
08-24 13:08:42.781   876  1381 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 13:08:42.779  4523  4552 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-24 13:08:42.784   876  1952 I ActivityManager: Process com.google.process.gapps (pid 1499) has died
08-24 13:08:42.784   876  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-24 13:08:42.784   876  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-24 13:08:42.784   876  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-24 13:08:42.798   876   889 I ActivityManager: Start proc 4588:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 13:08:42.802  1706  1706 W RocketImpressions: ClearcutLogger connection suspended: 1
08-24 13:08:42.812   876  1952 I ActivityManager: Start proc 4600:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
