#### Test 79896569fbe8035_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-26 21:53:02.627  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:53:02.639  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:53:02.642  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-26 21:53:02.689  1513  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 21:53:02.690  1513  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 21:53:02.690  1513  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:53:02.690  1513  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 21:53:02.737  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 21:53:02.737  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 21:53:02.738  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-26 21:53:03.339  3778  3778 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 21:53:03.344  3778  3778 D AndroidRuntime: CheckJNI is OFF
08-26 21:53:03.386  3778  3778 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 21:53:03.437  3778  3778 I Radio-JNI: register_android_hardware_Radio DONE
08-26 21:53:03.459  3778  3778 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 21:53:03.464   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 21:53:03.500  1953  1966 W SearchService: Abort, client detached.
08-26 21:53:03.507  1953  2289 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@62e2ef4
08-26 21:53:03.507  1953  1953 I HotwordDetector: Closing mic
08-26 21:53:03.507  1953  2301 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 21:53:03.514  3778  3778 D AndroidRuntime: Shutting down VM
08-26 21:53:03.555   872  1700 I ActivityManager: Start proc 3788:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 21:53:03.561   375  2303 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 21:53:03.564   375  2303 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 21:53:03.581   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 21:53:03.584  1953  2300 I MicroRecognitionRnrImpl: Detection finished
08-26 21:53:03.585  1953  2297 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 21:53:03.638  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-26 21:53:03.639  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-26 21:53:03.639  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:53:03.639  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 21:53:03.651  1953  2078 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-26 21:53:03.652  1953  2072 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 21:53:03.653  3788  3788 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 21:53:03.677  3788  3788 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 21:53:03.682  1953  2072 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 21:53:03.687  3788  3788 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1404-1406)
08-26 21:53:03.687  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:03.688  1953  2072 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1405-1408)
08-26 21:53:03.688  1953  2072 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:03.710  3788  3788 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ab749c4}
08-26 21:53:03.710  3788  3788 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:03.711  3788  3788 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 21:53:03.717  3788  3788 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 21:53:03.718  3788  3788 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 21:53:03.731  3788  3788 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 21:53:03.741  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:53:03.741  3788  3788 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:53:03.742  3788  3788 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:53:03.742  3788  3788 I Adreno  : Build Date                       : 10/20/15
08-26 21:53:03.742  3788  3788 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:53:03.742  3788  3788 I Adreno  : Local Branch                     : M14
08-26 21:53:03.742  3788  3788 I Adreno  : Remote Branch                    : 
08-26 21:53:03.742  3788  3788 I Adreno  : Remote Branch                    : 
08-26 21:53:03.742  3788  3788 I Adreno  : Reconstruct Branch               : 
08-26 21:53:03.797   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1169a4:true
08-26 21:53:03.828  3788  3788 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 21:53:03.841  3788  3788 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-26 21:53:03.884  3788  3841 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-26 21:53:03.892  3788  3820 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-26 21:53:03.915  3788  3841 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 21:53:03.977   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +444ms
08-26 21:53:03.982  1854  1854 I Keyboard.Facilitator: onFinishInput()
08-26 21:53:04.073  3788  3788 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3788
08-26 21:53:04.167  3788  3788 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 21:53:04.314  3788  3843 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1700792016
08-26 21:53:04.320  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 21:53:04.320  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 21:53:04.320  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 21:53:04.320  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 21:53:04.320  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 21:53:04.321  3788  3843 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f439ab added. We now have 1 listener(s)
08-26 21:53:04.325  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-26 21:53:04.326  3788  3843 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:53:04.326  3788  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:04.327  3788  3843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 21:53:04.330  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 21:53:04.331  3788  3843 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@48981c6 added. We now have 1 listener(s)
08-26 21:53:04.331  3788  3843 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:04.343   872  1302 D WifiService: New client listening to asynchronous messages
08-26 21:53:04.344  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:04.344  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 21:53:04.345  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 21:53:04.345  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 21:53:04.345  3788  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 21:53:04.354  3788  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:04.354  3788  3843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-26 21:53:04.362  3788  3843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:04.363  3788  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:04.363  3788  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 21:53:04.363  3788  3843 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:04.365  3788  3843 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 21:53:04.366  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:04.367  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:04.372   872  1700 I ActivityManager: Killing 3196:com.google.android.gm/u0a78 (adj 15): empty #17
08-26 21:53:04.395  3788  3788 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-26 21:53:04.399   872  1700 I ActivityManager: Killing 2696:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
08-26 21:53:05.117  3788  3853 W jxcore-log: Initializing JXcore engine
08-26 21:53:05.117  3788  3853 W jxcore-log: JXcore engine is ready
08-26 21:53:05.154  3853  3853 W Thread-330: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8938 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-26 21:53:05.154  3853  3853 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9645]" dev="sockfs" ino=9645 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 21:53:05.154  3853  3853 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 21:53:05.154  3853  3853 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26827]" dev="sockfs" ino=26827 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-26 21:53:05.169  3788  3853 W jxcore-log: Starting JXcore engine
08-26 21:53:05.248  3788  3853 W jxcore-log: Platform android
08-26 21:53:05.248  3788  3853 W jxcore-log: 
08-26 21:53:05.248  3788  3853 W jxcore-log: Process ARCH arm
08-26 21:53:05.248  3788  3853 W jxcore-log: 
,08-26 21:53:05.439  3788  3853 I jxcore-log: JXcore Cordova bridge is ready!
08-26 21:53:05.439  3788  3853 I jxcore-log: 
,08-26 21:53:05.439  3788  3853 W jxcore-log: JXcore engine is started
,08-26 21:53:05.456  3788  3843 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 21:53:05.462  3788  3788 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 21:53:07.344   872  2064 D NetlinkSocketObserver: NeighborEvent{elapsedMs=115063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 21:53:12.124  3738  3861 V KeepSync: Connecting to GoogleApiClient
,08-26 21:53:12.125   872  1698 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 21:53:12.183  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:12.187  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:12.235  1513  2272 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 21:53:12.235  1513  2272 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 21:53:12.235  1513  2272 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:53:12.235  1513  2272 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:53:12.257  1744  3862 V BaseAuthAsyncOperation: access token request failed
,08-26 21:53:12.258  3738  3861 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 21:53:12.368  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-26 21:53:12.368  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 21:53:12.368  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:53:12.368  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:53:12.394  3738  3861 E KeepSync: IOException
08-26 21:53:12.394  3738  3861 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 21:53:12.394  3738  3861 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 21:53:12.394  3738  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 21:53:12.394  3738  3861 E KeepSync: 	... 10 more
08-26 21:53:12.394  3738  3861 W KeepSync: Sync result 2
,08-26 21:53:12.409   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 90164, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 21:53:15.379  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 21:53:15.379  3788  3853 I jxcore-log: 
,08-26 21:53:15.382  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 21:53:15.382  3788  3853 I jxcore-log: 
,08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:15.394  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:15.400  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:15.402  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 21:53:15.402  3788  3853 I jxcore-log: 
,08-26 21:53:15.405  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 21:53:15.405  3788  3853 I jxcore-log: 
,08-26 21:53:15.832   872  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 21:53:15.910  3788  3853 D executeNativeTests: Running unit tests
,08-26 21:53:15.970  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:15.971  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 added. We now have 2 listener(s)
08-26 21:53:15.972  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:15.972  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:53:15.972  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:15.972  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:15.972  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 added. We now have 2 listener(s)
08-26 21:53:15.972  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:15.973  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:15.977  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:15.994  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:16.000  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:16.001  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:53:16.006  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.012  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.012  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 21:53:16.013  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:53:16.015  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 21:53:16.021  3788  3853 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 21:53:16.022  3788  3853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 21:53:16.022  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 21:53:16.026  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 21:53:16.026  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:16.028  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.029  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:16.029  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.031  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.031  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.031  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:16.032  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:53:16.032  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 removed from the list
,08-26 21:53:16.032  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.032  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 removed from the list
08-26 21:53:16.033  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.033  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.034  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.035  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.037  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:16.037  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.038  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.038  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.042  3788  3853 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 21:53:16.044  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.045  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:16.045  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.046  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.046  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.046  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.047  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.047  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.047  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.047  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.048  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.048  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.048  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.048  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.050  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.050  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:16.050  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.051  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.055  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 21:53:16.055  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 21:53:16.055  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:53:16.056  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-26 21:53:16.057  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:53:16.057  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.057  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.057  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.057  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.057  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.057  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.057  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.057  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.058  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.058  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 21:53:16.058  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.058  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.058  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.058  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.059  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:16.059  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.059  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.059  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.060  3788  3853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:53:16.062  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.066  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:16.067  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:16.067  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:53:16.069  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.070  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:53:16.071  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:16.071  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:53:16.071  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:16.071  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.071  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:53:16.081  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:53:16.082  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:53:16.087  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:16.089  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:53:16.089  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:16.092  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-26 21:53:16.094  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-26 21:53:16.094  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:53:16.094  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 21:53:16.095  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:53:16.096  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:16.101  2362  2373 D BtGatt.GattService: registerClient() - UUID=09b9a2bc-9a66-418d-9ff9-f1ac155d9123
,08-26 21:53:16.102  2362  2381 D BtGatt.GattService: onClientRegistered() - UUID=09b9a2bc-9a66-418d-9ff9-f1ac155d9123, clientIf=5
,08-26 21:53:16.103  3788  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:53:16.104  2362  2404 D BtGatt.GattService: start scan with filters
,08-26 21:53:16.108  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:53:16.108  2362  2384 D BtGatt.ScanManager: handling starting scan
,08-26 21:53:16.109  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:53:16.109  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:53:16.109  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:16.110  2362  2384 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:16.112  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:16.113  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:16.113  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:53:16.115  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:16.117  2362  2381 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:53:16.118  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.118  2362  2384 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:53:16.119  3788  3853 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:53:16.122  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:16.123  3788  3853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 21:53:16.123  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.123  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 21:53:16.123  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.123  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:53:16.123  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:16.123  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:16.123  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-26 21:53:16.123  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:16.124  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:16.124  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 21:53:16.124  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:16.125  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:53:16.125  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.125  2362  2384 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:16.125  2362  2384 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:53:16.126  2362  2373 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:53:16.129  2362  2374 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 21:53:16.130  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:53:16.130  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:53:16.130  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:53:16.131  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:53:16.131  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:53:16.134  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:16.135  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 21:53:16.135  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:53:16.136  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:53:16.137  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:16.138  2362  2381 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:53:16.138  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.140  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:16.140  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:16.140  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:16.140  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.140  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.141  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:16.141  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
,08-26 21:53:16.141  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.141  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.142  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.142  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.143  3788  3853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 21:53:16.145  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:16.148  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:53:16.148  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.158  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:16.163  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:53:16.163  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.163  2362  2384 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:53:16.163  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.164  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:16.164  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:16.164  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:16.164  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:53:16.164  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:16.164  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:16.167  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.169  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:53:16.169  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:53:16.172  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.175  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:16.175  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:53:16.175  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 21:53:16.177  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:53:16.177  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.178  2362  2384 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:53:16.197  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:53:16.198  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:53:16.198  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:53:16.200  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:16.201  2362  2381 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 21:53:16.201  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.204  2362  2411 D BtGatt.GattService: registerClient() - UUID=c9d944bf-567f-441b-ab2f-ceb39b18b975
,08-26 21:53:16.205  2362  2381 D BtGatt.GattService: onClientRegistered() - UUID=c9d944bf-567f-441b-ab2f-ceb39b18b975, clientIf=5
08-26 21:53:16.206  3788  3850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:53:16.206  2362  2373 D BtGatt.GattService: start scan with filters
,08-26 21:53:16.213  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:53:16.213  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:53:16.213  2362  2384 D BtGatt.ScanManager: handling starting scan
08-26 21:53:16.213  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:53:16.213  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:16.216  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:16.216  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:53:16.216  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:53:16.218  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:16.221  3788  3853 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:53:16.224  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.224  3788  3853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:53:16.224  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.224  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 21:53:16.225  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.225  2362  2381 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 21:53:16.225  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 21:53:16.226  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.226  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:16.226  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:16.226  2362  2384 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 21:53:16.227  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 21:53:16.227  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:16.228  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 21:53:16.228  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:53:16.230  3788  3853 D BluetoothAdapter: STATE_ON
08-26 21:53:16.231  2362  2411 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:53:16.232  2362  2373 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:53:16.232  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:16.232  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:53:16.232  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:53:16.232  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:53:16.232  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:53:16.233  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.233  2362  2384 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:16.233  2362  2384 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:53:16.233  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:53:16.238  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:16.238  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:53:16.238  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:53:16.238  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:16.239  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:16.241  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.241  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.241  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:16.242  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
,08-26 21:53:16.241  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:16.242  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:16.243  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.244  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.244  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:16.244  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.244  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:16.244  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.244  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.245  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.245  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:16.246  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.246  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.246  2362  2381 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:53:16.246  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.247  3788  3853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 21:53:16.249  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:16.253  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 21:53:16.253  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.254  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:16.260  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:16.260  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:16.260  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:16.260  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 21:53:16.261  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:16.261  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:16.261  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 21:53:16.263  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.266  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.267  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:53:16.267  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:16.269  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:53:16.269  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.269  2362  2384 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:53:16.271  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:16.272  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:53:16.273  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:16.278  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:53:16.278  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:53:16.278  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 21:53:16.279  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:16.280  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:53:16.280  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:16.280  2362  2384 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:53:16.282  2362  2404 D BtGatt.GattService: registerClient() - UUID=beb50ce8-47d8-4d1b-ac89-52aad9b62922
,08-26 21:53:16.283  2362  2381 D BtGatt.GattService: onClientRegistered() - UUID=beb50ce8-47d8-4d1b-ac89-52aad9b62922, clientIf=5
08-26 21:53:16.283  3788  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 21:53:16.284  2362  2374 D BtGatt.GattService: start scan with filters
,08-26 21:53:16.287  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:53:16.287  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:53:16.287  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 21:53:16.288  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:16.291  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:16.291  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:53:16.291  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:53:16.291  2362  2381 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:53:16.291  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.292  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:16.294  3788  3853 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 21:53:16.295  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.295  3788  3853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:53:16.295  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.295  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:53:16.295  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.295  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:53:16.295  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:16.295  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:16.295  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 21:53:16.295  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:16.295  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:16.295  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:53:16.296  3788  3853 D BluetoothAdapter: STATE_ON
08-26 21:53:16.296  2362  2384 D BtGatt.ScanManager: handling starting scan
,08-26 21:53:16.297  2362  2374 D BtGatt.GattService: stopScan() - queue size =0
08-26 21:53:16.299  2362  2411 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:53:16.299  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:16.299  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:53:16.299  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:53:16.299  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:53:16.299  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:53:16.301  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:16.301  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:53:16.301  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:53:16.301  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 21:53:16.302  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:16.303  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:16.303  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:16.303  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:16.304  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.304  3788  3853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:53:16.304  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.304  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.304  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.304  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.304  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:16.304  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.304  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.305  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.305  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.305  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.306  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.306  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.307  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.307  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.307  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.308  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.308  3788  3853 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 21:53:16.309  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:16.309  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:16.309  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.309  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.309  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.309  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.309  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.310  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.310  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.310  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:53:16.310  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:16.310  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.310  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.310  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.311  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.311  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:16.311  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.311  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.312  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:53:16.313  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.313  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.313  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:53:16.313  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.313  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.313  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.313  2362  2381 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:53:16.313  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.314  2362  2384 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 21:53:16.313  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.314  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.314  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.314  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.314  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.314  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.314  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.314  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.318  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.318  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.318  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.318  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.319  3788  3853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 21:53:16.319  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.319  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:16.319  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.319  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.319  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.319  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.319  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.320  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:16.323  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:53:16.323  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.323  2362  2384 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:16.323  2362  2384 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:53:16.320  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.324  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.324  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.324  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.324  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.324  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.325  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.325  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.325  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.325  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.326  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 21:53:16.326  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.327  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.327  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.327  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.327  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.327  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.327  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.327  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.327  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.327  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.327  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.327  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:16.327  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.327  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.329  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.329  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.329  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.329  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
,08-26 21:53:16.329  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:53:16.330  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:53:16.330  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:53:16.330  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:16.330  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 21:53:16.330  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 21:53:16.330  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:16.330  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.330  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.332  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:53:16.332  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.332  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.332  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.333  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.333  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.333  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:53:16.333  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.333  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.333  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.333  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.334  2362  2381 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:53:16.334  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.334  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.334  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.334  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.334  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.335  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:16.335  3788  3853 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:53:16.335  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 21:53:16.338  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:16.338  3788  3853 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 21:53:16.338  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 21:53:16.339  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 21:53:16.340  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 21:53:16.341  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 21:53:16.342  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 21:53:16.342  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 21:53:16.342  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 21:53:16.342  3788  3853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:16.343  3788  3853 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 21:53:16.343  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:16.343  3788  3853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:16.343  3788  3853 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 21:53:16.343  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:16.343  3788  3853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 21:53:16.343  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 21:53:16.344  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:53:16.344  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.346  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 2,1:53:16.347  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 21:53:16.347  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 21:53:16.348  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 21:53:16.348  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 21:53:16.349  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 21:53:16.349  3788  3853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 21:53:16.349  3788  3853 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 21:53:16.350  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.350  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.350  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.350  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.350  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.351  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.351  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 21:53:16.351  2362  2381 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:53:16.351  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.351  2362  2384 D BtGatt.ScanManager: stopping BLe Batch
08-26 21:53:16.352  3788  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
08-26 21:53:16.352  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.352  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.352  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.352  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.352  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.352  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.353  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.353  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.353  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.353  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.353  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.353  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.354  3788  3853 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 21:53:16.354  3788  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:16.355  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.355  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.355  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.355  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.355  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.355  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.355  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.355  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.355  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.355  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.355  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.355  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.355  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.356  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.357  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.357  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.357  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.357  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.358  3788  3853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 21:53:16.358  2362  2381 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:53:16.358  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.358  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.358  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.358  2362  2384 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 21:53:16.358  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.358  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.358  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.358  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.358  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.358  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.358  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.358  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.358  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.358  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.358  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.358  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.359  3788  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
08-26 21:53:16.359  3788  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
08-26 21:53:16.359  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.359  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.359  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.360  2362  2399 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 21:53:16.360  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.360  3788  3867 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
08-26 21:53:16.360  3788  3853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 21:53:16.360  3788  3853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 21:53:16.360  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:16.361  3788  3853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 21:53:16.361  3788  3853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:53:16.361  3788  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 21:53:16.361  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:16.361  3788  3853 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 21:53:16.361  3788  3853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 21:53:16.361  3788  3853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 21:53:16.361  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:16.361  3788  3853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 21:53:16.361  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.361  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.361  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.362  3788  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
08-26 21:53:16.363  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.363  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.364  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.364  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.364  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.364  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.364  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.365  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.365  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.365  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.365  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.366  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.366  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.366  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.366  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.367  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.367  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.367  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.367  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.367  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.367  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.367  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.367  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.367  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.367  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.367  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.367  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.368  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.368  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.368  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.368  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.368  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.368  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.368  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.368  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.368  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.368  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.368  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.369  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.369  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.369  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.369  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.369  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.369  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.370  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.370  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.370  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:16.370  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.371  3788  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 21:53:16.371  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:16.372  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 21:53:16.372  3788  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 21:53:16.373  3788  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 21:53:16.373  2362  2381 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-26 21:53:16.373  2362  2381 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:16.373  2362  2381 D BtGatt.GattService: current time is 124093702058
08-26 21:53:16.373  2362  2381 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-26 21:53:16.374  2362  2381 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-26 21:53:16.375  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 21:53:16.375  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 21:53:16.375  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:16.375  3788  3868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:16.375  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.375  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 21:53:16.375  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 21:53:16.375  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 21:53:16.376  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.376  3788  3853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 21:53:16.376  3788  3788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 21:53:16.376  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.376  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.376  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:16.376  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:53:16.376  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:16.377  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.377  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.377  3788  3868 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 21:53:16.378  3788  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 21:53:16.378  3788  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 21:53:16.378  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:16.378  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:16.378  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:16.378  3788  3788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 21:53:16.378  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:16.379  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.379  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.379  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.379  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.379  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.379  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.379  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.379  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.379  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.379  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.379  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.379  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.379  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.380  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.380  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.381  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.381  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.381  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.381  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.382  3788  3853 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 21:53:16.382  3788  3853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 21:53:16.382  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 21:53:16.382  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 21:53:16.382  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.382  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.383  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.383  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.383  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.383  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.383  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.383  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.383  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.383  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.383  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.383  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.383  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.383  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.384  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.385  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.385  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.385  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.389  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.389  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.389  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.389  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.389  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.389  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.389  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.389  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.389  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.389  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.389  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.389  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.389  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.389  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.390  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.390  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.390  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.390  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.391  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:16.391  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:16.391  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:16.391  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:16.391  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.391  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.391  3788  3853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9019cd8 not in the list
08-26 21:53:16.391  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.392  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.392  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:16.392  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.392  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.392  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:16.392  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:16.392  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:16.393  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:16.393  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:16.393  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a89c831 not in the list
08-26 21:53:16.393  3788  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 21:53:16.394  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:16.394  3788  3853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 21:53:16.394  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 21:53:16.394  3788  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 21:53:16.394  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 21:53:16.395  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 21:53:16.396  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 21:53:16.396  3788  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 21:53:16.396  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:53:16.396  3788  3853 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 21:53:16.397  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 21:53:16.397  3788  3853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 21:53:16.397  3788  3853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 21:53:16.397  3788  3853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 21:53:16.397  3788  3853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 21:53:16.398  3788  3853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 21:53:16.398  3788  3853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 21:53:16.398  3788  3853 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 21:53:16.398  3788  3853 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 21:53:16.399  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:16.399  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ad1dab added. We now have 2 listener(s)
08-26 21:53:16.400  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:16.402  3788  3853 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 21:53:16.402   872  1698 D WifiService: setWifiEnabled: true pid=3788, uid=10000
08-26 21:53:16.403   872  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 21:53:16.403  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:16.404  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a01ec08 added. We now have 3 listener(s)
08-26 21:53:16.404  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:16.412  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:16.412  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eec1fa1 added. We now have 4 listener(s)
08-26 21:53:16.412  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:16.415  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:16.415  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b2b5c6 added. We now have 5 listener(s)
08-26 21:53:16.415  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:16.417   872   882 D WifiService: setWifiEnabled: false pid=3788, uid=10000
08-26 21:53:16.418   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:16.423  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:16.424  2362  2377 D BluetoothAdapterState: Current state: ON, message: 23
08-26 21:53:16.424  2362  2377 D BluetoothAdapterProperties: Setting state to 13
08-26 21:53:16.424  2362  2377 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 21:53:16.425  2362  2377 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 21:53:16.425  2362  2377 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:53:16.426  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.426  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:16.426  2362  2381 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:16.426  2362  2377 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 21:53:16.428  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.428  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.428  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:16.428  2362  2362 D HeadsetService: Received stop request...Stopping profile...
08-26 21:53:16.431  2362  2362 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:16.431  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.431  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.431  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:16.432  1910  2071 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:16.432  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.433  1356  3787 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:16.433  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-26 21:53:16.433   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:16.433   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:16.433   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:16.434  2362  2362 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 21:53:16.434  2362  2362 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:16.435  2362  2381 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 21:53:16.435  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.435  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.435  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.435  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.436  2362  2381 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 21:53:16.436  2362  2362 D A2dpService: Received stop request...Stopping profile...
08-26 21:53:16.436  2362  2406 D A2dpStateMachine: Exit Disconnected: -1
08-26 21:53:16.438  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:16.438  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:16.439  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.439  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:16.442  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.446  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.448  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 21:53:16.448  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.450   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 21:53:16.451   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 21:53:16.451   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:53:16.451   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:16.457   872  2065 D DhcpClient: Clearing IP address
08-26 21:53:16.457   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:53:16.460   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:16.461  1513  2611 V NativeCrypto: Read error: ssl=0x9b3bf600: I/O error during system call, Connection timed out
08-26 21:53:16.461   872   885 I ActivityManager: Start proc 3871:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 21:53:16.462  1513  2611 V NativeCrypto: SSL shutdown failed: ssl=0x9b3bf600: I/O error during system call, Broken pipe
,08-26 21:53:16.463  1356  1356 D BluetoothA2dp: Proxy object disconnected
,08-26 21:53:16.464   872   872 D BluetoothA2dp: Proxy object disconnected
,08-26 21:53:16.465  2362  2362 D HidService: Received stop request...Stopping profile...
,08-26 21:53:16.465  2362  2362 D HidService: Stopping Bluetooth HidService
08-26 21:53:16.466   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 21:53:16.466   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-26 21:53:16.466  2362  2362 D HealthService: Received stop request...Stopping profile...
08-26 21:53:16.468  1356  1356 D BluetoothInputDevice: Proxy object disconnected
08-26 21:53:16.468  1356  1356 D HidProfile: Bluetooth service disconnected
08-26 21:53:16.468   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 21:53:16.469   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:53:16.469  2362  2362 D PanService: Received stop request...Stopping profile...
,08-26 21:53:16.470   394   394 E Parcel  : Reading a NULL string not supported here.
08-26 21:53:16.472   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-26 21:53:16.475  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:53:16.475  1356  1356 D PanProfile: Bluetooth service disconnected
08-26 21:53:16.475  2362  2362 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 21:53:16.475  2362  2362 D BluetoothMapService: stop()
08-26 21:53:16.476  2362  2362 D BluetoothMapAppObserver: deinitObservers()
08-26 21:53:16.477  2362  2362 D BluetoothMapAppObserver: removeReceiver()
08-26 21:53:16.477   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-26 21:53:16.481   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 21:53:16.482  2362  2362 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:16.482  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.482  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.482  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:16.484   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:53:16.484  2362  2362 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:53:16.484  2362  2362 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.484  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:16.485  2362  2362 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:53:16.485  2362  2381 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 21:53:16.485  2362  2381 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 21:53:16.485  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.485  2362  2381 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 21:53:16.485  2362  2362 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:53:16.485  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.485  2362  2362 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:53:16.485  2362  2395 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:16.485  2362  2395 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:16.485  2362  2395 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 21:53:16.485  2362  2395 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 21:53:16.485  2362  2362 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:53:16.485  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.486  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:16.486  2362  2362 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:53:16.486  2362  2362 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 21:53:16.487  2362  2362 D BluetoothMapService: MAP Service closeService in
08-26 21:53:16.487  2362  2362 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 21:53:16.487  2362  2362 D ObexServerSockets0: shutdown(block = true)
08-26 21:53:16.487  2362  2412 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 21:53:16.488  2362  2362 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 21:53:16.488  2362  2413 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 21:53:16.491  2362  2399 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 21:53:16.491  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:16.491  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:16.491  2362  2362 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 21:53:16.492  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.492  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:16.493  2362  2362 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:16.493  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.493  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:16.493  2362  2362 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:16.493  2362  2377 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 21:53:16.493  2362  2377 D BluetoothAdapterProperties: Setting state to 15
08-26 21:53:16.493  2362  2377 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 21:53:16.494  1356  1356 D BluetoothMap: Proxy object disconnected
08-26 21:53:16.494  1356  1356 D MapProfile: Bluetooth service disconnected
,08-26 21:53:16.494  1356  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:16.494  2362  2377 I BluetoothAdapterState: Entering BleOnState
08-26 21:53:16.495   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:16.495   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:16.495   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:16.495   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:16.495  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.495  1356  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:16.495  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:16.495  1356  3787 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 21:53:16.496  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:16.496  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:16.497  1356  2145 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:53:16.497  1356  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:53:16.498  1910  2071 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:16.498  1356  1372 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:53:16.499  2107  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:16.499  2362  2377 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 21:53:16.499  2362  2377 D BluetoothAdapterProperties: Setting state to 16
,08-26 21:53:16.499  2362  2377 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 21:53:16.500  2362  2377 D BluetoothAdapterProperties: onBleDisable
08-26 21:53:16.500  2362  2377 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:53:16.500  2362  2378 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 21:53:16.500  2362  2362 D BluetoothMapService: cleanup()
08-26 21:53:16.500  2362  2362 D BluetoothMapService: MAP Service closeService in
08-26 21:53:16.500  2362  2362 I BtOppRfcommListener: stopping Accept Thread
08-26 21:53:16.501  2362  3404 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:16.502  2362  2395 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 21:53:16.502  2362  3404 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 21:53:16.502  2362  2395 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:16.502  2362  2381 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:16.504  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.505  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.507   872  2084 D DhcpClient: Receive thread stopped
08-26 21:53:16.511  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.512  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.524   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:16.536  3871  3871 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 21:53:16.546  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:53:16.550   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:16.551   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 21:53:16.551   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:16.551  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:16.551   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f8d7a9:true
,08-26 21:53:16.558  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:16.558   872   889 D Tethering: MasterInitialState.processMessage what=3
08-26 21:53:16.559  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:16.567  3392  3392 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@66802ee and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 21:53:16.568  1953  1953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-26 21:53:16.569   872  1380 I ActivityManager: Start proc 3889:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 21:53:16.581  3871  3871 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 21:53:16.584  3871  3871 D BluetoothMap: Create BluetoothMap proxy object
,08-26 21:53:16.588  3871  3871 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 21:53:16.595  3871  3871 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:16.602   872  1985 I ActivityManager: Killing 2956:com.google.android.calendar/u0a37 (adj 15): empty #17
08-26 21:53:16.603   371   870 E Netd    : netlink response contains error (No such file or directory)
08-26 21:53:16.604   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 21:53:16.616  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 21:53:16.708  2362  2381 I bt_hci  : shut_down
,08-26 21:53:16.722  2362  2385 I bt_vendor: low_power_mode_cb
,08-26 21:53:16.728  2362  2385 D bt_hwcfg: hw_epilog_process
,08-26 21:53:16.743  2362  2385 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 21:53:16.744  2362  2385 I bt_vendor: epilog_cb
08-26 21:53:16.744  2362  2385 I bt_hci  : epilog_finished_callback
,08-26 21:53:16.748  2362  2381 I bt_hci_h4: hal_close
,08-26 21:53:16.748  2362  2381 I bt_userial_vendor: device fd = 51 close
,08-26 21:53:16.779  3889  3889 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:53:16.779  3889  3889 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.779  3889  3889 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.779  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.780  3889  3889 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.780  3889  3889 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.780  3889  3889 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.780  3889  3889 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:16.780  3889  3889 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:16.780  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 21:53:16.818   872  1909 I ActivityManager: Start proc 3920:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-26 21:53:16.819   872  1909 I ActivityManager: Killing 3392:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 21:53:16.879  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:53:16.883  2362  2378 D bt_stack_manager: event_shut_down_stack finished.
,08-26 21:53:16.883  2362  2377 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 21:53:16.885  2362  2362 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:16.885  2362  2377 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 21:53:16.886  2362  2362 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 21:53:16.886  2362  2362 D BtGatt.GattService: stop()
08-26 21:53:16.886  2362  2362 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 21:53:16.889  2362  2362 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:16.889  2362  2362 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:16.889  2362  2362 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:16.890  2362  2362 V BluetoothAdapterState: isBleTurningOff()=true
08-26 21:53:16.890  2362  2377 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 21:53:16.890  2362  2377 D BluetoothAdapterProperties: Setting state to 10
08-26 21:53:16.890  2362  2377 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 21:53:16.891  2362  2377 I BluetoothAdapterState: Entering OffState
08-26 21:53:16.891   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 21:53:16.898  2362  2362 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 21:53:16.898  2362  2362 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 21:53:16.898  2362  2362 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 21:53:16.898  2362  2378 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 21:53:16.900  2362  2378 D bt_stack_manager: event_clean_up_stack finished.
,08-26 21:53:16.903  2362  2362 I art     : System.exit called, status: 0
08-26 21:53:16.903  2362  2362 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 21:53:16.908  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 21:53:16.942   872  1981 I ActivityManager: Process com.android.bluetooth (pid 2362) has died
,08-26 21:53:16.974  3920  3920 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 21:53:17.015  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:53:17.043   872  1370 I ActivityManager: Start proc 3948:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 21:53:17.054  3871  3871 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:17.090  3889  3914 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 21:53:17.116   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9c75e89:true
,08-26 21:53:17.144  3948  3948 D AdapterServiceConfig: Adding HeadsetService
08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding A2dpService
08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding HidService
,08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding HealthService
08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding PanService
08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding GattService
08-26 21:53:17.145  3948  3948 D AdapterServiceConfig: Adding BluetoothMapService
08-26 21:53:17.147   872  1919 I ActivityManager: Killing 3175:android.process.acore/u0a5 (adj 15): empty #17
,08-26 21:53:17.193  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:17.219  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:53:17.224  1744  1744 D SystemUpdateService: onCreate
,08-26 21:53:17.232  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:53:17.238  1744  3961 I SystemUpdateService: active receiver: enabled
,08-26 21:53:17.248  1744  3961 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:53:17.269  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 21:53:17.271  1744  2581 I iu.UploadsManager: num queued entries: 0
,08-26 21:53:17.271  1744  3961 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 21:53:17.272  1744  2581 I iu.UploadsManager: num updated entries: 0
08-26 21:53:17.273  1744  2581 I iu.SyncManager: NEXT; no task
,08-26 21:53:17.272  1744  3961 I SystemUpdateService: now status is 0 (complete)
,08-26 21:53:17.273  1744  3961 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:53:17.273  1744  3961 I SystemUpdateService: file has been verified
08-26 21:53:17.273  1744  3961 I SystemUpdateService: OTA package size = 12249756,
08-26 21:53:17.274  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 21:53:17.276  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 21:53:17.279  1744  3961 I SystemUpdateService: showing system update notification
,08-26 21:53:17.308   872  1919 I ActivityManager: Start proc 3963:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 21:53:17.312  1744  1744 D SystemUpdateService: onDestroy
,08-26 21:53:17.350  3963  3963 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 21:53:17.353  3963  3963 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:17.368  3963  3963 D SprintDMHelper: simOperator: 
,08-26 21:53:17.368  3963  3963 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:53:17.408   872  1985 I ActivityManager: Start proc 3975:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 21:53:17.409   872  1985 I ActivityManager: Killing 3609:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 21:53:17.580   872  1981 I ActivityManager: Start proc 3990:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 21:53:17.583  3039  3989 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 21:53:17.588   872   882 I ActivityManager: Killing 3624:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 21:53:17.674  3990  3990 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 21:53:17.760  3990  3990 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 21:53:17.760  3990  3990 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 21:53:17.760  3990  3990 I GAv4    :   adb logcat -s GAv4
,08-26 21:53:17.783  3990  3990 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:53:17.792  3990  3990 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:53:17.826  3990  4007 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 21:53:17.931  3990  3990 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 21:53:17.967  3990  3990 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 21:53:17.974  3990  3990 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5691-5694)
,08-26 21:53:17.974  3990  3990 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 21:53:17.988  3990  3990 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {76e5338}
08-26 21:53:17.988  3990  3990 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 21:53:17.988  3990  3990 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 21:53:17.995  3990  3990 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 21:53:17.996  3990  3990 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 21:53:18.016  3990  3990 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 21:53:18.030  3990  3990 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:53:18.030  3990  3990 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 21:53:18.030  3990  3990 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:53:18.030  3990  3990 I Adreno  : Build Date                       : 10/20/15
08-26 21:53:18.030  3990  3990 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:53:18.030  3990  3990 I Adreno  : Local Branch                     : M14
08-26 21:53:18.030  3990  3990 I Adreno  : Remote Branch                    : 
08-26 21:53:18.030  3990  3990 I Adreno  : Remote Branch                    : 
08-26 21:53:18.030  3990  3990 I Adreno  : Reconstruct Branch               : 
,08-26 21:53:18.088  3990  4037 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 21:53:18.094  3990  3990 I NSApplication: Starting up...
,08-26 21:53:18.136   872  1698 I ActivityManager: Start proc 4042:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 21:53:18.139   872  1698 I ActivityManager: Killing 2191:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 21:53:18.208  4042  4042 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 21:53:18.370   872  1479 I ActivityManager: Killing 3647:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 21:53:19.447   872  1981 D WifiService: setWifiEnabled: true pid=3788, uid=10000
,08-26 21:53:19.447   872  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:19.460   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:53:19.469  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:19.469  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:19.469  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:19.469  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:19.470  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:19.470  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:19.471  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:19.471  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:19.506   872  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-26 21:53:19.507   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 21:53:19.508   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 21:53:19.509   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 21:53:19.509   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 21:53:19.509   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 21:53:19.509   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 21:53:19.521   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 21:53:19.522   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.50 rxSuccessRate=13.75 delta 1000 -> 994
,08-26 21:53:19.523   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:19.525   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 21:53:19.525   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:53:19.532   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 21:53:19.532   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:53:19.534   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 21:53:19.541   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 21:53:19.541   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 21:53:19.631   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 21:53:19.634  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 21:53:20.057  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 21:53:20.095  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 21:53:20.096  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 21:53:20.098   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:53:20.104   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:53:20.104   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:20.105   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 21:53:20.124   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:53:20.135   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:20.135   872  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 21:53:20.151   872  1303 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 21:53:20.153   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 21:53:20.173   872  4065 D DhcpClient: Receive thread started
,08-26 21:53:20.257   872  1301 E native  : do suspend false
,08-26 21:53:20.279   872  2065 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 21:53:20.294   872  4065 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172695, domain null
,08-26 21:53:20.298   872  2065 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172695 seconds
,08-26 21:53:20.302   872  2065 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 21:53:20.325   872  4065 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 21:53:20.327   872  2065 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 21:53:20.336   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:20.346   872  2065 D DhcpClient: Scheduling renewal in 86399s
,08-26 21:53:20.348   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 21:53:20.359   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 21:53:20.361   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 21:53:20.362   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 21:53:20.363   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 21:53:20.365   872  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 21:53:20.381   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 21:53:20.415   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 21:53:20.416   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 21:53:20.420   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 21:53:20.422   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 21:53:20.424   872  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 21:53:20.439   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 21:53:20.449   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 21:53:20.450   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 21:53:20.450   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:20.450   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 21:53:20.450   872  1303 D ConnectivityService:    accepting network in place of null
,08-26 21:53:20.451   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 21:53:20.451   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 21:53:20.461   872  4064 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128181, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 21:53:20.501   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:20.537   872  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:816::200e
,08-26 21:53:20.571   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:20.579   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 21:53:20.579   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:20.588   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:53:20.595  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:20.595  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:20.595  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:20.595  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:20.584   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 21:53:20.603  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:20.604  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 21:53:20.604  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:20.605  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:20.610   872  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:53:20 GMT], X-Android-Received-Millis=[1472241200609], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472241200580]}
,08-26 21:53:20.611   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 21:53:20.612   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-26 21:53:20.612   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 21:53:20.613   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 21:53:20.617  1953  1953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-26 21:53:20.619  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:53:20.621  1744  1744 D SystemUpdateService: onCreate
,08-26 21:53:20.626  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:53:20.631  1744  4076 I SystemUpdateService: active receiver: enabled
,08-26 21:53:20.638  1744  4076 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:53:20.643  1744  4076 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 21:53:20.643  1744  4076 I SystemUpdateService: now status is 0 (complete)
,08-26 21:53:20.643  1744  4076 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:53:20.643  1744  4076 I SystemUpdateService: file has been verified
,08-26 21:53:20.644  1744  4076 I SystemUpdateService: OTA package size = 12249756
,08-26 21:53:20.649  1744  4076 I SystemUpdateService: showing system update notification
,08-26 21:53:20.656  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 21:53:20.659  1744  4079 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 21:53:20.659  1744  4079 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 21:53:20.661  1744  4079 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 21:53:20.661  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:53:20.662  1744  2581 I iu.UploadsManager: num queued entries: 0
,08-26 21:53:20.663  1744  2581 I iu.UploadsManager: num updated entries: 0
08-26 21:53:20.663  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 21:53:20.664  1744  2581 I iu.SyncManager: NEXT; no task
08-26 21:53:20.665  3963  3963 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:20.668  1744  1744 D SystemUpdateService: onDestroy
,08-26 21:53:20.670  3963  3963 D SprintDMHelper: simOperator: 
08-26 21:53:20.670  3963  3963 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:53:20.676  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:20.678  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:20.714  1513  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 21:53:20.716  1513  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 21:53:20.716  1513  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 21:53:20.716  1513  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:53:20.750  1744  4079 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-26 21:53:20.801  3039  4081 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 21:53:21.579   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 21:53:22.111   872  1370 I ActivityManager: Killing 3462:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-26 21:53:22.329   872  1882 D AlarmManagerService: Setting time of day to sec=1472241202
,08-26 21:53:22.344   872  1882 W AlarmManagerService: Unable to set rtc to 1472241202: Invalid argument
,08-26 21:53:22.467   872   883 D WifiService: setWifiEnabled: false pid=3788, uid=10000
08-26 21:53:22.468   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:22.489  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 21:53:22.493   872  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 21:53:22.494   872  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 21:53:22.494   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:53:22.495   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:53:22.522   872  2065 D DhcpClient: Clearing IP address
,08-26 21:53:22.522   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:53:22.528   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:22.536  1513  4085 V NativeCrypto: Read error: ssl=0x9aa1c600: I/O error during system call, Connection timed out
08-26 21:53:22.539  1513  4085 V NativeCrypto: SSL shutdown failed: ssl=0x9aa1c600: I/O error during system call, Broken pipe
,08-26 21:53:22.543   872  1370 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 21:53:22.544   872  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 21:53:22.544   872  4065 D DhcpClient: Receive thread stopped
,08-26 21:53:22.545   872  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:816::200e
,08-26 21:53:22.553   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 21:53:22.554   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-26 21:53:22.560   394   394 E Parcel  : Reading a NULL string not supported here.
,08-26 21:53:22.562   872  4063 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 21:53:22.563   872  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
08-26 21:53:22.563   872  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 21:53:22.564   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 21:53:22.565   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-26 21:53:22.577   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:53:22.580  2107  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 21:53:22.582  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:22.582  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:22.582  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:22.582   872  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 21:53:22.582  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:22.583  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:22.583  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:22.583  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:22.583  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:22.608   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:22.637   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:22.638   872  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 21:53:22.638   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:22.639   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:53:22.643  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:22.644  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:22.648  1953  1953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-26 21:53:22.651  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:53:22.654  1744  1744 D SystemUpdateService: onCreate
,08-26 21:53:22.658  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:53:22.664  1744  4097 I SystemUpdateService: active receiver: enabled
,08-26 21:53:22.667  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 21:53:22.671  1744  2581 I iu.UploadsManager: num queued entries: 0
,08-26 21:53:22.671  1744  2581 I iu.UploadsManager: num updated entries: 0
08-26 21:53:22.672  1744  2581 I iu.SyncManager: NEXT; no task
,08-26 21:53:22.673  1744  4097 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:53:22.674  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:53:22.675  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 21:53:22.678  3963  3963 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:22.681  3963  3963 D SprintDMHelper: simOperator: 
,08-26 21:53:22.681  3963  3963 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:53:22.695  1744  4097 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 21:53:22.695  1744  4097 I SystemUpdateService: now status is 0 (complete)
08-26 21:53:22.695  1744  4097 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:53:22.695  1744  4097 I SystemUpdateService: file has been verified
,08-26 21:53:22.695  1744  4097 I SystemUpdateService: OTA package size = 12249756
,08-26 21:53:22.698  3039  4101 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 21:53:22.712   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-26 21:53:22.714   872  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 21:53:22.714   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 21:53:22.737  1744  4097 I SystemUpdateService: showing system update notification
,08-26 21:53:22.762  1744  1744 D SystemUpdateService: onDestroy
,08-26 21:53:24.755  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:24.817  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 21:53:24.818  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 21:53:24.818  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:53:24.818  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:53:24.860  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 21:53:24.861  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 21:53:24.861  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-26 21:53:25.517  3948  3948 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 21:53:25.517   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@deb9f9d:true
,08-26 21:53:25.523  3948  3948 I bt_bluedroid: init
,08-26 21:53:25.523  3948  4106 I BluetoothAdapterState: Entering OffState
,08-26 21:53:25.527  3948  4107 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 21:53:25.527  3948  4107 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:53:25.527  3948  4107 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 21:53:25.527  3948  4107 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 21:53:25.528  3948  3948 I bt_bluedroid: get_profile_interface socket
,08-26 21:53:25.531  3948  3948 I bt_bluedroid: get_profile_interface sdp
,08-26 21:53:25.533  3948  4110 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:53:25.536  3948  4110 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:53:25.539  3948  3959 I bt_bluedroid: config_hci_snoop_log
,08-26 21:53:25.543   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 21:53:25.551  3948  4106 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 21:53:25.552  3948  4106 D BluetoothAdapterProperties: Setting state to 14
08-26 21:53:25.552  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 21:53:25.556  3948  4106 D BluetoothBondStateMachine: make
,08-26 21:53:25.562  3948  4111 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 21:53:25.569  3948  4106 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:53:25.573  3948  3948 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 21:53:25.583  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:25.585  3948  3948 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:25.587  3948  3948 D BtGatt.GattService: Received start request. Starting profile...
,08-26 21:53:25.588  3948  3948 D BtGatt.GattService: start()
08-26 21:53:25.588  3948  3948 I bt_bluedroid: get_profile_interface gatt
,08-26 21:53:25.591  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
08-26 21:53:25.592  3948  3948 D BtGatt.AdvertiseManager: advertise manager created
,08-26 21:53:25.603  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:25.603  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:25.604  3948  3948 V BluetoothAdapterState: isBleTurningOn()=true
08-26 21:53:25.604  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:25.604  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 21:53:25.605  3948  4106 I bt_bluedroid: enable
,08-26 21:53:25.605  3948  4107 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 21:53:25.606  3948  4107 I bt_hci  : start_up
,08-26 21:53:25.614  3948  4107 I bt_vendor: alloc value 0xb39f9189
,08-26 21:53:25.615  3948  4107 I bt_vendor: init
08-26 21:53:25.615  3948  4107 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 21:53:25.615  3948  4107 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 21:53:25.721  3948  4107 D bt_hci  : start_up starting async portion
,08-26 21:53:25.722  3948  4114 I bt_hci  : event_finish_startup
08-26 21:53:25.722  3948  4114 I bt_hci_h4: hal_open
08-26 21:53:25.723  3948  4114 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 21:53:25.731  3948  4114 I bt_userial_vendor: device fd = 51 open
,08-26 21:53:25.764  3948  4114 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:53:25.796  3948  4114 D bt_hwcfg: Chipset BCM4354A2
,08-26 21:53:25.796  3948  4114 D bt_hwcfg: Target name = [BCM4354A2]
08-26 21:53:25.797  3948  4114 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 21:53:26.454  3948  4114 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 21:53:26.456  3948  4114 D bt_hwcfg: Settlement delay -- 100 ms
08-26 21:53:26.456  3948  4114 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 21:53:26.573  3948  4114 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:53:26.574  3948  4114 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 21:53:26.604  3948  4114 I bt_hwcfg: vendor lib fwcfg completed
08-26 21:53:26.604  3948  4114 I bt_vendor: firmware callback
08-26 21:53:26.605  3948  4114 I bt_hci  : firmware_config_callback
,08-26 21:53:26.617  3948  4116 I bt_btu  : btu_task pending for preload complete event
08-26 21:53:26.617  3948  4116 I bt_btu_task: Bluetooth chip preload is complete
08-26 21:53:26.617  3948  4116 I bt_btu  : btu_task received preload complete event
,08-26 21:53:26.627  3948  4116 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 21:53:26.628  3948  4116 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 21:53:26.628  3948  4116 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 21:53:26.628  3948  4116 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 21:53:26.628  3948  4116 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:53:26.629  3948  4116 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 21:53:26.629  3948  4116 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:53:26.629  3948  4116 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 21:53:26.629  3948  4116 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 21:53:26.630  3948  4116 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:53:26.630  3948  4116 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 21:53:26.630  3948  4116 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 21:53:26.631  3948  4116 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:53:26.631  3948  4116 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 21:53:26.631  3948  4116 I         : BTE_InitTraceLevels -- TRC_BTIF,
,08-26 21:53:26.767  3948  4116 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-26 21:53:26.768  3948  4116 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-26 21:53:26.776  3948  4110 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 21:53:26.778  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 21:53:26.778  3948  4110 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:53:26.784  3948  4110 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 21:53:26.787  3948  4110 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:53:26.787  3948  4110 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:26.788  3948  4110 D bt_hci  : do_postload posting postload work item
,08-26 21:53:26.788  3948  4114 I bt_hci  : event_postload
,08-26 21:53:26.788  3948  4114 I bt_vendor: sco_config_cb
08-26 21:53:26.788  3948  4114 I bt_hci  : sco_config_callback postload finished.
08-26 21:53:26.794  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:26.797  3948  4110 D bt_bte_conf: Device ID record 1 : primary
08-26 21:53:26.798  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:26.798  3948  4114 I bt_vendor: low_power_mode_cb
08-26 21:53:26.798  3948  4110 D bt_bte_conf:   vendorId            = 000f
08-26 21:53:26.799  3948  4110 D bt_bte_conf:   vendorIdSource      = 0001
08-26 21:53:26.799  3948  4110 D bt_bte_conf:   product             = 1200
08-26 21:53:26.799  3948  4110 D bt_bte_conf:   version             = 1436
,08-26 21:53:26.799  3948  4110 D bt_bte_conf:   clientExecutableURL = 
08-26 21:53:26.800  3948  4110 D bt_bte_conf:   serviceDescription  = 
08-26 21:53:26.800  3948  4110 D bt_bte_conf:   documentationURL    = 
,08-26 21:53:26.801  3948  4110 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 21:53:26.801  3948  4107 D bt_stack_manager: event_start_up_stack finished
08-26 21:53:26.801  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 21:53:26.802  3948  4106 D BluetoothAdapterProperties: Setting state to 15
08-26 21:53:26.802  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 21:53:26.803  3948  4106 I BluetoothAdapterState: Entering BleOnState
,08-26 21:53:26.810  3948  4106 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 21:53:26.811  3948  4106 D BluetoothAdapterProperties: Setting state to 11
08-26 21:53:26.811  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 21:53:26.823  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:26.826  3948  3948 D HeadsetService: Received start request. Starting profile...
08-26 21:53:26.826  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 21:53:26.828  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:26.831  3948  3948 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 21:53:26.831  3948  3948 D HeadsetStateMachine: make
,08-26 21:53:26.836  3948  4106 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:53:26.838  3948  3948 D HeadsetStateMachine: max_hf_connections = 1
,08-26 21:53:26.839  3948  3948 I bt_bluedroid: get_profile_interface handsfree
,08-26 21:53:26.839  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 21:53:26.839  3948  4110 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 21:53:26.843  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:26.844  3948  3948 D A2dpService: Received start request. Starting profile...
,08-26 21:53:26.845  3948  3948 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 21:53:26.845  3948  3948 I bt_bluedroid: get_profile_interface avrcp
,08-26 21:53:26.851  3948  3948 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:53:26.851  3948  3948 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 21:53:26.852  3948  3948 D A2dpStateMachine: make
,08-26 21:53:26.853  3948  3948 I bt_bluedroid: get_profile_interface a2dp
08-26 21:53:26.853  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 21:53:26.855  3948  4125 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:53:26.855  3948  3948 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 21:53:26.857  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
08-26 21:53:26.858  3871  3871 D BluetoothInputDevice: Proxy object connected
08-26 21:53:26.858  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:26.858  3948  3948 D HidService: Received start request. Starting profile...
08-26 21:53:26.858  3871  3871 D HidProfile: Bluetooth service connected
,08-26 21:53:26.859  3948  3948 I bt_bluedroid: get_profile_interface hidhost
08-26 21:53:26.859  3948  4110 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-26 21:53:26.859  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 21:53:26.859  3948  3948 D HidService: setHidService(): set to: null
08-26 21:53:26.860  3948  3948 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 21:53:26.861  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:26.861  3948  3948 D HealthService: Received start request. Starting profile...
,08-26 21:53:26.863  3948  3948 I bt_bluedroid: get_profile_interface health
,08-26 21:53:26.863  3948  3948 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 21:53:26.864  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:26.865  3948  3948 D PanService: Received start request. Starting profile...
,08-26 21:53:26.865  3871  3871 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 21:53:26.866  3948  3948 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 21:53:26.866  3948  3948 I bt_bluedroid: get_profile_interface pan
08-26 21:53:26.866  3871  3871 D PanProfile: Bluetooth service connected
,08-26 21:53:26.866  3948  4110 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 21:53:26.869  3948  3948 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:26.870  3871  3871 D BluetoothMap: Proxy object connected
,08-26 21:53:26.870  3948  3948 D BluetoothMapService: Received start request. Starting profile...
,08-26 21:53:26.870  3948  3948 D BluetoothMapService: start()
,08-26 21:53:26.870  3871  3871 D MapProfile: Bluetooth service connected
,08-26 21:53:26.871  3871  3871 D BluetoothMap: getConnectedDevices()
,08-26 21:53:26.871  3871  3871 D BluetoothMap: Bluetooth is Not enabled
08-26 21:53:26.872  3948  3948 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 21:53:26.873  3948  3948 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 21:53:26.873  3948  3948 D BluetoothMapAppObserver: createReceiver()
08-26 21:53:26.874  3948  3948 D BluetoothMapAppObserver: initObservers()
,08-26 21:53:26.874  3948  3948 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 21:53:26.882  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.882  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:26.882  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:26.882  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:26.883  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.883  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:26.883  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:26.883  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:26.884  3948  4123 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 21:53:26.885  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.885  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:26.885  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isTurningOn()=true
,08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:26.886  3948  3948 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:26.887  3948  3948 V BluetoothAdapterState: isTurningOn()=true
,08-26 21:53:26.887  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:26.887  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:26.888  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 21:53:26.888  3948  4106 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:53:26.888  3948  4106 D BluetoothAdapterProperties: State =  11
08-26 21:53:26.889  3948  4110 D BluetoothAdapterProperties: Scan Mode:21
,08-26 21:53:26.889  3948  4110 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:53:26.889  3948  4106 D BluetoothAdapterProperties: Setting state to 12
,08-26 21:53:26.890  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 21:53:26.890  3948  4106 I BluetoothAdapterState: Entering OnState
08-26 21:53:26.891  1356  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:26.893  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:26.893   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:26.893   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:26.893  3871  3883 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:53:26.894   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:26.894   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:26.894   872   872 D BluetoothA2dp: Proxy object connected
08-26 21:53:26.894  3871  3882 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:53:26.894  1356  1356 D BluetoothA2dp: Proxy object connected
,08-26 21:53:26.895  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:26.897  3871  3883 D BluetoothPan: onBluetoothStateChange on: true
,08-26 21:53:26.897  3871  3882 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:26.897  1356  3787 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:26.898  1356  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 21:53:26.899  1356  1371 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:26.899  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 21:53:26.900  3948  3948 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 21:53:26.901  1356  3787 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:53:26.901  3948  3948 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-26 21:53:26.902  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:53:26.902  1356  1356 D PanProfile: Bluetooth service connected
08-26 21:53:26.902  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:26.902  3948  3948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:26.903  1356  1356 D BluetoothMap: Proxy object connected
08-26 21:53:26.903  1356  1356 D MapProfile: Bluetooth service connected
08-26 21:53:26.903  1356  1356 D BluetoothMap: getConnectedDevices()
,08-26 21:53:26.903  1910  1925 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:26.904  1356  2145 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:26.905  3948  3948 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:26.905  1356  1356 D BluetoothInputDevice: Proxy object connected
08-26 21:53:26.905  1356  1356 D HidProfile: Bluetooth service connected
,08-26 21:53:26.907   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 21:53:26.914  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:26.914  3948  3948 D ObexServerSockets: Succeed to create listening sockets 
08-26 21:53:26.914  3948  3948 D ObexServerSockets0: startAccept()
08-26 21:53:26.914  3948  3948 D ObexServerSockets0: prepareForNewConnect()
08-26 21:53:26.915  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:26.918  3948  4135 D ObexServerSockets0: Accepting socket connection...
,08-26 21:53:26.918  3948  3948 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 21:53:26.919  3948  3948 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 21:53:26.919  3948  4136 D ObexServerSockets0: Accepting socket connection...
,08-26 21:53:26.919  3948  3948 D BluetoothMapService: onReceive
,08-26 21:53:26.919  3948  3948 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:26.919  3948  3948 D BluetoothMapService: STATE_ON
08-26 21:53:26.921  3871  3871 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 21:53:26.926  3871  3871 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 21:53:26.932  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:53:26.935  3871  3871 D BluetoothA2dp: Proxy object connected
,08-26 21:53:26.940  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:26.944  3871  3871 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:26.956  1356  1356 D BluetoothPbap: Proxy object connected
08-26 21:53:26.956  1356  1356 D PbapServerProfile: Bluetooth service connected
,08-26 21:53:26.957  3871  3871 D BluetoothPbap: Proxy object connected
08-26 21:53:26.957  3871  3871 D PbapServerProfile: Bluetooth service connected
,08-26 21:53:26.957  3948  3948 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 21:53:26.957  3948  3948 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:53:26.968  3948  4140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:26.983  3948  4144 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:26.985  3948  4144 I BtOppRfcommListener: Accept thread started.
,08-26 21:53:26.995  1910  2058 D BluetoothHeadset: Proxy object connected
,08-26 21:53:26.996  1356  1372 D BluetoothHeadset: Proxy object connected
08-26 21:53:26.996   872   872 D BluetoothHeadset: Proxy object connected
08-26 21:53:26.996  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-26 21:53:26.996   872   872 D BluetoothHeadset: Proxy object connected
08-26 21:53:26.996   872   872 D BluetoothHeadset: Proxy object connected
08-26 21:53:26.998  1356  1371 D BluetoothHeadset: Proxy object connected
,08-26 21:53:27.000  1356  1356 D HeadsetProfile: Bluetooth service connected
,08-26 21:53:27.004  1910  2071 D BluetoothHeadset: Proxy object connected
,08-26 21:53:27.028  3871  3883 D BluetoothHeadset: Proxy object connected
,08-26 21:53:27.030  3871  3871 D HeadsetProfile: Bluetooth service connected
,08-26 21:53:28.468   872  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-26 21:53:28.484  3948  4106 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 21:53:28.485  3948  4106 D BluetoothAdapterProperties: Setting state to 13
08-26 21:53:28.485  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 21:53:28.487  3948  4106 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 21:53:28.497  3948  3948 D BluetoothMapService: onReceive
,08-26 21:53:28.497  3948  3948 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 21:53:28.497  3948  3948 D BluetoothMapService: STATE_TURNING_OFF
,08-26 21:53:28.498  3948  3948 D BluetoothMapService: MAP Service closeService in
08-26 21:53:28.498  3948  3948 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 21:53:28.498  3948  4106 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:53:28.499  3948  3948 D ObexServerSockets0: shutdown(block = true)
,08-26 21:53:28.500  3948  4135 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 21:53:28.503  3948  3948 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 21:53:28.503  3948  4136 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 21:53:28.505  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:28.505  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:28.509  3948  3948 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 21:53:28.509  3948  3948 I BtOppRfcommListener: stopping Accept Thread
,08-26 21:53:28.509  3948  4144 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 21:53:28.510  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.510  3948  4110 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:28.510  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:28.510  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 21:53:28.511  3948  4118 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-26 21:53:28.512  3948  4144 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 21:53:28.512  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 21:53:28.517  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:28.517  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:28.518  3788  3788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 21:53:28.518  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:28.519  3948  3948 D HeadsetService: Received stop request...Stopping profile...
08-26 21:53:28.522  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.524  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.524  1910  1935 D BluetoothHeadset: Proxy object disconnected
,08-26 21:53:28.524  3948  3948 D A2dpService: Received stop request...Stopping profile...
,08-26 21:53:28.524  1356  1371 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:28.524  1356  1356 D HeadsetProfile: Bluetooth service disconnected
08-26 21:53:28.525  3948  4125 D A2dpStateMachine: Exit Disconnected: -1,
,08-26 21:53:28.525  3871  3883 D BluetoothHeadset: Proxy object disconnected
,08-26 21:53:28.525   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:28.525   872   872 D BluetoothHeadset: Proxy object disconnected
,08-26 21:53:28.525   872   872 D BluetoothHeadset: Proxy object disconnected
08-26 21:53:28.527   872   872 D BluetoothA2dp: Proxy object disconnected
08-26 21:53:28.527  1356  1356 D BluetoothA2dp: Proxy object disconnected
08-26 21:53:28.528  3948  3948 D HidService: Received stop request...Stopping profile...
08-26 21:53:28.528  3948  3948 D HidService: Stopping Bluetooth HidService
08-26 21:53:28.528  1356  1356 D BluetoothInputDevice: Proxy object disconnected
,08-26 21:53:28.528  1356  1356 D HidProfile: Bluetooth service disconnected
08-26 21:53:28.530  3948  3948 D HealthService: Received stop request...Stopping profile...
08-26 21:53:28.531  3948  3948 D PanService: Received stop request...Stopping profile...
08-26 21:53:28.533  1356  1356 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 21:53:28.533  1356  1356 D PanProfile: Bluetooth service disconnected
08-26 21:53:28.534  3948  3948 D BluetoothMapService: Received stop request...Stopping profile...
08-26 21:53:28.535  3948  3948 D BluetoothMapService: stop()
08-26 21:53:28.535  3871  3871 D DockEventReceiver: finishStartingService: stopping service
08-26 21:53:28.536  3871  3871 D HeadsetProfile: Bluetooth service disconnected
08-26 21:53:28.536  3871  3871 D BluetoothA2dp: Proxy object disconnected
08-26 21:53:28.536  3948  3948 D BluetoothMapAppObserver: deinitObservers()
08-26 21:53:28.536  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:28.536  3871  3871 D BluetoothInputDevice: Proxy object disconnected
08-26 21:53:28.537  3948  3948 D BluetoothMapAppObserver: removeReceiver()
08-26 21:53:28.537  3871  3871 D HidProfile: Bluetooth service disconnected
08-26 21:53:28.537  3871  3871 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 21:53:28.537  3871  3871 D PanProfile: Bluetooth service disconnected
,08-26 21:53:28.540  1356  1356 D BluetoothMap: Proxy object disconnected
,08-26 21:53:28.540  1356  1356 D MapProfile: Bluetooth service disconnected
,08-26 21:53:28.540  3948  3948 V BluetoothAdapterState: isTurningOff()=true
,08-26 21:53:28.540  3948  3948 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:53:28.540  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.541  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:28.541  3871  3871 D BluetoothMap: Proxy object disconnected
08-26 21:53:28.541  3871  3871 D MapProfile: Bluetooth service disconnected
08-26 21:53:28.542  3948  3948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 21:53:28.542  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 21:53:28.542  3948  3948 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 21:53:28.542  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:28.543  3948  3948 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:53:28.543  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:28.543  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:28.544  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 21:53:28.544  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:28.544  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:28.545  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.545  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:28.545  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:28.545  3948  3948 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 21:53:28.545  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:28.545  3948  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 21:53:28.545  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:28.545  3948  4110 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-26 21:53:28.545  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:28.545  3948  3948 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 21:53:28.545  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 21:53:28.545  3948  4116 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:28.546  3948  4116 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:28.546  3948  4116 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 21:53:28.546  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:28.546  3948  4116 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 21:53:28.546  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:28.546  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.546  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:28.546  3948  3948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 21:53:28.546  3948  4110 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 21:53:28.546  3948  3948 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 21:53:28.547  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:28.547  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:28.547  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.547  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:28.547  3948  3948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 21:53:28.548  3948  3948 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 21:53:28.550  1356  1356 D BluetoothPbap: Proxy object disconnected
08-26 21:53:28.550  1356  1356 D PbapServerProfile: Bluetooth service disconnected
08-26 21:53:28.550  3871  3871 D BluetoothPbap: Proxy object disconnected
08-26 21:53:28.550  3871  3871 D PbapServerProfile: Bluetooth service disconnected
08-26 21:53:28.552  3948  3948 D BluetoothMapService: MAP Service closeService in
08-26 21:53:28.552  3948  3948 V BluetoothAdapterState: isTurningOff()=true
08-26 21:53:28.552  3948  3948 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:28.552  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.552  3948  3948 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:28.553  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 21:53:28.553  3948  4106 D BluetoothAdapterProperties: Setting state to 15
08-26 21:53:28.553  3948  3948 D BluetoothMapService: cleanup()
,08-26 21:53:28.553  3948  3948 D BluetoothMapService: MAP Service closeService in
,08-26 21:53:28.553  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 21:53:28.553  1356  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:28.554  3948  4106 I BluetoothAdapterState: Entering BleOnState
08-26 21:53:28.554   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:28.554   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:28.554  3871  3882 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 21:53:28.555   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:28.555  3871  3883 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 21:53:28.555   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:28.555  3871  3882 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:53:28.556  3871  3883 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:53:28.556  3871  3882 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:53:28.557  1356  2145 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:28.557  1356  3787 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 21:53:28.559  1356  1372 D BluetoothPan: onBluetoothStateChange on: false
08-26 21:53:28.559  3871  3883 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 21:53:28.560  1356  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-26 21:53:28.560  1910  1925 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 21:53:28.561  1356  2145 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 21:53:28.561  3948  4106 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-26 21:53:28.561  3948  4106 D BluetoothAdapterProperties: Setting state to 16
,08-26 21:53:28.561  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 21:53:28.562  3948  4106 D BluetoothAdapterProperties: onBleDisable
08-26 21:53:28.562  3948  4107 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 21:53:28.563  3948  4106 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:53:28.564  3948  4110 D BluetoothAdapterProperties: Scan Mode:20
08-26 21:53:28.564  3948  4116 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 21:53:28.564  3948  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 21:53:28.566  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.566  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 21:53:28.567  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.568  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.569  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:28.571  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:28.573  3871  3871 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:28.766  3948  4110 I bt_hci  : shut_down
,08-26 21:53:28.781  3948  4114 D bt_hwcfg: hw_epilog_process
,08-26 21:53:28.781  3948  4114 I bt_vendor: low_power_mode_cb
,08-26 21:53:28.797  3948  4114 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 21:53:28.797  3948  4114 I bt_vendor: epilog_cb
08-26 21:53:28.798  3948  4114 I bt_hci  : epilog_finished_callback
,08-26 21:53:28.805  3948  4110 I bt_hci_h4: hal_close
,08-26 21:53:28.806  3948  4110 I bt_userial_vendor: device fd = 51 close
,08-26 21:53:28.927  3948  4107 D bt_stack_manager: event_shut_down_stack finished.
,08-26 21:53:28.928  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 21:53:28.934  3948  4106 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 21:53:28.935  3948  3948 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:28.937  3948  3948 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 21:53:28.937  3948  3948 D BtGatt.GattService: stop()
,08-26 21:53:28.939  3948  3948 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 21:53:28.945  3948  3948 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:53:28.946  3948  3948 V BluetoothAdapterState: isTurningOn()=false
,08-26 21:53:28.946  3948  3948 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:28.946  3948  3948 V BluetoothAdapterState: isBleTurningOff()=true
08-26 21:53:28.947  3948  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 21:53:28.948  3948  4106 D BluetoothAdapterProperties: Setting state to 10
08-26 21:53:28.948  3948  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 21:53:28.950  3948  4106 I BluetoothAdapterState: Entering OffState
,08-26 21:53:28.951   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 21:53:28.971  3948  3948 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 21:53:28.971  3948  3948 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 21:53:28.971  3948  3948 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 21:53:28.972  3948  4107 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 21:53:28.976  3948  4107 D bt_stack_manager: event_clean_up_stack finished.
,08-26 21:53:28.978  3948  3948 I art     : System.exit called, status: 0
,08-26 21:53:28.978  3948  3948 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 21:53:29.045   872  1380 I ActivityManager: Process com.android.bluetooth (pid 3948) has died
,08-26 21:53:31.481  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:53:31.482  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:34.490  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:34.490  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ccdc0b4 added. We now have 6 listener(s)
,08-26 21:53:34.491  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:34.495  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:34.495  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38a14dd added. We now have 7 listener(s)
08-26 21:53:34.496  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:34.497  3788  3853 I System.out: IsBluetoothEnabled
,08-26 21:53:34.509  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:34.554   872   889 I ActivityManager: Start proc 4155:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 21:53:34.694  4155  4155 D AdapterServiceConfig: Adding HeadsetService
08-26 21:53:34.694  4155  4155 D AdapterServiceConfig: Adding A2dpService
,08-26 21:53:34.694  4155  4155 D AdapterServiceConfig: Adding HidService
08-26 21:53:34.695  4155  4155 D AdapterServiceConfig: Adding HealthService
08-26 21:53:34.695  4155  4155 D AdapterServiceConfig: Adding PanService
08-26 21:53:34.695  4155  4155 D AdapterServiceConfig: Adding GattService
,08-26 21:53:34.695  4155  4155 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 21:53:34.708  4155  4155 D BluetoothAdapterState: make() - Creating AdapterState
08-26 21:53:34.708   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2d3046:true
,08-26 21:53:34.715  4155  4155 I bt_bluedroid: init
,08-26 21:53:34.716  4155  4167 I BluetoothAdapterState: Entering OffState
,08-26 21:53:34.721  4155  4168 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 21:53:34.722  4155  4168 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 21:53:34.722  4155  4168 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 21:53:34.723  4155  4168 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 21:53:34.725  4155  4155 I bt_bluedroid: get_profile_interface socket
,08-26 21:53:34.728  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 21:53:34.728  4155  4155 I bt_bluedroid: get_profile_interface sdp
08-26 21:53:34.729  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:53:34.732  4155  4166 I bt_bluedroid: config_hci_snoop_log
,08-26 21:53:34.735   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 21:53:34.746  4155  4167 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 21:53:34.747  4155  4167 D BluetoothAdapterProperties: Setting state to 14
,08-26 21:53:34.748  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 21:53:34.749  4155  4167 D BluetoothBondStateMachine: make
,08-26 21:53:34.753  4155  4172 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 21:53:34.755  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
,08-26 21:53:34.757  4155  4155 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 21:53:34.760  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:34.760  4155  4155 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 21:53:34.761  4155  4155 D BtGatt.GattService: Received start request. Starting profile...
08-26 21:53:34.761  4155  4155 D BtGatt.GattService: start()
,08-26 21:53:34.761  4155  4155 I bt_bluedroid: get_profile_interface gatt
,08-26 21:53:34.762  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:34.762  4155  4155 D BtGatt.AdvertiseManager: advertise manager created
,08-26 21:53:34.773  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:53:34.773  4155  4155 V BluetoothAdapterState: isTurningOn()=false
08-26 21:53:34.773  4155  4155 V BluetoothAdapterState: isBleTurningOn()=true
08-26 21:53:34.773  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:34.774  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 21:53:34.775  4155  4167 I bt_bluedroid: enable
,08-26 21:53:34.775  4155  4168 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 21:53:34.776  4155  4168 I bt_hci  : start_up
,08-26 21:53:34.795  4155  4168 I bt_vendor: alloc value 0xb3a4a189
,08-26 21:53:34.796  4155  4168 I bt_vendor: init
08-26 21:53:34.796  4155  4168 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 21:53:34.796  4155  4168 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 21:53:34.907  4155  4168 D bt_hci  : start_up starting async portion
,08-26 21:53:34.907  4155  4175 I bt_hci  : event_finish_startup
08-26 21:53:34.908  4155  4175 I bt_hci_h4: hal_open
08-26 21:53:34.908  4155  4175 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 21:53:34.921  4155  4175 I bt_userial_vendor: device fd = 51 open
,08-26 21:53:34.949  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:53:34.980  4155  4175 D bt_hwcfg: Chipset BCM4354A2
,08-26 21:53:34.980  4155  4175 D bt_hwcfg: Target name = [BCM4354A2]
08-26 21:53:34.982  4155  4175 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 21:53:35.839  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 21:53:35.841  4155  4175 D bt_hwcfg: Settlement delay -- 100 ms
08-26 21:53:35.841  4155  4175 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 21:53:35.959  4155  4175 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 21:53:35.961  4155  4175 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 21:53:35.989  4155  4175 I bt_hwcfg: vendor lib fwcfg completed
,08-26 21:53:35.989  4155  4175 I bt_vendor: firmware callback
,08-26 21:53:35.989  4155  4175 I bt_hci  : firmware_config_callback
,08-26 21:53:36.002  4155  4177 I bt_btu  : btu_task pending for preload complete event
,08-26 21:53:36.002  4155  4177 I bt_btu_task: Bluetooth chip preload is complete
08-26 21:53:36.003  4155  4177 I bt_btu  : btu_task received preload complete event
,08-26 21:53:36.016  4155  4177 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 21:53:36.017  4155  4177 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 21:53:36.017  4155  4177 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 21:53:36.017  4155  4177 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 21:53:36.018  4155  4177 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 21:53:36.018  4155  4177 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 21:53:36.018  4155  4177 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 21:53:36.018  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 21:53:36.019  4155  4177 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 21:53:36.020  4155  4177 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 21:53:36.020  4155  4177 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 21:53:36.022  4155  4177 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 21:53:36.022  4155  4177 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 21:53:36.022  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 21:53:36.022  4155  4177 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 21:53:36.167  4155  4177 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d,
08-26 21:53:36.167  4155  4177 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,08-26 21:53:36.181  4155  4171 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-26 21:53:36.184  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 21:53:36.185  4155  4171 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 21:53:36.188  4155  4171 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 21:53:36.191  4155  4171 D BluetoothAdapterProperties: Scan Mode:20
,08-26 21:53:36.194  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 21:53:36.194  4155  4171 D bt_hci  : do_postload posting postload work item
08-26 21:53:36.195  4155  4175 I bt_hci  : event_postload
08-26 21:53:36.195  4155  4175 I bt_vendor: sco_config_cb
08-26 21:53:36.195  4155  4175 I bt_hci  : sco_config_callback postload finished.
,08-26 21:53:36.197  4155  4171 D bt_bte_conf: Device ID record 1 : primary
08-26 21:53:36.197  4155  4171 D bt_bte_conf:   vendorId            = 000f
08-26 21:53:36.197  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:36.198  4155  4171 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 21:53:36.198  4155  4171 D bt_bte_conf:   product             = 1200
08-26 21:53:36.198  4155  4171 D bt_bte_conf:   version             = 1436
08-26 21:53:36.198  4155  4171 D bt_bte_conf:   clientExecutableURL = 
08-26 21:53:36.198  4155  4171 D bt_bte_conf:   serviceDescription  = 
08-26 21:53:36.199  4155  4171 D bt_bte_conf:   documentationURL    = 
,08-26 21:53:36.199  4155  4171 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 21:53:36.199  4155  4168 D bt_stack_manager: event_start_up_stack finished
08-26 21:53:36.201  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 21:53:36.202  4155  4167 D BluetoothAdapterProperties: Setting state to 15
,08-26 21:53:36.202  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 21:53:36.204  4155  4167 I BluetoothAdapterState: Entering BleOnState
08-26 21:53:36.205  4155  4175 I bt_vendor: low_power_mode_cb
,08-26 21:53:36.218  4155  4167 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 21:53:36.218  4155  4167 D BluetoothAdapterProperties: Setting state to 11
,08-26 21:53:36.218  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 21:53:36.226  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:36.227  4155  4155 D HeadsetService: Received start request. Starting profile...
,08-26 21:53:36.231  4155  4155 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 21:53:36.231  4155  4155 D HeadsetStateMachine: make
,08-26 21:53:36.234  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:36.246  4155  4167 I BluetoothAdapterState: Entering PendingCommandState
08-26 21:53:36.247  4155  4155 D HeadsetStateMachine: max_hf_connections = 1
,08-26 21:53:36.247  4155  4155 I bt_bluedroid: get_profile_interface handsfree
08-26 21:53:36.247  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 21:53:36.247  4155  4171 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 21:53:36.254  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:36.255  4155  4155 D A2dpService: Received start request. Starting profile...
08-26 21:53:36.255  4155  4155 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 21:53:36.256  4155  4155 I bt_bluedroid: get_profile_interface avrcp
,08-26 21:53:36.263  4155  4155 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 21:53:36.264  4155  4155 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 21:53:36.264  4155  4155 D A2dpStateMachine: make
,08-26 21:53:36.268  4155  4155 I bt_bluedroid: get_profile_interface a2dp
,08-26 21:53:36.268  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 21:53:36.274  4155  4186 D A2dpStateMachine: Enter Disconnected: -2
,08-26 21:53:36.275  4155  4155 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 21:53:36.276  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
08-26 21:53:36.276  4155  4155 D HidService: Received start request. Starting profile...
,08-26 21:53:36.276  4155  4155 I bt_bluedroid: get_profile_interface hidhost
,08-26 21:53:36.276  4155  4171 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
,08-26 21:53:36.276  4155  4155 D HidService: setHidService(): set to: null
08-26 21:53:36.277  4155  4171 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 21:53:36.279  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 21:53:36.279  4155  4155 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 21:53:36.279  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:36.280  4155  4155 D HealthService: Received start request. Starting profile...
08-26 21:53:36.281  4155  4155 I bt_bluedroid: get_profile_interface health
08-26 21:53:36.282  4155  4155 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 21:53:36.283  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
08-26 21:53:36.284  4155  4155 D PanService: Received start request. Starting profile...
,08-26 21:53:36.284  4155  4155 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 21:53:36.284  4155  4155 I bt_bluedroid: get_profile_interface pan
,08-26 21:53:36.284  4155  4171 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 21:53:36.286  4155  4155 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:36.287  4155  4155 D BluetoothMapService: Received start request. Starting profile...
,08-26 21:53:36.287  4155  4155 D BluetoothMapService: start()
08-26 21:53:36.291  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 21:53:36.291  4155  4155 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 21:53:36.291  4155  4155 D BluetoothMapAppObserver: createReceiver()
,08-26 21:53:36.292  4155  4155 D BluetoothMapAppObserver: initObservers()
08-26 21:53:36.292  4155  4155 D BluetoothMapAppObserver: getEnabledAccountItems()
08-26 21:53:36.298  4155  4183 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 21:53:36.298  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:36.298  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.298  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:36.298  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 21:53:36.300  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:36.304  4155  4155 V BluetoothAdapterState: isTurningOff()=false
08-26 21:53:36.304  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.304  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isTurningOff()=false
,08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isTurningOn()=true
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isBleTurningOn()=false
08-26 21:53:36.305  4155  4155 V BluetoothAdapterState: isBleTurningOff()=false
08-26 21:53:36.306  4155  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 21:53:36.306  4155  4167 D BluetoothAdapterProperties: ScanMode =  20
08-26 21:53:36.306  4155  4167 D BluetoothAdapterProperties: State =  11
08-26 21:53:36.306  4155  4167 D BluetoothAdapterProperties: Setting state to 12
,08-26 21:53:36.306  4155  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 21:53:36.307  1356  3787 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:36.307  4155  4171 D BluetoothAdapterProperties: Scan Mode:21
,08-26 21:53:36.307  4155  4171 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 21:53:36.307  4155  4167 I BluetoothAdapterState: Entering OnState
08-26 21:53:36.308   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:36.309   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.309  3871  3883 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:53:36.309   872   872 D BluetoothA2dp: Proxy object connected
08-26 21:53:36.309  1356  1356 D BluetoothA2dp: Proxy object connected
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:36.311  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:36.312  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 21:53:36.312   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.312  3871  3882 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.313   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.313  3871  3883 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:53:36.314  3871  3882 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:53:36.315  3871  3871 D BluetoothMap: Proxy object connected
08-26 21:53:36.315  3871  3871 D MapProfile: Bluetooth service connected
08-26 21:53:36.315  3871  3871 D BluetoothMap: getConnectedDevices()
08-26 21:53:36.316  3871  3883 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:36.317  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 21:53:36.317  1356  1372 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.318  1356  3787 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 21:53:36.318  4155  4155 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-26 21:53:36.319  3871  3871 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 21:53:36.319  1356  2145 D BluetoothPan: onBluetoothStateChange on: true
08-26 21:53:36.319  3871  3871 D PanProfile: Bluetooth service connected
08-26 21:53:36.319  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:36.320  1356  1356 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 21:53:36.320  3871  3882 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 21:53:36.320  1356  1356 D PanProfile: Bluetooth service connected
08-26 21:53:36.321  4155  4155 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 21:53:36.321  1356  3787 D BluetoothMap: onBluetoothStateChange: up=true
08-26 21:53:36.322  4155  4155 D ObexServerSockets: Succeed to create listening sockets 
08-26 21:53:36.322  4155  4155 D ObexServerSockets0: startAccept()
,08-26 21:53:36.322  4155  4155 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:53:36.322  1356  1356 D BluetoothMap: Proxy object connected
08-26 21:53:36.322  1910  1925 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 21:53:36.322  1356  1356 D MapProfile: Bluetooth service connected
08-26 21:53:36.322  1356  1356 D BluetoothMap: getConnectedDevices()
08-26 21:53:36.323  1356  2145 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 21:53:36.324  3871  3871 D BluetoothA2dp: Proxy object connected
08-26 21:53:36.324   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 21:53:36.324  4155  4155 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 21:53:36.325  4155  4155 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 21:53:36.326  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:36.326  4155  4194 D ObexServerSockets0: Accepting socket connection...
08-26 21:53:36.326  4155  4193 D ObexServerSockets0: Accepting socket connection...
08-26 21:53:36.327  1356  1356 D BluetoothInputDevice: Proxy object connected
08-26 21:53:36.327  1356  1356 D HidProfile: Bluetooth service connected
08-26 21:53:36.327  4155  4155 D BluetoothMapService: onReceive
,08-26 21:53:36.327  4155  4155 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 21:53:36.327  4155  4155 D BluetoothMapService: STATE_ON
08-26 21:53:36.330  3871  3871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 21:53:36.333  3871  3871 D BluetoothInputDevice: Proxy object connected
08-26 21:53:36.333  3871  3871 D HidProfile: Bluetooth service connected
,08-26 21:53:36.335  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 21:53:36.338  3871  3871 D DockEventReceiver: finishStartingService: stopping service
,08-26 21:53:36.343  1356  1356 D BluetoothPbap: Proxy object connected
08-26 21:53:36.344  1356  1356 D PbapServerProfile: Bluetooth service connected
08-26 21:53:36.344  3871  3871 D BluetoothPbap: Proxy object connected
08-26 21:53:36.344  3871  3871 D PbapServerProfile: Bluetooth service connected
,08-26 21:53:36.351  4155  4199 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:36.364  4155  4155 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 21:53:36.364  4155  4155 D ObexServerSockets0: prepareForNewConnect()
,08-26 21:53:36.371  4155  4203 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 21:53:36.372  4155  4203 I BtOppRfcommListener: Accept thread started.
,08-26 21:53:36.413   872   889 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.414  1910  2058 D BluetoothHeadset: Proxy object connected
08-26 21:53:36.415  3871  3882 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.415  1356  1371 D BluetoothHeadset: Proxy object connected
08-26 21:53:36.416  1356  1356 D HeadsetProfile: Bluetooth service connected
08-26 21:53:36.416   872   889 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.417  3871  3883 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.418  1356  1372 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.419   872   872 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.420   872   872 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.420   872   872 D BluetoothHeadset: Proxy object connected
08-26 21:53:36.419  3871  3871 D HeadsetProfile: Bluetooth service connected
,08-26 21:53:36.425  1356  1356 D HeadsetProfile: Bluetooth service connected
08-26 21:53:36.425  1910  2071 D BluetoothHeadset: Proxy object connected
,08-26 21:53:36.430  3871  3871 D HeadsetProfile: Bluetooth service connected
,08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:36.532  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:36.541  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:36.546  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:36.546  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4146852 added. We now have 8 listener(s)
08-26 21:53:36.547  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:36.554   872   883 D WifiService: setWifiEnabled: false pid=3788, uid=10000
,08-26 21:53:36.554   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:36.573  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:36.574   872   882 D WifiService: setWifiEnabled: true pid=3788, uid=10000
08-26 21:53:36.574   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 21:53:36.586   872  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 21:53:36.611  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 21:53:36.614  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 21:53:36.620   872  1301 D WifiConfigStore: loaded 0 passpoint configs
08-26 21:53:36.621   872  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-26 21:53:36.622   872  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-26 21:53:36.623   872  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 21:53:36.623   872  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 21:53:36.623   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 21:53:36.623   872  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 21:53:36.635   872  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.90 rxSuccessRate=1.06 delta 1000 -> 1000
08-26 21:53:36.635   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 21:53:36.637   371   870 D CommandListener: Setting iface cfg
08-26 21:53:36.638   872  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 21:53:36.638   872  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 21:53:36.643   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 21:53:36.643   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:53:36.654   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 21:53:36.654   872  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 21:53:36.701   872  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 21:53:36.719   872  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 21:53:36.721  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 21:53:37.188  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 21:53:37.231  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 21:53:37.232  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 21:53:37.245   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:53:37.255   872  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:53:37.255   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 21:53:37.256   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 21:53:37.274   872  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 21:53:37.285   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:37.289   872  1301 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 21:53:37.302   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 21:53:37.303   872  1303 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-26 21:53:37.303   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 21:53:37.310   872  4210 D DhcpClient: Receive thread started
,08-26 21:53:37.393   872  1301 E native  : do suspend false
,08-26 21:53:37.414   872  2065 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 21:53:37.427   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 21:53:37.429   872  2065 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 21:53:37.433   872  2065 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 21:53:37.449   872  4210 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 21:53:37.450   872  2065 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 21:53:37.456   371   870 D CommandListener: Setting iface cfg
,08-26 21:53:37.466   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 21:53:37.467   872  2065 D DhcpClient: Scheduling renewal in 86399s
,08-26 21:53:37.481   872  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 21:53:37.482   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
08-26 21:53:37.482   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 21:53:37.490   872  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 21:53:37.491   872  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 21:53:37.546   872  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 21:53:37.546   872  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 21:53:37.547   872  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 21:53:37.549   872  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 21:53:37.550   872  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 21:53:37.561   872  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 21:53:37.575   872  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-26 21:53:37.575   872  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 21:53:37.575   872  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 21:53:37.576   872  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 21:53:37.576   872  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-26 21:53:37.576   872  1303 D ConnectivityService:    accepting network in place of null
08-26 21:53:37.578   872  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 21:53:37.580   872  4209 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145287, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:37.592  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:37.595  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:37.600  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 21:53:37.601  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 21:53:37.603  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@776e93a Bundle[{}]
,08-26 21:53:37.604  3788  3853 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 21:53:37.604  3788  3853 I io.jxcore.node.LifeCycleMonitor: stop: OK,
08-26 21:53:37.605  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 21:53:37.606  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 21:53:37.606  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 21:53:37.607  3788  3853 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 21:53:37.612  3788  3853 I System.out: Running OutgoingSocketThread
,08-26 21:53:37.615  3788  4219 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-26 21:53:37.617  3788  4219 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45461
,08-26 21:53:37.617  3788  4219 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 21:53:37.628   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:37.653   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,08-26 21:53:37.656   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 21:53:37.663   872  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 21:53:37.663   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:37.677   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-26 21:53:37.677   872  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:37.684  3788  3788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:37.688  3788  3788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:37.698  1953  1953 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-26 21:53:37.707  1744  1744 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 21:53:37.717  1744  1744 D SystemUpdateService: onCreate
,08-26 21:53:37.721  1744  1744 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 21:53:37.734  1744  4223 I SystemUpdateService: active receiver: enabled
,08-26 21:53:37.740   872  4208 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 19:53:37 GMT], X-Android-Received-Millis=[1472241217739], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472241217702]}
,08-26 21:53:37.741  1744  4223 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 21:53:37.744   872  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 21:53:37.745   872  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 21:53:37.745   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 21:53:37.747   872  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 21:53:37.753  1744  4223 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 21:53:37.753  1744  4223 I SystemUpdateService: now status is 0 (complete)
08-26 21:53:37.753  1744  4223 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 21:53:37.753  1744  4223 I SystemUpdateService: file has been verified
,08-26 21:53:37.754  1744  4223 I SystemUpdateService: OTA package size = 12249756
,08-26 21:53:37.762  1744  1744 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 21:53:37.765  1744  2581 I iu.UploadsManager: num queued entries: 0
,08-26 21:53:37.766  1744  2581 I iu.UploadsManager: num updated entries: 0
08-26 21:53:37.766  1744  2581 I iu.SyncManager: NEXT; no task
,08-26 21:53:37.773  1744  4227 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 21:53:37.773  1744  4227 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 21:53:37.775  1744  4227 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 21:53:37.781  1744  4223 I SystemUpdateService: showing system update notification
,08-26 21:53:37.782  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:37.788  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 21:53:37.797  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 21:53:37.799  1744  1744 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 21:53:37.803  3963  3963 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 21:53:37.814  3963  3963 D SprintDMHelper: simOperator: 
,08-26 21:53:37.814  3963  3963 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 21:53:37.818  1744  1744 D SystemUpdateService: onDestroy
,08-26 21:53:37.844  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 21:53:37.846  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 21:53:37.846  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 21:53:37.848  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 21:53:37.861  1744  4227 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-26 21:53:37.948  3039  4229 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 21:53:38.616  3788  3853 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-26 21:53:38.616  3788  3853 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-26 21:53:38.626  3788  3853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-26 21:53:38.628  3788  3853 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 21:53:38.628  3788  3853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-26 21:53:38.633  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:38.633  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e59723 added. We now have 2 listener(s)
,08-26 21:53:38.635  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.635  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.635  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:38.635  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:38.635  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee03420 added. We now have 9 listener(s)
08-26 21:53:38.635  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.636  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:53:38.639  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:38.647  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:38.649  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:38.649  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:53:38.649  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:38.650  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96cb79e added. We now have 3 listener(s)
,08-26 21:53:38.652  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.653  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:53:38.653  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.653  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:38.653  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@570827f added. We now have 10 listener(s)
,08-26 21:53:38.653  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:38.654  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.654  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:38.654  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:38.655  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:38.655  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.655  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.655  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:38.655  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:53:38.656  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e59723 removed from the list
08-26 21:53:38.656  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.656  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee03420 removed from the list
,08-26 21:53:38.658  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.658  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:53:38.658  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.659  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.659  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.661  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:38.661  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.661  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.661  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee03420 not in the list
,08-26 21:53:38.662  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.662  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.663   872  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 21:53:38.664  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.664  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:38.664  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.664  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@570827f removed from the list
,08-26 21:53:38.665  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.665  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.665  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.665  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:53:38.666  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96cb79e removed from the list
08-26 21:53:38.667  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:38.668  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e4724c added. We now have 2 listener(s)
08-26 21:53:38.674  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.674  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.674  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.674  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.674  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe00295 added. We now have 9 listener(s)
,08-26 21:53:38.674  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.675  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:53:38.677  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:38.684  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:38.685  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.685  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:53:38.686  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:38.686  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@494c79b added. We now have 3 listener(s)
,08-26 21:53:38.688  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 21:53:38.688  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:53:38.688  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:38.688  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.688  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.688  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50c6738 added. We now have 10 listener(s)
,08-26 21:53:38.688  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.688  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:53:38.688  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 21:53:38.689  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:38.689  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:38.689  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:38.691  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 21:53:38.692  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 21:53:38.692  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 21:53:38.696  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 21:53:38.697  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:53:38.697  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:38.700  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:53:38.700  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:53:38.700  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:53:38.701  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:38.704  4155  4165 D BtGatt.GattService: registerClient() - UUID=39cf9cb1-183f-4f66-99cb-22a14d0a72c6
,08-26 21:53:38.704  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=39cf9cb1-183f-4f66-99cb-22a14d0a72c6, clientIf=5
,08-26 21:53:38.705  3788  3850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:53:38.706  4155  4195 D BtGatt.GattService: start scan with filters
,08-26 21:53:38.709  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:53:38.709  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 21:53:38.709  4155  4174 D BtGatt.ScanManager: handling starting scan
,08-26 21:53:38.709  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 21:53:38.710  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:38.711  4155  4174 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e7782e
,08-26 21:53:38.713  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:38.713  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:38.713  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:53:38.715  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:53:38.715  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.715  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:38.716  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:53:38.718  3788  3853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 21:53:38.718  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:38.719  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 21:53:38.719  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.719  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 21:53:38.719  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 21:53:38.719  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 21:53:38.719  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:53:38.719  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:53:38.720  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:38.720  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 21:53:38.721  3788  3853 D BluetoothAdapter: STATE_ON
08-26 21:53:38.721  4155  4195 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:53:38.722  4155  4184 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:53:38.723  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:53:38.723  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 21:53:38.723  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:53:38.723  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:53:38.723  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 21:53:38.723  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-26 21:53:38.723  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.724  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:38.724  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 21:53:38.726  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:38.726  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:53:38.726  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:53:38.726  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:53:38.727  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:38.728  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:38.728  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:38.728  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:38.731  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:38.731  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:38.731  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 21:53:38.732  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:53:38.732  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.732  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:38.732  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 21:53:38.732  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e4724c removed from the list
,08-26 21:53:38.732  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.732  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe00295 removed from the list,
08-26 21:53:38.732  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:38.732  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:53:38.733  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.733  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.734  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:38.734  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.734  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:53:38.734  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe00295 not in the list
,08-26 21:53:38.734  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.739  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 21:53:38.743  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.743  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:38.744  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.744  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 21:53:38.744  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.745  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50c6738 removed from the list
08-26 21:53:38.745  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.745  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.745  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:38.745  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.745  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@494c79b removed from the list
,08-26 21:53:38.746  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:38.746  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebcbee4 added. We now have 2 listener(s),
08-26 21:53:38.748  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.748  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.748  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.748  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.749  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deef4d added. We now have 9 listener(s)
,08-26 21:53:38.749  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.749  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:38.751  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 21:53:38.751  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.753  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:38.757  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:38.758  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:53:38.758  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.758  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:53:38.760  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.760  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:38.760  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:38.760  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fa8f13 added. We now have 3 listener(s)
,08-26 21:53:38.763  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.763  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:53:38.763  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.764  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.764  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.764  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f8e550 added. We now have 10 listener(s)
08-26 21:53:38.764  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 21:53:38.764  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:38.765  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 21:53:38.765  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.765  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:38.765  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:53:38.765  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:38.765  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 21:53:38.765  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:38.765  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:38.766  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.769  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 21:53:38.769  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:53:38.771  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 21:53:38.772  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.775  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:38.776  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 21:53:38.776  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:38.779  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 21:53:38.779  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:53:38.779  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:53:38.780  3788  3853 D BluetoothAdapter: STATE_ON
,08-26 21:53:38.782  4155  4191 D BtGatt.GattService: registerClient() - UUID=7b7ed385-ba1a-44ae-af3b-88d60a97e723
,08-26 21:53:38.782  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=7b7ed385-ba1a-44ae-af3b-88d60a97e723, clientIf=5
08-26 21:53:38.782  3788  3850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:53:38.783  4155  4195 D BtGatt.GattService: start scan with filters
,08-26 21:53:38.785  4155  4174 D BtGatt.ScanManager: handling starting scan
,08-26 21:53:38.785  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 21:53:38.785  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 21:53:38.785  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 21:53:38.786  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:38.788  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:38.789  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 21:53:38.789  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 21:53:38.791  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:38.791  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:53:38.791  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.792  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:53:38.794  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:53:38.794  3788  3853 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 21:53:38.794  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 21:53:38.794  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:38.794  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:53:38.795  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.795  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.795  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 21:53:38.795  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.795  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebcbee4 removed from the list
08-26 21:53:38.795  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.795  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deef4d removed from the list
08-26 21:53:38.795  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 21:53:38.795  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:38.796  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.796  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 21:53:38.796  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.796  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.797  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@deef4d not in the list
,08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 21:53:38.797  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:53:38.797  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:38.797  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:53:38.797  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 21:53:38.797  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.798  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:38.798  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:53:38.798  3788  3853 D BluetoothAdapter: STATE_ON
08-26 21:53:38.798  4155  4195 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:53:38.799  4155  4184 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:53:38.799  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 21:53:38.799  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:53:38.799  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 21:53:38.799  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 21:53:38.799  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:53:38.800  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:38.800  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:53:38.800  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 21:53:38.800  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:53:38.801  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:38.803  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:38.803  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 21:53:38.803  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:38.803  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.803  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:38.803  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.803  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f8e550 removed from the list
08-26 21:53:38.803  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.803  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.803  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:38.804  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.804  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fa8f13 removed from the list
08-26 21:53:38.804  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:38.804  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48f067c added. We now have 2 listener(s)
,08-26 21:53:38.806  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.806  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.806  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:38.807  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:38.807  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7bb05 added. We now have 9 listener(s)
,08-26 21:53:38.807  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.807  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 21:53:38.808  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 21:53:38.808  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.809  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:38.813  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 21:53:38.813  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:38.814  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:38.816  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:38.816  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 21:53:38.816  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 21:53:38.816  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372cd8b added. We now have 3 listener(s)
08-26 21:53:38.818  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.820  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.820  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.820  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.820  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.820  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7040e68 added. We now have 10 listener(s)
08-26 21:53:38.820  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.821  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 21:53:38.821  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 21:53:38.821  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 21:53:38.821  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 21:53:38.821  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 21:53:38.822  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 21:53:38.822  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.822  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
,08-26 21:53:38.824  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.825  3788  3853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 21:53:38.825  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 21:53:38.827  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 21:53:38.827  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.827  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 21:53:38.829  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 21:53:38.829  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 21:53:38.829  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 21:53:38.832  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 21:53:38.832  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.832  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 21:53:38.832  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 21:53:38.832  3788  3853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 21:53:38.833  3788  3853 D BluetoothAdapter: STATE_ON,
,08-26 21:53:38.835  4155  4184 D BtGatt.GattService: registerClient() - UUID=f239ec5c-4822-4c19-bd67-78bc24fa04bc
,08-26 21:53:38.835  4155  4171 D BtGatt.GattService: onClientRegistered() - UUID=f239ec5c-4822-4c19-bd67-78bc24fa04bc, clientIf=5
,08-26 21:53:38.835  3788  3801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 21:53:38.836  4155  4195 D BtGatt.GattService: start scan with filters
,08-26 21:53:38.838  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 21:53:38.838  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 21:53:38.838  4155  4174 D BtGatt.ScanManager: handling starting scan
08-26 21:53:38.838  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 21:53:38.838  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 21:53:38.841  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:38.841  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 21:53:38.841  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 21:53:38.843  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 21:53:38.844  4155  4171 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 21:53:38.844  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.844  4155  4174 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 21:53:38.847  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:38.847  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:38.847  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:53:38.847  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 21:53:38.848  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.848  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 21:53:38.848  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.848  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48f067c removed from the list
,08-26 21:53:38.848  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.848  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7bb05 removed from the list
08-26 21:53:38.848  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:38.848  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:38.849  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.849  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 21:53:38.849  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.849  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 21:53:38.850  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 21:53:38.850  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:38.850  4155  4174 D BtGatt.ScanManager: Starting BLE batch scan
08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 21:53:38.850  4155  4174 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.850  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c7bb05 not in the list
08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-26 21:53:38.850  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 21:53:38.850  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 21:53:38.850  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 21:53:38.851  3788  3853 D BluetoothAdapter: STATE_ON
08-26 21:53:38.851  4155  4184 D BtGatt.GattService: stopScan() - queue size =1
,08-26 21:53:38.852  4155  4195 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 21:53:38.852  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 21:53:38.852  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 21:53:38.852  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 21:53:38.853  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 21:53:38.853  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 21:53:38.853  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 21:53:38.854  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 21:53:38.854  3788  3853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 21:53:38.854  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 21:53:38.855  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.855  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.856  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:38.856  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 21:53:38.856  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7040e68 removed from the list
,08-26 21:53:38.856  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:38.856  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.856  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.856  3788  3788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 21:53:38.856  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.856  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.856  3788  3788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 21:53:38.856  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372cd8b removed from the list
08-26 21:53:38.857  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:38.857  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fa914 added. We now have 2 listener(s)
,08-26 21:53:38.859  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.859  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 21:53:38.859  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 21:53:38.859  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 21:53:38.859  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51745bd added. We now have 9 listener(s)
08-26 21:53:38.859  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.860  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 21:53:38.860  4155  4171 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 21:53:38.860  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.862  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 21:53:38.866  3788  3853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 21:53:38.867  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 21:53:38.868  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 21:53:38.869  3788  3853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 21:53:38.869  3788  3853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 21:53:38.869  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 21:53:38.869  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f56303 added. We now have 3 listener(s)
,08-26 21:53:38.871  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 21:53:38.871  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.871  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 21:53:38.871  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 21:53:38.871  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 21:53:38.871  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f84280 added. We now have 10 listener(s)
,08-26 21:53:38.871  3788  3853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 21:53:38.871  3788  3853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 21:53:38.872  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 21:53:38.872  3788  3853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 21:53:38.872  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.872  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.872  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 21:53:38.872  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.872  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fa914 removed from the list,
08-26 21:53:38.872  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 21:53:38.872  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51745bd removed from the list
08-26 21:53:38.873  3788  3788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 21:53:38.873  3788  3853 D io.jxcore.node.ConnectivityMonitor: stop
08-26 21:53:38.873  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 21:53:38.874  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.874  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.875  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 21:53:38.875  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 21:53:38.875  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.875  3788  3853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51745bd not in the list
08-26 21:53:38.875  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 21:53:38.875  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 21:53:38.876  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 21:53:38.876  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 21:53:38.876  3788  3853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 21:53:38.876  3788  3853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f84280 removed from the list
08-26 21:53:38.876  3788  3853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 21:53:38.877  3788  3853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 21:53:38.877  3788  3853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 21:53:38.877  3788  3853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 21:53:38.877  4155  4171 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-26 21:53:38.877  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.877  3788  3853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f56303 removed from the list
,08-26 21:53:38.877  4155  4174 D BtGatt.ScanManager: stopping BLe Batch
08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-26 21:53:38.878  3788  3853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 21:53:38.883  3788  4235 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,08-26 21:53:38.883  3788  4235 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
,08-26 21:53:38.884  3788  4235 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 21:53:38.885  4155  4171 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 21:53:38.885  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.885  4155  4174 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 21:53:38.885  3788  4236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-26 21:53:38.886  3788  4236 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
,08-26 21:53:38.886  3788  4236 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 21:53:38.887  3788  3853 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 21:53:38.887  3788  3853 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-26 21:53:38.887  3788  3853 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 21:53:38.887  3788  3853 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 21:53:38.887  3788  3853 D com.test.thalitest.ThaliTestRunner: Total duration: 22919 ms
,08-26 21:53:38.889  3788  3853 I jxcore-log: *Native tests were executed*
08-26 21:53:38.889  3788  3853 I jxcore-log: 
,08-26 21:53:38.889  3788  3853 I jxcore-log: Total number of executed tests:  80
08-26 21:53:38.889  3788  3853 I jxcore-log: 
08-26 21:53:38.889  3788  3853 I jxcore-log: Number of passed tests:  80
08-26 21:53:38.889  3788  3853 I jxcore-log: 
,08-26 21:53:38.890  3788  3853 I jxcore-log: Number of failed tests:  0
08-26 21:53:38.890  3788  3853 I jxcore-log: 
08-26 21:53:38.890  3788  3853 I jxcore-log: Number of ignored tests:  0
08-26 21:53:38.890  3788  3853 I jxcore-log: 
08-26 21:53:38.890  3788  3853 I jxcore-log: Total duration:  22919
08-26 21:53:38.890  3788  3853 I jxcore-log: 
,08-26 21:53:38.890  3788  3853 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 21:53:38.890  3788  3853 I jxcore-log: 
,08-26 21:53:38.893  4155  4171 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 21:53:38.894  4155  4171 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 21:53:38.895  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.895  3788  3853 I jxcore-log: 
08-26 21:53:38.899  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.899  3788  3853 I jxcore-log: 
08-26 21:53:38.900  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.900  3788  3853 I jxcore-log: 
08-26 21:53:38.900  3788  3788 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 21:53:38.901  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.901  3788  3853 I jxcore-log: 
08-26 21:53:38.902  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.902  3788  3853 I jxcore-log: 
08-26 21:53:38.903  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.903  3788  3853 I jxcore-log: 
,08-26 21:53:38.905  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.905  3788  3853 I jxcore-log: 
,08-26 21:53:38.907  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.907  3788  3853 I jxcore-log: 
,08-26 21:53:38.908  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.908  3788  3853 I jxcore-log: 
,08-26 21:53:38.909  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:53:38.909  3788  3853 I jxcore-log: 
,08-26 21:53:38.910  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:38.910  3788  3853 I jxcore-log: 
,08-26 21:53:38.911  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 21:53:38.911  3788  3853 I jxcore-log: 
,08-26 21:53:38.912  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.912  3788  3853 I jxcore-log: 
,08-26 21:53:38.912  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.912  3788  3853 I jxcore-log: 
,08-26 21:53:38.913  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.913  3788  3853 I jxcore-log: 
,08-26 21:53:38.913  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.913  3788  3853 I jxcore-log: 
,08-26 21:53:38.914  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.914  3788  3853 I jxcore-log: 
,08-26 21:53:38.915  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.915  3788  3853 I jxcore-log: 
08-26 21:53:38.915  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.915  3788  3853 I jxcore-log: 
08-26 21:53:38.916  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.916  3788  3853 I jxcore-log: 
,08-26 21:53:38.916  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.916  3788  3853 I jxcore-log: 
08-26 21:53:38.917  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 21:53:38.917  3788  3853 I jxcore-log: 
08-26 21:53:38.918  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 21:53:38.918  3788  3853 I jxcore-log: 
,08-26 21:53:38.918  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.918  3788  3853 I jxcore-log: 
,08-26 21:53:38.919  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.919  3788  3853 I jxcore-log: 
08-26 21:53:38.919  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.919  3788  3853 I jxcore-log: 
,08-26 21:53:38.920  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.920  3788  3853 I jxcore-log: 
,08-26 21:53:38.921  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.921  3788  3853 I jxcore-log: 
,08-26 21:53:38.921  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.921  3788  3853 I jxcore-log: 
08-26 21:53:38.922  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 21:53:38.922  3788  3853 I jxcore-log: 
,08-26 21:53:39.228  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:53:39.230  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:53:39.230  3788  3853 I jxcore-log: 
,08-26 21:53:39.303  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:53:39.305  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:53:39.305  3788  3853 I jxcore-log: 
,08-26 21:53:39.357  3788  3788 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 21:53:39.360  3788  3853 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 21:53:39.360  3788  3853 I jxcore-log: 
,08-26 21:53:39.587  4237  4237 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 21:53:39.592  4237  4237 D AndroidRuntime: CheckJNI is OFF
,08-26 21:53:39.635  4237  4237 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 21:53:39.683  4237  4237 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 21:53:39.705  4237  4237 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 21:53:39.715   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 21:53:39.715   872   885 I ActivityManager: Killing 3788:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 21:53:39.822   872  1370 D GraphicsStats: Buffer count: 2
08-26 21:53:39.822   872  1380 I WindowState: WIN DEATH: Window{87061be u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 21:53:39.824   872  1302 D WifiService: Client connection lost with reason: 4
,08-26 21:53:39.838   872   895 W PackageSettings: Skipping PackageSetting{60d9203 com.example.hello/10273} due to missing metadata
,08-26 21:53:39.852   872   885 W ActivityManager: Force removing ActivityRecord{537f944 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-26 21:53:39.896   872  1370 W ActivityManager: Spurious death for ProcessRecord{2477b33 0:com.test.thalitest/u0a0}, curProc for 3788: null
,08-26 21:53:39.897   872   895 I art     : Starting a blocking GC Explicit
,08-26 21:53:39.930   872  1919 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3788 uid 10000
,08-26 21:53:39.932  1854  1854 I Keyboard.Facilitator: onFinishInput()
,08-26 21:53:40.005   872   895 I art     : Explicit concurrent mark sweep GC freed 50135(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.808ms total 96.833ms
,08-26 21:53:40.006  1953  4250 I MicroRecognitionRnrImpl: Starting detection.
08-26 21:53:40.007  1953  4251 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@5c24b45
08-26 21:53:40.009   375  4253 I AudioFlinger: AudioFlinger's thread 0xb3180000 ready to run
,08-26 21:53:40.011   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-26 21:53:40.012  1953  4251 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@5c24b45
,08-26 21:53:40.022   375  4253 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-26 21:53:40.022   375  4253 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-26 21:53:40.022   375  4253 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-26 21:53:40.029   375  4253 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-26 21:53:40.035   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 21:53:40.037  4237  4237 I art     : System.exit called, status: 0
,08-26 21:53:40.038  4237  4237 I AndroidRuntime: VM exiting with result code 0.
,08-26 21:53:40.049   872   895 I ActivityManager: Start proc 4256:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-26 21:53:40.051   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 21:53:40.072  4155  4155 D BluetoothMapAppObserver: onReceive
,08-26 21:53:40.072  4155  4155 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 21:53:40.073  2107  2256 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 21:53:40.082  1854  1854 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 21:53:40.082  3595  3595 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-26 21:53:40.084   872  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 21:53:40.084  1854  4268 I Keyboard.Facilitator.DecoderInitializer: run()
08-26 21:53:40.085  1854  4268 I Decoder : createOrResetDecoder
,08-26 21:53:40.109  1953  1953 I HotwordWorkerImpl: onReady
,08-26 21:53:40.112  1910  1910 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 21:53:40.116   872  1479 I ActivityManager: Start proc 4272:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 21:53:40.127  1513  1513 I ConfigService: onCreate,
,08-26 21:53:40.155  4272  4272 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 21:53:40.159  1854  4268 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 21:53:40.174   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 21:53:40.189  1854  4268 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 21:53:40.191  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-26 21:53:40.191  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 21:53:40.193  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 21:53:40.193  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 21:53:40.194  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 21:53:40.194  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 21:53:40.198  1854  4268 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 21:53:40.198  1854  4268 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 21:53:40.198  1854  4268 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-26 21:53:40.199  1854  4268 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-26 21:53:40.199  1854  4268 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 21:53:40.199  1854  4268 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 21:53:40.205  1927  1982 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 21:53:40.207   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 21:53:40.208   872   884 E PackageManager: Failed to write settings, restoring backup
08-26 21:53:40.208   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 21:53:40.208   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 21:53:40.208   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 21:53:40.208   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 21:53:40.208   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 21:53:40.208   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.208   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.208   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.212   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-26 21:53:40.212   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 21:53:40.212   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:40.212   872   885 E DropBoxManagerService: 	... 13 more
,08-26 21:53:40.217   872  1380 I ActivityManager: Start proc 4289:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 21:53:40.218  1927  1982 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 21:53:40.218  1927  1982 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1927
08-26 21:53:40.218  1927  1982 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.218  1927  1982 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.220   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 21:53:40.220   872  4297 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:53:40.220   872  4297 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:40.220   872  4297 E DropBoxManagerService: 	... 5 more
,08-26 21:53:40.227  1953  1966 W SearchService: Abort, client detached.
,08-26 21:53:40.230  1953  1953 I HotwordDetector: Closing mic
08-26 21:53:40.230  1953  2289 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5c24b45
08-26 21:53:40.231  1953  4251 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 21:53:40.236   872  4302 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 21:53:40.237  4272  4272 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 21:53:40.249  1953  4303 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-26 21:53:40.263   872  1909 I ActivityManager: Start proc 4304:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 21:53:40.289   872  4302 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 21:53:40.289   872  4302 I Adreno  : Build Date                       : 10/20/15
08-26 21:53:40.289   872  4302 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 21:53:40.289   872  4302 I Adreno  : Local Branch                     : M14
08-26 21:53:40.289   872  4302 I Adreno  : Remote Branch                    : 
08-26 21:53:40.289   872  4302 I Adreno  : Remote Branch                    : 
08-26 21:53:40.289   872  4302 I Adreno  : Reconstruct Branch               : 
,08-26 21:53:40.291   375  4253 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-26 21:53:40.292   375  4253 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-26 21:53:40.294   872  4302 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 21:53:40.296   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-26 21:53:40.299  1953  2297 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-26 21:53:40.300  1953  4250 I MicroRecognitionRnrImpl: Detection finished
,08-26 21:53:40.316   872  1380 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 21:53:40.321   872  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 21:53:40.328  1927  1927 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c05fcf new=com.google.android.velvet.VelvetApplication@2c05fcf
,08-26 21:53:40.358  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 21:53:40.364  4272  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.364  4272  4287 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.364  4272  4287 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.373  4272  4320 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 21:53:40.374  1927  1927 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-26 21:53:40.400  1513  1513 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 21:53:40.401  1513  1513 D AndroidRuntime: Shutting down VM
08-26 21:53:40.401  1513  1513 E AndroidRuntime: FATAL EXCEPTION: main
08-26 21:53:40.401  1513  1513 E AndroidRuntime: Process: com.google.process.gapps, PID: 1513
08-26 21:53:40.401  1513  1513 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 21:53:40.401  1513  1513 E AndroidRuntime: 	... 8 more
,08-26 21:53:40.405   872  4327 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:53:40.405   872  4327 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:40.405   872  4327 E DropBoxManagerService: 	... 5 more
,08-26 21:53:40.430   872   890 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +111ms
,08-26 21:53:40.431   872  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,08-26 21:53:40.451   872  1380 I ActivityManager: Killing 3482:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 21:53:40.478  4272  4287 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 21:53:40.483  4272  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.483  4272  4320 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.485  4272  4320 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 21:53:40.485  4272  4320 E AndroidRuntime: Process: android.process.acore, PID: 4272
08-26 21:53:40.485  4272  4320 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:40.485  4272  4320 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:40.486  4272  4287 I Process : Sending signal. PID: 4272 SIG: 9
,08-26 21:53:40.495   872  4330 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:53:40.495   872  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:40.495   872  4330 E DropBoxManagerService: 	... 5 more
,08-26 21:53:40.515  1744  4329 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-26 21:53:40.516  1744  4329 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-26 21:53:40.567   872  1700 I ActivityManager: Process android.process.acore (pid 4272) has died
,08-26 21:53:40.567   872  1700 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-26 21:53:40.767   872   890 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
,08-26 21:53:41.059   872  1700 I ActivityManager: Killing 3712:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-26 21:53:41.236  1854  4268 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-26 21:53:41.237  1854  4268 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-26 21:53:41.281   872  1909 I ActivityManager: Start proc 4332:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-26 21:53:41.364  4332  4332 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 21:53:41.422  4332  4332 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 21:53:41.432  4332  4346 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:41.432  4332  4346 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:41.433  4332  4346 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:41.458  4332  4346 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 21:53:41.463  4332  4346 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-26 21:53:41.463  4332  4346 E AndroidRuntime: Process: android.process.acore, PID: 4332
08-26 21:53:41.463  4332  4346 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 21:53:41.463  4332  4346 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 21:53:41.469   872  4348 E DropBoxManagerService: Can't write: system_app_crash
08-26 21:53:41.469   872  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 21:53:41.469   872  4348 E DropBoxManagerService: 	... 5 more
,08-26 21:53:42.347   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 21:53:42.399   281  1293 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (182 us)
,08-26 21:53:43.037   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 21:53:43.055   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 21:53:43.062   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 21:53:43.063   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-26 21:53:43.063   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 21:53:43.073   872   872 W AtomicFile: Couldn't rename file /data/system/usagestats/0/screen_on_time to backup file /data/system/usagestats/0/screen_on_time.bak
,08-26 21:53:43.300   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 21:53:43.305   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-26 21:53:43.311   872  1327 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
,08-26 21:53:43.315   872   892 I DreamManagerService: Entering dreamland.
,08-26 21:53:43.316   872   892 I PowerManagerService: Dozing...
,08-26 21:53:43.317   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 21:53:43.320   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{6fa2efb u-1 android.intent.action.CLOSE_SYSTEM_DIALOGS} to ReceiverList{d222870 1927 com.google.android.googlequicksearchbox/10028/u0 remote:f006ab3}: process crashing
,08-26 21:53:43.352   872   885 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2221bad u-1 android.intent.action.DREAMING_STARTED} to ReceiverList{5c2d740 1513 com.google.process.gapps/10011/u0 remote:b2e52c3}: process crashing
,08-26 21:53:43.378   375  1273 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 21:53:43.379   375  1273 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 21:53:43.389   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:53:43.399   872  1700 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{271c5a9 u-1 android.intent.action.SCREEN_ON} to ReceiverList{5c2d740 1513 com.google.process.gapps/10011/u0 remote:b2e52c3}: process crashing
08-26 21:53:43.399  1899  4353 D NfcService: Discovery configuration equal, not updating.
,08-26 21:53:43.408   872  1301 E native  : do suspend false
,08-26 21:53:43.427   872  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 21:53:43.440   872  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 21:53:43.443   872  1301 E native  : do suspend true
,08-26 21:53:43.510   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 21:53:43.511   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 21:53:43.540   872  1981 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{e60d72e u-1 android.intent.action.SCREEN_OFF} to ReceiverList{5c2d740 1513 com.google.process.gapps/10011/u0 remote:b2e52c3}: process crashing
,08-26 21:53:43.544   872   885 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{e60d72e u-1 android.intent.action.SCREEN_OFF} to ReceiverList{334dfe8 1513 com.google.process.gapps/10011/u0 remote:885f50b}: process crashing
,08-26 21:53:43.567   872   882 W BroadcastQueue: Skipping deliver [foreground] BroadcastRecord{e60d72e u-1 android.intent.action.SCREEN_OFF} to ReceiverList{c9a785d 1927 com.google.android.googlequicksearchbox/10028/u0 remote:31b8234}: process crashing
,08-26 21:53:43.896   872  1301 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-26 21:53:45.367  1953  4360 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-26 21:53:45.455   373   605 E QMI_FW  : xport_send: Sendto failed for port 3328
,08-26 21:53:45.462   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 21:53:45.464   975   975 E kickstart: ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,08-26 21:53:45.465   975   975 E kickstart: ERROR: function: sahara_main:1143 Sahara protocol error
08-26 21:53:45.466   975   975 E kickstart: ERROR: function: main:268 Uploading  Image using Sahara protocol failed
,08-26 21:53:45.472   975   975 I kickstart: STATUS: Wrote to /sys/power/wake_unlock

```
