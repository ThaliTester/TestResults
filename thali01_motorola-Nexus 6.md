#### Test 814185775e43c41_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 12:24:54.721   874  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 12:24:55.455  3827  3827 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 12:24:55.460  3827  3827 D AndroidRuntime: CheckJNI is OFF
08-16 12:24:55.496  3827  3827 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 12:24:55.538  3827  3827 I Radio-JNI: register_android_hardware_Radio DONE
08-16 12:24:55.558  3827  3827 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 12:24:55.563   874  3115 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 12:24:55.603  1988  2000 W SearchService: Abort, client detached.
08-16 12:24:55.605  1988  1988 I HotwordDetector: Closing mic
08-16 12:24:55.606  1988  2280 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9f70201
08-16 12:24:55.607  1988  2317 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 12:24:55.619  3827  3827 D AndroidRuntime: Shutting down VM
08-16 12:24:55.646   874   885 I ActivityManager: Start proc 3836:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 12:24:55.669   376  2320 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 12:24:55.670   376  2320 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 12:24:55.676   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 12:24:55.680  1988  2305 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 12:24:55.683  1988  2314 I MicroRecognitionRnrImpl: Detection finished
08-16 12:24:55.740  3836  3836 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 12:24:55.744  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 12:24:55.745  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 12:24:55.760  1517  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-16 12:24:55.760  1517  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-16 12:24:55.760  1517  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:24:55.760  1517  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 12:24:55.766  3836  3836 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:24:55.769  1988  2112 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-16 12:24:55.770  1988  2388 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 12:24:55.773  3836  3836 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3525-3527)
08-16 12:24:55.773  3836  3836 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:24:55.785  3836  3836 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a13ea0}
08-16 12:24:55.785  3836  3836 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 12:24:55.786  3836  3836 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 12:24:55.790  3836  3836 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 12:24:55.792  3836  3836 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 12:24:55.804  3836  3836 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 12:24:55.812  1988  2388 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 12:24:55.814  3836  3836 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 12:24:55.814  3836  3836 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 12:24:55.814  3836  3836 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:24:55.814  3836  3836 I Adreno  : Build Date                       : 10/20/15
08-16 12:24:55.814  3836  3836 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:24:55.814  3836  3836 I Adreno  : Local Branch                     : M14
08-16 12:24:55.814  3836  3836 I Adreno  : Remote Branch                    : 
08-16 12:24:55.814  3836  3836 I Adreno  : Remote Branch                    : 
08-16 12:24:55.814  3836  3836 I Adreno  : Reconstruct Branch               : 
08-16 12:24:55.818  1988  2388 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3569-3572)
08-16 12:24:55.818  1988  2388 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 12:24:55.856   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dcb6e6e:true
,08-16 12:24:55.893  3836  3836 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 12:24:55.904  3836  3836 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 12:24:55.936  3836  3889 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 12:24:55.943  3836  3868 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 12:24:55.975  3836  3889 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 12:24:56.031   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +409ms
,08-16 12:24:56.042  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-16 12:24:56.085  3836  3836 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3836
,08-16 12:24:56.284  3836  3836 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 12:24:56.434  3836  3892 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1680930512
,08-16 12:24:56.438  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 12:24:56.438  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 12:24:56.438  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 12:24:56.438  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 12:24:56.438  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 12:24:56.439  3836  3892 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5af7224 added. We now have 1 listener(s)
08-16 12:24:56.441  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-16 12:24:56.442  3836  3892 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:24:56.442  3836  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:24:56.443  3836  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 12:24:56.447  3836  3892 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f764b53 added. We now have 1 listener(s)
08-16 12:24:56.447  3836  3892 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:24:56.451   874  1308 D WifiService: New client listening to asynchronous messages
08-16 12:24:56.452  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:24:56.452  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 12:24:56.452  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 12:24:56.452  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 12:24:56.453  3836  3892 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 12:24:56.456  3836  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:24:56.456  3836  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 12:24:56.465  3836  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:24:56.465  3836  3892 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:24:56.465  3836  3892 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 12:24:56.465  3836  3892 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:24:56.466  3836  3892 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 12:24:56.523   874  1390 I ActivityManager: Killing 3064:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 12:24:56.555   874  1390 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-16 12:24:56.615  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:24:56.618  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:24:56.620  3836  3836 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 12:24:57.225  3836  3899 W jxcore-log: Initializing JXcore engine
,08-16 12:24:57.225  3836  3899 W jxcore-log: JXcore engine is ready
,08-16 12:24:57.295  3899  3899 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 12:24:57.295  3899  3899 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11185]" dev="sockfs" ino=11185 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 12:24:57.295  3899  3899 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 12:24:57.298  3899  3899 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25864]" dev="sockfs" ino=25864 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 12:24:57.311  3836  3899 W jxcore-log: Starting JXcore engine
,08-16 12:24:57.393  3836  3899 W jxcore-log: Platform android
08-16 12:24:57.393  3836  3899 W jxcore-log: 
,08-16 12:24:57.393  3836  3899 W jxcore-log: Process ARCH arm
08-16 12:24:57.393  3836  3899 W jxcore-log: 
,08-16 12:24:57.566  3836  3899 I jxcore-log: JXcore Cordova bridge is ready!
08-16 12:24:57.566  3836  3899 I jxcore-log: 
,08-16 12:24:57.566  3836  3899 W jxcore-log: JXcore engine is started
,08-16 12:24:57.574  3836  3892 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 12:24:57.577  3836  3836 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 12:24:58.989  3014  3903 V KeepSync: Connecting to GoogleApiClient
,08-16 12:24:58.990   874  3115 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 12:24:59.062  1517  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 12:24:59.063  1517  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-16 12:24:59.063  1517  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:24:59.063  1517  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:24:59.093  1739  3904 V BaseAuthAsyncOperation: access token request failed
,08-16 12:24:59.094  3014  3903 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 12:24:59.172  1517  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 12:24:59.173  1517  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 12:24:59.173  1517  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:24:59.173  1517  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:24:59.205  3014  3903 E KeepSync: IOException
08-16 12:24:59.205  3014  3903 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 12:24:59.205  3014  3903 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 12:24:59.205  3014  3903 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 12:24:59.205  3014  3903 E KeepSync: 	... 10 more
,08-16 12:24:59.205  3014  3903 W KeepSync: Sync result 2
,08-16 12:24:59.213   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126604, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:25:00.863  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:00.910  1517  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:25:00.911  1517  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 12:25:00.912  1517  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:00.913  1517  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:00.934  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:25:00.934  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 12:25:00.934  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 12:25:05.772  3783  3913 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 12:25:05.801  1517  2223 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 12:25:05.801  1517  2223 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 12:25:05.801  1517  2223 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:05.801  1517  2223 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 12:25:05.893  3783  3913 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 12:25:07.642  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 12:25:07.642  3836  3899 I jxcore-log: 
08-16 12:25:07.644  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 12:25:07.644  3836  3899 I jxcore-log: 
,08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:07.652  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:07.657  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:07.660  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 12:25:07.660  3836  3899 I jxcore-log: 
,08-16 12:25:07.662  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 12:25:07.662  3836  3899 I jxcore-log: 
,08-16 12:25:07.985  3836  3899 D ExecuteNativeTests: Running unit tests
,08-16 12:25:08.043  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:25:08.044  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a added. We now have 2 listener(s)
08-16 12:25:08.045  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:08.045  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:08.045  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:08.045  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:08.045  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb added. We now have 2 listener(s)
08-16 12:25:08.045  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:08.046  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:25:08.050  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.056  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:08.060  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:08.060  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:25:08.062  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 12:25:08.063  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:25:08.063  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 12:25:08.064  3836  3899 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 12:25:08.064  3836  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:25:08.064  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:25:08.064  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:25:08.064  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:25:08.065  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.066  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 12:25:08.067  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.068  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.068  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.068  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.069  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.069  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:08.069  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:08.070  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a removed from the list
08-16 12:25:08.070  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:08.070  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb removed from the list
08-16 12:25:08.071  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.071  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.073  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.073  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.077  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:08.080  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:25:08.080  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:08.083  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.085  3836  3899 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 12:25:08.086  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:08.086  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.086  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.086  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.086  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.086  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.086  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list,
08-16 12:25:08.087  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.087  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.087  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.087  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.087  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.087  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.087  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 12:25:08.089  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:08.089  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.089  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.089  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 12:25:08.094  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:25:08.095  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:25:08.096  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:25:08.096  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.096  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.096  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.096  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.096  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.096  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.097  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
,08-16 12:25:08.097  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.097  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.097  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:25:08.097  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.097  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.097  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.097  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.098  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:08.098  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.099  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.099  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.099  3836  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:25:08.101  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.111  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:08.117  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:08.117  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:25:08.118  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:08.118  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 12:25:08.119  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:25:08.119  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:08.119  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:25:08.123  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.128  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.133  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:25:08.133  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:25:08.141  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:25:08.144  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 12:25:08.144  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:25:08.149  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 12:25:08.154  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 12:25:08.155  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:25:08.155  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 12:25:08.159  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 12:25:08.161  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:08.171  2656  2830 D BtGatt.GattService: registerClient() - UUID=b96bb670-d12f-4914-a0cf-83c6cfa0644b
,08-16 12:25:08.172  2656  2681 D BtGatt.GattService: onClientRegistered() - UUID=b96bb670-d12f-4914-a0cf-83c6cfa0644b, clientIf=5
,08-16 12:25:08.174  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:25:08.175  2656  2669 D BtGatt.GattService: start scan with filters
,08-16 12:25:08.182  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:25:08.182  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:08.182  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 12:25:08.183  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:25:08.183  2656  2684 D BtGatt.ScanManager: handling starting scan
,08-16 12:25:08.186  2656  2684 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:08.188  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:25:08.188  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 12:25:08.189  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:08.190  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:25:08.195  2656  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:25:08.195  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.196  2656  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:25:08.201  3836  3899 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 12:25:08.205  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:25:08.205  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.206  2656  2684 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 12:25:08.206  2656  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:25:08.209  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:08.209  3836  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 12:25:08.210  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:25:08.210  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:25:08.210  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.210  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:25:08.211  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 12:25:08.211  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:25:08.211  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:25:08.211  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:25:08.213  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 12:25:08.213  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:25:08.215  3836  3899 D BluetoothAdapter: STATE_ON
08-16 12:25:08.217  2656  2830 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:25:08.218  2656  2669 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 12:25:08.218  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:25:08.218  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:08.218  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:25:08.219  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:25:08.219  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:25:08.220  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.221  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:25:08.221  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:08.222  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:08.222  2656  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:08.222  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.223  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:08.225  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.226  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.226  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:08.226  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
,08-16 12:25:08.226  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:08.226  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.226  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.226  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.226  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.226  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:25:08.227  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:25:08.227  3836  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 12:25:08.230  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:25:08.230  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.232  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:08.241  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:25:08.241  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.241  2656  2684 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.242  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:08.245  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:08.246  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:25:08.246  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:08.246  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:25:08.246  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 12:25:08.246  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:08.247  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:25:08.250  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 12:25:08.250  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.250  2656  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:25:08.251  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.255  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:25:08.256  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:25:08.257  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.259  2656  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 12:25:08.259  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.264  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:25:08.265  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 12:25:08.265  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:25:08.273  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 12:25:08.273  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 12:25:08.273  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 12:25:08.275  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:08.280  2656  2798 D BtGatt.GattService: registerClient() - UUID=fb5125c7-676f-4f85-a008-64109224e1a0
,08-16 12:25:08.281  2656  2681 D BtGatt.GattService: onClientRegistered() - UUID=fb5125c7-676f-4f85-a008-64109224e1a0, clientIf=5
,08-16 12:25:08.282  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:25:08.283  2656  2669 D BtGatt.GattService: start scan with filters
,08-16 12:25:08.289  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:25:08.289  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:08.289  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:25:08.289  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 12:25:08.289  2656  2684 D BtGatt.ScanManager: handling starting scan
,08-16 12:25:08.295  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:08.297  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:08.297  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:25:08.300  2656  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:25:08.300  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.300  2656  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:25:08.304  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:25:08.309  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:25:08.309  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.310  2656  2684 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 12:25:08.310  2656  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 12:25:08.311  3836  3899 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 12:25:08.316  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:08.316  3836  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 12:25:08.316  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.316  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:25:08.316  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.317  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:25:08.317  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:25:08.317  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:25:08.317  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:25:08.317  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:25:08.317  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:25:08.317  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:25:08.318  3836  3899 D BluetoothAdapter: STATE_ON
08-16 12:25:08.319  2656  2798 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:25:08.321  2656  2668 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:25:08.322  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:25:08.322  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:08.322  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:25:08.323  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 12:25:08.323  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 12:25:08.326  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:25:08.326  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:25:08.326  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:08.326  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:08.327  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:08.329  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:25:08.329  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.329  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.329  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.329  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.330  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:08.330  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.330  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.330  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.330  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.330  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.331  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.331  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.333  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:08.334  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.334  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.334  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.336  3836  3899 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 12:25:08.337  2656  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:08.337  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.340  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:08.349  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:25:08.349  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.350  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:08.354  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:08.354  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:25:08.355  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 12:25:08.356  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 12:25:08.356  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 12:25:08.358  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.358  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:08.358  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:25:08.365  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 12:25:08.365  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.365  2656  2684 D BtGatt.ScanManager: stopping BLe Batch
,08-16 12:25:08.366  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:25:08.366  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:25:08.367  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.374  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:25:08.376  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 12:25:08.376  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:25:08.378  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:25:08.378  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.378  2656  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:25:08.386  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 12:25:08.386  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 12:25:08.386  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 12:25:08.388  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:08.391  2656  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 12:25:08.391  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.394  2656  2669 D BtGatt.GattService: registerClient() - UUID=3cfb1571-14b9-461c-b666-abb68fcbc177
,08-16 12:25:08.395  2656  2681 D BtGatt.GattService: onClientRegistered() - UUID=3cfb1571-14b9-461c-b666-abb68fcbc177, clientIf=5
,08-16 12:25:08.396  3836  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:25:08.397  2656  2830 D BtGatt.GattService: start scan with filters
,08-16 12:25:08.404  2656  2684 D BtGatt.ScanManager: handling starting scan
08-16 12:25:08.404  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:25:08.405  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:08.405  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:25:08.405  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 12:25:08.414  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:08.414  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:08.415  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:25:08.419  2656  2681 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:25:08.419  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.420  2656  2684 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 12:25:08.421  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:25:08.429  3836  3899 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 12:25:08.429  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 12:25:08.429  3836  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 12:25:08.430  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:25:08.430  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:25:08.430  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.430  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:25:08.430  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 12:25:08.431  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:25:08.431  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:25:08.431  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 12:25:08.431  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:25:08.431  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 12:25:08.433  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:08.434  2656  2830 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:25:08.435  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 12:25:08.435  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:08.435  2656  2684 D BtGatt.ScanManager: Starting BLE batch scan,
,08-16 12:25:08.436  2656  2684 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 12:25:08.436  2656  2668 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 12:25:08.437  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:25:08.437  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:08.437  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:25:08.438  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:25:08.438  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:25:08.440  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.441  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:25:08.441  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:08.441  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:08.443  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:08.447  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.447  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.448  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.449  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.449  3836  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 12:25:08.449  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.449  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.450  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.450  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.450  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:08.451  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.451  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.451  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.451  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.452  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.453  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.453  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.455  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-16 12:25:08.455  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.455  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-16 12:25:08.455  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.457  3836  3899 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 12:25:08.458  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.458  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.458  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.459  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.459  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.459  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.460  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.460  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.460  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.460  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.460  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.461  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.461  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.461  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.463  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.463  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.464  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.464  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.466  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:25:08.466  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.467  2656  2681 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:08.467  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.467  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.467  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.467  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:25:08.467  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.468  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.468  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.468  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.468  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.468  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.468  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.469  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.469  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.469  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.471  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:08.471  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.471  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.472  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.473  3836  3899 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 12:25:08.473  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:08.479  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:25:08.474  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.481  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.481  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.482  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.482  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.482  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.482  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.483  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.483  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.483  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.483  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.483  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.483  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.484  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.486  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.486  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.486  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.486  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.488  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 12:25:08.488  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.488  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.488  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.488  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.489  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.489  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.489  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.489  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:08.489  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.489  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 12:25:08.489  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.489  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.489  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.489  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.491  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.491  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.491  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.491  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
,08-16 12:25:08.491  2656  2681 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 12:25:08.492  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.492  2656  2684 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:25:08.492  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 12:25:08.492  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:25:08.493  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 12:25:08.493  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:25:08.493  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-16 12:25:08.493  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 12:25:08.493  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:08.493  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:25:08.493  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.494  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.494  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.494  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.494  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.494  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.494  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.494  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.494  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:08.494  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.494  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.494  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:08.498  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.498  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:25:08.498  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.498  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.499  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:25:08.499  3836  3899 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 12:25:08.499  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 12:25:08.501  2656  2681 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:25:08.501  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.502  2656  2684 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 12:25:08.503  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:25:08.504  3836  3899 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 12:25:08.504  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 12:25:08.505  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 12:25:08.506  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 12:25:08.506  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-16 12:25:08.506  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 12:25:08.506  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 12:25:08.507  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 12:25:08.508  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 12:25:08.508  3836  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:25:08.508  3836  3899 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 12:25:08.508  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:25:08.508  3836  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:25:08.508  3836  3899 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 12:25:08.508  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:25:08.509  3836  3899 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 12:25:08.509  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 12:25:08.513  2656  2681 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 12:25:08.513  2656  2681 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:08.513  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 12:25:08.514  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 12:25:08.514  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 12:25:08.515  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 12:25:08.516  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 12:25:08.516  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 12:25:08.516  3836  3899 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 12:25:08.516  3836  3899 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 12:25:08.517  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.517  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.517  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.517  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.517  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.517  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.517  3836  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-16 12:25:08.518  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 12:25:08.519  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.519  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.519  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.519  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.519  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.519  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.519  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.519  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.520  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.521  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.521  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.521  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.521  3836  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-16 12:25:08.522  3836  3899 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 12:25:08.522  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.522  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.522  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.523  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.523  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.523  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.523  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.523  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.523  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.523  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.523  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.523  3836  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:25:08.523  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.523  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.523  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.526  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.526  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.526  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.526  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.527  3836  3899 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 12:25:08.527  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.527  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.527  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.527  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.527  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.528  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.528  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.528  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.528  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.528  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.528  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.528  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.528  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.528  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.529  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.529  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopD,iscovery
08-16 12:25:08.529  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.529  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 12:25:08.530  3836  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:25:08.530  3836  3899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:25:08.530  3836  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:25:08.530  3836  3899 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 12:25:08.530  3836  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 12:25:08.530  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:25:08.530  3836  3899 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 12:25:08.531  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.531  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.531  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.531  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.531  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.531  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.531  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.531  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.531  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.531  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.531  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.531  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.531  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.531  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.532  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.532  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.532  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.532  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.533  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.533  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.533  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.533  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.533  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.533  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.533  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.533  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.533  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.534  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.534  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.534  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.534  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.534  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.534  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.534  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.534  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.534  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.534  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.534  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.534  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.535  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.535  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.535  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.535  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.535  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.535  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.535  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.535  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.536  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.536  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.536  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.536  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.537  3836  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 12:25:08.537  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:08.538  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 12:25:08.539  3836  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 12:25:08.539  3836  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 12:25:08.539  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 12:25:08.539  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 12:25:08.539  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:25:08.539  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.540  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 12:25:08.540  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 12:25:08.540  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 12:25:08.540  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.540  3836  3899 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 12:25:08.540  3836  3836 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 12:25:08.540  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.540  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.540  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:25:08.540  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:25:08.540  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:25:08.541  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.541  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.541  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.542  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.542  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:08.542  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:08.542  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.542  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.542  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.542  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.542  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.542  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.543  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.543  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.543  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.543  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.543  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.543  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.543  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.543  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.543  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.544  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.544  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.544  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.544  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.545  3836  3899 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 12:25:08.545  3836  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 12:25:08.546  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 12:25:08.546  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 12:25:08.546  3836  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 12:25:08.546  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.546  3836  3917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 12:25:08.546  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.546  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.546  3836  3836 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 12:25:08.546  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.546  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.546  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.546  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.546  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.546  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.546  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.547  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.547  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.547  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.547  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.547  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.547  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.547  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.548  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.552  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.552  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.552  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.553  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.553  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.553  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.553  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.553  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.553  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.553  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.553  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.553  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.553  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.553  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.554  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.554  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.554  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.554  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.555  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:08.555  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:08.555  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:08.555  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:08.555  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.555  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.555  3836  3899 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96043a not in the list
08-16 12:25:08.555  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.556  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.556  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:08.556  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.556  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.556  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:08.556  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:08.556  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:08.556  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:08.556  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:08.556  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@405a8eb not in the list
08-16 12:25:08.557  3836  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 12:25:08.557  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:25:08.557  3836  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 12:25:08.557  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 12:25:08.557  3836  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 12:25:08.557  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 12:25:08.559  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 12:25:08.559  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 12:25:08.559  3836  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 12:25:08.559  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:25:08.559  3836  3899 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 12:25:08.560  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 12:25:08.560  3836  3899 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 12:25:08.560  3836  3899 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 12:25:08.560  3836  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 12:25:08.560  3836  3899 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 12:25:08.560  3836  3899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 12:25:08.561  3836  3899 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 12:25:08.561  3836  3899 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 12:25:08.561  3836  3899 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 12:25:08.561  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:08.561  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@abf1bd5 added. We now have 2 listener(s)
08-16 12:25:08.561  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:08.562  3836  3899 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 12:25:08.563   874   885 D WifiService: setWifiEnabled: true pid=3836, uid=10000
08-16 12:25:08.563   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:25:08.563  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:08.563  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@997efea added. We now have 3 listener(s)
08-16 12:25:08.563  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:08.568  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:08.568  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c6a2db added. We now have 4 listener(s)
08-16 12:25:08.568  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:08.570  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:08.570  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f944178 added. We now have 5 listener(s)
08-16 12:25:08.570  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:08.573   874  2716 D WifiService: setWifiEnabled: false pid=3836, uid=10000
08-16 12:25:08.573   874  2716 E Wif,iService: Invoking mWifiStateMachine.setWifiEnabled
08-16 12:25:08.576  2656  2677 D BluetoothAdapterState: Current state: ON, message: 23
08-16 12:25:08.576  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:08.576  2656  2677 D BluetoothAdapterProperties: Setting state to 13
08-16 12:25:08.576  2656  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 12:25:08.577  2656  2677 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 12:25:08.578  2656  2677 I BluetoothAdapterState: Entering PendingCommandState
08-16 12:25:08.578  2656  2681 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:25:08.578  2656  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 12:25:08.578  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.579  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:08.579  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.580  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.580  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:25:08.581  2656  2656 D BluetoothMapService: onReceive
08-16 12:25:08.581  2656  2656 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:25:08.582  2656  2656 D BluetoothMapService: STATE_TURNING_OFF
08-16 12:25:08.582  2656  2656 D BluetoothMapService: MAP Service closeService in
08-16 12:25:08.582  2656  2656 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 12:25:08.582  2656  2656 D ObexServerSockets0: shutdown(block = true)
08-16 12:25:08.582  2656  2656 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:25:08.582  2656  2832 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 12:25:08.582  2656  2656 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:25:08.583  2656  2833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 12:25:08.583  2656  2656 I BtOppRfcommListener: stopping Accept Thread
,08-16 12:25:08.583  2656  2795 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 12:25:08.583  2656  3439 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:25:08.584  2656  3439 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:25:08.584  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.587  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.593  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:08.593  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:08.594  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:08.594  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:08.595   874   887 I ActivityManager: Start proc 3920:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 12:25:08.600  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 12:25:08.600  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.602  2656  2656 D HeadsetService: Received stop request...Stopping profile...
08-16 12:25:08.605   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 12:25:08.605  1362  1373 D BluetoothHeadset: Proxy object disconnected
,08-16 12:25:08.605   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 12:25:08.605   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:08.605   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:08.605   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 12:25:08.605   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:08.605   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:25:08.605  1910  1930 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:08.606  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.607  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:08.607  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:08.607  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:08.607  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:08.608  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.608  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-16 12:25:08.610  2656  2656 D A2dpService: Received stop request...Stopping profile...
08-16 12:25:08.610  2656  2801 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:25:08.615   874   874 D BluetoothA2dp: Proxy object disconnected
08-16 12:25:08.616  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-16 12:25:08.616  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:08.616  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:08.616  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:08.616  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:08.617  2656  2656 D HidService: Received stop request...Stopping profile...
,08-16 12:25:08.617  2656  2656 D HidService: Stopping Bluetooth HidService
08-16 12:25:08.617  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-16 12:25:08.617  1362  1362 D HidProfile: Bluetooth service disconnected
08-16 12:25:08.617   874  1878 D DhcpClient: Clearing IP address
08-16 12:25:08.618  2656  2656 D HealthService: Received stop request...Stopping profile...
08-16 12:25:08.619   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:25:08.622   372   872 D CommandListener: Setting iface cfg
08-16 12:25:08.622  2656  2656 D PanService: Received stop request...Stopping profile...
08-16 12:25:08.623  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 12:25:08.623  1362  1362 D PanProfile: Bluetooth service disconnected
08-16 12:25:08.624  2656  2656 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:25:08.624  2656  2656 D BluetoothMapService: stop()
,08-16 12:25:08.624  2656  2656 D BluetoothMapAppObserver: deinitObservers()
,08-16 12:25:08.624  2656  2656 D BluetoothMapAppObserver: removeReceiver()
,08-16 12:25:08.626  1517  2128 V NativeCrypto: Read error: ssl=0xaeb2ae00: I/O error during system call, Connection timed out
,08-16 12:25:08.627  1362  1362 D BluetoothMap: Proxy object disconnected
08-16 12:25:08.627  1362  1362 D MapProfile: Bluetooth service disconnected
,08-16 12:25:08.627  1517  2128 V NativeCrypto: SSL shutdown failed: ssl=0xaeb2ae00: I/O error during system call, Broken pipe
08-16 12:25:08.627  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:25:08.628  2656  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 12:25:08.628  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.628  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.628  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.629  2656  2681 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 12:25:08.628  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 12:25:08.629   874  3115 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-16 12:25:08.630   874  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-16 12:25:08.633   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:25:08.634   395   395 E Parcel  : Reading a NULL string not supported here.
08-16 12:25:08.634   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 12:25:08.634  2656  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 12:25:08.634  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.634  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.634  2656  2779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:25:08.634  2656  2779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:25:08.634  2656  2779 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:25:08.634  2656  2779 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 12:25:08.634  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:08.634  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:08.635  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:08.635  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:08.635  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:25:08.635  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:25:08.635  2656  2656 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:25:08.635  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:08.635  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:25:08.635  2656  2681 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 12:25:08.636  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:08.636   874  1867 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-16 12:25:08.637  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 12:25:08.637  2656  2681 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 12:25:08.637  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:25:08.637  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:08.637  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:08.637  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:08.638  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:08.638  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:25:08.638  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 12:25:08.644   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 12:25:08.645   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:25:08.648  2656  2656 D BluetoothMapService: MAP Service closeService in
,08-16 12:25:08.648   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:25:08.649   874  1943 D DhcpClient: Receive thread stopped
08-16 12:25:08.650   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 12:25:08.648  2656  2656 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:25:08.650  2656  2656 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:25:08.650  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:08.653  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:08.654  2656  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 12:25:08.654  2656  2677 D BluetoothAdapterProperties: Setting state to 15
08-16 12:25:08.654  2656  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-16 12:25:08.656  2656  2677 I BluetoothAdapterState: Entering BleOnState
,08-16 12:25:08.657   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:08.657  1362  1984 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:25:08.657  2656  2656 D BluetoothMapService: cleanup()
08-16 12:25:08.658  2656  2656 D BluetoothMapService: MAP Service closeService in
08-16 12:25:08.658  1362  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:08.658   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:25:08.658  1910  2036 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:08.658   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:08.659  1362  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:25:08.659   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:08.659  1362  1984 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 12:25:08.660  1362  2001 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:25:08.660  1362  1374 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:25:08.661  2656  2677 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 12:25:08.661  2656  2677 D BluetoothAdapterProperties: Setting state to 16
08-16 12:25:08.661  2656  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 12:25:08.662  2656  2677 D BluetoothAdapterProperties: onBleDisable
08-16 12:25:08.662  2656  2677 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:08.662  2656  2678 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 12:25:08.663  2656  2681 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:25:08.663  2656  2779 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 12:25:08.663  2656  2779 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:08.664  3836  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
,08-16 12:25:08.664  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:08.664  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:08.665  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.665  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:08.666  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:08.666  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:08.666  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:08.666  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:08.670   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 12:25:08.670  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:08.670  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:08.670  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:08.670  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:08.671   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:25:08.672  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:08.672  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:08.672  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:08.672  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:08.673  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.674  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.691  2132  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 12:25:08.698   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:08.706  3920  3920 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 12:25:08.715  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:25:08.717   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:08.718   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 12:25:08.718   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:08.720   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:25:08.723  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:08.723  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:08.725  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:08.726  3383  3383 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5af7224 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 12:25:08.736  1988  1988 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-16 12:25:08.738   874  1390 I ActivityManager: Start proc 3938:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 12:25:08.744   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b77433:true
,08-16 12:25:08.766   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-16 12:25:08.768   874  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 12:25:08.768   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 12:25:08.770  3920  3920 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 12:25:08.772  3938  3938 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 12:25:08.774  3920  3920 D BluetoothMap: Create BluetoothMap proxy object
,08-16 12:25:08.782  3920  3920 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 12:25:08.802  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:25:08.811   874  1390 I ActivityManager: Killing 3563:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 12:25:08.869  2656  2681 I bt_hci  : shut_down
,08-16 12:25:08.870  2656  2685 D bt_hwcfg: hw_epilog_process
,08-16 12:25:08.871  2656  2685 I bt_vendor: low_power_mode_cb
,08-16 12:25:08.891  2656  2685 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 12:25:08.892  2656  2685 I bt_vendor: epilog_cb
08-16 12:25:08.892  2656  2685 I bt_hci  : epilog_finished_callback
,08-16 12:25:08.897  2656  2681 I bt_hci_h4: hal_close
,08-16 12:25:08.899  2656  2681 I bt_userial_vendor: device fd = 51 close
,08-16 12:25:08.970  3938  3938 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:25:08.970  3938  3938 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:08.970  3938  3938 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:08.970  3938  3938 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.970  3938  3938 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.970  3938  3938 D StrictMode: ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405),
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.970  3938  3938 D StrictMode: ,	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726),
08-16 12:25:08.970  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:25:08.971  3938  3938 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
,08-16 12:25:08.971  3938  3938 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 12:25:08.971  3938  3938 D StrictMode: 	,at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:08.971  3938  3938 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.971  3938  3938 D StrictMode,: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:08.971  3938  3938 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.971  3938  3938 D StrictMode: ,	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method),
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:25:08.971  3938  3938 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 12:25:08.971  3938  3938 D StrictMode: 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 12:25:08.971  3938  3938 D StrictMode: ,	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 12:25:08.971  3938  3938 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:08.971  3938  3938 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:25:09.003   874   885 I ActivityManager: Start proc 3971:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 12:25:09.004   874   885 I ActivityManager: Killing 3383:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 12:25:09.043  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:25:09.098  2656  2678 D bt_stack_manager: event_shut_down_stack finished.
,08-16 12:25:09.098  2656  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 12:25:09.100  2656  2656 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:25:09.100  2656  2677 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 12:25:09.100  2656  2656 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 12:25:09.100  2656  2656 D BtGatt.GattService: stop()
08-16 12:25:09.100  2656  2656 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 12:25:09.102  2656  2656 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:09.102  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:09.102  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:09.102  2656  2656 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 12:25:09.102  2656  2677 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 12:25:09.103  2656  2677 D BluetoothAdapterProperties: Setting state to 10
,08-16 12:25:09.103  2656  2677 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 12:25:09.103  2656  2677 I BluetoothAdapterState: Entering OffState
08-16 12:25:09.104   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 12:25:09.104  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 12:25:09.111  2656  2656 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 12:25:09.111  2656  2656 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 12:25:09.111  2656  2656 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 12:25:09.112  2656  2678 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 12:25:09.114  2656  2678 D bt_stack_manager: event_clean_up_stack finished.
,08-16 12:25:09.120  2656  2656 I art     : System.exit called, status: 0
,08-16 12:25:09.120  2656  2656 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 12:25:09.191   874   885 I ActivityManager: Process com.android.bluetooth (pid 2656) has died
,08-16 12:25:09.340  3971  3991 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 12:25:09.340  3971  3991 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 12:25:09.349  3971  3991 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 12:25:09.349  3971  3991 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 12:25:09.374  3971  3991 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 12:25:09.374  3971  3991 I Babel_SMS: MmsConfig.loadFromResources
,08-16 12:25:09.375  3971  3991 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 12:25:09.377  3971  3991 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 12:25:09.473  3971  3971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:25:09.476  3971  3971 I Babel_Crash: startup - clean
,08-16 12:25:09.514  3971  3971 I Babel_telephony: TeleModule.launchCompleted
,08-16 12:25:09.519   874   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 12:25:09.530  3971  3971 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 12:25:09.537  3971  3971 W Babel   : BAM#gBA: invalid account id: -1
,08-16 12:25:09.537  3971  3971 W Babel   : BAM#gBA: invalid account id: -1
08-16 12:25:09.537  3971  3971 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 12:25:09.542   874  1922 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 12:25:09.544  3971  3996 I Babel   : deleted: false for 0
,08-16 12:25:09.555  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:25:09.579   874   885 I ActivityManager: Start proc 3999:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 12:25:09.580  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:25:09.593  3938  3965 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 12:25:09.606  3971  3971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:25:09.672  3971  3971 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 12:25:09.687  3971  3971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:25:09.688  3971  3971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:25:09.701  3971  3971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:25:09.703  3999  3999 D AdapterServiceConfig: Adding HeadsetService
08-16 12:25:09.703  3999  3999 D AdapterServiceConfig: Adding A2dpService
08-16 12:25:09.703  3999  3999 D AdapterServiceConfig: Adding HidService
,08-16 12:25:09.704  3999  3999 D AdapterServiceConfig: Adding HealthService
08-16 12:25:09.704  3999  3999 D AdapterServiceConfig: Adding PanService
,08-16 12:25:09.704  3999  3999 D AdapterServiceConfig: Adding GattService
08-16 12:25:09.704  3999  3999 D AdapterServiceConfig: Adding BluetoothMapService
08-16 12:25:09.708  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:09.737  3971  3971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 12:25:09.751  3971  3971 I vclib   : onServiceConnected
,08-16 12:25:09.769  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:25:09.775   874  1917 I ActivityManager: Killing 3611:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-16 12:25:09.803   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21cc381:true
,08-16 12:25:09.843  1739  1739 D SystemUpdateService: onCreate
,08-16 12:25:09.862  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:25:09.874  1739  4012 I SystemUpdateService: active receiver: enabled
,08-16 12:25:09.882  1739  4012 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:25:09.887  1739  4012 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 12:25:09.887  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-16 12:25:09.887  1739  4012 I SystemUpdateService: now status is 0 (complete)
08-16 12:25:09.888  1739  4012 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:25:09.888  1739  4012 I SystemUpdateService: file has been verified
08-16 12:25:09.888  1739  4012 I SystemUpdateService: OTA package size = 12249756
,08-16 12:25:09.896  1739  2447 I iu.UploadsManager: num queued entries: 0
08-16 12:25:09.896  1739  2447 I iu.UploadsManager: num updated entries: 0
,08-16 12:25:09.898  1739  4012 I SystemUpdateService: showing system update notification
,08-16 12:25:09.901  1739  2447 I iu.SyncManager: NEXT; no task
,08-16 12:25:09.915  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:25:09.919  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:25:09.941   874  2716 I ActivityManager: Start proc 4014:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 12:25:09.949  1739  1739 D SystemUpdateService: onDestroy
,08-16 12:25:09.998  4014  4014 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 12:25:10.005  4014  4014 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:10.015  4014  4014 D SprintDMHelper: simOperator: 
,08-16 12:25:10.015  4014  4014 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:25:10.029   874  1390 I ActivityManager: Start proc 4026:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 12:25:10.031   874  1390 I ActivityManager: Killing 3454:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 12:25:10.196   874  3115 I ActivityManager: Start proc 4041:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 12:25:10.201  3971  4040 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 12:25:10.205   874  1954 I ActivityManager: Killing 3493:android.process.acore/u0a5 (adj 15): empty #17
,08-16 12:25:10.272  4041  4041 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 12:25:10.320  4041  4041 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 12:25:10.320  4041  4041 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 12:25:10.320  4041  4041 I GAv4    :   adb logcat -s GAv4
,08-16 12:25:10.332  4041  4041 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:25:10.337  4041  4041 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:25:10.368  4041  4058 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 12:25:10.463  4041  4041 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 12:25:10.499  4041  4041 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 12:25:10.506  4041  4041 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8258-8260)
,08-16 12:25:10.506  4041  4041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 12:25:10.517  4041  4041 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e5ac54}
,08-16 12:25:10.517  4041  4041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 12:25:10.518  4041  4041 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 12:25:10.524  4041  4041 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 12:25:10.526  4041  4041 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 12:25:10.545  4041  4041 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 12:25:10.558  4041  4041 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 12:25:10.559  4041  4041 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 12:25:10.559  4041  4041 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:25:10.559  4041  4041 I Adreno  : Build Date                       : 10/20/15
08-16 12:25:10.559  4041  4041 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:25:10.559  4041  4041 I Adreno  : Local Branch                     : M14
08-16 12:25:10.559  4041  4041 I Adreno  : Remote Branch                    : 
08-16 12:25:10.559  4041  4041 I Adreno  : Remote Branch                    : 
08-16 12:25:10.559  4041  4041 I Adreno  : Reconstruct Branch               : 
,08-16 12:25:10.612  4041  4041 I NSApplication: Starting up...
,08-16 12:25:10.619  4041  4087 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 12:25:10.657   874  1917 I ActivityManager: Start proc 4092:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 12:25:10.660   874  1917 I ActivityManager: Killing 3684:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 12:25:10.754  4092  4092 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 12:25:10.959   874  1917 I ActivityManager: Killing 3699:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 12:25:11.589   874  1922 D WifiService: setWifiEnabled: true pid=3836, uid=10000
,08-16 12:25:11.589   874  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:25:11.603   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 12:25:11.612  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:11.612  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:11.612  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:11.613  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:11.616  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:11.617  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:11.617  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:11.618  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:11.642   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-16 12:25:11.643   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 12:25:11.644   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 12:25:11.645   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 12:25:11.645   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2,
08-16 12:25:11.645   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 12:25:11.646   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 12:25:11.658   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 12:25:11.658   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=13.00 rxSuccessRate=16.50 delta 1000 -> 994
,08-16 12:25:11.659   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:11.661   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 12:25:11.661   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 12:25:11.668   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 12:25:11.668   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:11.677   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 12:25:11.720   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 12:25:11.728   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 12:25:11.739   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 12:25:11.745  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 12:25:12.170  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:25:12.206  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 12:25:12.209  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 12:25:12.215   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:25:12.229   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:25:12.230   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:12.232   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 12:25:12.257   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:12.268   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:12.270   874  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 12:25:12.289   874  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 12:25:12.296   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 12:25:12.301   874  4116 D DhcpClient: Receive thread started
,08-16 12:25:12.390   874  1307 E native  : do suspend false
,08-16 12:25:12.412   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 12:25:12.426   874  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-16 12:25:12.427   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-16 12:25:12.430   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 12:25:12.443   874  4116 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 12:25:12.444   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 12:25:12.449   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:12.461   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 12:25:12.462   874  1878 D DhcpClient: Scheduling renewal in 86399s
,08-16 12:25:12.481   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 12:25:12.482   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 12:25:12.482   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:25:12.483   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 12:25:12.485   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 12:25:12.491   874  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 12:25:12.549   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 12:25:12.549   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 12:25:12.550   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 12:25:12.553   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 12:25:12.555   874  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 12:25:12.566   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 12:25:12.573   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 12:25:12.573   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 12:25:12.573   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 12:25:12.573   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 12:25:12.574   874  1309 D ConnectivityService:    accepting network in place of null
,08-16 12:25:12.575   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:25:12.576   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:25:12.586   874  4115 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140340, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 12:25:12.623   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:12.654   874  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:816::200e
,08-16 12:25:12.671   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:12.681   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 12:25:12.682   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:12.692   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:25:12.703   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 12:25:12.717  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:12.717  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:12.717  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:12.717  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:12.722  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:12.722  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:12.722  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:12.723  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:12.737   874  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:25:12 GMT], X-Android-Received-Millis=[1471343112736], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471343112705]}
,08-16 12:25:12.776   874   886 I ActivityManager: Start proc 4128:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-16 12:25:12.782   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 12:25:12.782   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 12:25:12.782   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:25:12.783   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:25:12.795  1988  1988 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 12:25:12.796  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:25:12.804  1739  1739 D SystemUpdateService: onCreate
,08-16 12:25:12.807  4128  4128 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-16 12:25:12.808  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:25:12.814  1739  4141 I SystemUpdateService: active receiver: enabled
,08-16 12:25:12.820  1739  4141 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:25:12.829  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 12:25:12.834  1739  2447 I iu.UploadsManager: num queued entries: 0
,08-16 12:25:12.834  1739  2447 I iu.UploadsManager: num updated entries: 0
08-16 12:25:12.835  1739  2447 I iu.SyncManager: NEXT; no task
,08-16 12:25:12.835  1739  4141 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 12:25:12.835  1739  4141 I SystemUpdateService: now status is 0 (complete)
,08-16 12:25:12.835  1739  4141 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:25:12.836  1739  4141 I SystemUpdateService: file has been verified
,08-16 12:25:12.836  1739  4141 I SystemUpdateService: OTA package size = 12249756
,08-16 12:25:12.840  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:25:12.843  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:25:12.852  4014  4014 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:12.852  1739  4141 I SystemUpdateService: showing system update notification
,08-16 12:25:12.853  1739  4146 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 12:25:12.853  1739  4146 W BaseAppContext: Using Auth Proxy for data requests.
08-16 12:25:12.854  1739  4146 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 12:25:12.859  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:12.860  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:12.861  1739  1739 D SystemUpdateService: onDestroy
,08-16 12:25:12.892  4128  4128 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 12:25:12.892  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 12:25:12.892  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 12:25:12.892  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:12.892  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:12.899  4014  4014 D SprintDMHelper: simOperator: 
,08-16 12:25:12.900  4128  4128 I BooksApp: Created application version: 3.6.9 (30609)
,08-16 12:25:12.900  4014  4014 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-16 12:25:12.906  1739  4146 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 12:25:12.940  1517  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 12:25:12.940  1517  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 12:25:12.940  1517  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:25:12.940  1517  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:12.954  3547  4143 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 12:25:12.954  3547  4143 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jdm.a(PG:82)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jcs.o(PG:406)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jcn.a(PG:1379)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jcs.i(PG:143)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at blb.a(PG:3937)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at czp.a(PG:18188)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at czp.a(PG:9081)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at czq.run(PG:1686)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:25:12.954  3547  4143 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jdj.a(PG:4091)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jdj.a(PG:1125)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jdm.a(PG:77)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	... 12 more
08-16 12:25:12.954  3547  4143 E HttpOperation: Caused by: faj: BadAuthentication
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at fal.a(PG:38)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	at jdj.a(PG:4089)
08-16 12:25:12.954  3547  4143 E HttpOperation: 	... 14 more
,08-16 12:25:13.012  1517  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 12:25:13.012  1517  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 12:25:13.012  1517  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:13.012  1517  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:13.022  3547  4143 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 12:25:13.022  3547  4143 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jdm.a(PG:82)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jcs.o(PG:406)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jcn.a(PG:1379)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jcs.i(PG:143)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at hec.a(PG:42)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at hee.a(PG:102)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at czr.a(PG:65)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at kka.a(PG:108)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at czp.a(PG:19176)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at czp.a(PG:9081)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at czq.run(PG:1686)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:25:13.022  3547  4143 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jdj.a(PG:4091)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jdj.a(PG:1125)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jdm.a(PG:77)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	... 15 more
08-16 12:25:13.022  3547  4143 E HttpOperation: Caused by: faj: BadAuthentication
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at fal.a(PG:38)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	at jdj.a(PG:4089)
08-16 12:25:13.022  3547  4143 E HttpOperation: 	... 17 more
,08-16 12:25:13.022  3547  4143 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 12:25:13.022  3547  4143 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at hec.a(PG:42)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at hee.a(PG:102)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at czr.a(PG:65)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at kka.a(PG:108)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	... 15 more
08-16 12:25:13.022  3547  4143 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at fal.a(PG:38)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 12:25:13.022  3547  4143 E ExperimentLoader: 	... 17 more
,08-16 12:25:13.046  4128  4154 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 12:25:13.066  3971  4153 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 12:25:13.107   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128780, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 12:25:13.163  4128  4167 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 12:25:13.225  1517  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:25:13.225  1517  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 12:25:13.225  1517  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:25:13.226  1517  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:13.277  1517  2883 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 12:25:13.277  1517  2883 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 12:25:13.277  1517  2883 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:13.277  1517  2883 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:13.299  4128  4167 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 12:25:13.301  4128  4154 E BooksSync: Soft error
08-16 12:25:13.301  4128  4154 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:25:13.301  4128  4154 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 12:25:13.301  4128  4154 E BooksSync: Sync error
08-16 12:25:13.301  4128  4154 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 12:25:13.301  4128  4154 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 12:25:13.302  4128  4154 I BooksSync: Finished books sync
,08-16 12:25:13.316   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127173, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
08-16 12:25:13.316   874   884 I ActivityManager: Killing 2187:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 12:25:13.679   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 12:25:14.530   874  2716 I ActivityManager: Killing 3722:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 12:25:14.597   874  1917 D WifiService: setWifiEnabled: false pid=3836, uid=10000
,08-16 12:25:14.598   874  1917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:25:14.622  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 12:25:14.630   874  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 12:25:14.631   874  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 12:25:14.631   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:25:14.632   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:14.652   874  1878 D DhcpClient: Clearing IP address
,08-16 12:25:14.652   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-16 12:25:14.658   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:14.664  1517  4156 V NativeCrypto: Read error: ssl=0x9a720e00: I/O error during system call, Connection timed out
,08-16 12:25:14.666  1517  4156 V NativeCrypto: SSL shutdown failed: ssl=0x9a720e00: I/O error during system call, Broken pipe
,08-16 12:25:14.669   874  1919 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-16 12:25:14.669   874  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-16 12:25:14.671   874  4114 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-16 12:25:14.672   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-16 12:25:14.673   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 12:25:14.674   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:25:14.674   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 12:25:14.674   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 12:25:14.675   874  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 12:25:14.676   874  4116 D DhcpClient: Receive thread stopped
,08-16 12:25:14.678   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 12:25:14.681   395   395 E Parcel  : Reading a NULL string not supported here.
08-16 12:25:14.682   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-16 12:25:14.690   874  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 12:25:14.696   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:25:14.699   874  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 12:25:14.703  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:14.703  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:14.703  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:14.703  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:14.704  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:14.704  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:14.704  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:14.704  2132  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 12:25:14.704  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:14.725   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:14.749   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:14.750   874  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 12:25:14.750   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:14.752   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:25:14.754  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:14.755  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:14.760  1988  1988 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-16 12:25:14.762  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:25:14.766  1739  1739 D SystemUpdateService: onCreate
,08-16 12:25:14.768  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-16 12:25:14.773  1739  4179 I SystemUpdateService: active receiver: enabled
,08-16 12:25:14.776  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 12:25:14.781  1739  2447 I iu.UploadsManager: num queued entries: 0
,08-16 12:25:14.781  1739  2447 I iu.UploadsManager: num updated entries: 0
,08-16 12:25:14.783  1739  4179 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:25:14.785  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:25:14.786  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:25:14.787  4014  4014 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:14.790  4014  4014 D SprintDMHelper: simOperator: 
,08-16 12:25:14.790  4014  4014 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:25:14.812  1739  2447 I iu.SyncManager: NEXT; no task
,08-16 12:25:14.813   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-16 12:25:14.813   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 12:25:14.816  3971  4183 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 12:25:14.816  1739  4179 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 12:25:14.818  1739  4179 I SystemUpdateService: now status is 0 (complete)
08-16 12:25:14.818  1739  4179 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:25:14.818  1739  4179 I SystemUpdateService: file has been verified
,08-16 12:25:14.818  1739  4179 I SystemUpdateService: OTA package size = 12249756
,08-16 12:25:14.826  1739  4179 I SystemUpdateService: showing system update notification
,08-16 12:25:14.834  1739  1739 D SystemUpdateService: onDestroy
,08-16 12:25:17.649   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d91ebe2:true
,08-16 12:25:17.650  3999  3999 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 12:25:17.655  3999  3999 I bt_bluedroid: init
,08-16 12:25:17.657  3999  4187 I BluetoothAdapterState: Entering OffState
,08-16 12:25:17.661  3999  4188 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 12:25:17.661  3999  4188 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 12:25:17.661  3999  4188 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:25:17.661  3999  4188 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 12:25:17.662  3999  3999 I bt_bluedroid: get_profile_interface socket
08-16 12:25:17.664  3999  3999 I bt_bluedroid: get_profile_interface sdp
,08-16 12:25:17.667  3999  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:25:17.670  3999  4009 I bt_bluedroid: config_hci_snoop_log
,08-16 12:25:17.671  3999  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:25:17.675   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 12:25:17.684  3999  4187 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 12:25:17.684  3999  4187 D BluetoothAdapterProperties: Setting state to 14
08-16 12:25:17.685  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 12:25:17.689  3999  4187 D BluetoothBondStateMachine: make
,08-16 12:25:17.694  3999  4192 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 12:25:17.701  3999  4187 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:17.704  3999  3999 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 12:25:17.710  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:17.712  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:25:17.713  3999  3999 D BtGatt.GattService: Received start request. Starting profile...
,08-16 12:25:17.713  3999  3999 D BtGatt.GattService: start()
,08-16 12:25:17.713  3999  3999 I bt_bluedroid: get_profile_interface gatt
,08-16 12:25:17.715  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:17.715  3999  3999 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:25:17.726  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:17.726  3999  3999 V BluetoothAdapterState: isTurningOn()=false,
08-16 12:25:17.726  3999  3999 V BluetoothAdapterState: isBleTurningOn()=true
08-16 12:25:17.726  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:17.727  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 12:25:17.727  3999  4187 I bt_bluedroid: enable
08-16 12:25:17.728  3999  4188 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 12:25:17.728  3999  4188 I bt_hci  : start_up
,08-16 12:25:17.737  3999  4188 I bt_vendor: alloc value 0xb39a0189
,08-16 12:25:17.737  3999  4188 I bt_vendor: init
08-16 12:25:17.737  3999  4188 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 12:25:17.737  3999  4188 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 12:25:17.842  3999  4188 D bt_hci  : start_up starting async portion
,08-16 12:25:17.843  3999  4195 I bt_hci  : event_finish_startup
,08-16 12:25:17.843  3999  4195 I bt_hci_h4: hal_open
,08-16 12:25:17.843  3999  4195 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 12:25:17.851  3999  4195 I bt_userial_vendor: device fd = 51 open
,08-16 12:25:17.886  3999  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:25:17.911  4128  4151 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 12:25:17.918  3999  4195 D bt_hwcfg: Chipset BCM4354A2
08-16 12:25:17.918  3999  4195 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 12:25:17.919  3999  4195 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 12:25:18.593  3999  4195 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 12:25:18.595  3999  4195 D bt_hwcfg: Settlement delay -- 100 ms
08-16 12:25:18.596  3999  4195 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 12:25:18.712  3999  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:25:18.714  3999  4195 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 12:25:18.742  3999  4195 I bt_hwcfg: vendor lib fwcfg completed
,08-16 12:25:18.742  3999  4195 I bt_vendor: firmware callback
08-16 12:25:18.743  3999  4195 I bt_hci  : firmware_config_callback
,08-16 12:25:18.754  3999  4199 I bt_btu  : btu_task pending for preload complete event
,08-16 12:25:18.754  3999  4199 I bt_btu_task: Bluetooth chip preload is complete
,08-16 12:25:18.755  3999  4199 I bt_btu  : btu_task received preload complete event
,08-16 12:25:18.764  3999  4199 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 12:25:18.765  3999  4199 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 12:25:18.765  3999  4199 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 12:25:18.765  3999  4199 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 12:25:18.766  3999  4199 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 12:25:18.766  3999  4199 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:25:18.766  3999  4199 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 12:25:18.767  3999  4199 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 12:25:18.767  3999  4199 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:25:18.767  3999  4199 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:25:18.767  3999  4199 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:25:18.768  3999  4199 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 12:25:18.768  3999  4199 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:25:18.768  3999  4199 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 12:25:18.769  3999  4199 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:25:18.905  3999  4199 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb391dd9d
,08-16 12:25:18.906  3999  4199 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb391dd9d 
,08-16 12:25:18.929  3999  4191 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 12:25:18.930  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 12:25:18.931  3999  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:25:18.935  3999  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:25:18.940  3999  4191 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:25:18.941  3999  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:25:18.941  3999  4191 D bt_hci  : do_postload posting postload work item
08-16 12:25:18.942  3999  4195 I bt_hci  : event_postload
08-16 12:25:18.942  3999  4195 I bt_vendor: sco_config_cb
,08-16 12:25:18.942  3999  4195 I bt_hci  : sco_config_callback postload finished.
,08-16 12:25:18.945  3999  4191 D bt_bte_conf: Device ID record 1 : primary
08-16 12:25:18.945  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:18.946  3999  4191 D bt_bte_conf:   vendorId            = 000f
08-16 12:25:18.946  3999  4191 D bt_bte_conf:   vendorIdSource      = 0001
08-16 12:25:18.946  3999  4191 D bt_bte_conf:   product             = 1200
08-16 12:25:18.946  3999  4191 D bt_bte_conf:   version             = 1436
,08-16 12:25:18.946  3999  4191 D bt_bte_conf:   clientExecutableURL = 
08-16 12:25:18.947  3999  4191 D bt_bte_conf:   serviceDescription  = 
08-16 12:25:18.947  3999  4191 D bt_bte_conf:   documentationURL    = 
,08-16 12:25:18.947  3999  4191 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 12:25:18.947  3999  4188 D bt_stack_manager: event_start_up_stack finished
,08-16 12:25:18.949  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:18.949  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 12:25:18.950  3999  4187 D BluetoothAdapterProperties: Setting state to 15
08-16 12:25:18.950  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 12:25:18.951  3999  4187 I BluetoothAdapterState: Entering BleOnState
08-16 12:25:18.954  3999  4195 I bt_vendor: low_power_mode_cb
08-16 12:25:18.958  3999  4187 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 12:25:18.958  3999  4187 D BluetoothAdapterProperties: Setting state to 11
,08-16 12:25:18.959  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 12:25:18.970  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:18.974  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:18.974  3999  3999 D HeadsetService: Received start request. Starting profile...
08-16 12:25:18.976  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:18.980  3999  3999 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:25:18.980  3999  3999 D HeadsetStateMachine: make
,08-16 12:25:18.985  3999  4187 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:18.990  3999  3999 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:25:18.990  3999  3999 I bt_bluedroid: get_profile_interface handsfree
,08-16 12:25:18.991  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 12:25:18.991  3999  4191 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 12:25:18.996  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:18.997  3999  3999 D A2dpService: Received start request. Starting profile...
,08-16 12:25:18.998  3999  3999 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 12:25:18.998  3999  3999 I bt_bluedroid: get_profile_interface avrcp
,08-16 12:25:19.007  3999  3999 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:25:19.007  3999  3999 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:25:19.007  3999  3999 D A2dpStateMachine: make
,08-16 12:25:19.009  3999  3999 I bt_bluedroid: get_profile_interface a2dp
08-16 12:25:19.010  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 12:25:19.012  3999  4208 D A2dpStateMachine: Enter Disconnected: -2
,08-16 12:25:19.012  3999  3999 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 12:25:19.014  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:19.016  3920  3920 D BluetoothInputDevice: Proxy object connected
,08-16 12:25:19.016  3999  3999 D HidService: Received start request. Starting profile...
08-16 12:25:19.016  3999  3999 I bt_bluedroid: get_profile_interface hidhost
08-16 12:25:19.016  3999  3999 D HidService: setHidService(): set to: null
08-16 12:25:19.016  3999  4191 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38ff3e5
08-16 12:25:19.016  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 12:25:19.017  3999  3999 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 12:25:19.018  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
08-16 12:25:19.019  3999  3999 D HealthService: Received start request. Starting profile...
08-16 12:25:19.019  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:25:19.019  3920  3920 D HidProfile: Bluetooth service connected
08-16 12:25:19.020  3999  3999 I bt_bluedroid: get_profile_interface health
08-16 12:25:19.021  3999  3999 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 12:25:19.022  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:19.023  3999  3999 D PanService: Received start request. Starting profile...
08-16 12:25:19.023  3920  3920 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:25:19.024  3999  3999 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 12:25:19.024  3999  3999 I bt_bluedroid: get_profile_interface pan
08-16 12:25:19.024  3920  3920 D PanProfile: Bluetooth service connected
08-16 12:25:19.025  3999  4191 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 12:25:19.028  3999  3999 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:19.029  3920  3920 D BluetoothMap: Proxy object connected
,08-16 12:25:19.030  3999  3999 D BluetoothMapService: Received start request. Starting profile...
,08-16 12:25:19.030  3999  3999 D BluetoothMapService: start()
,08-16 12:25:19.032  3920  3920 D MapProfile: Bluetooth service connected
,08-16 12:25:19.033  3920  3920 D BluetoothMap: getConnectedDevices()
,08-16 12:25:19.034  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 12:25:19.035  3920  3920 D BluetoothMap: Bluetooth is Not enabled
,08-16 12:25:19.035  3999  3999 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 12:25:19.035  3999  3999 D BluetoothMapAppObserver: createReceiver()
,08-16 12:25:19.036  3999  3999 D BluetoothMapAppObserver: initObservers()
08-16 12:25:19.036  3999  3999 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 12:25:19.044  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:19.044  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.044  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:19.045  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:25:19.047  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isTurningOff()=false
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:19.049  3999  4206 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:25:19.048  3999  3999 V BluetoothAdapterState: isTurningOff()=false
08-16 12:25:19.049  3999  3999 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:19.050  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:19.050  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:19.050  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 12:25:19.050  3999  4187 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:25:19.050  3999  4187 D BluetoothAdapterProperties: State =  11
08-16 12:25:19.055  3999  4191 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:25:19.055  3999  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:25:19.055  3999  4187 D BluetoothAdapterProperties: Setting state to 12
08-16 12:25:19.055  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:25:19.056   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:19.056  3999  4187 I BluetoothAdapterState: Entering OnState
08-16 12:25:19.056  1362  2001 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:25:19.060  3920  3931 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 12:25:19.061  1362  1373 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:19.062   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:25:19.063  3920  3932 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:25:19.063  1910  2036 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:25:19.064  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 12:25:19.064   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:25:19.064  1362  1984 D BluetoothMap: onBluetoothStateChange: up=true
08-16 12:25:19.064  3999  3999 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 12:25:19.066   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:19.067  1362  1362 D BluetoothMap: Proxy object connected
08-16 12:25:19.067  3920  3931 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:25:19.067  1362  1362 D MapProfile: Bluetooth service connected
08-16 12:25:19.067  1362  1362 D BluetoothMap: getConnectedDevices()
,08-16 12:25:19.067  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:25:19.069  3920  3932 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:19.070  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:19.073  3999  3999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:25:19.073  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:19.074  3999  3999 D ObexServerSockets: Succeed to create listening sockets 
,08-16 12:25:19.075  1362  2001 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:25:19.075  3999  3999 D ObexServerSockets0: startAccept()
,08-16 12:25:19.075  3999  3999 D ObexServerSockets0: prepareForNewConnect()
08-16 12:25:19.076  1362  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:19.078  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:19.080  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-16 12:25:19.080  1362  1362 D HidProfile: Bluetooth service connected
,08-16 12:25:19.081  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:19.081  3999  3999 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 12:25:19.081  3999  3999 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 12:25:19.082  1362  1374 D BluetoothPan: onBluetoothStateChange on: true
08-16 12:25:19.083   874   874 D BluetoothA2dp: Proxy object connected
08-16 12:25:19.083  1362  1362 D BluetoothA2dp: Proxy object connected
08-16 12:25:19.084  3999  4215 D ObexServerSockets0: Accepting socket connection...
,08-16 12:25:19.085  3999  4214 D ObexServerSockets0: Accepting socket connection...
08-16 12:25:19.085  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:25:19.086  1362  1362 D PanProfile: Bluetooth service connected
08-16 12:25:19.087   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 12:25:19.088  3999  3999 D BluetoothMapService: onReceive
08-16 12:25:19.088  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:25:19.088  3999  3999 D BluetoothMapService: STATE_ON
,08-16 12:25:19.089  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:19.089  3920  3920 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 12:25:19.090  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:19.094  3920  3920 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 12:25:19.099  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:25:19.102  3920  3920 D BluetoothA2dp: Proxy object connected
,08-16 12:25:19.107  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:19.107  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:25:19.114  1362  1362 D BluetoothPbap: Proxy object connected
,08-16 12:25:19.114  1362  1362 D PbapServerProfile: Bluetooth service connected
08-16 12:25:19.114  3999  3999 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 12:25:19.114  3999  3999 D ObexServerSockets0: prepareForNewConnect()
08-16 12:25:19.114  3920  3920 D BluetoothPbap: Proxy object connected
08-16 12:25:19.115  3920  3920 D PbapServerProfile: Bluetooth service connected
,08-16 12:25:19.126  3999  4220 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:25:19.136  3999  4224 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:25:19.138  3999  4224 I BtOppRfcommListener: Accept thread started.
,08-16 12:25:19.157  1362  2001 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.158   874   874 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.158  1362  1362 D HeadsetProfile: Bluetooth service connected
08-16 12:25:19.158   874   874 D BluetoothHeadset: Proxy object connected
08-16 12:25:19.158   874   874 D BluetoothHeadset: Proxy object connected
08-16 12:25:19.158  1910  1930 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.162  1362  1984 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.162  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-16 12:25:19.164  1910  1925 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.164   874   891 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.167   874   891 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.197  3920  3931 D BluetoothHeadset: Proxy object connected
,08-16 12:25:19.198  3920  3920 D HeadsetProfile: Bluetooth service connected
,08-16 12:25:20.579   874  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-16 12:25:20.616  3999  4187 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 12:25:20.617  3999  4187 D BluetoothAdapterProperties: Setting state to 13
,08-16 12:25:20.617  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 12:25:20.619  3999  4187 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 12:25:20.625  3999  4187 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:20.634  3999  3999 D BluetoothMapService: onReceive,
,08-16 12:25:20.634  3999  3999 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 12:25:20.635  3999  3999 D BluetoothMapService: STATE_TURNING_OFF
,08-16 12:25:20.636  3999  3999 D BluetoothMapService: MAP Service closeService in
08-16 12:25:20.636  3999  3999 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 12:25:20.636  3999  3999 D ObexServerSockets0: shutdown(block = true)
,08-16 12:25:20.637  3999  4214 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 12:25:20.638  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:20.638  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:20.641  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:20.641  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:20.645  3999  4191 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:25:20.646  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 12:25:20.646  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:25:20.646  3999  4215 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 12:25:20.647  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:20.647  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:20.648  3836  3836 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 12:25:20.647  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 12:25:20.648  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 12:25:20.648  3999  4201 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 12:25:20.649  3999  3999 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 12:25:20.650  3999  3999 D HeadsetService: Received stop request...Stopping profile...
08-16 12:25:20.655  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:20.656  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant sta,te changes
08-16 12:25:20.657  1362  2001 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.657  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-16 12:25:20.657   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.657   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.658  3999  3999 D A2dpService: Received stop request...Stopping profile...
08-16 12:25:20.658  3920  3931 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.658   874   874 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.659  3999  4208 D A2dpStateMachine: Exit Disconnected: -1
08-16 12:25:20.659  1910  2061 D BluetoothHeadset: Proxy object disconnected
08-16 12:25:20.660   874   874 D BluetoothA2dp: Proxy object disconnected
08-16 12:25:20.661  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-16 12:25:20.661  3999  3999 D HidService: Received stop request...Stopping profile...
08-16 12:25:20.661  3999  3999 D HidService: Stopping Bluetooth HidService
08-16 12:25:20.662  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-16 12:25:20.662  1362  1362 D HidProfile: Bluetooth service disconnected
08-16 12:25:20.663  3999  3999 I BtOppRfcommListener: stopping Accept Thread
08-16 12:25:20.663  3999  4224 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 12:25:20.663  3999  4224 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 12:25:20.664  3999  3999 D HealthService: Received stop request...Stopping profile...
,08-16 12:25:20.666  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:25:20.666  3999  3999 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:20.666  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.666  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:20.668  3920  3920 D DockEventReceiver: finishStartingService: stopping service
08-16 12:25:20.669  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:20.669  3920  3920 D HeadsetProfile: Bluetooth service disconnected
08-16 12:25:20.670  3920  3920 D BluetoothA2dp: Proxy object disconnected
08-16 12:25:20.670  3920  3920 D BluetoothInputDevice: Proxy object disconnected
08-16 12:25:20.670  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 12:25:20.670  3920  3920 D HidProfile: Bluetooth service disconnected
08-16 12:25:20.670  3999  3999 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 12:25:20.671  3999  3999 D PanService: Received stop request...Stopping profile...
08-16 12:25:20.671  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 12:25:20.671  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:20.671  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:20.671  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:20.672  3999  4191 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-16 12:25:20.673  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:25:20.673  1362  1362 D PanProfile: Bluetooth service disconnected
,08-16 12:25:20.674  3999  3999 D BluetoothMapService: Received stop request...Stopping profile...
08-16 12:25:20.674  3999  3999 D BluetoothMapService: stop()
08-16 12:25:20.674  3920  3920 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 12:25:20.674  3920  3920 D PanProfile: Bluetooth service disconnected
,08-16 12:25:20.674  3999  3999 D BluetoothMapAppObserver: deinitObservers()
08-16 12:25:20.674  3999  3999 D BluetoothMapAppObserver: removeReceiver()
08-16 12:25:20.675  1362  1362 D BluetoothMap: Proxy object disconnected
08-16 12:25:20.675  1362  1362 D MapProfile: Bluetooth service disconnected
08-16 12:25:20.676  3920  3920 D BluetoothMap: Proxy object disconnected
08-16 12:25:20.676  3999  3999 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:20.676  3920  3920 D MapProfile: Bluetooth service disconnected
08-16 12:25:20.676  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:25:20.676  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.676  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:20.677  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 12:25:20.677  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:20.678  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 12:25:20.678  3999  4199 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:25:20.678  3999  4199 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:25:20.678  3999  4199 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 12:25:20.678  3999  4199 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 12:25:20.679  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:25:20.679  3999  3999 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:20.679  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.679  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:20.679  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 12:25:20.679  3999  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 12:25:20.680  3999  3999 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 12:25:20.681  3999  3999 V BluetoothAdapterState: isTurningOff()=true
,08-16 12:25:20.681  3999  3999 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:20.681  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.681  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:20.681  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 12:25:20.682  3999  4191 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 12:25:20.682  3999  3999 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 12:25:20.684  1362  1362 D BluetoothPbap: Proxy object disconnected
08-16 12:25:20.684  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-16 12:25:20.684  3920  3920 D BluetoothPbap: Proxy object disconnected
,08-16 12:25:20.684  3920  3920 D PbapServerProfile: Bluetooth service disconnected
08-16 12:25:20.685  3999  3999 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:20.685  3999  3999 V BluetoothAdapterState: isTurningOn()=false
,08-16 12:25:20.685  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.685  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:20.685  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 12:25:20.685  3999  3999 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 12:25:20.686  3999  3999 D BluetoothMapService: MAP Service closeService in
08-16 12:25:20.686  3999  3999 V BluetoothAdapterState: isTurningOff()=true
08-16 12:25:20.687  3999  3999 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:20.687  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:20.687  3999  3999 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:20.687  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 12:25:20.687  3999  4187 D BluetoothAdapterProperties: Setting state to 15
08-16 12:25:20.687  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 12:25:20.688  3999  4187 I BluetoothAdapterState: Entering BleOnState
,08-16 12:25:20.688  3999  3999 D BluetoothMapService: cleanup()
08-16 12:25:20.688  3999  3999 D BluetoothMapService: MAP Service closeService in
,08-16 12:25:20.689   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:25:20.689  1362  2001 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:25:20.690  3920  3932 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:25:20.691  3920  3931 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:20.691  1362  1984 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:20.691   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:25:20.692  3920  3932 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 12:25:20.692  1910  2036 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:20.693   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 12:25:20.693  1362  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-16 12:25:20.694   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 12:25:20.694  3920  3931 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:25:20.694  3920  3932 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 12:25:20.695  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 12:25:20.695  1362  2001 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 12:25:20.696  3920  3931 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 12:25:20.697  1362  1984 D BluetoothPan: onBluetoothStateChange on: false
08-16 12:25:20.698  3999  4187 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 12:25:20.698  3999  4187 D BluetoothAdapterProperties: Setting state to 16
08-16 12:25:20.698  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-16 12:25:20.699  3999  4187 D BluetoothAdapterProperties: onBleDisable
,08-16 12:25:20.699  3999  4187 I BluetoothAdapterState: Entering PendingCommandState
08-16 12:25:20.699  3999  4188 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 12:25:20.701  3999  4199 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 12:25:20.701  3999  4199 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 12:25:20.701  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:20.702  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:20.703  3999  4191 D BluetoothAdapterProperties: Scan Mode:20
08-16 12:25:20.705  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 12:25:20.705  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:20.707  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:20.709  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:20.710  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:25:20.901  3999  4191 I bt_hci  : shut_down
,08-16 12:25:20.912  3999  4195 I bt_vendor: low_power_mode_cb
,08-16 12:25:20.912  3999  4195 D bt_hwcfg: hw_epilog_process
,08-16 12:25:20.936  3999  4195 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 12:25:20.937  3999  4195 I bt_vendor: epilog_cb
08-16 12:25:20.937  3999  4195 I bt_hci  : epilog_finished_callback
,08-16 12:25:20.942  3999  4191 I bt_hci_h4: hal_close
,08-16 12:25:20.943  3999  4191 I bt_userial_vendor: device fd = 51 close
,08-16 12:25:21.073  3999  4188 D bt_stack_manager: event_shut_down_stack finished.
,08-16 12:25:21.074  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 12:25:21.082  3999  3999 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:25:21.082  3999  4187 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 12:25:21.084  3999  3999 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 12:25:21.084  3999  3999 D BtGatt.GattService: stop()
,08-16 12:25:21.086  3999  3999 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 12:25:21.093  3999  3999 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:21.093  3999  3999 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:21.094  3999  3999 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:25:21.094  3999  3999 V BluetoothAdapterState: isBleTurningOff()=true
08-16 12:25:21.095  3999  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 12:25:21.095  3999  4187 D BluetoothAdapterProperties: Setting state to 10
08-16 12:25:21.096  3999  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 12:25:21.097  3999  4187 I BluetoothAdapterState: Entering OffState
,08-16 12:25:21.100   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 12:25:21.127  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 12:25:21.128  3999  3999 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 12:25:21.128  3999  4188 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 12:25:21.131  3999  3999 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 12:25:21.136  3999  4188 D bt_stack_manager: event_clean_up_stack finished.
,08-16 12:25:21.138  3999  3999 I art     : System.exit called, status: 0
,08-16 12:25:21.138  3999  3999 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 12:25:21.210   874  3115 I ActivityManager: Process com.android.bluetooth (pid 3999) has died
,08-16 12:25:21.580  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:21.596  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:21.601  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:21.661  1517  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 12:25:21.661  1517  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 12:25:21.661  1517  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:21.661  1517  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:21.705  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 12:25:21.705  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 12:25:21.707  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 12:25:22.255   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 12:25:22.267  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-16 12:25:22.283   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 12:25:22.283   874   894 I Adreno  : Build Date                       : 10/20/15
08-16 12:25:22.283   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 12:25:22.283   874   894 I Adreno  : Local Branch                     : M14
08-16 12:25:22.283   874   894 I Adreno  : Remote Branch                    : 
08-16 12:25:22.283   874   894 I Adreno  : Remote Branch                    : 
08-16 12:25:22.283   874   894 I Adreno  : Reconstruct Branch               : 
,08-16 12:25:22.330   281  2323 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (329 us)
,08-16 12:25:22.946  3510  3591 D Finsky  : [294] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-16 12:25:22.995  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 12:25:22.996  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 12:25:23.031   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 12:25:23.037  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@da3baf6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4fd20b6, 16908290=android.view.AbsSavedState$1@4fd20b6}, android:focusedViewId=100}]}]
08-16 12:25:23.037  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 12:25:23.037  3836  3836 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 12:25:23.038  3836  3836 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 12:25:23.042  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:23.052   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 12:25:23.059   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 12:25:23.059   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-16 12:25:23.059   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 12:25:23.074   874   883 I art     : Background partial concurrent mark sweep GC freed 35297(2MB) AllocSpace objects, 6(168KB) LOS objects, 33% free, 29MB/43MB, paused 1.111ms total 105.662ms
,08-16 12:25:23.077  1517  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-16 12:25:23.077  1517  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 12:25:23.078  1517  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 12:25:23.078  1517  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:23.092  3510  3591 D Finsky  : [294] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-16 12:25:23.293   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 12:25:23.297   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 12:25:23.300   874  1330 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,08-16 12:25:23.305   874   894 I DreamManagerService: Entering dreamland.
,08-16 12:25:23.306   874   894 I PowerManagerService: Dozing...
08-16 12:25:23.308   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 12:25:23.353   376  1980 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 12:25:23.353   376  1980 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 12:25:23.361   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:25:23.362  1897  4236 D NfcService: Discovery configuration equal, not updating.
,08-16 12:25:23.368   874  1307 E native  : do suspend false
,08-16 12:25:23.386   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:25:23.391   874  1307 E native  : do suspend true
,08-16 12:25:23.491   376  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 12:25:23.491   376  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 12:25:23.613  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:23.614  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:26.621  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:25:26.622  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28291b7 added. We now have 6 listener(s)
08-16 12:25:26.622  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:25:26.627  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:25:26.627  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@487fd24 added. We now have 7 listener(s)
,08-16 12:25:26.628  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:26.629  3836  3899 I System.out: IsBluetoothEnabled
,08-16 12:25:26.641  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:26.690   874   891 I ActivityManager: Start proc 4244:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 12:25:26.809  4244  4244 D AdapterServiceConfig: Adding HeadsetService
,08-16 12:25:26.809  4244  4244 D AdapterServiceConfig: Adding A2dpService
08-16 12:25:26.809  4244  4244 D AdapterServiceConfig: Adding HidService
08-16 12:25:26.810  4244  4244 D AdapterServiceConfig: Adding HealthService
,08-16 12:25:26.810  4244  4244 D AdapterServiceConfig: Adding PanService
08-16 12:25:26.810  4244  4244 D AdapterServiceConfig: Adding GattService
,08-16 12:25:26.810  4244  4244 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 12:25:26.827  4244  4244 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 12:25:26.827   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5ea58b:true
,08-16 12:25:26.834  4244  4244 I bt_bluedroid: init
,08-16 12:25:26.835  4244  4256 I BluetoothAdapterState: Entering OffState
,08-16 12:25:26.843  4244  4257 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 12:25:26.843  4244  4257 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 12:25:26.844  4244  4257 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 12:25:26.844  4244  4257 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 12:25:26.847  4244  4244 I bt_bluedroid: get_profile_interface socket
,08-16 12:25:26.849  4244  4244 I bt_bluedroid: get_profile_interface sdp
,08-16 12:25:26.854  4244  4260 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 12:25:26.855  4244  4254 I bt_bluedroid: config_hci_snoop_log
,08-16 12:25:26.856  4244  4260 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 12:25:26.860   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 12:25:26.871  4244  4256 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 12:25:26.872  4244  4256 D BluetoothAdapterProperties: Setting state to 14
,08-16 12:25:26.872  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 12:25:26.876  4244  4256 D BluetoothBondStateMachine: make
,08-16 12:25:26.880  4244  4261 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 12:25:26.889  4244  4244 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 12:25:26.890  4244  4256 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:26.895  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:26.897  4244  4244 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 12:25:26.898  4244  4244 D BtGatt.GattService: Received start request. Starting profile...
08-16 12:25:26.898  4244  4244 D BtGatt.GattService: start()
,08-16 12:25:26.898  4244  4244 I bt_bluedroid: get_profile_interface gatt
08-16 12:25:26.900  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:26.900  4244  4244 D BtGatt.AdvertiseManager: advertise manager created
,08-16 12:25:26.914  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:26.915  4244  4244 V BluetoothAdapterState: isTurningOn()=false
08-16 12:25:26.915  4244  4244 V BluetoothAdapterState: isBleTurningOn()=true
08-16 12:25:26.915  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:26.916  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 12:25:26.917  4244  4256 I bt_bluedroid: enable
,08-16 12:25:26.918  4244  4257 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 12:25:26.920  4244  4257 I bt_hci  : start_up
,08-16 12:25:26.943  4244  4257 I bt_vendor: alloc value 0xb39b0189
,08-16 12:25:26.943  4244  4257 I bt_vendor: init
,08-16 12:25:26.943  4244  4257 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 12:25:26.944  4244  4257 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 12:25:27.054  4244  4257 D bt_hci  : start_up starting async portion
,08-16 12:25:27.054  4244  4264 I bt_hci  : event_finish_startup
,08-16 12:25:27.055  4244  4264 I bt_hci_h4: hal_open
08-16 12:25:27.055  4244  4264 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 12:25:27.064  4244  4264 I bt_userial_vendor: device fd = 51 open
,08-16 12:25:27.096  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:25:27.128  4244  4264 D bt_hwcfg: Chipset BCM4354A2
,08-16 12:25:27.128  4244  4264 D bt_hwcfg: Target name = [BCM4354A2]
08-16 12:25:27.129  4244  4264 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 12:25:27.789  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 12:25:27.790  4244  4264 D bt_hwcfg: Settlement delay -- 100 ms
08-16 12:25:27.790  4244  4264 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 12:25:27.907  4244  4264 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 12:25:27.908  4244  4264 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 12:25:27.938  4244  4264 I bt_hwcfg: vendor lib fwcfg completed
08-16 12:25:27.938  4244  4264 I bt_vendor: firmware callback
,08-16 12:25:27.938  4244  4264 I bt_hci  : firmware_config_callback
,08-16 12:25:27.949  4244  4267 I bt_btu  : btu_task pending for preload complete event
,08-16 12:25:27.950  4244  4267 I bt_btu_task: Bluetooth chip preload is complete
08-16 12:25:27.950  4244  4267 I bt_btu  : btu_task received preload complete event
,08-16 12:25:27.960  4244  4267 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 12:25:27.960  4244  4267 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 12:25:27.960  4244  4267 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 12:25:27.961  4244  4267 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 12:25:27.961  4244  4267 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 12:25:27.961  4244  4267 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 12:25:27.961  4244  4267 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 12:25:27.962  4244  4267 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 12:25:27.962  4244  4267 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 12:25:27.962  4244  4267 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 12:25:27.963  4244  4267 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 12:25:27.963  4244  4267 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 12:25:27.963  4244  4267 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 12:25:27.963  4244  4267 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 12:25:27.963  4244  4267 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 12:25:28.101  4244  4267 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-16 12:25:28.101  4244  4267 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-16 12:25:28.113  4244  4260 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-16 12:25:28.115  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 12:25:28.117  4244  4260 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 12:25:28.121  4244  4260 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 12:25:28.123  4244  4260 D BluetoothAdapterProperties: Scan Mode:20
,08-16 12:25:28.123  4244  4260 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:25:28.123  4244  4260 D bt_hci  : do_postload posting postload work item
08-16 12:25:28.123  4244  4264 I bt_hci  : event_postload
08-16 12:25:28.123  4244  4264 I bt_vendor: sco_config_cb
08-16 12:25:28.123  4244  4264 I bt_hci  : sco_config_callback postload finished.
,08-16 12:25:28.128  4244  4264 I bt_vendor: low_power_mode_cb
,08-16 12:25:28.128  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:28.129  4244  4260 D bt_bte_conf: Device ID record 1 : primary
08-16 12:25:28.129  4244  4260 D bt_bte_conf:   vendorId            = 000f
08-16 12:25:28.129  4244  4260 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 12:25:28.129  4244  4260 D bt_bte_conf:   product             = 1200
08-16 12:25:28.130  4244  4260 D bt_bte_conf:   version             = 1436
08-16 12:25:28.130  4244  4260 D bt_bte_conf:   clientExecutableURL = 
08-16 12:25:28.130  4244  4260 D bt_bte_conf:   serviceDescription  = 
08-16 12:25:28.130  4244  4260 D bt_bte_conf:   documentationURL    = 
,08-16 12:25:28.131  4244  4260 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 12:25:28.131  4244  4257 D bt_stack_manager: event_start_up_stack finished
,08-16 12:25:28.132  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 12:25:28.132  4244  4256 D BluetoothAdapterProperties: Setting state to 15
08-16 12:25:28.132  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 12:25:28.133  4244  4256 I BluetoothAdapterState: Entering BleOnState
,08-16 12:25:28.137  4244  4256 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 12:25:28.137  4244  4256 D BluetoothAdapterProperties: Setting state to 11
08-16 12:25:28.137  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 12:25:28.143  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:28.144  4244  4244 D HeadsetService: Received start request. Starting profile...
08-16 12:25:28.149  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:28.156  4244  4244 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 12:25:28.156  4244  4244 D HeadsetStateMachine: make
08-16 12:25:28.166  4244  4244 D HeadsetStateMachine: max_hf_connections = 1
08-16 12:25:28.166  4244  4244 I bt_bluedroid: get_profile_interface handsfree
,08-16 12:25:28.167  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 12:25:28.167  4244  4260 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-16 12:25:28.168  4244  4256 I BluetoothAdapterState: Entering PendingCommandState
,08-16 12:25:28.172  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:28.173  4244  4244 D A2dpService: Received start request. Starting profile...
,08-16 12:25:28.174  4244  4244 I BluetoothAvrcpServiceJni: classInitNative: succeeds,
08-16 12:25:28.175  4244  4244 I bt_bluedroid: get_profile_interface avrcp
,08-16 12:25:28.181  4244  4244 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 12:25:28.181  4244  4244 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 12:25:28.181  4244  4244 D A2dpStateMachine: make
,08-16 12:25:28.183  4244  4244 I bt_bluedroid: get_profile_interface a2dp
,08-16 12:25:28.183  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 12:25:28.186  4244  4276 D A2dpStateMachine: Enter Disconnected: -2
08-16 12:25:28.186  4244  4244 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 12:25:28.187  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
08-16 12:25:28.187  4244  4244 D HidService: Received start request. Starting profile...
08-16 12:25:28.187  4244  4244 I bt_bluedroid: get_profile_interface hidhost
08-16 12:25:28.187  4244  4260 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
,08-16 12:25:28.188  4244  4260 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 12:25:28.188  4244  4244 D HidService: setHidService(): set to: null
,08-16 12:25:28.190  4244  4244 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 12:25:28.191  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 12:25:28.192  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
08-16 12:25:28.192  4244  4244 D HealthService: Received start request. Starting profile...
,08-16 12:25:28.193  4244  4244 I bt_bluedroid: get_profile_interface health
,08-16 12:25:28.194  4244  4244 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 12:25:28.195  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:28.195  4244  4244 D PanService: Received start request. Starting profile...
08-16 12:25:28.196  4244  4244 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 12:25:28.196  4244  4244 I bt_bluedroid: get_profile_interface pan
,08-16 12:25:28.197  4244  4260 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 12:25:28.200  4244  4244 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
08-16 12:25:28.200  4244  4244 D BluetoothMapService: Received start request. Starting profile...
08-16 12:25:28.201  4244  4244 D BluetoothMapService: start()
,08-16 12:25:28.204  4244  4244 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 12:25:28.206  4244  4244 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 12:25:28.206  4244  4244 D BluetoothMapAppObserver: createReceiver()
,08-16 12:25:28.208  4244  4244 D BluetoothMapAppObserver: initObservers()
,08-16 12:25:28.208  4244  4244 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 12:25:28.219  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:28.220  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:28.220  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:28.220  4244  4274 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 12:25:28.220  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 12:25:28.222  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-16 12:25:28.222  4244  4244 V BluetoothAdapterState: isTurningOn()=true
,08-16 12:25:28.222  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:25:28.223  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:28.223  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-16 12:25:28.223  4244  4244 V BluetoothAdapterState: isTurningOn()=true
,08-16 12:25:28.223  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 12:25:28.223  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isTurningOff()=false
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isTurningOn()=true
08-16 12:25:28.224  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:28.225  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:28.225  4244  4244 V BluetoothAdapterState: isTurningOff()=false
,08-16 12:25:28.225  4244  4244 V BluetoothAdapterState: isTurningOn()=true
,08-16 12:25:28.225  4244  4244 V BluetoothAdapterState: isBleTurningOn()=false
08-16 12:25:28.225  4244  4244 V BluetoothAdapterState: isBleTurningOff()=false
08-16 12:25:28.225  4244  4256 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 12:25:28.225  4244  4256 D BluetoothAdapterProperties: ScanMode =  20
08-16 12:25:28.225  4244  4256 D BluetoothAdapterProperties: State =  11
,08-16 12:25:28.226  4244  4256 D BluetoothAdapterProperties: Setting state to 12
08-16 12:25:28.226  4244  4256 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 12:25:28.227   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:25:28.228  4244  4256 I BluetoothAdapterState: Entering OnState
08-16 12:25:28.228  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 12:25:28.230  4244  4260 D BluetoothAdapterProperties: Scan Mode:21
08-16 12:25:28.231  4244  4260 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 12:25:28.231  3920  3932 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 12:25:28.238  3920  3931 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:25:28.240  4244  4244 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:28.240  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 12:25:28.240  1362  2001 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 12:25:28.240  4244  4244 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 12:25:28.241   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 12:25:28.242  3920  3932 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:25:28.242  4244  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:25:28.243  3920  3920 D BluetoothInputDevice: Proxy object connected
08-16 12:25:28.243  3920  3920 D HidProfile: Bluetooth service connected
08-16 12:25:28.246  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:28.247  4244  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:25:28.251  1910  2061 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:28.251  4244  4244 D ObexServerSockets: Succeed to create listening sockets 
08-16 12:25:28.252  4244  4244 D ObexServerSockets0: startAccept()
08-16 12:25:28.252  4244  4244 D ObexServerSockets0: prepareForNewConnect()
,08-16 12:25:28.253   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:28.253  1362  1984 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 12:25:28.257   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 12:25:28.257  3920  3931 D BluetoothPan: onBluetoothStateChange on: true
,08-16 12:25:28.257  4244  4244 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 12:25:28.258  4244  4244 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 12:25:28.260  4244  4282 D ObexServerSockets0: Accepting socket connection...
,08-16 12:25:28.260   874   874 D BluetoothA2dp: Proxy object connected
,08-16 12:25:28.262  1362  1362 D BluetoothMap: Proxy object connected
08-16 12:25:28.262  1362  1362 D MapProfile: Bluetooth service connected
08-16 12:25:28.262  1362  1362 D BluetoothMap: getConnectedDevices()
08-16 12:25:28.263  3920  4281 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 12:25:28.265  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:25:28.265  4244  4283 D ObexServerSockets0: Accepting socket connection...
,08-16 12:25:28.266  1362  1362 D BluetoothA2dp: Proxy object connected
08-16 12:25:28.267  1362  1984 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 12:25:28.267  3920  3920 D BluetoothMap: Proxy object connected
,08-16 12:25:28.268  3920  3920 D MapProfile: Bluetooth service connected
08-16 12:25:28.268  3920  3920 D BluetoothMap: getConnectedDevices()
08-16 12:25:28.269  3920  3931 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 12:25:28.269  1362  1362 D BluetoothInputDevice: Proxy object connected
08-16 12:25:28.270  1362  1362 D HidProfile: Bluetooth service connected
,08-16 12:25:28.273  1362  2001 D BluetoothPan: onBluetoothStateChange on: true
,08-16 12:25:28.275  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 12:25:28.275  1362  1362 D PanProfile: Bluetooth service connected
,08-16 12:25:28.276   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 12:25:28.280  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:28.280  4244  4244 D BluetoothMapService: onReceive
08-16 12:25:28.280  4244  4244 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 12:25:28.280  4244  4244 D BluetoothMapService: STATE_ON
,08-16 12:25:28.285  3920  3920 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 12:25:28.285  3920  3920 D PanProfile: Bluetooth service connected
,08-16 12:25:28.285  3920  3920 D BluetoothA2dp: Proxy object connected
,08-16 12:25:28.293  3920  3920 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 12:25:28.305  3920  3920 D DockEventReceiver: finishStartingService: stopping service
,08-16 12:25:28.307  4244  4244 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 12:25:28.308  4244  4244 D ObexServerSockets0: prepareForNewConnect()
,08-16 12:25:28.309  1517  1517 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 12:25:28.326  1362  1362 D BluetoothPbap: Proxy object connected
,08-16 12:25:28.326  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-16 12:25:28.326  3920  3920 D BluetoothPbap: Proxy object connected
08-16 12:25:28.326  3920  3920 D PbapServerProfile: Bluetooth service connected
,08-16 12:25:28.356  4244  4288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 12:25:28.375  1362  2001 D BluetoothHeadset: Proxy object connected
,08-16 12:25:28.375  1362  1362 D HeadsetProfile: Bluetooth service connected
08-16 12:25:28.376   874   874 D BluetoothHeadset: Proxy object connected
08-16 12:25:28.376   874   874 D BluetoothHeadset: Proxy object connected
08-16 12:25:28.376  3920  3932 D BluetoothHeadset: Proxy object connected
08-16 12:25:28.377   874   874 D BluetoothHeadset: Proxy object connected
08-16 12:25:28.377  1910  2036 D BluetoothHeadset: Proxy object connected
08-16 12:25:28.381  3920  3920 D HeadsetProfile: Bluetooth service connected
08-16 12:25:28.384  4244  4292 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 12:25:28.386  4244  4292 I BtOppRfcommListener: Accept thread started.
,08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:28.663  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:28.670  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 12:25:28.673  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:25:28.673  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@adff08d added. We now have 8 listener(s)
,08-16 12:25:28.674  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:25:28.679   874  1922 D WifiService: setWifiEnabled: false pid=3836, uid=10000
,08-16 12:25:28.679   874  1922 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:25:28.691  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:28.692   874  1919 D WifiService: setWifiEnabled: true pid=3836, uid=10000
,08-16 12:25:28.692   874  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 12:25:28.709   874  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:28.726  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:28.733  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:28.742   874  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-16 12:25:28.743   874  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 12:25:28.744   874  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 12:25:28.744   874  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 12:25:28.745   874  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 12:25:28.745   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 12:25:28.745   874  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 12:25:28.759   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 12:25:28.759   874  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.26 rxSuccessRate=0.30 delta 1000 -> 1000
,08-16 12:25:28.760   874  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 12:25:28.760   372   872 D CommandListener: Setting iface cfg,
,08-16 12:25:28.768   874  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 12:25:28.768   874  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 12:25:28.769   874  1307 E native  : do suspend true
,08-16 12:25:28.783   874  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 12:25:28.783   874  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 12:25:28.784   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 12:25:28.784   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:28.792   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 12:25:28.854   874  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 12:25:28.856  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 12:25:28.983  2132  2617 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 12:25:29.299  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 12:25:29.342  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 12:25:29.343  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 12:25:29.347   874  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 12:25:29.361   874  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:25:29.361   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 12:25:29.362   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 12:25:29.380   874  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 12:25:29.398   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:29.399   874  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 12:25:29.409   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 12:25:29.433   874  4300 D DhcpClient: Receive thread started
,08-16 12:25:29.520   874  1307 E native  : do suspend false
,08-16 12:25:29.542   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 12:25:29.556   874  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 12:25:29.557   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 12:25:29.562   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 12:25:29.574   874  4300 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 12:25:29.576   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 12:25:29.581   372   872 D CommandListener: Setting iface cfg
,08-16 12:25:29.593   874  1878 D DhcpClient: Scheduling renewal in 86399s
,08-16 12:25:29.594   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 12:25:29.598   874  1307 E native  : do suspend true
,08-16 12:25:29.627   874  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 12:25:29.628   874  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 12:25:29.629   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 12:25:29.630   874  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 12:25:29.631   874  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 12:25:29.714  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 12:25:29.716   874  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 12:25:29.716   874  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 12:25:29.718   874  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 12:25:29.718  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 12:25:29.720   874  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 12:25:29.722   874  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 12:25:29.727  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 12:25:29.728  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 12:25:29.731  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@da3baf6 Bundle[{}]
,08-16 12:25:29.731  3836  3899 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 12:25:29.731  3836  3899 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 12:25:29.732  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 12:25:29.733  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 12:25:29.733  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 12:25:29.734  3836  3899 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 12:25:29.736   874  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 12:25:29.738  3836  3899 I System.out: Running OutgoingSocketThread
,08-16 12:25:29.739  3836  4303 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 427)
,08-16 12:25:29.741  3836  4303 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48604
,08-16 12:25:29.741  3836  4303 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 12:25:29.746   874  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 12:25:29.747   874  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 12:25:29.748   874  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 12:25:29.747   874  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-16 12:25:29.748   874  1309 D ConnectivityService:    accepting network in place of null
,08-16 12:25:29.749   874  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 12:25:29.749   874  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 12:25:29.758   874  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157512, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 12:25:29.788   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:29.818   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 12:25:29.824   874  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:815::200e
,08-16 12:25:29.829   874  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 12:25:29.831   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:29.838   874  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 12:25:29.854   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:29.865  3836  3836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:29.868  3836  3836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:29.872  1988  1988 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-16 12:25:29.877  1739  1739 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 12:25:29.883  1739  1739 D SystemUpdateService: onCreate
,08-16 12:25:29.886  1739  1739 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 12:25:29.892   874  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 10:25:29 GMT], X-Android-Received-Millis=[1471343129892], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471343129865]}
,08-16 12:25:29.894   874  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 12:25:29.895   874  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-16 12:25:29.895   874  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 12:25:29.899   874  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 12:25:29.906  1739  4310 I SystemUpdateService: active receiver: enabled
,08-16 12:25:29.909  1739  1739 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 12:25:29.911  1739  2447 I iu.UploadsManager: num queued entries: 0
,08-16 12:25:29.912  1739  2447 I iu.UploadsManager: num updated entries: 0
,08-16 12:25:29.922  1739  1739 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 12:25:29.923  1739  1739 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 12:25:29.926  1739  4310 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 12:25:29.927  4014  4014 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 12:25:29.933  1739  4314 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 12:25:29.933  1739  4314 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 12:25:29.936  1739  4314 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 12:25:29.937  4014  4014 D SprintDMHelper: simOperator: 
,08-16 12:25:29.937  4014  4014 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 12:25:29.940  1739  2447 I iu.SyncManager: NEXT; no task
,08-16 12:25:29.940  1739  4310 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 12:25:29.940  1739  4310 I SystemUpdateService: now status is 0 (complete)
08-16 12:25:29.940  1739  4310 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 12:25:29.940  1739  4310 I SystemUpdateService: file has been verified
,08-16 12:25:29.941  1739  4310 I SystemUpdateService: OTA package size = 12249756
,08-16 12:25:29.946  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:29.948  1517  1517 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 12:25:29.957  1739  4310 I SystemUpdateService: showing system update notification
,08-16 12:25:30.001  1739  1739 D SystemUpdateService: onDestroy
,08-16 12:25:30.008  1517  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 12:25:30.008  1517  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 12:25:30.008  1517  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 12:25:30.008  1517  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 12:25:30.034  1739  4314 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-16 12:25:30.061  3971  4316 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 12:25:30.741  3836  3899 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 428)
,08-16 12:25:30.742  3836  3899 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 428)
,08-16 12:25:30.751  3836  3899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 433)
,08-16 12:25:30.753  3836  3899 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 12:25:30.754  3836  3899 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-16 12:25:30.758  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.758  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b29242 added. We now have 2 listener(s)
,08-16 12:25:30.760  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.760  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:30.761  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:30.761  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.761  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a49253 added. We now have 9 listener(s)
08-16 12:25:30.761  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:25:30.762  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:25:30.766  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:30.776  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:30.778  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:30.779  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:25:30.779  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.779  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e80889 added. We now have 3 listener(s)
,08-16 12:25:30.781  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.781  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:25:30.781  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:25:30.782  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 12:25:30.782  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85b908e added. We now have 10 listener(s)
08-16 12:25:30.782  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.782  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:30.782  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:30.782  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:30.782  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:30.782  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.782  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:30.783  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.783  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b29242 removed from the list
08-16 12:25:30.783  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.783  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a49253 removed from the list
08-16 12:25:30.784  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:30.788  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:30.788  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:30.788  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:30.789  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.789  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.790  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:30.790  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:30.790  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.790  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a49253 not in the list
,08-16 12:25:30.790  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.790  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.791  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:30.791  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:30.791  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:30.791  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85b908e removed from the list
08-16 12:25:30.792  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:30.792  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.792  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.792  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.792  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e80889 removed from the list
,08-16 12:25:30.793  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.793  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc00af added. We now have 2 listener(s)
08-16 12:25:30.795  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.795  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:30.795  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:25:30.795  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.795  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3bccbc added. We now have 9 listener(s)
08-16 12:25:30.795  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.796  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 12:25:30.800  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:30.805  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:30.808  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.808  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 12:25:30.809  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.810  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@884279a added. We now have 3 listener(s)
08-16 12:25:30.810  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:30.813  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:30.815  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:25:30.816  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:30.816  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 12:25:30.816  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.817  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f71f8cb added. We now have 10 listener(s)
08-16 12:25:30.817  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 12:25:30.817  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:30.818  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:25:30.818  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 12:25:30.818  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:30.818  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:25:30.824  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:25:30.824  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:25:30.828  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 12:25:30.828   874  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-16 12:25:30.829  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:25:30.829  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:25:30.832  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:25:30.833  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:25:30.833  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:25:30.833  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:30.837  4244  4284 D BtGatt.GattService: registerClient() - UUID=1f8fd2ca-8d2c-4dcc-a443-ad883f2978ad
,08-16 12:25:30.838  4244  4260 D BtGatt.GattService: onClientRegistered() - UUID=1f8fd2ca-8d2c-4dcc-a443-ad883f2978ad, clientIf=5
,08-16 12:25:30.839  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:25:30.841  4244  4255 D BtGatt.GattService: start scan with filters
,08-16 12:25:30.844  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:25:30.844  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:30.845  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:25:30.845  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:25:30.845  4244  4263 D BtGatt.ScanManager: handling starting scan
,08-16 12:25:30.848  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:25:30.848  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:30.848  4244  4263 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4bd662a
,08-16 12:25:30.849  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 12:25:30.850  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:25:30.853  3836  3899 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 12:25:30.853  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:30.853  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 12:25:30.853  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:30.853  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:25:30.854  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 12:25:30.854  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:25:30.854  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:25:30.854  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 12:25:30.854  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:25:30.854  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 12:25:30.855  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:30.857  4244  4255 D BtGatt.GattService: stopScan() - queue size =1
,08-16 12:25:30.858  4244  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 12:25:30.858  4244  4260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 12:25:30.858  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.859  4244  4263 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 12:25:30.859  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 12:25:30.860  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:30.860  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 12:25:30.860  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 12:25:30.860  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 12:25:30.861  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 12:25:30.861  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 12:25:30.861  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:30.861  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:30.862  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:30.866  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 12:25:30.866  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:30.866  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-16 12:25:30.870  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:30.870  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:25:30.870  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:30.871  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:25:30.871  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:30.871  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:30.872  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.873  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dc00af removed from the list
,08-16 12:25:30.873  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:30.874  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3bccbc removed from the list
,08-16 12:25:30.874  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:30.874  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.880  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.880  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 12:25:30.882  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:30.882  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:25:30.882  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.882  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3bccbc not in the list
08-16 12:25:30.882  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.883  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.884  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:30.884  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:30.884  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.884  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f71f8cb removed from the list
08-16 12:25:30.884  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 12:25:30.884  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:30.884  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.884  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.885  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.885  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 12:25:30.885  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@884279a removed from the list
08-16 12:25:30.885  4244  4263 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:25:30.885  4244  4263 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 12:25:30.886  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.886  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62556a7 added. We now have 2 listener(s)
08-16 12:25:30.888  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.888  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:25:30.888  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:30.888  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.888  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76f754 added. We now have 9 listener(s)
08-16 12:25:30.888  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.889  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:25:30.892  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:30.897  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 12:25:30.902  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 12:25:30.903  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:25:30.903  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 12:25:30.903  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a980ff2 added. We now have 3 listener(s)
,08-16 12:25:30.905  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:30.907  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 12:25:30.909  4244  4260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:30.909  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.909  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 12:25:30.909  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 12:25:30.909  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:30.910  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.910  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec6b643 added. We now have 10 listener(s)
08-16 12:25:30.910  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.910  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:30.911  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 12:25:30.911  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:25:30.911  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:25:30.911  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:30.911  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 12:25:30.914  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 12:25:30.914  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 12:25:30.918  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 12:25:30.918  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:30.918  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:25:30.919  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:25:30.919  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 12:25:30.922  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 12:25:30.923  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:25:30.923  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:25:30.923  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:30.926  4244  4284 D BtGatt.GattService: registerClient() - UUID=9553a8f9-a50e-4639-8f36-a6ca3f0e2e7f
,08-16 12:25:30.926  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:25:30.926  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.926  4244  4260 D BtGatt.GattService: onClientRegistered() - UUID=9553a8f9-a50e-4639-8f36-a6ca3f0e2e7f, clientIf=5
08-16 12:25:30.926  3836  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 12:25:30.927  4244  4263 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:25:30.927  4244  4255 D BtGatt.GattService: start scan with filters
,08-16 12:25:30.930  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 12:25:30.930  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:30.930  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 12:25:30.930  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 12:25:30.932  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:30.932  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:25:30.933  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 12:25:30.933  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 12:25:30.933  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:30.933  4244  4263 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 12:25:30.934  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 12:25:30.937  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:30.937  3836  3899 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 12:25:30.938  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 12:25:30.938  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 12:25:30.938  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:30.938  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 12:25:30.938  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.939  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 12:25:30.939  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.939  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62556a7 removed from the list
,08-16 12:25:30.939  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:30.939  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76f754 removed from the list
,08-16 12:25:30.939  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:30.939  4244  4260 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
,08-16 12:25:30.939  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:30.939  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:30.940  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:30.940  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 12:25:30.940  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 12:25:30.940  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:30.941  4244  4263 D BtGatt.ScanManager: handling starting scan
,08-16 12:25:30.941  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 12:25:30.941  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 12:25:30.941  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 12:25:30.941  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a76f754 not in the list
,08-16 12:25:30.941  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 12:25:30.941  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 12:25:30.941  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 12:25:30.941  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 12:25:30.942  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:25:30.942  3836  3899 D BluetoothAdapter: STATE_ON
,08-16 12:25:30.943  4244  4254 D BtGatt.GattService: stopScan() - queue size =1
08-16 12:25:30.943  4244  4273 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 12:25:30.944  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:25:30.944  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:30.944  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:25:30.944  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:25:30.944  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:25:30.945  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:30.945  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:25:30.945  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:30.945  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:30.946  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.947  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:30.947  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:30.947  4244  4260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 12:25:30.947  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.947  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.947  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:30.947  4244  4263 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 12:25:30.947  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:30.947  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:30.948  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec6b643 removed from the list
08-16 12:25:30.948  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:30.948  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.948  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:30.948  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.948  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a980ff2 removed from the list
08-16 12:25:30.949  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.949  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@594739f added. We now have 2 listener(s)
08-16 12:25:30.951  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnect,ivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.951  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:30.951  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:30.951  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.951  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769dcec added. We now have 9 listener(s)
08-16 12:25:30.951  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.952  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:25:30.953  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 12:25:30.953  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.953  4244  4263 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:25:30.954  4244  4263 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 12:25:30.954  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:30.958  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:30.960  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:30.961  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:25:30.961  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:30.961  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285ab4a added. We now have 3 listener(s)
08-16 12:25:30.963  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:30.964  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:30.964  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:30.964  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:30.965  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:30.965  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSe,ttings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256aabb added. We now have 10 listener(s)
08-16 12:25:30.965  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:30.965  4244  4260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:30.965  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.965  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:30.965  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:30.965  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 12:25:30.965  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 12:25:30.965  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:30.965  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 12:25:30.968  3836  3899 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 12:25:30.968  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 12:25:30.971  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 12:25:30.971  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.973  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 12:25:30.973  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 12:25:30.973  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 12:25:30.976  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 12:25:30.977  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 12:25:30.977  3836  3899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 12:25:30.977  3836  3899 D BluetoothAdapter: STATE_ON
08-16 12:25:30.977  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:25:30.977  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.978  4244  4263 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:25:30.979  4244  4255 D BtGatt.GattService: registerClient() - UUID=26b5866a-7034-4a1f-90fd-570a84708f88
08-16 12:25:30.980  4244  4260 D BtGatt.GattService: onClientRegistered() - UUID=26b5866a-7034-4a1f-90fd-570a84708f88, clientIf=5
08-16 12:25:30.980  3836  3848 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 12:25:30.980  4244  4254 D BtGatt.GattService: start scan with filters
08-16 12:25:30.983  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 12:25:30.983  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:25:30.983  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 12:25:30.984  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.984  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 12:25:30.984  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 12:25:30.984  4244  4263 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 12:25:30.987  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:25:30.987  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 12:25:30.987  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 12:25:30.989  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 12:25:30.989  4244  4260 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 12:25:30.990  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.991  4244  4263 D BtGatt.ScanManager: handling starting scan
08-16 12:25:30.993  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:30.994  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:30.994  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:30.994  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:30.994  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.994  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 12:25:30.994  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:30.994  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@594739f removed from the list
08-16 12:25:30.994  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.994  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769dcec removed from the list
08-16 12:25:30.994  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:30.994  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:30.995  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.995  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 12:25:30.995  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:30.995  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 12:25:30.996  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:30.996  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:30.996  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:30.996  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769dcec not in the list
08-16 12:25:30.996  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 12:25:30.996  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 12:25:30.996  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 12:25:30.996  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 12:25:30.997  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 12:25:30.997  3836  3899 D BluetoothAdapter: STATE_ON
08-16 12:25:30.997  4244  4260 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 12:25:30.997  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:30.997  4244  4263 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 12:25:30.998  4244  4254 D BtGatt.GattService: stopScan() - queue size =1
08-16 12:25:30.998  4244  4284 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 12:25:30.998  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 12:25:30.999  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 12:25:30.999  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 12:25:30.999  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 12:25:30.999  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 12:25:31.000  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:31.000  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 12:25:31.000  3836  3899 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 12:25:31.000  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 12:25:31.000  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.001  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:31.001  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:31.002  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:31.002  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:31.002  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256aabb removed from the list
08-16 12:25:31.002  3836  3836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 12:25:31.002  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:31.002  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:31.002  3836  3836 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 12:25:31.002  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.002  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:31.002  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285ab4a removed from the list
08-16 12:25:31.003  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:31.003  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b3797 added. We now have 2 listener(s)
08-16 12:25:31.003  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 12:25:31.003  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:31.003  4244  4263 D BtGatt.ScanManager: Starting BLE batch scan
08-16 12:25:31.004  4244  4263 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 12:25:31.004  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:31.005  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:31.005  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:31.005  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:31.005  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f0dd84 added. We now have 9 listener(s)
08-16 12:25:31.005  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:31.005  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 12:25:31.015  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 12:25:31.018  4244  4260 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 12:25:31.018  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 12:25:31.020  3836  3899 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 12:25:31.023  3836  3899 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 12:25:31.023  3836  3899 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 12:25:31.023  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 12:25:31.025  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 12:25:31.025  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 12:25:31.026  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:31.024  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57059a2 added. We now have 3 listener(s)
08-16 12:25:31.029  3836  3836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 12:25:31.030  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 12:25:31.030  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 12:25:31.031  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 12:25:31.031  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 12:25:31.031  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171b633 added. We now have 10 listener(s)
08-16 12:25:31.031  3836  3899 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 12:25:31.031  3836  3899 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 12:25:31.031  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:31.031  3836  3899 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 12:25:31.031  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:31.032  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:31.032  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 12:25:31.032  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:31.032  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73b3797 removed from the list
08-16 12:25:31.032  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:31.032  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f0dd84 removed from the list
08-16 12:25:31.032  3836  3899 D io.jxcore.node.ConnectivityMonitor: stop
08-16 12:25:31.032  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.033  4244  4260 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 12:25:31.033  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:31.033  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:31.033  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.033  4244  4263 D BtGatt.ScanManager: stopping BLe Batch
08-16 12:25:31.034  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:31.034  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:31.034  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:31.034  3836  3899 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f0dd84 not in the list
08-16 12:25:31.034  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:31.034  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.035  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 12:25:31.035  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 12:25:31.035  3836  3899 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 12:25:31.035  3836  3899 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@171b633 removed from the list
08-16 12:25:31.035  3836  3899 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 12:25:31.035  3836  3899 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 12:25:31.035  3836  3899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 12:25:31.035  3836  3899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 12:25:31.035  3836  3899 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57059a2 removed from the list
08-16 12:25:31.036  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 12:25:31.036  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 12:25:31.036  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 12:25:31.036  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 12:25:31.036  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 12:25:31.037  3836  3899 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 12:25:31.039  4244  4260 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 12:25:31.039  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:31.039  4244  4263 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 12:25:31.042  3836  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
08-16 12:25:31.042  3836  4322 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
08-16 12:25:31.042  3836  4322 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 12:25:31.043  4244  4260 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 12:25:31.043  4244  4260 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 12:25:31.045  3836  4323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: My test thread name)
08-16 12:25:31.045  3836  4323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: My test thread name)
08-16 12:25:31.045  3836  4323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 12:25:31.046  3836  3899 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 12:25:31.046  3836  3899 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 12:25:31.047  3836  3899 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 12:25:31.047  3836  3899 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 12:25:31.047  3836  3899 D com.test.thalitest.ThaliTestRunner: Total duration: 23005 ms
08-16 12:25:31.048  3836  3899 I jxcore-log: Total number of executed tests:  80
08-16 12:25:31.048  3836  3899 I jxcore-log: 
08-16 12:25:31.048  3836  3899 I jxcore-log: Number of passed tests:  80
08-16 12:25:31.048  3836  3899 I jxcore-log: 
08-16 12:25:31.048  3836  3899 I jxcore-log: Number of failed tests:  0
08-16 12:25:31.048  3836  3899 I jxcore-log: 
08-16 12:25:31.049  3836  3899 I jxcore-log: Number of ignored tests:  0
08-16 12:25:31.049  3836  3899 I jxcore-log: 
08-16 12:25:31.049  3836  3899 I jxcore-log: Total duration:  23005
08-16 12:25:31.049  3836  3899 I jxcore-log: 
08-16 12:25:31.050  3836  3899 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 12:25:31.050  3836  3899 I jxcore-log: 
08-16 12:25:31.053  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.053  3836  3899 I jxcore-log: 
08-16 12:25:31.056  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.056  3836  3899 I jxcore-log: 
08-16 12:25:31.057  3836  3836 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 12:25:31.058  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.058  3836  3899 I jxcore-log: 
08-16 12:25:31.058  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.058  3836  3899 I jxcore-log: 
08-16 12:25:31.059  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.059  3836  3899 I jxcore-log: 
08-16 12:25:31.061  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.061  3836  3899 I jxcore-log: 
08-16 12:25:31.062  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.062  3836  3899 I jxcore-log: 
08-16 12:25:31.063  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.063  3836  3899 I jxcore-log: 
08-16 12:25:31.064  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.064  3836  3899 I jxcore-log: 
08-16 12:25:31.065  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.065  3836  3899 I jxcore-log: 
08-16 12:25:31.066  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.066  3836  3899 I jxcore-log: 
08-16 12:25:31.066  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:25:31.066  3836  3899 I jxcore-log: 
08-16 12:25:31.067  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.067  3836  3899 I jxcore-log: 
08-16 12:25:31.068  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.068  3836  3899 I jxcore-log: 
08-16 12:25:31.068  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.068  3836  3899 I jxcore-log: 
08-16 12:25:31.069  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.069  3836  3899 I jxcore-log: 
08-16 12:25:31.069  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.069  3836  3899 I jxcore-log: 
08-16 12:25:31.070  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.070  3836  3899 I jxcore-log: 
08-16 12:25:31.071  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.071  3836  3899 I jxcore-log: 
08-16 12:25:31.071  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.071  3836  3899 I jxcore-log: 
08-16 12:25:31.072  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.072  3836  3899 I jxcore-log: 
08-16 12:25:31.073  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.073  3836  3899 I jxcore-log: 
08-16 12:25:31.074  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.074  3836  3899 I jxcore-log: 
08-16 12:25:31.074  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 12:25:31.074  3836  3899 I jxcore-log: 
08-16 12:25:31.075  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.075  3836  3899 I jxcore-log: 
08-16 12:25:31.076  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 12:25:31.076  3836  3899 I jxcore-log: 
08-16 12:25:31.077  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.077  3836  3899 I jxcore-log: 
,08-16 12:25:31.078  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.078  3836  3899 I jxcore-log: 
08-16 12:25:31.078  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.078  3836  3899 I jxcore-log: 
08-16 12:25:31.079  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.079  3836  3899 I jxcore-log: 
08-16 12:25:31.079  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.079  3836  3899 I jxcore-log: 
08-16 12:25:31.080  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 12:25:31.080  3836  3899 I jxcore-log: 
,08-16 12:25:31.367  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:25:31.370  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:25:31.370  3836  3899 I jxcore-log: 
,08-16 12:25:31.448  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:25:31.451  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:25:31.451  3836  3899 I jxcore-log: 
,08-16 12:25:31.502  3836  3836 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 12:25:31.505  3836  3899 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 12:25:31.505  3836  3899 I jxcore-log: 
,08-16 12:25:31.703  4324  4324 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 12:25:31.708  4324  4324 D AndroidRuntime: CheckJNI is OFF
,08-16 12:25:31.750  4324  4324 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 12:25:31.797  4324  4324 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 12:25:31.820  4324  4324 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 12:25:31.832   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 12:25:31.833   874   887 I ActivityManager: Killing 3836:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 12:25:31.952   874   898 W PackageSettings: Skipping PackageSetting{361ce8f com.example.hello/10273} due to missing metadata
,08-16 12:25:31.953   874   885 D GraphicsStats: Buffer count: 2
,08-16 12:25:31.954   874   884 I WindowState: WIN DEATH: Window{ebb73f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 12:25:31.954   874  1308 D WifiService: Client connection lost with reason: 4
,08-16 12:25:31.996   874   898 I art     : Starting a blocking GC Explicit
,08-16 12:25:32.003   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 12:25:32.004   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 12:25:32.004   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-16 12:25:32.004   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 12:25:32.004   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.004   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.004   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 12:25:32.004   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 12:25:32.005   874   887 I ActivityManager:   Force finishing activity ActivityRecord{169c13c u0 com.test.thalitest/.MainActivity t2}
,08-16 12:25:32.016   874   885 W ActivityManager: Spurious death for ProcessRecord{7125864 0:com.test.thalitest/u0a0}, curProc for 3836: null
,08-16 12:25:32.043   874   898 I art     : Explicit concurrent mark sweep GC freed 13839(965KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 686us total 46.668ms
,08-16 12:25:32.079   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 12:25:32.087  4324  4324 I art     : System.exit called, status: 0
08-16 12:25:32.087  4324  4324 I AndroidRuntime: VM exiting with result code 0.
,08-16 12:25:32.093   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 12:25:32.123   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 12:25:32.134   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 12:25:32.137  4244  4244 D BluetoothMapAppObserver: onReceive
08-16 12:25:32.137  4244  4244 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 12:25:32.138  2132  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 12:25:32.142  3670  3670 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 12:25:32.148  1851  1851 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 12:25:32.175  1910  1910 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 12:25:32.178   874  1954 I ActivityManager: Start proc 4338:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-16 12:25:32.160  1851  4337 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 12:25:32.193   874  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-16 12:25:32.194  1851  4337 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-16 12:25:32.194  1851  4337 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-16 12:25:32.194  1851  4337 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-16 12:25:32.194  1851  4337 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-16 12:25:32.195  1851  4337 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-16 12:25:32.195  1851  4337 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-16 12:25:32.208  1851  4337 I Decoder : createOrResetDecoder
,08-16 12:25:32.218  4338  4338 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 12:25:32.221   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 12:25:32.223  1517  1517 I ConfigService: onCreate
,08-16 12:25:32.226  1517  4350 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 12:25:32.226  1517  4350 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 12:25:32.226  1517  4350 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-16 12:25:32.227  1517  4350 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 12:25:32.238  1851  4337 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 12:25:32.240   874  1390 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3836 uid 10000
08-16 12:25:32.242  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-16 12:25:32.258   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 12:25:32.259   874   886 E PackageManager: Failed to write settings, restoring backup
08-16 12:25:32.259   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 12:25:32.259   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 12:25:32.259   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 12:25:32.259   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 12:25:32.259   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 12:25:32.259   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.259   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.259   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.262   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-16 12:25:32.262   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 12:25:32.262   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:32.262   874   887 E DropBoxManagerService: 	... 13 more
,08-16 12:25:32.277  1926  1994 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 12:25:32.277  1851  4337 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 12:25:32.291  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 12:25:32.291  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 12:25:32.295   874  1922 I ActivityManager: Start proc 4354:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 12:25:32.296  1926  1994 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 12:25:32.296  1926  1994 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1926
08-16 12:25:32.296  1926  1994 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.296  1926  1994 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.298   874  4359 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:25:32.298   874  4359 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:32.298   874  4359 E DropBoxManagerService: 	... 5 more
,08-16 12:25:32.298   874  2716 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 12:25:32.297  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 12:25:32.299  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 12:25:32.303  1926  1994 I Process : Sending signal. PID: 1926 SIG: 9
,08-16 12:25:32.312  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-16 12:25:32.312  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 12:25:32.319  1851  4337 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 12:25:32.319  1851  4337 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 12:25:32.319  1851  4337 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 12:25:32.319  1851  4337 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 12:25:32.319  1851  4337 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 12:25:32.319  1851  4337 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 12:25:32.337  4338  4338 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 12:25:32.346  4338  4352 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.346  4338  4352 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.347  4338  4352 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.349  4338  4368 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 12:25:32.353   874  1954 D GraphicsStats: Buffer count: 1
,08-16 12:25:32.354   874  2716 I WindowState: WIN DEATH: Window{f7a61f6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 12:25:32.391   874  1917 I ActivityManager: Start proc 4370:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 12:25:32.392   874   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1926) has died
,08-16 12:25:32.392   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 12:25:32.393   874   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 12:25:32.412  4338  4352 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 12:25:32.416   874   887 I ActivityManager: Start proc 4382:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 12:25:32.438  4338  4368 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.438  4338  4368 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.438  4338  4368 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 12:25:32.438  4338  4368 E AndroidRuntime: Process: android.process.acore, PID: 4338
08-16 12:25:32.438  4338  4368 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.438  4338  4368 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 12:25:32.440  4338  4368 I Process : Sending signal. PID: 4338 SIG: 9
,08-16 12:25:32.441   874  4395 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:25:32.441   874  4395 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:32.441   874  4395 E DropBoxManagerService: 	... 5 more
,08-16 12:25:32.448  4370  4370 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 12:25:32.456   279   279 E lowmemorykiller: Error writing /proc/4338/oom_score_adj; errno=22
,08-16 12:25:32.457   279   279 E lowmemorykiller: Error writing /proc/4338/oom_score_adj; errno=22
,08-16 12:25:32.459  4382  4382 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:32.459  4382  4382 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 12:25:32.459  4382  4382 D AndroidRuntime: Shutting down VM
,08-16 12:25:32.464  4382  4382 E AndroidRuntime: FATAL EXCEPTION: main
08-16 12:25:32.464  4382  4382 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4382
08-16 12:25:32.464  4382  4382 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 12:25:32.464  4382  4382 E AndroidRuntime: 	... 10 more
,08-16 12:25:32.465   874  1954 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 12:25:32.466  4382  4382 I Process : Sending signal. PID: 4382 SIG: 9
,08-16 12:25:32.467   874  4397 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:25:32.467   874  4397 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:32.467   874  4397 E DropBoxManagerService: 	... 5 more
,08-16 12:25:32.475  1517  1517 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 12:25:32.477  1517  1517 D AndroidRuntime: Shutting down VM
08-16 12:25:32.478  1517  1517 E AndroidRuntime: FATAL EXCEPTION: main
08-16 12:25:32.478  1517  1517 E AndroidRuntime: Process: com.google.process.gapps, PID: 1517
08-16 12:25:32.478  1517  1517 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 12:25:32.478  1517  1517 E AndroidRuntime: 	... 8 more
08-16 12:25:32.482   874  4400 E DropBoxManagerService: Can't write: system_app_crash
08-16 12:25:32.482   874  4400 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at libcore.,io.Posix.open(Native Method)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 12:25:32.482   874  4400 E DropBoxManagerService: 	... 5 more
08-16 12:25:32.483   874  1919 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4382) has died
08-16 12:25:32.485   874  1919 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 12:25:32.489   874  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-16 12:25:32.501   874   887 I ActivityManager: Start proc 4402:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 12:25:32.505  1517  1517 I Process : Sending signal. PID: 1517 SIG: 9
08-16 12:25:32.507   279   279 E lowmemorykiller: Error writing /proc/4338/oom_score_adj; errno=22
08-16 12:25:32.514   279   279 E lowmemorykiller: Error writing /proc/4338/oom_score_adj; errno=22
,08-16 12:25:32.528   874  1919 I ActivityManager: Process android.process.acore (pid 4338) has died
,08-16 12:25:32.528   874  1919 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-16 12:25:32.533   874  1308 D WifiService: Client connection lost with reason: 4
,08-16 12:25:32.537  1739  4409 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@c4e78f0
,08-16 12:25:32.538   874  1922 I ActivityManager: Process com.google.process.gapps (pid 1517) has died
,08-16 12:25:32.539   874  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-16 12:25:32.539   874  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
08-16 12:25:32.539   874  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-16 12:25:32.539   874  1922 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,08-16 12:25:32.555   874  1954 I ActivityManager: Start proc 4415:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-16 12:25:32.556  1739  1739 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-16 12:25:32.572  4402  4402 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 12:25:32.572  4402  4402 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```
