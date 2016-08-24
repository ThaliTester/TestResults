#### Test 82203060198550b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 14:03:50.728  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:03:50.743  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:03:50.750  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 14:03:50.828  1516  3149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 14:03:50.829  1516  3149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 14:03:50.829  1516  3149 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:03:50.829  1516  3149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 14:03:50.880  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 14:03:50.880  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 14:03:50.881  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-24 14:03:51.404  4015  4015 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 14:03:51.408  4015  4015 D AndroidRuntime: CheckJNI is OFF
08-24 14:03:51.444  4015  4015 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 14:03:51.486  4015  4015 I Radio-JNI: register_android_hardware_Radio DONE
08-24 14:03:51.505  4015  4015 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:03:51.509   870  1697 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:03:51.567  2020  3964 W SearchService: Abort, client detached.
08-24 14:03:51.568   870  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
08-24 14:03:51.572  2020  2020 I HotwordDetector: Closing mic
08-24 14:03:51.573  2020  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@12b86d6
08-24 14:03:51.574  2020  2350 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 14:03:51.575  4015  4015 D AndroidRuntime: Shutting down VM
08-24 14:03:51.593   870  1957 I ActivityManager: Start proc 4024:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 14:03:51.632   374  2352 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 14:03:51.634   374  2352 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 14:03:51.639   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 14:03:51.643  2020  2349 I MicroRecognitionRnrImpl: Detection finished
08-24 14:03:51.643  2020  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 14:03:51.676  4024  4024 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 14:03:51.700  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 14:03:51.707  4024  4024 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3033-3035)
08-24 14:03:51.707  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:03:51.724  4024  4024 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c264bbd}
08-24 14:03:51.724  4024  4024 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:03:51.724  4024  4024 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:03:51.730  4024  4024 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 14:03:51.733  4024  4024 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 14:03:51.755  4024  4024 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 14:03:51.764  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:03:51.764  4024  4024 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:03:51.764  4024  4024 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:03:51.764  4024  4024 I Adreno  : Build Date                       : 10/20/15
08-24 14:03:51.764  4024  4024 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:03:51.764  4024  4024 I Adreno  : Local Branch                     : M14
08-24 14:03:51.764  4024  4024 I Adreno  : Remote Branch                    : 
08-24 14:03:51.764  4024  4024 I Adreno  : Remote Branch                    : 
08-24 14:03:51.764  4024  4024 I Adreno  : Reconstruct Branch               : 
,08-24 14:03:51.835   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5b1e21:true
,08-24 14:03:51.894  4024  4024 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:03:51.911  4024  4024 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 14:03:52.025  4024  4063 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 14:03:52.036  4024  4049 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 14:03:52.068  4024  4063 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 14:03:52.148   870   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +568ms
,08-24 14:03:52.154  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-24 14:03:52.212  4024  4024 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4024
,08-24 14:03:52.403   870  1957 I ActivityManager: Killing 2862:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 14:03:52.414  4024  4024 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:03:52.461   870  1957 I ActivityManager: Killing 3156:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-24 14:03:52.555  4024  4065 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1717569232
,08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:03:52.559  4024  4065 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667e458 added. We now have 1 listener(s)
,08-24 14:03:52.563  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 14:03:52.563  4024  4065 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 14:03:52.564  4024  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:03:52.564  4024  4065 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-24 14:03:52.568  4024  4065 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9213a17 added. We now have 1 listener(s)
,08-24 14:03:52.569  4024  4065 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:03:52.578   870  1314 D WifiService: New client listening to asynchronous messages
,08-24 14:03:52.579  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 14:03:52.579  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 14:03:52.579  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:03:52.580  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:03:52.580  4024  4065 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 14:03:52.584  4024  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:03:52.584  4024  4065 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-24 14:03:52.591  4024  4065 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:03:52.591  4024  4065 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 14:03:52.591  4024  4065 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 14:03:52.591  4024  4065 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:03:52.592  4024  4065 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:03:52.594  4024  4024 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:03:52.596  4024  4024 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:03:52.619  4024  4024 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:03:53.201   870  1873 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 14:03:53.512  4024  4074 W jxcore-log: Initializing JXcore engine
,08-24 14:03:53.512  4024  4074 W jxcore-log: JXcore engine is ready
,08-24 14:03:53.558  4074  4074 W Thread-373: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-24 14:03:53.558  4074  4074 W Thread-373: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10794]" dev="sockfs" ino=10794 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 14:03:53.558  4074  4074 W Thread-373: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 14:03:53.558  4074  4074 W Thread-373: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28928]" dev="sockfs" ino=28928 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 14:03:53.569  4024  4074 W jxcore-log: Starting JXcore engine
,08-24 14:03:53.647  4024  4074 W jxcore-log: Platform android
08-24 14:03:53.647  4024  4074 W jxcore-log: 
,08-24 14:03:53.647  4024  4074 W jxcore-log: Process ARCH arm
08-24 14:03:53.647  4024  4074 W jxcore-log: 
,08-24 14:03:53.902  4024  4074 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:03:53.902  4024  4074 I jxcore-log: 
,08-24 14:03:53.902  4024  4074 W jxcore-log: JXcore engine is started
,08-24 14:03:53.907  4024  4065 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:03:53.910  4024  4024 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 14:04:00.160  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:04:00.161  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 14:04:00.213  1516  3149 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 14:04:00.214  1516  3149 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 14:04:00.215  1516  3149 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 14:04:00.216  1516  3149 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:04:00.246  3726  4083 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 14:04:00.246  3726  4083 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jdm.a(PG:82)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jcs.o(PG:406)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jcn.a(PG:1379)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jcs.i(PG:143)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at blb.a(PG:3937)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at czp.a(PG:18188)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at czp.a(PG:9081)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at czq.run(PG:1686)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:04:00.246  3726  4083 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jdj.a(PG:4091)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jdj.a(PG:1125)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jdm.a(PG:77)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	... 12 more
08-24 14:04:00.246  3726  4083 E HttpOperation: Caused by: faj: BadAuthentication
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at fal.a(PG:38)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	at jdj.a(PG:4089)
08-24 14:04:00.246  3726  4083 E HttpOperation: 	... 14 more
,08-24 14:04:00.299  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 14:04:00.299  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 14:04:00.299  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 14:04:00.299  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 14:04:00.311  3726  4083 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 14:04:00.311  3726  4083 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jdm.a(PG:82)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jcs.o(PG:406)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jcn.a(PG:1379)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jcs.i(PG:143)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at hec.a(PG:42)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at hee.a(PG:102)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at czr.a(PG:65)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at kka.a(PG:108)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at czp.a(PG:19176)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at czp.a(PG:9081)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at czq.run(PG:1686)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:04:00.311  3726  4083 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jdj.a(PG:4091)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jdj.a(PG:1125)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jdm.a(PG:77)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	... 15 more
08-24 14:04:00.311  3726  4083 E HttpOperation: Caused by: faj: BadAuthentication
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at fal.a(PG:38)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	at jdj.a(PG:4089)
08-24 14:04:00.311  3726  4083 E HttpOperation: 	... 17 more
,08-24 14:04:00.311  3726  4083 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 14:04:00.311  3726  4083 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at hec.a(PG:42)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at hee.a(PG:102)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at czr.a(PG:65)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at kka.a(PG:108)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	... 15 more
08-24 14:04:00.311  3726  4083 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at fal.a(PG:38)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 14:04:00.311  3726  4083 E ExperimentLoader: 	... 17 more
,08-24 14:04:00.377  4024  4074 E jxcore  : Error!: syntax error
08-24 14:04:00.377  4024  4074 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:04:00.384  4024  4024 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-24 14:04:00.385  4024  4024 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:04:00.389   280   389 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (260 us)
,08-24 14:04:00.424  4024  4024 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 14:04:00.425  4024  4024 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 14:04:00.426  4024  4065 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 41ms. Plugin should use CordovaInterface.getThreadPool().
,08-24 14:04:00.438   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 130481, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 14:04:00.442   870  1959 I ActivityManager: Killing 3597:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-24 14:04:00.446  4024  4024 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-24 14:04:00.446  4024  4024 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 14:04:00.446  4024  4024 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-24 14:04:00.446  4024  4024 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-24 14:04:00.446  4024  4024 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:04:00.446  4024  4024 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:04:00.446  4024  4024 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:04:00.446  4024  4024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:04:00.447  4024  4024 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@667e458 removed from the list
08-24 14:04:00.447  4024  4024 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:04:00.447  4024  4024 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9213a17 removed from the list
08-24 14:04:00.447  4024  4024 D io.jxcore.node.ConnectivityMonitor: stop
,08-24 14:04:00.447  4024  4024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-24 14:04:00.491  4024  4024 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-24 14:04:00.544  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-24 14:04:00.610  2020  4090 I MicroRecognitionRnrImpl: Starting detection.
,08-24 14:04:00.611  2020  4091 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@1a65d87
,08-24 14:04:00.612   374  4093 I AudioFlinger: AudioFlinger's thread 0xb1c00000 ready to run
,08-24 14:04:00.615   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-24 14:04:00.616  2020  4091 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@1a65d87
,08-24 14:04:00.626   374  4093 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-24 14:04:00.626   374  4093 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-24 14:04:00.626   374  4093 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-24 14:04:00.633   374  4093 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-24 14:04:00.702  2020  2020 I HotwordWorkerImpl: onReady
,08-24 14:04:01.040  4085  4085 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-24 14:04:01.044  4085  4085 D AndroidRuntime: CheckJNI is OFF
,08-24 14:04:01.054  1963  2197 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,08-24 14:04:01.086  4085  4085 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-24 14:04:01.175  4085  4085 I Radio-JNI: register_android_hardware_Radio DONE
,08-24 14:04:01.211  4085  4085 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:04:01.224   870   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-24 14:04:01.225   870   883 I ActivityManager: Killing 4024:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-24 14:04:01.307   870  1314 D WifiService: Client connection lost with reason: 4
,08-24 14:04:01.308   870  1951 D GraphicsStats: Buffer count: 2
,08-24 14:04:01.319   870  3338 W ActivityManager: Spurious death for ProcessRecord{63a3f89 0:com.test.thalitest/u0a0}, curProc for 4024: null
,08-24 14:04:01.376   870   893 W PackageSettings: Skipping PackageSetting{bfc33d0 com.example.hello/10273} due to missing metadata
,08-24 14:04:01.429   870   893 I art     : Starting a blocking GC Explicit
,08-24 14:04:01.439  1360  1360 W RecentsTaskLoader: Missing ActivityInfo for ComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} u=0
,08-24 14:04:01.510   870   893 I art     : Explicit concurrent mark sweep GC freed 21333(1307KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.072ms total 74.973ms
,08-24 14:04:01.544   870   893 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-24 14:04:01.550  4085  4085 I art     : System.exit called, status: 0
,08-24 14:04:01.550  4085  4085 I AndroidRuntime: VM exiting with result code 0.
,08-24 14:04:01.554   870   893 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-24 14:04:01.578  2635  2635 D BluetoothMapAppObserver: onReceive
,08-24 14:04:01.578  2635  2635 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-24 14:04:01.581  2037  2286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-24 14:04:01.581  3855  3855 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-24 14:04:01.584  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 14:04:01.584   870  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:04:01.589  1874  4105 I Keyboard.Facilitator.DecoderInitializer: run()
,08-24 14:04:01.598  1874  4105 I Decoder : createOrResetDecoder
,08-24 14:04:01.624  1516  1516 I ConfigService: onCreate
,08-24 14:04:01.663  1940  1940 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-24 14:04:01.675  1874  4105 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-24 14:04:01.685  1516  1516 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-24 14:04:01.685  1516  1516 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-24 14:04:01.686  1516  1516 E AndroidRuntime: FATAL EXCEPTION: main
08-24 14:04:01.686  1516  1516 E AndroidRuntime: Process: com.google.process.gapps, PID: 1516
08-24 14:04:01.686  1516  1516 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 14:04:01.686  1516  1516 E AndroidRuntime: 	... 8 more
,08-24 14:04:01.696   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 14:04:01.703   870  4112 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:04:01.703   870  4112 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-24 14:04:01.703   870  4112 E DropBoxManagerService: 	... 8 more
08-24 14:04:01.709  3216  4109 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 14:04:01.715   870  4113 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 14:04:01.734   870  1341 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-24 14:04:01.734   870  1341 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-24 14:04:01.734   870  1341 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-24 14:04:01.734   870  1341 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-24 14:04:01.734   870  1341 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-24 14:04:01.734   870  1341 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
08-24 14:04:01.734   870  1341 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,08-24 14:04:01.734   870  1341 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-24 14:04:01.735   870  1341 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-24 14:04:01.735   870  1341 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-24 14:04:01.735   870  1341 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
,08-24 14:04:01.735   870  1341 W System.err: 	... 4 more
08-24 14:04:01.735   870  1341 D skia    : ------- write threw an exception
08-24 14:04:01.735  1963  2019 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-24 14:04:01.736  3216  4109 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-24 14:04:01.737  3216  4109 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 14:04:01.737  3216  4109 E AndroidRuntime: Process: android.process.acore, PID: 3216
08-24 14:04:01.737  3216  4109 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:04:01.737  3216  4109 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:04:01.740  1874  4105 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-24 14:04:01.742   870   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 14:04:01.742  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 14:04:01.742  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-24 14:04:01.744   870   882 E PackageManager: Failed to write settings, restoring backup
08-24 14:04:01.744   870   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 14:04:01.744   870   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 14:04:01.744   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 14:04:01.744   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 14:04:01.744   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 14:04:01.744   870   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:04:01.744   870   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:04:01.744   870   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:04:01.745  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 14:04:01.745  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-24 14:04:01.747   870   883 E DropBoxManagerService: Can't write: system_server_wtf
08-24 14:04:01.747   870   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 14:04:01.747   870   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:04:01.747   870   883 E DropBoxManagerService: 	... 13 more
,08-24 14:04:01.748  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-24 14:04:01.748  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-24 14:04:01.749   870  1390 I ActivityManager: Start proc 4115:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-24 14:04:01.751  1963  2019 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 14:04:01.751  1963  2019 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
08-24 14:04:01.751  1963  2019 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 14:04:01.751  1963  2019 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-24 14:04:01.752   870  3338 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 14:04:01.752   870  4113 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 14:04:01.752   870  4113 I Adreno  : Build Date                       : 10/20/15
08-24 14:04:01.752   870  4113 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 14:04:01.752   870  4113 I Adreno  : Local Branch                     : M14
08-24 14:04:01.752   870  4113 I Adreno  : Remote Branch                    : 
08-24 14:04:01.752   870  4113 I Adreno  : Remote Branch                    : 
08-24 14:04:01.752   870  4113 I Adreno  : Reconstruct Branch               : 
08-24 14:04:01.755  2020  2032 W SearchService: Abort, client detached.
08-24 14:04:01.757   870  4113 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:04:01.761   870  4120 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:04:01.761   870  4120 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:04:01.761   870  4120 E DropBoxManagerService: 	... 5 more
,08-24 14:04:01.763   870  4121 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:04:01.763   870  4121 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 14:04:01.763   870  4121 E DropBoxManagerService: 	... 5 more
08-24 14:04:01.769  2020  2020 I HotwordDetector: Closing mic
08-24 14:04:01.769  2020  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1a65d87
08-24 14:04:01.769  2020  4091 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-24 14:04:01.774  1874  4105 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-24 14:04:01.775  1874  4105 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-24 14:04:01.775  1874  4105 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 14:04:01.775  1874  4105 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 14:04:01.775  1874  4105 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 14:04:01.775  1874  4105 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-24 14:04:01.804   870  2241 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-24 14:04:01.817  2020  4131 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-24 14:04:01.821  1963  1963 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@31c24ac new=com.google.android.velvet.VelvetApplication@31c24ac
,08-24 14:04:01.827   374  4093 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 14:04:01.827   374  4093 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 14:04:01.830   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-24 14:04:01.872  1963  1963 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-24 14:04:01.889  2020  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-24 14:04:01.889  2020  4090 I MicroRecognitionRnrImpl: Detection finished
,08-24 14:04:01.940   870   888 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +132ms
,08-24 14:04:01.962  1722  4138 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-24 14:04:01.962  1722  4138 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-24 14:04:02.076   280   280 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,08-24 14:04:02.076   280   280 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=16 fd=18 dpy=0 numHwLayers=10
,08-24 14:04:02.076   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
08-24 14:04:02.076   280   280 E qdoverlay: MdpData failed to play
08-24 14:04:02.077   280   280 E qdoverlay: == Dump MdpData start ==
,08-24 14:04:02.077   280   280 E qdoverlay: == Dump OvFD fd=32 path=/dev/graphics/fb0 start/end ==
08-24 14:04:02.077   280   280 E qdoverlay: mOvData msmfb_overlay_data id=8
,08-24 14:04:02.077   280   280 E qdoverlay: data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
08-24 14:04:02.078   280   280 E qdoverlay: == Dump MdpData end ==
,08-24 14:04:02.078   280   280 E qdhwcomposer: draw: queue failed for left of dpy = 0
,08-24 14:04:02.078   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
,08-24 14:04:02.079   280   280 E qdoverlay: MdpData failed to play
08-24 14:04:02.079   280   280 E qdoverlay: == Dump MdpData start ==
08-24 14:04:02.079   280   280 E qdoverlay: == Dump OvFD fd=41 path=/dev/graphics/fb0 start/end ==
,08-24 14:04:02.080   280   280 E qdoverlay: mOvData msmfb_overlay_data id=16
08-24 14:04:02.080   280   280 E qdoverlay: data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
08-24 14:04:02.081   280   280 E qdoverlay: == Dump MdpData end ==
,08-24 14:04:02.081   280   280 E qdhwcomposer: draw: queue failed for right of dpy = 0
08-24 14:04:02.081   280   280 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
08-24 14:04:02.082   280   280 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
08-24 14:04:02.082   280   280 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&, const overlay::utils::Dim&): commit failed
08-24 14:04:02.082   280   280 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,08-24 14:04:02.089   280   280 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-24 14:04:02.089   280   280 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
,08-24 14:04:02.089   280   280 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-24 14:04:02.089   280   280 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-24 14:04:02.089   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-24 14:04:02.089   280   280 E qdoverlay: MdpCtrl close error in unset
,08-24 14:04:02.352   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 14:04:02.352   280   280 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-24 14:04:02.352   280   280 E qdoverlay: MdpCtrl close error in unset

```
