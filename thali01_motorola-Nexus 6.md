#### Test 827284243e10cd0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 17:19:53.055  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:19:53.068  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 17:19:53.074  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 17:19:53.128  1494  2967 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 17:19:53.128  1494  2967 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 17:19:53.128  1494  2967 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:19:53.128  1494  2967 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 17:19:53.169  3497  3497 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 17:19:53.170  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 17:19:53.171  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-25 17:19:53.741  3805  3805 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 17:19:53.745  3805  3805 D AndroidRuntime: CheckJNI is OFF
08-25 17:19:53.781  3805  3805 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 17:19:53.825  3805  3805 I Radio-JNI: register_android_hardware_Radio DONE
08-25 17:19:53.845  3805  3805 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 17:19:53.850   873  1995 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 17:19:53.905  2000  2013 W SearchService: Abort, client detached.
08-25 17:19:53.909  2000  2000 I HotwordDetector: Closing mic
08-25 17:19:53.910  3805  3805 D AndroidRuntime: Shutting down VM
08-25 17:19:53.910  2000  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@450c6e2
08-25 17:19:53.911  2000  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 17:19:53.928   873   884 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 17:19:53.970   376  2346 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 17:19:53.973   376  2346 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 17:19:53.978   376  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 17:19:53.980  2000  2336 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 17:19:53.983  2000  2343 I MicroRecognitionRnrImpl: Detection finished
08-25 17:19:54.018  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 17:19:54.049  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 17:19:54.060  3815  3815 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9962-9967)
08-25 17:19:54.060  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:19:54.075  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a76c6ce}
08-25 17:19:54.076  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:19:54.076  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 17:19:54.081  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 17:19:54.083  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 17:19:54.096  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-25 17:19:54.105  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 17:19:54.105  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 17:19:54.105  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:19:54.105  3815  3815 I Adreno  : Build Date                       : 10/20/15
08-25 17:19:54.105  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:19:54.105  3815  3815 I Adreno  : Local Branch                     : M14
08-25 17:19:54.105  3815  3815 I Adreno  : Remote Branch                    : 
08-25 17:19:54.105  3815  3815 I Adreno  : Remote Branch                    : 
08-25 17:19:54.105  3815  3815 I Adreno  : Reconstruct Branch               : 
,08-25 17:19:54.159   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@813adbe:true
,08-25 17:19:54.223  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 17:19:54.235  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 17:19:54.344  3815  3853 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 17:19:54.368  3815  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 17:19:54.440  3815  3853 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 17:19:54.592   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +681ms,
08-25 17:19:54.599  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 17:19:54.633  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,08-25 17:19:54.749   873   884 I ActivityManager: Killing 3557:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 17:19:54.781   873   884 I ActivityManager: Killing 2446:com.google.android.talk/u0a61 (adj 15): empty #18
,08-25 17:19:54.810  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 17:19:54.999  3815  3856 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1659631312
,08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 17:19:55.007  3815  3856 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc5a0f2 added. We now have 1 listener(s)
,08-25 17:19:55.010  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 17:19:55.011  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:19:55.012  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:19:55.012  3815  3856 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 17:19:55.017  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 17:19:55.018  3815  3856 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61aaaf9 added. We now have 1 listener(s)
08-25 17:19:55.018  3815  3856 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:19:55.024   873  1304 D WifiService: New client listening to asynchronous messages
,08-25 17:19:55.026  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:19:55.026  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 17:19:55.026  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 17:19:55.026  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 17:19:55.026  3815  3856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 17:19:55.032  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:19:55.033  3815  3856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 17:19:55.044  3815  3856 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:19:55.045  3815  3856 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:19:55.046  3815  3856 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 17:19:55.046  3815  3856 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:19:55.047  3815  3856 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 17:19:55.049  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:19:55.053  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:19:55.085  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 17:19:56.021  3815  3865 W jxcore-log: Initializing JXcore engine
,08-25 17:19:56.021  3815  3865 W jxcore-log: JXcore engine is ready
,08-25 17:19:56.070  3865  3865 W Thread-338: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 17:19:56.070  3865  3865 W Thread-338: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[12870]" dev="sockfs" ino=12870 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-25 17:19:56.070  3865  3865 W Thread-338: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 17:19:56.070  3865  3865 W Thread-338: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[24156]" dev="sockfs" ino=24156 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 17:19:56.085  3815  3865 W jxcore-log: Starting JXcore engine
,08-25 17:19:56.177  3815  3865 W jxcore-log: Platform android
08-25 17:19:56.177  3815  3865 W jxcore-log: 
,08-25 17:19:56.177  3815  3865 W jxcore-log: Process ARCH arm
08-25 17:19:56.177  3815  3865 W jxcore-log: 
,08-25 17:19:56.384  3815  3865 I jxcore-log: JXcore Cordova bridge is ready!
08-25 17:19:56.384  3815  3865 I jxcore-log: 
08-25 17:19:56.385  3815  3865 W jxcore-log: JXcore engine is started
,08-25 17:19:56.393  3815  3856 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 17:19:56.397  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 17:19:56.786   873  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 17:19:59.822   873  1851 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 17:20:03.802  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:03.807  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:03.863  1494  2288 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 17:20:03.863  1494  2288 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 17:20:03.864  1494  2288 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:20:03.864  1494  2288 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:20:03.904  3536  3875 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 17:20:03.904  3536  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jdm.a(PG:82)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jcs.o(PG:406)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jcn.a(PG:1379)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jcs.i(PG:143)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at blb.a(PG:3937)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at czp.a(PG:18188)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at czp.a(PG:9081)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at czq.run(PG:1686)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 17:20:03.904  3536  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jdj.a(PG:4091)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jdj.a(PG:1125)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jdm.a(PG:77)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	... 12 more
08-25 17:20:03.904  3536  3875 E HttpOperation: Caused by: faj: BadAuthentication
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at fal.a(PG:38)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	at jdj.a(PG:4089)
08-25 17:20:03.904  3536  3875 E HttpOperation: 	... 14 more
,08-25 17:20:03.987  1494  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-25 17:20:03.987  1494  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 17:20:03.987  1494  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:20:03.988  1494  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:20:04.004  3536  3875 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 17:20:04.004  3536  3875 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jdm.a(PG:82)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jcs.o(PG:406)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jcn.a(PG:1379)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jcs.i(PG:143)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at hec.a(PG:42)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at hee.a(PG:102)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at czr.a(PG:65)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at kka.a(PG:108)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at czp.a(PG:19176)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at czp.a(PG:9081)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at czq.run(PG:1686)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 17:20:04.004  3536  3875 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jdj.a(PG:4091)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jdj.a(PG:1125)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jdm.a(PG:77)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	... 15 more
08-25 17:20:04.004  3536  3875 E HttpOperation: Caused by: faj: BadAuthentication
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at fal.a(PG:38)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	at jdj.a(PG:4089)
08-25 17:20:04.004  3536  3875 E HttpOperation: 	... 17 more
,08-25 17:20:04.005  3536  3875 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 17:20:04.005  3536  3875 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at hec.a(PG:42)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at hee.a(PG:102)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at czr.a(PG:65)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at kka.a(PG:108)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	... 15 more
08-25 17:20:04.005  3536  3875 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at fal.a(PG:38)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 17:20:04.005  3536  3875 E ExperimentLoader: 	... 17 more
,08-25 17:20:04.090   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129451, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-25 17:20:06.465  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 17:20:06.465  3815  3865 I jxcore-log: 
,08-25 17:20:06.467  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 17:20:06.467  3815  3865 I jxcore-log: 
,08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:06.480  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:06.486  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:06.493  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 17:20:06.493  3815  3865 I jxcore-log: 
,08-25 17:20:06.501  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 17:20:06.501  3815  3865 I jxcore-log: 
,08-25 17:20:07.043  3815  3865 D executeNativeTests: Running unit tests
,08-25 17:20:07.101  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:07.101  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 added. We now have 2 listener(s)
,08-25 17:20:07.103  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:07.103  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:07.103  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:07.103  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:07.103  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 added. We now have 2 listener(s)
08-25 17:20:07.103  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:07.104  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:20:07.109  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.123  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:07.128  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:07.128  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:20:07.131  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:20:07.136  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:20:07.136  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.136  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 17:20:07.142  3815  3865 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 17:20:07.143  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:20:07.143  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 17:20:07.143  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:20:07.144  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 17:20:07.144  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.145  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.146  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:20:07.146  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.147  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.148  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.148  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.149  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:07.149  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 removed from the list
08-25 17:20:07.150  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.150  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 removed from the list
08-25 17:20:07.150  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:20:07.150  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.152  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.152  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.154  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.155  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:07.155  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.155  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.160  3815  3865 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 17:20:07.162  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.162  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.162  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.163  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.163  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.163  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.164  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.164  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.164  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.164  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.165  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.165  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.165  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.165  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.168  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.168  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.168  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.168  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.173  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:20:07.174  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:20:07.175  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:20:07.176  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:20:07.176  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:20:07.176  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.176  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.176  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.176  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.176  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.176  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.176  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.176  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:07.176  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.176  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.176  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.177  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.177  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.177  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.179  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.179  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.179  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:07.179  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.180  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:20:07.183  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.193  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,08-25 17:20:07.198  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:07.198  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:07.199  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:20:07.199  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:20:07.199  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:20:07.200  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:07.200  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:20:07.204  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.206  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:20:07.206  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:20:07.210  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.215  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:20:07.217  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 17:20:07.218  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:07.224  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 17:20:07.229  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 17:20:07.229  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 17:20:07.230  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:20:07.231  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 17:20:07.233  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:07.244  2652  2759 D BtGatt.GattService: registerClient() - UUID=064ed9c6-e26c-462f-9cd4-859400606223
,08-25 17:20:07.245  2652  2672 D BtGatt.GattService: onClientRegistered() - UUID=064ed9c6-e26c-462f-9cd4-859400606223, clientIf=5
,08-25 17:20:07.247  3815  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:20:07.249  2652  2664 D BtGatt.GattService: start scan with filters
,08-25 17:20:07.258  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:07.259  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:07.259  2652  2678 D BtGatt.ScanManager: handling starting scan
08-25 17:20:07.259  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:20:07.260  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:07.263  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:07.263  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:07.264  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:20:07.264  2652  2678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
08-25 17:20:07.265  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:07.271  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:20:07.274  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.274  3815  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 17:20:07.274  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,08-25 17:20:07.274  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 17:20:07.274  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.274  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 17:20:07.274  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:20:07.274  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 17:20:07.274  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 17:20:07.274  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:20:07.275  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 17:20:07.275  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:20:07.276  3815  3865 D BluetoothAdapter: STATE_ON
08-25 17:20:07.277  2652  2664 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:20:07.277  2652  2759 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:20:07.278  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:20:07.278  2652  2672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:20:07.278  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:20:07.278  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:20:07.278  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:20:07.278  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.281  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:07.283  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.283  2652  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 17:20:07.283  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:20:07.283  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:20:07.283  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:20:07.286  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:20:07.287  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.287  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.288  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.288  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.288  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.288  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.288  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:20:07.288  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.288  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 17:20:07.288  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.288  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.289  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:20:07.297  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:07.309  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 17:20:07.309  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.311  2652  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:07.311  2652  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.317  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:07.321  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:07.322  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:20:07.323  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:20:07.323  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 17:20:07.323  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 17:20:07.323  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:07.324  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:20:07.326  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.331  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.334  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:20:07.334  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:20:07.335  2652  2672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:20:07.336  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.342  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:20:07.344  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:20:07.345  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:07.346  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 17:20:07.347  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.355  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:20:07.355  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.355  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:20:07.355  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:20:07.355  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:20:07.356  2652  2678 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:20:07.356  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:07.363  2652  2664 D BtGatt.GattService: registerClient() - UUID=59948edf-c7cb-4504-a6b6-37a8b4ccbecd
,08-25 17:20:07.364  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:20:07.364  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.364  2652  2672 D BtGatt.GattService: onClientRegistered() - UUID=59948edf-c7cb-4504-a6b6-37a8b4ccbecd, clientIf=5
08-25 17:20:07.365  3815  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 17:20:07.365  2652  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:20:07.365  2652  2663 D BtGatt.GattService: start scan with filters
,08-25 17:20:07.372  2652  2672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:20:07.372  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.372  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:07.373  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:07.373  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:20:07.373  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:07.378  2652  2678 D BtGatt.ScanManager: handling starting scan
,08-25 17:20:07.381  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:07.382  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:20:07.382  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:20:07.384  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:07.391  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 17:20:07.391  2652  2672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:20:07.391  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.392  2652  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:20:07.395  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.395  3815  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:20:07.395  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.396  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 17:20:07.396  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.396  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:20:07.396  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:20:07.396  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:20:07.396  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:20:07.396  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:20:07.397  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:20:07.398  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:20:07.400  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:07.401  2652  2663 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:20:07.401  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:20:07.401  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.402  2652  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:07.402  2652  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 17:20:07.406  2652  2664 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 17:20:07.406  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:20:07.406  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:20:07.406  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 17:20:07.406  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:20:07.406  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:07.407  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.407  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:20:07.407  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:20:07.407  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 17:20:07.408  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.409  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.409  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.409  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.409  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.409  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.409  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.409  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.409  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.410  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.410  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.410  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.410  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.410  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.411  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.411  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.411  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.411  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.412  3815  3865 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 17:20:07.412  2652  2672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:20:07.412  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.414  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:07.417  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:20:07.417  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.417  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:20:07.419  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.419  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:20:07.421  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.422  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:20:07.422  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:20:07.422  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 17:20:07.422  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.422  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 17:20:07.423  2652  2678 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:20:07.423  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:07.423  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.423  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:20:07.426  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 17:20:07.426  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 17:20:07.429  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 17:20:07.430  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.430  2652  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 17:20:07.431  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:20:07.431  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:20:07.431  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:07.435  2652  2672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 17:20:07.435  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.435  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 17:20:07.435  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:20:07.435  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 17:20:07.436  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:07.438  2652  2664 D BtGatt.GattService: registerClient() - UUID=932c6309-1e45-45e4-a87e-635b4e9f6894
08-25 17:20:07.440  2652  2672 D BtGatt.GattService: onClientRegistered() - UUID=932c6309-1e45-45e4-a87e-635b4e9f6894, clientIf=5
,08-25 17:20:07.440  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 17:20:07.441  2652  2759 D BtGatt.GattService: start scan with filters
,08-25 17:20:07.443  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:07.443  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:07.444  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:20:07.444  2652  2678 D BtGatt.ScanManager: handling starting scan
08-25 17:20:07.444  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:07.446  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:07.446  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:20:07.446  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:20:07.447  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:07.449  3815  3865 I io.jxcore.node.ConnectionHelper: start: OK
08-25 17:20:07.449  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.449  3815  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:20:07.449  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.449  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 17:20:07.449  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.449  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:20:07.450  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:20:07.450  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:20:07.450  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:20:07.450  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:20:07.450  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:20:07.450  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:20:07.450  2652  2672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:20:07.450  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.451  3815  3865 D BluetoothAdapter: STATE_ON
08-25 17:20:07.451  2652  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 17:20:07.451  2652  2663 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:20:07.451  2652  2664 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:20:07.452  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:20:07.452  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:20:07.452  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 17:20:07.452  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:20:07.452  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:07.453  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:20:07.453  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 17:20:07.453  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:20:07.453  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:20:07.453  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.454  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.454  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.454  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.455  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.455  3815  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 17:20:07.455  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.455  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.455  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.455  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.455  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:07.455  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
,08-25 17:20:07.455  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.455  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.455  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.455  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.456  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.456  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 17:20:07.456  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.456  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.456  2652  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:07.456  2652  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:20:07.456  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.456  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.456  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.456  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.457  3815  3865 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 17:20:07.457  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.457  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.457  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.458  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.458  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.458  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.458  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.458  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.458  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.458  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.458  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.458  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.458  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.458  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.459  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.459  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:07.459  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.459  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.460  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:20:07.460  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.460  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.460  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.460  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.460  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.460  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.460  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.460  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.460  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.460  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.460  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.460  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.461  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.461  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.461  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.462  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.462  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:07.462  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.463  3815  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 17:20:07.463  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:07.463  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.463  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.463  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.463  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.463  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.463  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
,08-25 17:20:07.463  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.463  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.463  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:20:07.463  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.463  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.464  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.464  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.464  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:20:07.464  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.464  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.464  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.465  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 17:20:07.465  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.465  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.465  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.465  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.465  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.465  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.466  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.466  2652  2672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:20:07.466  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.466  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.466  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.466  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.466  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.466  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.466  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.466  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.468  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
,08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:20:07.468  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:20:07.468  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 17:20:07.468  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 17:20:07.469  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 17:20:07.469  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.469  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.469  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.469  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.469  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.469  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.469  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.469  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.469  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.469  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.469  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.470  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:07.470  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.470  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.470  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.470  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:07.470  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:07.470  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.471  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:20:07.471  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:20:07.471  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.471  3815  3865 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-25 17:20:07.471  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 17:20:07.473  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:20:07.473  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 17:20:07.473  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 17:20:07.473  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 17:20:07.474  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 17:20:07.475  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 17:20:07.475  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 17:20:07.475  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:20:07.475  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-25 17:20:07.475  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:20:07.476  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:20:07.476  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 17:20:07.476  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:20:07.476  3815  3865 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 17:20:07.476  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 17:20:07.479  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 17:20:07.479  2652  2672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:20:07.479  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.479  2652  2678 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:20:07.480  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 17:20:07.480  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 17:20:07.480  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 17:20:07.480  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 17:20:07.480  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 17:20:07.480  3815  3865 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 17:20:07.480  3815  3865 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 17:20:07.481  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.481  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.481  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:20:07.481  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.481  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.481  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.481  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 17:20:07.482  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.482  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.482  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.482  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.482  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:07.482  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.482  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.482  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.483  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.483  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.483  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.483  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.484  3815  3865 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 17:20:07.485  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.485  3815  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
,08-25 17:20:07.485  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.485  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.485  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.485  2652  2672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 17:20:07.485  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:07.486  2652  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:20:07.486  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.486  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.486  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
,08-25 17:20:07.486  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.486  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.486  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.486  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.486  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.486  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.486  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.488  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.488  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.488  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.488  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.489  3815  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
08-25 17:20:07.489  3815  3879 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
08-25 17:20:07.490  3815  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 17:20:07.490  2652  2672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:20:07.490  2652  2672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:07.490  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.490  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.490  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.491  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.491  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.491  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.491  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.491  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.492  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.492  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.492  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.492  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.492  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.492  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.493  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.493  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.493  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.493  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.494  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 17:20:07.494  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 17:20:07.494  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:20:07.494  3815  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 17:20:07.494  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:20:07.494  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 17:20:07.495  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:20:07.495  3815  3865 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 17:20:07.495  3815  3865 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 17:20:07.495  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 17:20:07.495  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:20:07.495  3815  3865 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 17:20:07.495  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.495  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.495  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.495  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.496  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.496  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.496  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.496  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.496  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.496  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.496  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.496  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.496  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.496  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.497  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.497  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.497  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.497  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.498  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.498  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.498  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.498  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.498  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.498  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.498  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.498  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.498  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.498  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.498  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.498  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.498  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.499  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.499  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.499  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.499  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.499  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.499  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.499  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.499  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.499  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.499  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.499  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.499  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.499  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.499  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.499  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.499  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.500  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.500  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.500  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.500  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.501  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 17:20:07.501  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:07.502  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 17:20:07.502  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 17:20:07.502  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 17:20:07.502  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 17:20:07.503  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 17:20:07.503  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.503  3815  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 17:20:07.503  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 17:20:07.503  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.503  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:20:07.503  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 17:20:07.503  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:20:07.504  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.504  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.504  3815  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:20:07.504  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.504  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.504  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:07.505  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:07.505  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.505  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.505  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.505  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.505  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.505  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.505  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.505  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.505  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.505  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.505  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.505  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.506  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.506  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.506  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.506  3815  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 17:20:07.506  3815  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 17:20:07.506  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 17:20:07.506  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 17:20:07.507  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.507  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.507  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.507  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.508  3815  3865 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 17:20:07.508  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 17:20:07.509  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 17:20:07.509  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 17:20:07.509  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.509  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.509  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.509  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.509  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.509  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.509  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.509  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.509  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.509  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.509  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.509  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.509  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.510  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.510  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.511  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.511  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.511  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.513  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.513  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.513  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.513  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.513  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.513  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.513  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.513  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.513  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.513  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.513  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.513  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.513  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.513  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.514  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.514  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.514  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.514  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.515  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:07.515  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:07.515  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:07.515  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:07.515  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.515  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.515  3815  3865 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9235742 not in the list
08-25 17:20:07.515  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.515  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.515  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:07.515  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.515  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.516  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:07.516  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:07.516  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:07.516  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:07.516  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:07.516  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ae7353 not in the list
08-25 17:20:07.517  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 17:20:07.517  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:20:07.517  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 17:20:07.517  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 17:20:07.517  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 17:20:07.517  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 17:20:07.519  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 17:20:07.519  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 17:20:07.519  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 17:20:07.519  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:20:07.519  3815  3865 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 17:20:07.519  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 17:20:07.519  3815  3865 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 17:20:07.519  3815  3865 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 17:20:07.520  3815  3865 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 17:20:07.521  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:07.521  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a700ffd added. We now have 2 listener(s)
08-25 17:20:07.521  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:07.522  3815  3865 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 17:20:07.522   873  1995 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-25 17:20:07.522   873  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:20:07.523  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:07.523  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14414f2 added. We now have 3 listener(s)
08-25 17:20:07.523  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:07.528  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:07.528  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8ad743 added. We now have 4 listener(s)
08-25 17:20:07.528  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:07.530  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:07.530  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28641c0 added. We now have 5 listener(s)
08-25 17:20:07.530  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:07.531   873   884 D WifiService: setWifiEnabled: false pid=3815, uid=10000
08-25 17:20:07.531   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 17:20:07.535  2652  2668 D BluetoothAdapterState: Current state: ON, message: 23
08-25 17:20:07.536  2652  2668 D BluetoothAdapterProperties: Setting state to 13
08-25 17:20:07.536  2652  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:20:07.536  2652  2668 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 17:20:07.536  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:07.537  2652  2672 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:20:07.538  2652  2668 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:20:07.538  2652  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 17:20:07.539  2652  2652 D BluetoothMapService: onReceive
08-25 17:20:07.539  2652  2652 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:20:07.539  2652  2652 D BluetoothMapService: STATE_TURNING_OFF
,08-25 17:20:07.539  2652  2652 D BluetoothMapService: MAP Service closeService in
08-25 17:20:07.539  2652  2652 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 17:20:07.539  2652  2652 D ObexServerSockets0: shutdown(block = true)
08-25 17:20:07.540  2652  2652 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 17:20:07.540  2652  2652 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 17:20:07.540  2652  2756 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 17:20:07.541  2652  2797 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 17:20:07.541  2652  2798 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 17:20:07.541  2652  2652 I BtOppRfcommListener: stopping Accept Thread
08-25 17:20:07.541  2652  3394 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:20:07.541  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.541  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:20:07.542  2652  3394 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:20:07.543  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.543  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.543  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:07.545  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.546  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 17:20:07.547  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.548   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:20:07.548   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 17:20:07.549   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:20:07.549   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:07.550  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:07.550  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:07.551  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:07.551  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:07.551   873   886 I ActivityManager: Start proc 3885:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-25 17:20:07.552  2652  2652 D HeadsetService: Received stop request...Stopping profile...
,08-25 17:20:07.554  1349  1360 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:07.554   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:07.554   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:07.555  1928  2324 D BluetoothHeadset: Proxy object disconnected
08-25 17:20:07.555   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 17:20:07.559  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.560   873  1860 D DhcpClient: Clearing IP address
08-25 17:20:07.560   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:20:07.561  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.563   372   871 D CommandListener: Setting iface cfg
08-25 17:20:07.563  2652  2652 D A2dpService: Received stop request...Stopping profile...
,08-25 17:20:07.563  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:07.564  2652  2764 D A2dpStateMachine: Exit Disconnected: -1
,08-25 17:20:07.565  1494  2431 V NativeCrypto: Read error: ssl=0x9a751000: I/O error during system call, Connection timed out
,08-25 17:20:07.565   873   873 D BluetoothA2dp: Proxy object disconnected
,08-25 17:20:07.566  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.566  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.566  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.566  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:07.566  2652  2652 D HidService: Received stop request...Stopping profile...
08-25 17:20:07.566  2652  2652 D HidService: Stopping Bluetooth HidService
08-25 17:20:07.567  1494  2431 V NativeCrypto: SSL shutdown failed: ssl=0x9a751000: I/O error during system call, Broken pipe
08-25 17:20:07.568   873  1995 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-25 17:20:07.569   873  1843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-25 17:20:07.570   873  1864 D DhcpClient: Receive thread stopped
08-25 17:20:07.571  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-25 17:20:07.571  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-25 17:20:07.571  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-25 17:20:07.571  1349  1349 D HidProfile: Bluetooth service disconnected
08-25 17:20:07.572   395   395 E Parcel  : Reading a NULL string not supported here.
08-25 17:20:07.574   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:20:07.574   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-25 17:20:07.578  2652  2652 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 17:20:07.578  2652  2672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-25 17:20:07.578  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.578  2652  2652 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:20:07.578  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.578  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.578  2652  2672 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 17:20:07.579   873  1843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 17:20:07.579  2652  2652 D HealthService: Received stop request...Stopping profile...
08-25 17:20:07.581   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 17:20:07.582  2652  2652 D PanService: Received stop request...Stopping profile...
08-25 17:20:07.582   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 17:20:07.582  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:20:07.583  1349  1349 D PanProfile: Bluetooth service disconnected
08-25 17:20:07.583  2652  2652 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:20:07.583  2652  2652 D BluetoothMapService: stop()
08-25 17:20:07.584   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-25 17:20:07.585  2652  2652 D BluetoothMapAppObserver: deinitObservers()
08-25 17:20:07.585  2652  2652 D BluetoothMapAppObserver: removeReceiver()
08-25 17:20:07.586  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.586  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.586  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.586  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:07.587  2652  2672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 17:20:07.587  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.587  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.587  2652  2747 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 17:20:07.588  2652  2747 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:20:07.588  2652  2747 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:20:07.588  2652  2747 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:07.588  2652  2652 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 17:20:07.588  2652  2672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 17:20:07.588  2652  2652 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:20:07.588   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.588  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:07.589  2652  2652 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:20:07.589  2652  2672 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 17:20:07.589  2652  2652 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:20:07.589  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.589  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.589  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.589  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:07.589  2652  2652 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 17:20:07.590  2652  2652 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:20:07.590  2652  2652 D BluetoothMapService: MAP Service closeService in
,08-25 17:20:07.590  2652  2652 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:07.590  2652  2652 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:07.590  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:07.590  2652  2652 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:07.591  2652  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 17:20:07.591  2652  2668 D BluetoothAdapterProperties: Setting state to 15
08-25 17:20:07.591  2652  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 17:20:07.591  2652  2668 I BluetoothAdapterState: Entering BleOnState
08-25 17:20:07.591  2652  2652 D BluetoothMapService: cleanup()
08-25 17:20:07.591  2652  2652 D BluetoothMapService: MAP Service closeService in
08-25 17:20:07.591  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 17:20:07.593  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:20:07.593  1928  1939 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:20:07.593   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:07.594  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:20:07.594   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:07.595   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:20:07.595  1349  2023 D BluetoothPan: onBluetoothStateChange on: false
08-25 17:20:07.595  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:07.598   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:07.598  1349  1361 D BluetoothMap: onBluetoothStateChange: up=false
08-25 17:20:07.599  2652  2668 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 17:20:07.599  2652  2668 D BluetoothAdapterProperties: Setting state to 16
,08-25 17:20:07.599  2652  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 17:20:07.600  2652  2668 D BluetoothAdapterProperties: onBleDisable
,08-25 17:20:07.600  2652  2668 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:20:07.600  2652  2669 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 17:20:07.601  2652  2672 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:20:07.601  2652  2747 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 17:20:07.601  2652  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:07.603  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:07.603  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:07.604  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.604  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:07.606  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:07.606  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:07.606   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:07.607  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.607  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:07.609  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:07.609  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:07.610  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.610  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:07.611   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 17:20:07.612  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:07.612  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:07.612  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:07.612  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:07.614  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.615  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.619  2028  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 17:20:07.630  3885  3885 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 17:20:07.636   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:07.642  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:20:07.646   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f36aeb:true
,08-25 17:20:07.647  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:07.657   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:07.658   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 17:20:07.658   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:20:07.662   873  1384 I ActivityManager: Start proc 3902:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 17:20:07.666   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:20:07.667  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.669  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:07.676  3885  3885 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 17:20:07.678  3885  3885 D BluetoothMap: Create BluetoothMap proxy object
,08-25 17:20:07.693  3885  3885 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 17:20:07.703  3902  3902 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 17:20:07.707  3885  3885 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:20:07.713   372   871 E Netd    : netlink response contains error (No such file or directory)
08-25 17:20:07.713   873  1368 I ActivityManager: Killing 3477:android.process.acore/u0a5 (adj 15): empty #17
08-25 17:20:07.714   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 17:20:07.714   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 17:20:07.806  2652  2672 I bt_hci  : shut_down
08-25 17:20:07.806  2652  2679 D bt_hwcfg: hw_epilog_process
,08-25 17:20:07.811  2652  2679 I bt_vendor: low_power_mode_cb
,08-25 17:20:07.832  2652  2679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 17:20:07.833  2652  2679 I bt_vendor: epilog_cb
,08-25 17:20:07.833  2652  2679 I bt_hci  : epilog_finished_callback
,08-25 17:20:07.838  2652  2672 I bt_hci_h4: hal_close
,08-25 17:20:07.838  2652  2672 I bt_userial_vendor: device fd = 51 close
,08-25 17:20:07.899  3902  3902 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.899  3902  3902 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.899  3902  3902 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.899  3902  3902 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.899  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.900  3902  3902 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.900  3902  3902 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.900  3902  3902 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.900  3902  3902 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:07.900  3902  3902 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:07.926   873  1963 I ActivityManager: Start proc 3935:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-25 17:20:07.927   873  1963 I ActivityManager: Killing 3635:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 17:20:07.996  2652  2669 D bt_stack_manager: event_shut_down_stack finished.
,08-25 17:20:07.996  2652  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 17:20:08.001  2652  2652 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:20:08.001  2652  2668 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-25 17:20:08.001  2652  2652 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 17:20:08.001  2652  2652 D BtGatt.GattService: stop()
08-25 17:20:08.001  2652  2652 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 17:20:08.005  2652  2652 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:08.005  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:20:08.005  2652  2652 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:08.007  2652  2652 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:08.007  2652  2652 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 17:20:08.008  2652  2668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 17:20:08.008  2652  2668 D BluetoothAdapterProperties: Setting state to 10
08-25 17:20:08.009  2652  2668 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 17:20:08.010  2652  2668 I BluetoothAdapterState: Entering OffState
,08-25 17:20:08.010   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 17:20:08.019  3935  3935 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 17:20:08.026  2652  2652 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-25 17:20:08.026  2652  2652 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 17:20:08.026  2652  2669 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 17:20:08.028  2652  2669 D bt_stack_manager: event_clean_up_stack finished.
08-25 17:20:08.028  2652  2652 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 17:20:08.039  2652  2652 I art     : System.exit called, status: 0
,08-25 17:20:08.040  2652  2652 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 17:20:08.085   873   884 I ActivityManager: Process com.android.bluetooth (pid 2652) has died
,08-25 17:20:08.249  3935  3954 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 17:20:08.249  3935  3954 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 17:20:08.251  3935  3954 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-25 17:20:08.251  3935  3954 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 17:20:08.299  3935  3954 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 17:20:08.299  3935  3954 I Babel_SMS: MmsConfig.loadFromResources
08-25 17:20:08.301  3935  3954 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-25 17:20:08.303  3935  3954 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 17:20:08.335  3935  3935 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:20:08.338  3935  3935 I Babel_Crash: startup - clean
,08-25 17:20:08.364  3935  3935 I Babel_telephony: TeleModule.launchCompleted
,08-25 17:20:08.374   873  1995 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 17:20:08.390  3935  3935 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 17:20:08.398  3935  3935 W Babel   : BAM#gBA: invalid account id: -1
,08-25 17:20:08.398  3935  3935 W Babel   : BAM#gBA: invalid account id: -1
,08-25 17:20:08.398  3935  3935 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 17:20:08.409  3935  3959 I Babel   : deleted: false for 0
08-25 17:20:08.409   873  1963 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 17:20:08.438  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:20:08.471   873   884 I ActivityManager: Start proc 3962:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 17:20:08.473  3885  3885 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:20:08.510  3935  3935 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:20:08.636  3935  3935 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 17:20:08.659  3935  3935 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:20:08.661  3935  3935 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:20:08.692  3962  3962 D AdapterServiceConfig: Adding HeadsetService
,08-25 17:20:08.692  3962  3962 D AdapterServiceConfig: Adding A2dpService
,08-25 17:20:08.693  3962  3962 D AdapterServiceConfig: Adding HidService
08-25 17:20:08.693  3962  3962 D AdapterServiceConfig: Adding HealthService
08-25 17:20:08.693  3962  3962 D AdapterServiceConfig: Adding PanService
08-25 17:20:08.693  3962  3962 D AdapterServiceConfig: Adding GattService
,08-25 17:20:08.693  3962  3962 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 17:20:08.697  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:08.700  3935  3935 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:20:08.713  3935  3935 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 17:20:08.723  3935  3935 I vclib   : onServiceConnected
,08-25 17:20:08.801  3902  3925 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 17:20:08.807   873  1996 I ActivityManager: Start proc 3976:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 17:20:08.810   873  1996 I ActivityManager: Killing 3652:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 17:20:08.848   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e4fd9f2:true
,08-25 17:20:08.908  3976  3976 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 17:20:08.953  3976  3976 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 17:20:08.971   873  1995 I ActivityManager: Killing 2208:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 17:20:09.039  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:20:09.044  1694  1694 D SystemUpdateService: onCreate
,08-25 17:20:09.055  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:20:09.060  1694  4000 I SystemUpdateService: active receiver: enabled
,08-25 17:20:09.068  1694  4000 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:20:09.071  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 17:20:09.072  1694  4000 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 17:20:09.074  1694  4000 I SystemUpdateService: now status is 0 (complete)
,08-25 17:20:09.074  1694  4000 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 17:20:09.074  1694  4000 I SystemUpdateService: file has been verified
08-25 17:20:09.074  1694  2405 I iu.UploadsManager: num queued entries: 0
08-25 17:20:09.075  1694  4000 I SystemUpdateService: OTA package size = 12249756
08-25 17:20:09.075  1694  2405 I iu.UploadsManager: num updated entries: 0
,08-25 17:20:09.076  1694  2405 I iu.SyncManager: NEXT; no task
,08-25 17:20:09.084  1694  4000 I SystemUpdateService: showing system update notification
,08-25 17:20:09.100  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 17:20:09.103  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 17:20:09.104  1694  1694 D SystemUpdateService: onDestroy
,08-25 17:20:09.120   873  1944 I ActivityManager: Start proc 4002:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 17:20:09.163  4002  4002 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 17:20:09.166  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:20:09.171  4002  4002 D SprintDMHelper: simOperator: 
,08-25 17:20:09.171  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:20:09.201   873  2090 I ActivityManager: Start proc 4014:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 17:20:09.204   873  2090 I ActivityManager: Killing 3673:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 17:20:09.351   873   883 I ActivityManager: Start proc 4029:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 17:20:09.354  3935  4028 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 17:20:09.360   873  1963 I ActivityManager: Killing 3601:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-25 17:20:09.432  4029  4029 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 17:20:09.493  4029  4029 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 17:20:09.493  4029  4029 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 17:20:09.493  4029  4029 I GAv4    :   adb logcat -s GAv4
,08-25 17:20:09.513  4029  4029 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:20:09.521  4029  4029 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:20:09.550  4029  4046 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 17:20:09.660  4029  4029 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 17:20:09.705  4029  4029 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 17:20:09.716  4029  4029 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5621-5623)
08-25 17:20:09.716  4029  4029 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 17:20:09.725  4029  4029 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {da42aa2}
,08-25 17:20:09.726  4029  4029 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 17:20:09.726  4029  4029 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 17:20:09.734  4029  4029 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 17:20:09.736  4029  4029 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 17:20:09.755  4029  4029 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 17:20:09.768  4029  4029 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 17:20:09.768  4029  4029 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 17:20:09.768  4029  4029 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:20:09.768  4029  4029 I Adreno  : Build Date                       : 10/20/15
08-25 17:20:09.768  4029  4029 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:20:09.768  4029  4029 I Adreno  : Local Branch                     : M14
08-25 17:20:09.768  4029  4029 I Adreno  : Remote Branch                    : 
08-25 17:20:09.768  4029  4029 I Adreno  : Remote Branch                    : 
08-25 17:20:09.768  4029  4029 I Adreno  : Reconstruct Branch               : 
,08-25 17:20:09.817  4029  4075 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 17:20:09.834  4029  4029 I NSApplication: Starting up...
,08-25 17:20:09.880   873   883 I ActivityManager: Start proc 4080:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 17:20:09.882   873   883 I ActivityManager: Killing 3735:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-25 17:20:09.957  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 17:20:10.142   873   884 I ActivityManager: Killing 2973:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 17:20:10.546   873  1994 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,08-25 17:20:10.546   873  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:20:10.560   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-25 17:20:10.568  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:10.568  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:10.569  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:10.569  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-25 17:20:10.572  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:10.573  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:10.573  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:10.573  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:20:10.600   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-25 17:20:10.601   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 17:20:10.602   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-25 17:20:10.603   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 17:20:10.603   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 17:20:10.603   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 17:20:10.603   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 17:20:10.616   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 17:20:10.618   372   871 D CommandListener: Setting iface cfg
08-25 17:20:10.618   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.25 rxSuccessRate=13.00 delta 1000 -> 994
08-25 17:20:10.619   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 17:20:10.619   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 17:20:10.623   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
08-25 17:20:10.624   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 17:20:10.633   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 17:20:10.634   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:10.648   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 17:20:10.698   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 17:20:10.700  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 17:20:11.124  1449  1449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:20:11.165  1449  1449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:20:11.165  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 17:20:11.171   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:11.186   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:20:11.186   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 17:20:11.186   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 17:20:11.220   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:11.237   372   871 D CommandListener: Setting iface cfg
,08-25 17:20:11.238   873  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 17:20:11.257   873  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 17:20:11.263   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 17:20:11.294   873  4103 D DhcpClient: Receive thread started
,08-25 17:20:11.380   873  1303 E native  : do suspend false
,08-25 17:20:11.400   873  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 17:20:11.414   873  4103 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-25 17:20:11.416   873  1860 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-25 17:20:11.420   873  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 17:20:11.436   873  4103 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 17:20:11.437   873  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 17:20:11.442   372   871 D CommandListener: Setting iface cfg
,08-25 17:20:11.454   873  1860 D DhcpClient: Scheduling renewal in 86399s
,08-25 17:20:11.454   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 17:20:11.478   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 17:20:11.482   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 17:20:11.482   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 17:20:11.484   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 17:20:11.487   873  1305 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 17:20:11.493   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:20:11.554   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 17:20:11.554   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 17:20:11.556   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
,08-25 17:20:11.558   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 17:20:11.560   873  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 17:20:11.574   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 17:20:11.581   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 17:20:11.582   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-25 17:20:11.582   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 17:20:11.582   873  1305 D ConnectivityService:    accepting network in place of null
,08-25 17:20:11.582   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 17:20:11.583   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 17:20:11.584   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 17:20:11.604   873  4102 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137511, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 17:20:11.627   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:11.683   873  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-25 17:20:11.694   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:11.698   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 17:20:11.698   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:20:11.700   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 17:20:11.706   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 17:20:11.721  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:11.722  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:20:11.722  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:11.722  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:11.724  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:11.725  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:20:11.725  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:11.725  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:11.735  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:20:11.738  1694  1694 D SystemUpdateService: onCreate
,08-25 17:20:11.740  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:20:11.743  1694  4113 I SystemUpdateService: active receiver: enabled
,08-25 17:20:11.746   873  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:20:11 GMT], X-Android-Received-Millis=[1472138411745], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472138411725]},
,08-25 17:20:11.747  1694  4113 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-25 17:20:11.748   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 17:20:11.748   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-25 17:20:11.748   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 17:20:11.749   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 17:20:11.754  1694  4113 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 17:20:11.754  1694  4113 I SystemUpdateService: now status is 0 (complete)
08-25 17:20:11.754  1694  4113 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 17:20:11.755  1694  4113 I SystemUpdateService: file has been verified
,08-25 17:20:11.755  1694  4113 I SystemUpdateService: OTA package size = 12249756
,08-25 17:20:11.762  1694  4113 I SystemUpdateService: showing system update notification
,08-25 17:20:11.764  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 17:20:11.767  1694  2405 I iu.UploadsManager: num queued entries: 0
,08-25 17:20:11.768  1694  2405 I iu.UploadsManager: num updated entries: 0
,08-25 17:20:11.769  1694  2405 I iu.SyncManager: NEXT; no task
,08-25 17:20:11.771  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 17:20:11.772  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 17:20:11.774  1694  4117 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 17:20:11.774  1694  4117 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 17:20:11.775  1694  4117 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
08-25 17:20:11.778  1694  1694 D SystemUpdateService: onDestroy
08-25 17:20:11.778  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:20:11.783  4002  4002 D SprintDMHelper: simOperator: 
,08-25 17:20:11.783  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:20:11.787  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 17:20:11.788  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:11.821  1494  2966 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 17:20:11.821  1494  2966 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 17:20:11.821  1494  2966 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:20:11.821  1494  2966 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:20:11.834  1694  4117 E MDM     : [173] SitrepService.a: Error sending sitrep.
,08-25 17:20:11.906  3935  4119 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 17:20:12.699   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 17:20:13.413  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:13.455  1494  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 17:20:13.455  1494  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 17:20:13.455  1494  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 17:20:13.455  1494  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:20:13.484  3497  3497 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 17:20:13.484  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-25 17:20:13.484  3497  3497 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 17:20:13.556   873  2090 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,08-25 17:20:13.556   873  2090 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:20:13.596  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 17:20:13.605   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 17:20:13.605   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 17:20:13.606   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 17:20:13.606   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:13.622   873  1860 D DhcpClient: Clearing IP address
08-25 17:20:13.623   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:20:13.627   372   871 D CommandListener: Setting iface cfg
,08-25 17:20:13.636  1494  4124 V NativeCrypto: Read error: ssl=0x9a751000: I/O error during system call, Connection timed out
,08-25 17:20:13.641  1494  4124 V NativeCrypto: SSL shutdown failed: ssl=0x9a751000: I/O error during system call, Broken pipe
08-25 17:20:13.643   873  4103 D DhcpClient: Receive thread stopped
,08-25 17:20:13.646   873  1963 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-25 17:20:13.646   873  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 17:20:13.647   873  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-25 17:20:13.648   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 17:20:13.649   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-25 17:20:13.654   395   395 E Parcel  : Reading a NULL string not supported here.
,08-25 17:20:13.654   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-25 17:20:13.660   873  4101 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-25 17:20:13.661   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 17:20:13.662   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-25 17:20:13.668   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 17:20:13.671   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:13.673  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:13.673  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:13.673  2028  2308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 17:20:13.673  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:13.673  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:13.674  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:13.674  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:13.674  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:13.674  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:13.677   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-25 17:20:13.698   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:13.715   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:13.716   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 17:20:13.716   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 17:20:13.717   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 17:20:13.721  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:13.723  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:13.726  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 17:20:13.729  1694  1694 D SystemUpdateService: onCreate
,08-25 17:20:13.731  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:20:13.736  1694  4139 I SystemUpdateService: active receiver: enabled
,08-25 17:20:13.738  1694  4139 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:20:13.740  1694  4139 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 17:20:13.741  1694  4139 I SystemUpdateService: now status is 0 (complete)
,08-25 17:20:13.741  1694  4139 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 17:20:13.741  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-25 17:20:13.741  1694  4139 I SystemUpdateService: file has been verified
08-25 17:20:13.743  1694  4139 I SystemUpdateService: OTA package size = 12249756
,08-25 17:20:13.744  1694  2405 I iu.UploadsManager: num queued entries: 0
,08-25 17:20:13.749  1694  4139 I SystemUpdateService: showing system update notification
,08-25 17:20:13.750  1694  2405 I iu.UploadsManager: num updated entries: 0
,08-25 17:20:13.751  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 17:20:13.752  1694  2405 I iu.SyncManager: NEXT; no task
,08-25 17:20:13.753  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 17:20:13.756  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:20:13.760  4002  4002 D SprintDMHelper: simOperator: 
,08-25 17:20:13.760  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:20:13.766  1694  1694 D SystemUpdateService: onDestroy
,08-25 17:20:13.776  3935  4143 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 17:20:13.806   372   871 E Netd    : netlink response contains error (No such file or directory)
08-25 17:20:13.807   873  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 17:20:13.807   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 17:20:13.916   873  1997 I ActivityManager: Killing 3763:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-25 17:20:16.616   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5ae60d:true
,08-25 17:20:16.616  3962  3962 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 17:20:16.621  3962  3962 I bt_bluedroid: init
,08-25 17:20:16.621  3962  4148 I BluetoothAdapterState: Entering OffState
,08-25 17:20:16.627  3962  4149 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 17:20:16.627  3962  4149 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 17:20:16.628  3962  4149 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:20:16.628  3962  4149 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 17:20:16.630  3962  3962 I bt_bluedroid: get_profile_interface socket
,08-25 17:20:16.633  3962  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 17:20:16.635  3962  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:20:16.636  3962  3962 I bt_bluedroid: get_profile_interface sdp
,08-25 17:20:16.643  3962  3973 I bt_bluedroid: config_hci_snoop_log
,08-25 17:20:16.648   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 17:20:16.657  3962  4148 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 17:20:16.658  3962  4148 D BluetoothAdapterProperties: Setting state to 14
,08-25 17:20:16.659  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 17:20:16.663  3962  4148 D BluetoothBondStateMachine: make
,08-25 17:20:16.668  3962  4153 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:20:16.679  3962  3962 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 17:20:16.680  3962  4148 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:20:16.687  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:16.690  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 17:20:16.691  3962  3962 D BtGatt.GattService: Received start request. Starting profile...
,08-25 17:20:16.692  3962  3962 D BtGatt.GattService: start()
08-25 17:20:16.692  3962  3962 I bt_bluedroid: get_profile_interface gatt
,08-25 17:20:16.694  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:16.695  3962  3962 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:20:16.710  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:16.711  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:16.711  3962  3962 V BluetoothAdapterState: isBleTurningOn()=true
08-25 17:20:16.712  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:16.713  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 17:20:16.714  3962  4148 I bt_bluedroid: enable
,08-25 17:20:16.714  3962  4149 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 17:20:16.715  3962  4149 I bt_hci  : start_up
,08-25 17:20:16.738  3962  4149 I bt_vendor: alloc value 0xb39f9189
,08-25 17:20:16.738  3962  4149 I bt_vendor: init
,08-25 17:20:16.738  3962  4149 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 17:20:16.738  3962  4149 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 17:20:16.846  3962  4149 D bt_hci  : start_up starting async portion
,08-25 17:20:16.847  3962  4156 I bt_hci  : event_finish_startup
,08-25 17:20:16.847  3962  4156 I bt_hci_h4: hal_open
08-25 17:20:16.848  3962  4156 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 17:20:16.859  3962  4156 I bt_userial_vendor: device fd = 51 open
,08-25 17:20:16.890  3962  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:20:16.921  3962  4156 D bt_hwcfg: Chipset BCM4354A2
08-25 17:20:16.922  3962  4156 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 17:20:16.923  3962  4156 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 17:20:17.621  3962  4156 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 17:20:17.623  3962  4156 D bt_hwcfg: Settlement delay -- 100 ms
08-25 17:20:17.623  3962  4156 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 17:20:17.740  3962  4156 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:20:17.741  3962  4156 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 17:20:17.771  3962  4156 I bt_hwcfg: vendor lib fwcfg completed
,08-25 17:20:17.771  3962  4156 I bt_vendor: firmware callback
08-25 17:20:17.771  3962  4156 I bt_hci  : firmware_config_callback
,08-25 17:20:17.782  3962  4158 I bt_btu  : btu_task pending for preload complete event
,08-25 17:20:17.783  3962  4158 I bt_btu_task: Bluetooth chip preload is complete
08-25 17:20:17.783  3962  4158 I bt_btu  : btu_task received preload complete event
,08-25 17:20:17.792  3962  4158 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 17:20:17.793  3962  4158 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:20:17.793  3962  4158 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 17:20:17.793  3962  4158 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 17:20:17.794  3962  4158 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 17:20:17.794  3962  4158 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 17:20:17.794  3962  4158 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:20:17.794  3962  4158 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 17:20:17.795  3962  4158 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 17:20:17.795  3962  4158 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:20:17.795  3962  4158 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:20:17.796  3962  4158 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 17:20:17.796  3962  4158 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:20:17.796  3962  4158 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:20:17.796  3962  4158 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:20:17.933  3962  4158 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-25 17:20:17.933  3962  4158 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-25 17:20:17.943  3962  4152 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 17:20:17.944  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 17:20:17.945  3962  4152 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 17:20:17.949  3962  4152 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:20:17.953  3962  4152 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:20:17.955  3962  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:20:17.958  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:17.959  3962  4152 D bt_hci  : do_postload posting postload work item
,08-25 17:20:17.959  3962  4156 I bt_hci  : event_postload
,08-25 17:20:17.960  3962  4156 I bt_vendor: sco_config_cb
,08-25 17:20:17.960  3962  4156 I bt_hci  : sco_config_callback postload finished.
,08-25 17:20:17.961  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:17.966  3962  4152 D bt_bte_conf: Device ID record 1 : primary
08-25 17:20:17.967  3962  4152 D bt_bte_conf:   vendorId            = 000f
,08-25 17:20:17.967  3962  4156 I bt_vendor: low_power_mode_cb
08-25 17:20:17.967  3962  4152 D bt_bte_conf:   vendorIdSource      = 0001
08-25 17:20:17.967  3962  4152 D bt_bte_conf:   product             = 1200
08-25 17:20:17.967  3962  4152 D bt_bte_conf:   version             = 1436
08-25 17:20:17.967  3962  4152 D bt_bte_conf:   clientExecutableURL = 
08-25 17:20:17.968  3962  4152 D bt_bte_conf:   serviceDescription  = 
08-25 17:20:17.968  3962  4152 D bt_bte_conf:   documentationURL    = 
08-25 17:20:17.968  3962  4152 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 17:20:17.968  3962  4149 D bt_stack_manager: event_start_up_stack finished
08-25 17:20:17.970  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 17:20:17.971  3962  4148 D BluetoothAdapterProperties: Setting state to 15
08-25 17:20:17.971  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 17:20:17.972  3962  4148 I BluetoothAdapterState: Entering BleOnState
,08-25 17:20:17.977  3962  4148 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 17:20:17.978  3962  4148 D BluetoothAdapterProperties: Setting state to 11
08-25 17:20:17.978  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 17:20:17.986  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:17.987  3962  3962 D HeadsetService: Received start request. Starting profile...
08-25 17:20:17.990  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:17.991  3962  3962 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 17:20:17.991  3962  3962 D HeadsetStateMachine: make
08-25 17:20:17.993  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:18.004  3962  4148 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:20:18.004  3962  3962 D HeadsetStateMachine: max_hf_connections = 1
08-25 17:20:18.004  3962  3962 I bt_bluedroid: get_profile_interface handsfree
08-25 17:20:18.005  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 17:20:18.005  3962  4152 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 17:20:18.010  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:18.011  3962  3962 D A2dpService: Received start request. Starting profile...
,08-25 17:20:18.011  3962  3962 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:20:18.013  3962  3962 I bt_bluedroid: get_profile_interface avrcp
,08-25 17:20:18.021  3962  3962 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 17:20:18.021  3962  3962 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 17:20:18.021  3962  3962 D A2dpStateMachine: make
08-25 17:20:18.022  3962  3962 I bt_bluedroid: get_profile_interface a2dp
,08-25 17:20:18.023  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 17:20:18.027  3962  4167 D A2dpStateMachine: Enter Disconnected: -2
,08-25 17:20:18.028  3962  3962 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:20:18.028  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:18.030  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:18.031  3962  3962 D HidService: Received start request. Starting profile...
08-25 17:20:18.031  3962  3962 I bt_bluedroid: get_profile_interface hidhost
08-25 17:20:18.031  3962  3962 D HidService: setHidService(): set to: null
08-25 17:20:18.031  3962  4152 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-25 17:20:18.031  3885  3885 D BluetoothInputDevice: Proxy object connected
08-25 17:20:18.031  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 17:20:18.032  3962  3962 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:20:18.033  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
08-25 17:20:18.033  3885  3885 D HidProfile: Bluetooth service connected
,08-25 17:20:18.034  3962  3962 D HealthService: Received start request. Starting profile...
,08-25 17:20:18.035  3962  3962 I bt_bluedroid: get_profile_interface health
,08-25 17:20:18.036  3962  3962 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 17:20:18.036  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:18.037  3962  3962 D PanService: Received start request. Starting profile...
,08-25 17:20:18.037  3962  3962 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 17:20:18.037  3962  3962 I bt_bluedroid: get_profile_interface pan
08-25 17:20:18.037  3885  3885 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:20:18.038  3962  4152 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:20:18.039  3885  3885 D PanProfile: Bluetooth service connected
,08-25 17:20:18.041  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:18.042  3962  3962 D BluetoothMapService: Received start request. Starting profile...
,08-25 17:20:18.042  3962  3962 D BluetoothMapService: start()
,08-25 17:20:18.043  3885  3885 D BluetoothMap: Proxy object connected
,08-25 17:20:18.043  3885  3885 D MapProfile: Bluetooth service connected
,08-25 17:20:18.044  3885  3885 D BluetoothMap: getConnectedDevices()
08-25 17:20:18.045  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 17:20:18.045  3885  3885 D BluetoothMap: Bluetooth is Not enabled
,08-25 17:20:18.045  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 17:20:18.045  3962  3962 D BluetoothMapAppObserver: createReceiver()
08-25 17:20:18.046  3962  3962 D BluetoothMapAppObserver: initObservers()
,08-25 17:20:18.046  3962  3962 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 17:20:18.052  3962  4165 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 17:20:18.053  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:18.053  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.053  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:18.053  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:18.055  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:18.055  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.055  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:20:18.055  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:18.057  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:18.057  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.057  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:18.057  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:18.058  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:18.058  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.058  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:18.058  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:18.059  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:18.059  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 17:20:18.059  3962  4148 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:20:18.059  3962  4148 D BluetoothAdapterProperties: State =  11
,08-25 17:20:18.062  3962  4152 D BluetoothAdapterProperties: Scan Mode:21
,08-25 17:20:18.062  3962  4152 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:20:18.063  3962  4148 D BluetoothAdapterProperties: Setting state to 12
08-25 17:20:18.063  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:20:18.063  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 17:20:18.064  3962  4148 I BluetoothAdapterState: Entering OnState
,08-25 17:20:18.066  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:18.066  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:18.067  1349  1349 D BluetoothInputDevice: Proxy object connected
,08-25 17:20:18.067  1349  1349 D HidProfile: Bluetooth service connected
08-25 17:20:18.067  3885  3897 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:20:18.068  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:20:18.068  1928  2324 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:18.069   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:18.069  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:20:18.070   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:20:18.071  3885  3895 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:20:18.071  1349  1349 D BluetoothA2dp: Proxy object connected
,08-25 17:20:18.071  3885  3897 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:18.071  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:18.071   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:20:18.072   873   873 D BluetoothA2dp: Proxy object connected
08-25 17:20:18.072  3885  3895 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:20:18.072  1349  1360 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:20:18.073  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 17:20:18.073  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:20:18.074  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:20:18.074  1349  1349 D PanProfile: Bluetooth service connected
08-25 17:20:18.074  1349  2023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:18.074  3962  3962 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 17:20:18.074   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:18.074  1349  1361 D BluetoothMap: onBluetoothStateChange: up=true
08-25 17:20:18.075  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:18.076  1349  1349 D BluetoothMap: Proxy object connected
08-25 17:20:18.076  1349  1349 D MapProfile: Bluetooth service connected
08-25 17:20:18.076  1349  1349 D BluetoothMap: getConnectedDevices()
08-25 17:20:18.079   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 17:20:18.079  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 17:20:18.080  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:18.080  3962  3962 D ObexServerSockets: Succeed to create listening sockets 
08-25 17:20:18.080  3885  3885 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 17:20:18.080  3962  3962 D ObexServerSockets0: startAccept()
,08-25 17:20:18.080  3962  3962 D ObexServerSockets0: prepareForNewConnect()
08-25 17:20:18.081  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:18.083  3962  4174 D ObexServerSockets0: Accepting socket connection...
08-25 17:20:18.083  3885  3885 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 17:20:18.084  3962  3962 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 17:20:18.084  3962  3962 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 17:20:18.084  3962  4175 D ObexServerSockets0: Accepting socket connection...
,08-25 17:20:18.084  3962  3962 D BluetoothMapService: onReceive
08-25 17:20:18.084  3962  3962 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:20:18.084  3962  3962 D BluetoothMapService: STATE_ON
,08-25 17:20:18.091  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:20:18.094  3885  3885 D BluetoothA2dp: Proxy object connected
,08-25 17:20:18.099  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:18.102  3885  3885 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:20:18.109  1349  1349 D BluetoothPbap: Proxy object connected
,08-25 17:20:18.109  1349  1349 D PbapServerProfile: Bluetooth service connected
08-25 17:20:18.110  3885  3885 D BluetoothPbap: Proxy object connected
08-25 17:20:18.111  3885  3885 D PbapServerProfile: Bluetooth service connected
,08-25 17:20:18.113  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:20:18.113  3962  3962 D ObexServerSockets0: prepareForNewConnect()
08-25 17:20:18.115  3962  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:18.128  3962  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:18.130  3962  4183 I BtOppRfcommListener: Accept thread started.
,08-25 17:20:18.172  1349  1360 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.172  1349  1349 D HeadsetProfile: Bluetooth service connected
08-25 17:20:18.172   873   873 D BluetoothHeadset: Proxy object connected
08-25 17:20:18.172   873   873 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.173  1928  2071 D BluetoothHeadset: Proxy object connected
08-25 17:20:18.175   873   873 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.175  1349  1361 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.176  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-25 17:20:18.175   873   890 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.188  3885  3897 D BluetoothHeadset: Proxy object connected
,08-25 17:20:18.191  3885  3885 D HeadsetProfile: Bluetooth service connected
,08-25 17:20:19.574  3962  4148 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 17:20:19.574  3962  4148 D BluetoothAdapterProperties: Setting state to 13
08-25 17:20:19.575  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 17:20:19.577  3962  4148 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 17:20:19.586   873  1305 D ConnectivityService: handlePromptUnvalidated 101
08-25 17:20:19.585  3962  4148 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:20:19.589  3962  3962 D BluetoothMapService: onReceive
08-25 17:20:19.589  3962  3962 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:20:19.590  3962  3962 D BluetoothMapService: STATE_TURNING_OFF
,08-25 17:20:19.590  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:19.590  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:19.591  3962  3962 D BluetoothMapService: MAP Service closeService in
08-25 17:20:19.591  3962  3962 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 17:20:19.591  3962  3962 D ObexServerSockets0: shutdown(block = true)
,08-25 17:20:19.593  3962  4174 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 17:20:19.593  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:19.593  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:19.594  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 17:20:19.598  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:19.598  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:19.599  3962  4161 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 17:20:19.599  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 17:20:19.599  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 17:20:19.599  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:19.600  3962  4152 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:20:19.600  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-25 17:20:19.604  3962  4175 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 17:20:19.604  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.606  3962  3962 I BtOppRfcommListener: stopping Accept Thread
,08-25 17:20:19.606  3962  4183 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 17:20:19.606  3962  4183 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 17:20:19.607  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.609  3962  3962 D HeadsetService: Received stop request...Stopping profile...
,08-25 17:20:19.611  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:20:19.612  1349  2023 D BluetoothHeadset: Proxy object disconnected
08-25 17:20:19.612  1349  1349 D HeadsetProfile: Bluetooth service disconnected
08-25 17:20:19.613   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 17:20:19.613   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:19.613  3962  3962 D A2dpService: Received stop request...Stopping profile...
08-25 17:20:19.613  3962  4167 D A2dpStateMachine: Exit Disconnected: -1
08-25 17:20:19.615  1349  1349 D BluetoothA2dp: Proxy object disconnected
08-25 17:20:19.616  3885  3895 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:19.616  1928  1939 D BluetoothHeadset: Proxy object disconnected
,08-25 17:20:19.616   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 17:20:19.616  3962  3962 D HidService: Received stop request...Stopping profile...
08-25 17:20:19.617  3962  3962 D HidService: Stopping Bluetooth HidService
08-25 17:20:19.617   873   873 D BluetoothA2dp: Proxy object disconnected
08-25 17:20:19.617  1349  1349 D BluetoothInputDevice: Proxy object disconnected
08-25 17:20:19.617  1349  1349 D HidProfile: Bluetooth service disconnected
08-25 17:20:19.618  3962  3962 D HealthService: Received stop request...Stopping profile...
,08-25 17:20:19.619  3962  3962 D PanService: Received stop request...Stopping profile...
08-25 17:20:19.620  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:20:19.620  1349  1349 D PanProfile: Bluetooth service disconnected
,08-25 17:20:19.623  3962  3962 D BluetoothMapService: Received stop request...Stopping profile...
08-25 17:20:19.623  3962  3962 D BluetoothMapService: stop()
,08-25 17:20:19.624  3962  3962 D BluetoothMapAppObserver: deinitObservers()
,08-25 17:20:19.624  3962  3962 D BluetoothMapAppObserver: removeReceiver()
08-25 17:20:19.624  3885  3885 D DockEventReceiver: finishStartingService: stopping service
08-25 17:20:19.625  1349  1349 D BluetoothMap: Proxy object disconnected
08-25 17:20:19.625  1349  1349 D MapProfile: Bluetooth service disconnected
,08-25 17:20:19.625  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:20:19.625  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:19.625  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.626  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.626  3885  3885 D BluetoothA2dp: Proxy object disconnected
,08-25 17:20:19.626  3885  3885 D HeadsetProfile: Bluetooth service disconnected
,08-25 17:20:19.627  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 17:20:19.627  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 17:20:19.627  3885  3885 D BluetoothInputDevice: Proxy object disconnected
08-25 17:20:19.627  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:20:19.627  3885  3885 D HidProfile: Bluetooth service disconnected
08-25 17:20:19.627  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:19.628  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:19.628  3885  3885 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 17:20:19.628  3885  3885 D PanProfile: Bluetooth service disconnected
,08-25 17:20:19.629  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 17:20:19.629  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:19.629  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:19.629  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.629  3962  4152 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 17:20:19.629  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.630  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:20:19.630  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 17:20:19.631  3962  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:20:19.631  3962  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 17:20:19.631  3962  4158 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 17:20:19.631  3962  4158 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 17:20:19.631  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 17:20:19.632  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-25 17:20:19.632  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:19.632  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.632  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.633  3885  3885 D BluetoothMap: Proxy object disconnected
08-25 17:20:19.634  3885  3885 D MapProfile: Bluetooth service disconnected
08-25 17:20:19.635  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-25 17:20:19.635  3962  4152 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 17:20:19.635  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 17:20:19.636  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 17:20:19.636  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:19.636  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:19.636  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.636  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.636  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 17:20:19.636  3962  4152 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 17:20:19.636  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 17:20:19.637  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:19.637  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:19.637  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.637  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.637  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 17:20:19.637  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 17:20:19.638  3962  3962 D BluetoothMapService: MAP Service closeService in
08-25 17:20:19.638  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-25 17:20:19.638  3962  3962 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:19.638  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:19.638  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:19.639  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 17:20:19.639  3962  4148 D BluetoothAdapterProperties: Setting state to 15
08-25 17:20:19.639  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 17:20:19.639  3962  4148 I BluetoothAdapterState: Entering BleOnState
08-25 17:20:19.639  3962  3962 D BluetoothMapService: cleanup()
,08-25 17:20:19.639  3962  3962 D BluetoothMapService: MAP Service closeService in
,08-25 17:20:19.642  3885  3885 D BluetoothPbap: Proxy object disconnected
08-25 17:20:19.642  3885  3885 D PbapServerProfile: Bluetooth service disconnected
,08-25 17:20:19.642  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 17:20:19.642  1349  1349 D BluetoothPbap: Proxy object disconnected
08-25 17:20:19.642  1349  1349 D PbapServerProfile: Bluetooth service disconnected
,08-25 17:20:19.642  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 17:20:19.643  3885  3897 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 17:20:19.646  1928  1958 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:19.646   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:19.646  1349  2023 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:20:19.646   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:20:19.647  3885  4186 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 17:20:19.648  3885  3895 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:19.648  3885  3897 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 17:20:19.648  3885  4186 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 17:20:19.649   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 17:20:19.649  3885  3895 D BluetoothPan: onBluetoothStateChange on: false
,08-25 17:20:19.650  1349  1361 D BluetoothPan: onBluetoothStateChange on: false
,08-25 17:20:19.650  1349  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 17:20:19.650   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 17:20:19.650  1349  2023 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 17:20:19.651  3962  4148 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-25 17:20:19.651  3962  4148 D BluetoothAdapterProperties: Setting state to 16
08-25 17:20:19.651  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 17:20:19.651  3962  4148 D BluetoothAdapterProperties: onBleDisable
08-25 17:20:19.652  3962  4148 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:20:19.652  3962  4149 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-25 17:20:19.653  3962  4158 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 17:20:19.653  3962  4158 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 17:20:19.654  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.654  3962  4152 D BluetoothAdapterProperties: Scan Mode:20
08-25 17:20:19.655  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.657  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.657  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 17:20:19.658  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:19.661  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:19.664  3885  3885 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:20:19.855  3962  4152 I bt_hci  : shut_down
,08-25 17:20:19.874  3962  4156 D bt_hwcfg: hw_epilog_process
,08-25 17:20:19.875  3962  4156 I bt_vendor: low_power_mode_cb
,08-25 17:20:19.889  3962  4156 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 17:20:19.889  3962  4156 I bt_vendor: epilog_cb
08-25 17:20:19.890  3962  4156 I bt_hci  : epilog_finished_callback
,08-25 17:20:19.899  3962  4152 I bt_hci_h4: hal_close
,08-25 17:20:19.901  3962  4152 I bt_userial_vendor: device fd = 51 close
,08-25 17:20:20.020  3962  4149 D bt_stack_manager: event_shut_down_stack finished.
,08-25 17:20:20.021  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 17:20:20.027  3962  4148 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 17:20:20.027  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:20:20.029  3962  3962 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 17:20:20.029  3962  3962 D BtGatt.GattService: stop()
08-25 17:20:20.030  3962  3962 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 17:20:20.034  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:20.035  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-25 17:20:20.035  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:20.035  3962  3962 V BluetoothAdapterState: isBleTurningOff()=true
08-25 17:20:20.036  3962  4148 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 17:20:20.037  3962  4148 D BluetoothAdapterProperties: Setting state to 10
08-25 17:20:20.037  3962  4148 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 17:20:20.038  3962  4148 I BluetoothAdapterState: Entering OffState
,08-25 17:20:20.041   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 17:20:20.064  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 17:20:20.064  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 17:20:20.065  3962  3962 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 17:20:20.066  3962  4149 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 17:20:20.074  3962  4149 D bt_stack_manager: event_clean_up_stack finished.
,08-25 17:20:20.079  3962  3962 I art     : System.exit called, status: 0
,08-25 17:20:20.080  3962  3962 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 17:20:20.130   873  1384 I ActivityManager: Process com.android.bluetooth (pid 3962) has died
,08-25 17:20:22.571  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:22.572  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:24.293   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 17:20:24.303  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 17:20:24.310   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 17:20:24.310   873   893 I Adreno  : Build Date                       : 10/20/15
08-25 17:20:24.310   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 17:20:24.310   873   893 I Adreno  : Local Branch                     : M14
,08-25 17:20:24.310   873   893 I Adreno  : Remote Branch                    : 
08-25 17:20:24.310   873   893 I Adreno  : Remote Branch                    : 
08-25 17:20:24.310   873   893 I Adreno  : Reconstruct Branch               : 
,08-25 17:20:24.363   280  1294 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (211 us)
,08-25 17:20:24.981  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:20:24.982  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 17:20:25.042   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 17:20:25.044  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7f27f94 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@bfa8e3e, 16908290=android.view.AbsSavedState$1@bfa8e3e}, android:focusedViewId=100}]}]
,08-25 17:20:25.044  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 17:20:25.045  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 17:20:25.045  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 17:20:25.050   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 17:20:25.053   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 17:20:25.055   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-25 17:20:25.055   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 17:20:25.290   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 17:20:25.293   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-25 17:20:25.294   873  1329 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,08-25 17:20:25.297   873   893 I DreamManagerService: Entering dreamland.
,08-25 17:20:25.301   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 17:20:25.299   873   893 I PowerManagerService: Dozing...
,08-25 17:20:25.342   376  1274 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-25 17:20:25.342   376  1274 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 17:20:25.353   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:25.358  1916  4195 D NfcService: Discovery configuration equal, not updating.
,08-25 17:20:25.358   873  1303 E native  : do suspend false
,08-25 17:20:25.381   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:25.384   873  1303 E native  : do suspend true
,08-25 17:20:25.485   376  1311 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 17:20:25.486   376  1311 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 17:20:25.579  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:25.580  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f9a49f added. We now have 6 listener(s)
08-25 17:20:25.580  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:25.584  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:25.584  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66db9ec added. We now have 7 listener(s)
08-25 17:20:25.584  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:25.586  3815  3865 I System.out: IsBluetoothEnabled
,08-25 17:20:25.599  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:25.648   873   890 I ActivityManager: Start proc 4201:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 17:20:25.809  4201  4201 D AdapterServiceConfig: Adding HeadsetService
08-25 17:20:25.809  4201  4201 D AdapterServiceConfig: Adding A2dpService
08-25 17:20:25.809  4201  4201 D AdapterServiceConfig: Adding HidService
08-25 17:20:25.810  4201  4201 D AdapterServiceConfig: Adding HealthService
08-25 17:20:25.810  4201  4201 D AdapterServiceConfig: Adding PanService
08-25 17:20:25.810  4201  4201 D AdapterServiceConfig: Adding GattService
08-25 17:20:25.810  4201  4201 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 17:20:25.827   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26b4385:true
,08-25 17:20:25.828  4201  4201 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 17:20:25.837  4201  4213 I BluetoothAdapterState: Entering OffState
08-25 17:20:25.837  4201  4201 I bt_bluedroid: init
,08-25 17:20:25.843  4201  4214 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 17:20:25.843  4201  4214 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 17:20:25.844  4201  4214 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 17:20:25.845  4201  4214 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 17:20:25.847  4201  4201 I bt_bluedroid: get_profile_interface socket
,08-25 17:20:25.851  4201  4201 I bt_bluedroid: get_profile_interface sdp
,08-25 17:20:25.852  4201  4217 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 17:20:25.854  4201  4212 I bt_bluedroid: config_hci_snoop_log
,08-25 17:20:25.855  4201  4217 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:20:25.856   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 17:20:25.863  4201  4213 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 17:20:25.863  4201  4213 D BluetoothAdapterProperties: Setting state to 14
08-25 17:20:25.863  4201  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-25 17:20:25.867  4201  4213 D BluetoothBondStateMachine: make
,08-25 17:20:25.871  4201  4218 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 17:20:25.878  4201  4213 I BluetoothAdapterState: Entering PendingCommandState
,08-25 17:20:25.879  4201  4201 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 17:20:25.882  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:25.883  4201  4201 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 17:20:25.884  4201  4201 D BtGatt.GattService: Received start request. Starting profile...
,08-25 17:20:25.884  4201  4201 D BtGatt.GattService: start()
08-25 17:20:25.884  4201  4201 I bt_bluedroid: get_profile_interface gatt
,08-25 17:20:25.885  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:25.885  4201  4201 D BtGatt.AdvertiseManager: advertise manager created
,08-25 17:20:25.894  4201  4201 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:25.895  4201  4201 V BluetoothAdapterState: isTurningOn()=false
,08-25 17:20:25.895  4201  4201 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 17:20:25.895  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:25.895  4201  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 17:20:25.896  4201  4213 I bt_bluedroid: enable
,08-25 17:20:25.896  4201  4214 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-25 17:20:25.897  4201  4214 I bt_hci  : start_up
,08-25 17:20:25.907  4201  4214 I bt_vendor: alloc value 0xb3a6a189
,08-25 17:20:25.907  4201  4214 I bt_vendor: init
08-25 17:20:25.907  4201  4214 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-25 17:20:25.907  4201  4214 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 17:20:26.013  4201  4214 D bt_hci  : start_up starting async portion
,08-25 17:20:26.013  4201  4221 I bt_hci  : event_finish_startup
,08-25 17:20:26.014  4201  4221 I bt_hci_h4: hal_open
08-25 17:20:26.016  4201  4221 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 17:20:26.024  4201  4221 I bt_userial_vendor: device fd = 51 open
,08-25 17:20:26.057  4201  4221 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:20:26.088  4201  4221 D bt_hwcfg: Chipset BCM4354A2
,08-25 17:20:26.088  4201  4221 D bt_hwcfg: Target name = [BCM4354A2]
08-25 17:20:26.089  4201  4221 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 17:20:26.747  4201  4221 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 17:20:26.748  4201  4221 D bt_hwcfg: Settlement delay -- 100 ms
08-25 17:20:26.748  4201  4221 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 17:20:26.865  4201  4221 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 17:20:26.866  4201  4221 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 17:20:26.896  4201  4221 I bt_hwcfg: vendor lib fwcfg completed
,08-25 17:20:26.896  4201  4221 I bt_vendor: firmware callback
08-25 17:20:26.896  4201  4221 I bt_hci  : firmware_config_callback
,08-25 17:20:26.908  4201  4223 I bt_btu  : btu_task pending for preload complete event
,08-25 17:20:26.908  4201  4223 I bt_btu_task: Bluetooth chip preload is complete
08-25 17:20:26.908  4201  4223 I bt_btu  : btu_task received preload complete event
,08-25 17:20:26.919  4201  4223 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 17:20:26.920  4201  4223 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 17:20:26.920  4201  4223 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 17:20:26.920  4201  4223 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 17:20:26.921  4201  4223 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 17:20:26.921  4201  4223 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 17:20:26.921  4201  4223 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 17:20:26.922  4201  4223 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 17:20:26.923  4201  4223 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 17:20:26.923  4201  4223 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 17:20:26.923  4201  4223 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 17:20:26.924  4201  4223 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 17:20:26.925  4201  4223 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 17:20:26.925  4201  4223 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 17:20:26.926  4201  4223 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 17:20:27.058  4201  4223 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39e7d9d
,08-25 17:20:27.058  4201  4223 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39e7d9d 
,08-25 17:20:27.075  4201  4217 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 17:20:27.077  4201  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 17:20:27.078  4201  4217 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 17:20:27.080  4201  4217 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 17:20:27.083  4201  4217 D BluetoothAdapterProperties: Scan Mode:20
,08-25 17:20:27.083  4201  4217 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 17:20:27.084  4201  4217 D bt_hci  : do_postload posting postload work item
,08-25 17:20:27.084  4201  4221 I bt_hci  : event_postload
08-25 17:20:27.084  4201  4221 I bt_vendor: sco_config_cb
,08-25 17:20:27.084  4201  4221 I bt_hci  : sco_config_callback postload finished.
08-25 17:20:27.087  4201  4217 D bt_bte_conf: Device ID record 1 : primary
08-25 17:20:27.088  4201  4217 D bt_bte_conf:   vendorId            = 000f
,08-25 17:20:27.088  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:27.088  4201  4217 D bt_bte_conf:   vendorIdSource      = 0001
08-25 17:20:27.088  4201  4217 D bt_bte_conf:   product             = 1200
,08-25 17:20:27.088  4201  4217 D bt_bte_conf:   version             = 1436
08-25 17:20:27.088  4201  4217 D bt_bte_conf:   clientExecutableURL = 
08-25 17:20:27.089  4201  4217 D bt_bte_conf:   serviceDescription  = 
,08-25 17:20:27.089  4201  4217 D bt_bte_conf:   documentationURL    = 
08-25 17:20:27.089  4201  4217 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 17:20:27.090  4201  4214 D bt_stack_manager: event_start_up_stack finished
08-25 17:20:27.090  4201  4221 I bt_vendor: low_power_mode_cb
,08-25 17:20:27.091  4201  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 17:20:27.092  4201  4213 D BluetoothAdapterProperties: Setting state to 15
08-25 17:20:27.092  4201  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 17:20:27.096  4201  4213 I BluetoothAdapterState: Entering BleOnState
,08-25 17:20:27.099  4201  4213 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 17:20:27.099  4201  4213 D BluetoothAdapterProperties: Setting state to 11
08-25 17:20:27.100  4201  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 17:20:27.112  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:27.112  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:27.117  4201  4201 D HeadsetService: Received start request. Starting profile...
,08-25 17:20:27.123  4201  4213 I BluetoothAdapterState: Entering PendingCommandState
08-25 17:20:27.123  4201  4201 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-25 17:20:27.124  4201  4201 D HeadsetStateMachine: make
,08-25 17:20:27.134  4201  4201 D HeadsetStateMachine: max_hf_connections = 1
,08-25 17:20:27.134  4201  4201 I bt_bluedroid: get_profile_interface handsfree
08-25 17:20:27.134  4201  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 17:20:27.135  4201  4217 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 17:20:27.138  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:27.139  4201  4201 D A2dpService: Received start request. Starting profile...
,08-25 17:20:27.139  4201  4201 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 17:20:27.140  4201  4201 I bt_bluedroid: get_profile_interface avrcp
,08-25 17:20:27.147  4201  4201 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 17:20:27.148  4201  4201 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 17:20:27.148  4201  4201 D A2dpStateMachine: make
,08-25 17:20:27.150  4201  4201 I bt_bluedroid: get_profile_interface a2dp
,08-25 17:20:27.151  4201  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 17:20:27.153  4201  4232 D A2dpStateMachine: Enter Disconnected: -2
08-25 17:20:27.153  4201  4201 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 17:20:27.154  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:27.155  4201  4201 D HidService: Received start request. Starting profile...
08-25 17:20:27.155  4201  4201 I bt_bluedroid: get_profile_interface hidhost
08-25 17:20:27.155  4201  4201 D HidService: setHidService(): set to: null
08-25 17:20:27.155  4201  4217 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c93e5
08-25 17:20:27.156  4201  4217 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 17:20:27.156  4201  4201 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 17:20:27.157  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
08-25 17:20:27.157  4201  4201 D HealthService: Received start request. Starting profile...
,08-25 17:20:27.159  4201  4201 I bt_bluedroid: get_profile_interface health
,08-25 17:20:27.162  4201  4201 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 17:20:27.162  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:27.164  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:27.165  4201  4201 D PanService: Received start request. Starting profile...
,08-25 17:20:27.166  4201  4201 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 17:20:27.166  4201  4201 I bt_bluedroid: get_profile_interface pan
,08-25 17:20:27.167  4201  4217 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 17:20:27.175  4201  4201 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:27.176  4201  4201 D BluetoothMapService: Received start request. Starting profile...
,08-25 17:20:27.177  4201  4201 D BluetoothMapService: start()
,08-25 17:20:27.182  4201  4201 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 17:20:27.184  4201  4201 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 17:20:27.184  4201  4201 D BluetoothMapAppObserver: createReceiver()
,08-25 17:20:27.187  4201  4201 D BluetoothMapAppObserver: initObservers()
,08-25 17:20:27.187  4201  4201 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 17:20:27.199  4201  4230 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 17:20:27.199  4201  4201 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:27.200  4201  4201 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:27.200  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:20:27.200  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:27.201  4201  4201 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:27.201  4201  4201 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:27.201  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:27.201  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isTurningOff()=false
,08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isTurningOn()=true
,08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:20:27.202  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isTurningOn()=true
08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isTurningOff()=false
08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isTurningOn()=true
,08-25 17:20:27.203  4201  4201 V BluetoothAdapterState: isBleTurningOn()=false
08-25 17:20:27.204  4201  4201 V BluetoothAdapterState: isBleTurningOff()=false
08-25 17:20:27.204  4201  4213 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 17:20:27.204  4201  4213 D BluetoothAdapterProperties: ScanMode =  20
08-25 17:20:27.204  4201  4213 D BluetoothAdapterProperties: State =  11
08-25 17:20:27.207  4201  4217 D BluetoothAdapterProperties: Scan Mode:21
,08-25 17:20:27.207  4201  4213 D BluetoothAdapterProperties: Setting state to 12
,08-25 17:20:27.207  4201  4213 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 17:20:27.208  4201  4217 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 17:20:27.208  4201  4213 I BluetoothAdapterState: Entering OnState
,08-25 17:20:27.208  1349  1360 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:20:27.211  1349  2023 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:27.211  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:27.214  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:27.216  3885  4186 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 17:20:27.218  1349  1349 D BluetoothInputDevice: Proxy object connected
08-25 17:20:27.218  1349  1349 D HidProfile: Bluetooth service connected
08-25 17:20:27.218  4201  4201 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:20:27.219  4201  4201 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 17:20:27.221  1928  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:27.221  4201  4201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:27.222   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:27.222  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:20:27.223  4201  4201 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:27.225   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 17:20:27.225  4201  4201 D ObexServerSockets: Succeed to create listening sockets 
08-25 17:20:27.225  4201  4201 D ObexServerSockets0: startAccept()
08-25 17:20:27.225  3885  3895 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 17:20:27.225  4201  4201 D ObexServerSockets0: prepareForNewConnect()
,08-25 17:20:27.228  4201  4201 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 17:20:27.228  3885  4186 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:27.228  4201  4201 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 17:20:27.229  3885  3895 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 17:20:27.229  4201  4237 D ObexServerSockets0: Accepting socket connection...
08-25 17:20:27.229  4201  4238 D ObexServerSockets0: Accepting socket connection...
08-25 17:20:27.230  1349  1349 D BluetoothA2dp: Proxy object connected
,08-25 17:20:27.232  3885  4186 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:20:27.234   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 17:20:27.234   873   873 D BluetoothA2dp: Proxy object connected
08-25 17:20:27.234  3885  3897 D BluetoothPan: onBluetoothStateChange on: true
,08-25 17:20:27.236  3885  3885 D BluetoothInputDevice: Proxy object connected
08-25 17:20:27.236  3885  3885 D HidProfile: Bluetooth service connected,
08-25 17:20:27.236  1349  1361 D BluetoothPan: onBluetoothStateChange on: true
08-25 17:20:27.238  3885  3885 D BluetoothA2dp: Proxy object connected
08-25 17:20:27.238  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 17:20:27.238  1349  1349 D PanProfile: Bluetooth service connected
08-25 17:20:27.239  1349  2023 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 17:20:27.239   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-25 17:20:27.240  1349  1360 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 17:20:27.240  3885  3885 D BluetoothMap: Proxy object connected
08-25 17:20:27.240  3885  3885 D MapProfile: Bluetooth service connected
,08-25 17:20:27.241  1349  1349 D BluetoothMap: Proxy object connected
08-25 17:20:27.242  3885  3885 D BluetoothMap: getConnectedDevices()
,08-25 17:20:27.242  1349  1349 D MapProfile: Bluetooth service connected
08-25 17:20:27.242  1349  1349 D BluetoothMap: getConnectedDevices()
08-25 17:20:27.242   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 17:20:27.244  4201  4201 D BluetoothMapService: onReceive
08-25 17:20:27.244  4201  4201 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 17:20:27.244  4201  4201 D BluetoothMapService: STATE_ON
08-25 17:20:27.246  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:27.248  3885  3885 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 17:20:27.248  3885  3885 D PanProfile: Bluetooth service connected
,08-25 17:20:27.254  3885  3885 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 17:20:27.261  3885  3885 D DockEventReceiver: finishStartingService: stopping service
,08-25 17:20:27.265  1494  1494 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 17:20:27.273  3885  3885 D BluetoothPbap: Proxy object connected
,08-25 17:20:27.273  3885  3885 D PbapServerProfile: Bluetooth service connected
08-25 17:20:27.273  4201  4201 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 17:20:27.274  4201  4201 D ObexServerSockets0: prepareForNewConnect()
08-25 17:20:27.274  1349  1349 D BluetoothPbap: Proxy object connected
08-25 17:20:27.274  1349  1349 D PbapServerProfile: Bluetooth service connected
,08-25 17:20:27.286  4201  4244 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:27.305  4201  4248 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 17:20:27.306  4201  4248 I BtOppRfcommListener: Accept thread started.
,08-25 17:20:27.324  1349  1361 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.324   873   890 D BluetoothHeadset: Proxy object connected
08-25 17:20:27.324  1349  1349 D HeadsetProfile: Bluetooth service connected
08-25 17:20:27.324   873   873 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.325   873   873 D BluetoothHeadset: Proxy object connected
08-25 17:20:27.325  3885  3897 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.325  3885  3885 D HeadsetProfile: Bluetooth service connected
08-25 17:20:27.326  1928  2324 D BluetoothHeadset: Proxy object connected
08-25 17:20:27.326   873   873 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.329  3885  3895 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.331  3885  3885 D HeadsetProfile: Bluetooth service connected
,08-25 17:20:27.339  1349  1360 D BluetoothHeadset: Proxy object connected
08-25 17:20:27.339  1349  1349 D HeadsetProfile: Bluetooth service connected
,08-25 17:20:27.340   873   890 D BluetoothHeadset: Proxy object connected
,08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:27.621  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:27.628  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:20:27.632  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:27.633  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e641b5 added. We now have 8 listener(s)
,08-25 17:20:27.633  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:27.638   873  1994 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,08-25 17:20:27.639   873  1994 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:20:27.651  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:27.652   873  1996 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-25 17:20:27.652   873  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 17:20:27.667   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:27.686  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 17:20:27.691  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 17:20:27.698   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-25 17:20:27.699   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 17:20:27.700   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-25 17:20:27.701   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 17:20:27.701   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 17:20:27.701   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 17:20:27.701   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 17:20:27.713   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-25 17:20:27.714   873  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,08-25 17:20:27.714   873  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 17:20:27.715   372   871 D CommandListener: Setting iface cfg
08-25 17:20:27.715   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 17:20:27.715   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 17:20:27.725   873  1303 E native  : do suspend true
,08-25 17:20:27.725   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 17:20:27.731   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 17:20:27.740   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 17:20:27.740   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:27.761   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 17:20:27.828   873  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 17:20:27.833  1449  1449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 17:20:28.279  1449  1449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 17:20:28.320  1449  1449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 17:20:28.321  1449  1449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 17:20:28.324   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 17:20:28.338   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:20:28.338   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:28.339   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 17:20:28.360   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 17:20:28.370   372   871 D CommandListener: Setting iface cfg
,08-25 17:20:28.372   873  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 17:20:28.388   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 17:20:28.413   873  4257 D DhcpClient: Receive thread started
,08-25 17:20:28.499   873  1303 E native  : do suspend false
,08-25 17:20:28.518   873  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 17:20:28.533   873  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-25 17:20:28.534   873  1860 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 17:20:28.537   873  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 17:20:28.554   873  4257 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 17:20:28.555   873  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 17:20:28.560   372   871 D CommandListener: Setting iface cfg
,08-25 17:20:28.570   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 17:20:28.573   873  1860 D DhcpClient: Scheduling renewal in 86399s
08-25 17:20:28.573   873  1303 E native  : do suspend true
,08-25 17:20:28.598   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 17:20:28.600   873  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 17:20:28.602   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 17:20:28.604   873  1305 D ConnectivityService: Adding iface wlan0 to network 102
08-25 17:20:28.605   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 17:20:28.672   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 17:20:28.673   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 17:20:28.674   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 17:20:28.676  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 17:20:28.678   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-25 17:20:28.679  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 17:20:28.679   873  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 17:20:28.683  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 17:20:28.684  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 17:20:28.686  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7f27f94 Bundle[{}]
08-25 17:20:28.688   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 17:20:28.689  3815  3865 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 17:20:28.690  3815  3865 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-25 17:20:28.690  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-25 17:20:28.691  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 17:20:28.692  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 17:20:28.693  3815  3865 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 17:20:28.695   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 17:20:28.695   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-25 17:20:28.695   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 17:20:28.695   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 17:20:28.695   873  1305 D ConnectivityService:    accepting network in place of null
,08-25 17:20:28.696   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 17:20:28.697   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 17:20:28.700  3815  3865 I System.out: Running OutgoingSocketThread
,08-25 17:20:28.701  3815  4262 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,08-25 17:20:28.703  3815  4262 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38241
,08-25 17:20:28.703  3815  4262 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 17:20:28.707   873  4256 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154614, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 17:20:28.724   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:28.749   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 17:20:28.753   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 17:20:28.754   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 17:20:28.758   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 17:20:28.758   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:28.771  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:28.773   873  4255 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-25 17:20:28.774  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:28.785  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 17:20:28.791  1694  1694 D SystemUpdateService: onCreate
,08-25 17:20:28.795  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 17:20:28.807  1694  4267 I SystemUpdateService: active receiver: enabled
,08-25 17:20:28.815  1694  4267 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 17:20:28.819  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 17:20:28.821  1694  2405 I iu.UploadsManager: num queued entries: 0
,08-25 17:20:28.821  1694  2405 I iu.UploadsManager: num updated entries: 0
,08-25 17:20:28.822  1694  2405 I iu.SyncManager: NEXT; no task
,08-25 17:20:28.826  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 17:20:28.828  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 17:20:28.829  1694  4267 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 17:20:28.830  1694  4267 I SystemUpdateService: now status is 0 (complete)
,08-25 17:20:28.833   873  4255 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 15:20:28 GMT], X-Android-Received-Millis=[1472138428832], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472138428810]}
,08-25 17:20:28.833  1694  4267 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 17:20:28.833  1694  4267 I SystemUpdateService: file has been verified
08-25 17:20:28.833  1694  4267 I SystemUpdateService: OTA package size = 12249756
,08-25 17:20:28.837   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 17:20:28.837  4002  4002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-25 17:20:28.838   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-25 17:20:28.838   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 17:20:28.844  4002  4002 D SprintDMHelper: simOperator: 
,08-25 17:20:28.844  4002  4002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 17:20:28.849   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 17:20:28.852  1694  4267 I SystemUpdateService: showing system update notification
,08-25 17:20:28.864  1694  4270 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 17:20:28.864  1694  4270 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 17:20:28.872  1694  4270 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 17:20:28.883  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:28.887  1494  1494 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 17:20:28.905  1694  1694 D SystemUpdateService: onDestroy
,08-25 17:20:28.928  1494  2964 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 17:20:28.928  1494  2964 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 17:20:28.928  1494  2964 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 17:20:28.928  1494  2964 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 17:20:28.946  1694  4270 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-25 17:20:28.967  3935  4273 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 17:20:29.703  3815  3865 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,08-25 17:20:29.703  3815  3865 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,08-25 17:20:29.713  3815  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-25 17:20:29.715  3815  3865 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 17:20:29.716  3815  3865 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,08-25 17:20:29.721  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:20:29.721  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80d504a added. We now have 2 listener(s)
,08-25 17:20:29.723  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:20:29.723  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.723  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:20:29.723  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:29.723  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5debbb added. We now have 9 listener(s)
,08-25 17:20:29.724  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:29.724  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:20:29.728  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:29.737  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:29.740  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:29.740  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:29.740  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.740  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3864431 added. We now have 3 listener(s)
,08-25 17:20:29.742  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:20:29.742  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.742  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.743  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:29.743  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d82716 added. We now have 10 listener(s)
08-25 17:20:29.743  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:29.743  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:29.743  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:20:29.743  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:29.743  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.743  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.743  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:20:29.743  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.744  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80d504a removed from the list
08-25 17:20:29.744  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.744  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5debbb removed from the list
08-25 17:20:29.745  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:29.745  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:20:29.746  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:29.746  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.746  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:20:29.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:29.749  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.749  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5debbb not in the list
,08-25 17:20:29.749  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.749  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.752  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.752  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:29.753  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.753  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d82716 removed from the list
08-25 17:20:29.753  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.753  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.753  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.753  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.753  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3864431 removed from the list
08-25 17:20:29.754  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.754  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f58897 added. We now have 2 listener(s)
,08-25 17:20:29.754   873  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-25 17:20:29.754  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:29.756  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.756  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.756  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.756  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:29.756  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af35a84 added. We now have 9 listener(s)
08-25 17:20:29.756  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:29.757  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:20:29.760  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:29.765  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:29.768  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:29.768  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:29.768  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.768  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a79ea2 added. We now have 3 listener(s)
,08-25 17:20:29.770  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.770  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:20:29.770  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.770  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.770  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e001733 added. We now have 10 listener(s)
08-25 17:20:29.771  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:29.771  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:20:29.771  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:20:29.771  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:20:29.771  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:29.771  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 17:20:29.773  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:29.775  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:20:29.775  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:20:29.777  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:29.779  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:20:29.779  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 17:20:29.779  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:29.783  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:20:29.783  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:20:29.784  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 17:20:29.784  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:29.787  4201  4229 D BtGatt.GattService: registerClient() - UUID=e18b38be-7081-40b3-a041-018aff5ba08e
,08-25 17:20:29.788  4201  4217 D BtGatt.GattService: onClientRegistered() - UUID=e18b38be-7081-40b3-a041-018aff5ba08e, clientIf=5
,08-25 17:20:29.789  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:20:29.790  4201  4212 D BtGatt.GattService: start scan with filters
,08-25 17:20:29.794  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:29.794  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:29.795  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:20:29.795  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:29.795  4201  4220 D BtGatt.ScanManager: handling starting scan
,08-25 17:20:29.798  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:29.798  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:20:29.798  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:29.800  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:29.801  4201  4220 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3e7ce8
,08-25 17:20:29.806  4201  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 17:20:29.806  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-25 17:20:29.807  3815  3865 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 17:20:29.807  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:20:29.807  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 17:20:29.807  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.807  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 17:20:29.807  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 17:20:29.807  4201  4220 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:20:29.807  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-25 17:20:29.807  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 17:20:29.807  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 17:20:29.808  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 17:20:29.808  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:20:29.808  3815  3865 D BluetoothAdapter: STATE_ON
08-25 17:20:29.809  4201  4212 D BtGatt.GattService: stopScan() - queue size =1
08-25 17:20:29.810  4201  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:20:29.810  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:20:29.810  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:20:29.810  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:20:29.811  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:20:29.811  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:29.812  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:29.812  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:20:29.812  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:20:29.812  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:20:29.816  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:29.817  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:29.817  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:29.817  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:29.820  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:29.820  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:29.820  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:29.820  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.820  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.820  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:29.821  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.821  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f58897 removed from the list
08-25 17:20:29.821  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.821  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af35a84 removed from the list
08-25 17:20:29.821  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-,25 17:20:29.821  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.822  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.822  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:29.824  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:20:29.824  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.824  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:29.825  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:29.825  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.825  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af35a84 not in the list
08-25 17:20:29.826  4201  4220 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:29.826  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.826  4201  4220 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:20:29.826  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:20:29.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.828  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e001733 removed from the list
,08-25 17:20:29.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.828  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.828  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.828  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:20:29.828  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a79ea2 removed from the list
08-25 17:20:29.829  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:20:29.829  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51af38f added. We now have 2 listener(s)
08-25 17:20:29.831  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:20:29.831  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.831  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.832  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 17:20:29.832  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249761c added. We now have 9 listener(s)
,08-25 17:20:29.832  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-25 17:20:29.832  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 17:20:29.836  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:29.841  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:29.843  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:29.843  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 17:20:29.844  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.844  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac25ffa added. We now have 3 listener(s)
,08-25 17:20:29.847  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:29.847  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 17:20:29.847  4201  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 17:20:29.847  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.847  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.847  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:20:29.847  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.847  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d39ab added. We now have 10 listener(s)
,08-25 17:20:29.848  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:29.848  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:20:29.849  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-25 17:20:29.850  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:20:29.850  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:20:29.850  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:20:29.850  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:29.850  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:20:29.852  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 17:20:29.852  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.853  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:20:29.853  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:20:29.858  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 17:20:29.858  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 17:20:29.858  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:29.859  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:20:29.859  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-25 17:20:29.860  4201  4220 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:20:29.862  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:20:29.862  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 17:20:29.862  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:20:29.863  3815  3865 D BluetoothAdapter: STATE_ON,
08-25 17:20:29.865  4201  4240 D BtGatt.GattService: registerClient() - UUID=658c639f-de63-4fe0-8f44-bb4257cdb8bb
08-25 17:20:29.865  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 17:20:29.865  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.865  4201  4217 D BtGatt.GattService: onClientRegistered() - UUID=658c639f-de63-4fe0-8f44-bb4257cdb8bb, clientIf=5,
08-25 17:20:29.865  4201  4220 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:20:29.866  3815  3825 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 17:20:29.866  4201  4239 D BtGatt.GattService: start scan with filters
,08-25 17:20:29.868  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:29.868  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:29.868  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 17:20:29.869  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:29.871  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:20:29.871  4201  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:20:29.871  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.872  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 17:20:29.872  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 17:20:29.873  4201  4220 D BtGatt.ScanManager: handling starting scan
,08-25 17:20:29.873  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:29.876  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 17:20:29.876  3815  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 17:20:29.876  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:29.876  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:29.876  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:20:29.876  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.876  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.876  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:20:29.877  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.877  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51af38f removed from the list
08-25 17:20:29.877  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.877  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249761c removed from the list
08-25 17:20:29.877  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
08-25 17:20:29.877  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:20:29.877  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.877  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 17:20:29.877  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.877  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:20:29.878  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:20:29.878  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.878  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.878  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249761c not in the list,
08-25 17:20:29.878  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 17:20:29.878  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 17:20:29.879  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:20:29.879  4201  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 17:20:29.879  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.879  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 17:20:29.879  4201  4220 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 17:20:29.879  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 17:20:29.879  3815  3865 D BluetoothAdapter: STATE_ON
08-25 17:20:29.880  4201  4212 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:20:29.880  4201  4211 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:20:29.881  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 17:20:29.881  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 17:20:29.881  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 17:20:29.881  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 17:20:29.881  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:29.882  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:29.882  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:20:29.882  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 17:20:29.882  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:20:29.882  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.883  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:29.883  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:29.883  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:29.883  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.883  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:29.884  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.884  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35d39ab removed from the list
08-25 17:20:29.884  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:20:29.884  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.884  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.884  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.884  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.884  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.884  4201  4220 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:29.884  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac25ffa removed from the list
08-25 17:20:29.884  4201  4220 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 17:20:29.885  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.885  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333c587 added. We now have 2 listener(s)
08-25 17:20:29.886  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.886  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.886  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.886  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.887  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46cb4 added. We now have 9 listener(s)
08-25 17:20:29.887  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:29.887  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:20:29.889  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:29.892  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 17:20:29.893  4201  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:20:29.893  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.894  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.894  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:29.894  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.895  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@298f452 added. We now have 3 listener(s)
08-25 17:20:29.896  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:29.897  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.897  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.897  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.897  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.897  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efd3323 added. We now have 10 listener(s)
08-25 17:20:29.897  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 17:20:29.897  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:20:29.897  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 17:20:29.898  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 17:20:29.898  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 17:20:29.898  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 17:20:29.898  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:29.899  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 17:20:29.899  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.900  3815  3865 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 17:20:29.900  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 17:20:29.904  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 17:20:29.904  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 17:20:29.904  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 17:20:29.905  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 17:20:29.905  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.906  4201  4220 D BtGatt.ScanManager: stopping BLe Batch
,08-25 17:20:29.907  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 17:20:29.907  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 17:20:29.907  3815  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 17:20:29.908  3815  3865 D BluetoothAdapter: STATE_ON
,08-25 17:20:29.909  4201  4229 D BtGatt.GattService: registerClient() - UUID=1c77e2ba-96a5-4f7d-b9c1-443e13fad1a5
,08-25 17:20:29.910  4201  4217 D BtGatt.GattService: onClientRegistered() - UUID=1c77e2ba-96a5-4f7d-b9c1-443e13fad1a5, clientIf=5
08-25 17:20:29.910  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 17:20:29.910  4201  4239 D BtGatt.GattService: start scan with filters
,08-25 17:20:29.912  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:20:29.912  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.912  4201  4220 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 17:20:29.912  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 17:20:29.912  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 17:20:29.912  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 17:20:29.912  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 17:20:29.915  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:29.915  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 17:20:29.915  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 17:20:29.916  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 17:20:29.917  4201  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 17:20:29.917  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.918  4201  4220 D BtGatt.ScanManager: handling starting scan
,08-25 17:20:29.921  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 17:20:29.921  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:20:29.921  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 17:20:29.921  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.921  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 17:20:29.921  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 17:20:29.921  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.921  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333c587 removed from the list
,08-25 17:20:29.921  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.921  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46cb4 removed from the list
08-25 17:20:29.921  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop,
08-25 17:20:29.921  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:29.922  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.922  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 17:20:29.922  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.922  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 17:20:29.923  4201  4217 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 17:20:29.923  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:29.924  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 17:20:29.924  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.924  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.924  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a46cb4 not in the list
08-25 17:20:29.924  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 17:20:29.924  4201  4220 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 17:20:29.924  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 17:20:29.924  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 17:20:29.924  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 17:20:29.924  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 17:20:29.925  3815  3865 D BluetoothAdapter: STATE_ON
08-25 17:20:29.925  4201  4240 D BtGatt.GattService: stopScan() - queue size =1
,08-25 17:20:29.926  4201  4229 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 17:20:29.926  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 17:20:29.926  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
08-25 17:20:29.926  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 17:20:29.926  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 17:20:29.926  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 17:20:29.927  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 17:20:29.927  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 17:20:29.927  3815  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 17:20:29.927  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 17:20:29.928  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:29.929  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.929  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-25 17:20:29.929  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.929  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-25 17:20:29.929  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efd3323 removed from the list
08-25 17:20:29.929  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:20:29.929  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 17:20:29.929  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.929  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:29.929  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 17:20:29.929  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.929  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@298f452 removed from the list
,08-25 17:20:29.929  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 17:20:29.929  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.930  4201  4220 D BtGatt.ScanManager: Starting BLE batch scan
08-25 17:20:29.930  4201  4220 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 17:20:29.930  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 17:20:29.930  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65de7f added. We now have 2 listener(s)
,08-25 17:20:29.931  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.931  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 17:20:29.932  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 17:20:29.932  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.932  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@649e4c added. We now have 9 listener(s)
08-25 17:20:29.932  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:29.932  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 17:20:29.934  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 17:20:29.942  3815  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 17:20:29.943  3815  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 17:20:29.943  3815  3865 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 17:20:29.944  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 17:20:29.944  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@872bbaa added. We now have 3 listener(s)
,08-25 17:20:29.945  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 17:20:29.946  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 17:20:29.946  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 17:20:29.946  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 17:20:29.947  4201  4217 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 17:20:29.947  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 17:20:29.947  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.947  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d83e39b added. We now have 10 listener(s)
08-25 17:20:29.947  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 17:20:29.949  3815  3865 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 17:20:29.949  3815  3865 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 17:20:29.949  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 17:20:29.949  3815  3865 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 17:20:29.949  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 17:20:29.949  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 17:20:29.949  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 17:20:29.949  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 17:20:29.950  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e65de7f removed from the list
08-25 17:20:29.950  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 17:20:29.950  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@649e4c removed from the list
08-25 17:20:29.950  3815  3865 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 17:20:29.950  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 17:20:29.950  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.950  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.951  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 17:20:29.951  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.951  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.951  3815  3865 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@649e4c not in the list
,08-25 17:20:29.952  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.952  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.953  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 17:20:29.953  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 17:20:29.953  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.953  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 17:20:29.954  3815  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 17:20:29.954  3815  3865 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d83e39b removed from the list
,08-25 17:20:29.954  3815  3865 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 17:20:29.954  3815  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 17:20:29.954  3815  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 17:20:29.954  3815  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 17:20:29.954  3815  3865 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@872bbaa removed from the list
08-25 17:20:29.955  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 17:20:29.955  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 17:20:29.955  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 17:20:29.955  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 17:20:29.955  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 17:20:29.956  3815  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 17:20:29.960  4201  4217 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 17:20:29.960  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 17:20:29.960  4201  4220 D BtGatt.ScanManager: stopping BLe Batch
08-25 17:20:29.962  3815  4280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
08-25 17:20:29.962  3815  4280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
,08-25 17:20:29.963  3815  4280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 17:20:29.966  3815  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
08-25 17:20:29.966  3815  4281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
,08-25 17:20:29.966  3815  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 17:20:29.966  4201  4217 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 17:20:29.967  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.967  4201  4220 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 17:20:29.968  3815  3865 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 17:20:29.968  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-25 17:20:29.969  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-25 17:20:29.969  3815  3865 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-25 17:20:29.969  3815  3865 D com.test.thalitest.ThaliTestRunner: Total duration: 22869 ms
08-25 17:20:29.970  3815  3865 I jxcore-log: Total number of executed tests:  80
08-25 17:20:29.970  3815  3865 I jxcore-log: 
08-25 17:20:29.970  3815  3865 I jxcore-log: Number of passed tests:  80
08-25 17:20:29.970  3815  3865 I jxcore-log: 
,08-25 17:20:29.971  3815  3865 I jxcore-log: Number of failed tests:  0
08-25 17:20:29.971  3815  3865 I jxcore-log: 
,08-25 17:20:29.971  3815  3865 I jxcore-log: Number of ignored tests:  0
08-25 17:20:29.971  3815  3865 I jxcore-log: 
08-25 17:20:29.971  3815  3865 I jxcore-log: Total duration:  22869
08-25 17:20:29.971  3815  3865 I jxcore-log: 
,08-25 17:20:29.971  3815  3865 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 17:20:29.971  3815  3865 I jxcore-log: 
08-25 17:20:29.972  4201  4217 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 17:20:29.972  4201  4217 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 17:20:29.974  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.974  3815  3865 I jxcore-log: 
08-25 17:20:29.977  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.977  3815  3865 I jxcore-log: 
08-25 17:20:29.978  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.978  3815  3865 I jxcore-log: 
,08-25 17:20:29.979  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.979  3815  3865 I jxcore-log: 
,08-25 17:20:29.979  3815  3815 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 17:20:29.979  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.979  3815  3865 I jxcore-log: 
08-25 17:20:29.981  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.981  3815  3865 I jxcore-log: 
08-25 17:20:29.983  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.983  3815  3865 I jxcore-log: 
08-25 17:20:29.985  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.985  3815  3865 I jxcore-log: 
08-25 17:20:29.986  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.986  3815  3865 I jxcore-log: 
08-25 17:20:29.986  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.986  3815  3865 I jxcore-log: 
08-25 17:20:29.987  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.987  3815  3865 I jxcore-log: 
08-25 17:20:29.988  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:20:29.988  3815  3865 I jxcore-log: 
08-25 17:20:29.989  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.989  3815  3865 I jxcore-log: 
08-25 17:20:29.990  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.990  3815  3865 I jxcore-log: 
08-25 17:20:29.991  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.991  3815  3865 I jxcore-log: 
08-25 17:20:29.991  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.991  3815  3865 I jxcore-log: 
08-25 17:20:29.992  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.992  3815  3865 I jxcore-log: 
08-25 17:20:29.993  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.993  3815  3865 I jxcore-log: 
08-25 17:20:29.994  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.994  3815  3865 I jxcore-log: 
08-25 17:20:29.994  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.994  3815  3865 I jxcore-log: 
08-25 17:20:29.995  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.995  3815  3865 I jxcore-log: 
0,8-25 17:20:29.996  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.996  3815  3865 I jxcore-log: 
08-25 17:20:29.996  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.996  3815  3865 I jxcore-log: 
08-25 17:20:29.997  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 17:20:29.997  3815  3865 I jxcore-log: 
08-25 17:20:29.998  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.998  3815  3865 I jxcore-log: 
,08-25 17:20:29.998  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 17:20:29.998  3815  3865 I jxcore-log: 
08-25 17:20:29.999  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:29.999  3815  3865 I jxcore-log: 
,08-25 17:20:30.000  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:30.000  3815  3865 I jxcore-log: 
,08-25 17:20:30.001  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:30.001  3815  3865 I jxcore-log: 
,08-25 17:20:30.001  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:30.001  3815  3865 I jxcore-log: 
,08-25 17:20:30.002  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:30.002  3815  3865 I jxcore-log: 
,08-25 17:20:30.003  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 17:20:30.003  3815  3865 I jxcore-log: 
,08-25 17:20:30.318  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:20:30.321  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:20:30.321  3815  3865 I jxcore-log: 
,08-25 17:20:30.384  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:20:30.387  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:20:30.387  3815  3865 I jxcore-log: 
,08-25 17:20:30.430  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 17:20:30.433  3815  3865 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 17:20:30.433  3815  3865 I jxcore-log: 
,08-25 17:20:30.621  4282  4282 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 17:20:30.626  4282  4282 D AndroidRuntime: CheckJNI is OFF
,08-25 17:20:30.668  4282  4282 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 17:20:30.717  4282  4282 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 17:20:30.740  4282  4282 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 17:20:30.752   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 17:20:30.753   873   886 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 17:20:30.881   873  1384 I WindowState: WIN DEATH: Window{7eda7a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 17:20:30.881   873  1368 D GraphicsStats: Buffer count: 2
,08-25 17:20:30.883   873  1304 D WifiService: Client connection lost with reason: 4
,08-25 17:20:30.895   873   896 W PackageSettings: Skipping PackageSetting{e1f595 com.example.hello/10273} due to missing metadata
,08-25 17:20:30.930   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 17:20:30.930   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-25 17:20:30.931   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-25 17:20:30.931   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 17:20:30.931   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:30.931   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:30.931   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:20:30.931   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 17:20:30.931   873   886 I ActivityManager:   Force finishing activity ActivityRecord{5209ec2 u0 com.test.thalitest/.MainActivity t2}
,08-25 17:20:30.939   873  1944 W ActivityManager: Spurious death for ProcessRecord{318e876 0:com.test.thalitest/u0a0}, curProc for 3815: null
,08-25 17:20:30.943   873   896 I art     : Starting a blocking GC Explicit
,08-25 17:20:30.982  2028  2636 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 17:20:30.995   873   896 I art     : Explicit concurrent mark sweep GC freed 13936(971KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 773us total 51.653ms
,08-25 17:20:31.044   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 17:20:31.048  4282  4282 I art     : System.exit called, status: 0
08-25 17:20:31.049  4282  4282 I AndroidRuntime: VM exiting with result code 0.
,08-25 17:20:31.101   873   896 I ActivityManager: Start proc 4292:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-25 17:20:31.103   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 17:20:31.138   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 17:20:31.144  4201  4201 D BluetoothMapAppObserver: onReceive
08-25 17:20:31.144  4201  4201 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 17:20:31.147  2028  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-25 17:20:31.153   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 17:20:31.161  3621  3621 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 17:20:31.161  1865  1865 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 17:20:31.191   873  1368 I ActivityManager: Start proc 4308:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 17:20:31.199   873   883 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
,08-25 17:20:31.201   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-25 17:20:31.201  1865  1865 I Keyboard.Facilitator: onFinishInput()
,08-25 17:20:31.203  1928  1928 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-25 17:20:31.204   873   885 E PackageManager: Failed to write settings, restoring backup
08-25 17:20:31.204   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 17:20:31.204   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 17:20:31.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 17:20:31.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 17:20:31.204   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 17:20:31.204   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:31.204   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.204   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:20:31.207   873  1301 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-25 17:20:31.210   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-25 17:20:31.210   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 17:20:31.210   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:20:31.210   873   886 E DropBoxManagerService: 	... 13 more
,08-25 17:20:31.230  1865  4306 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 17:20:31.250  1865  4306 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-25 17:20:31.250  1865  4306 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-25 17:20:31.251  1865  4306 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-25 17:20:31.251  1865  4306 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-25 17:20:31.251  1865  4306 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-25 17:20:31.251  1865  4306 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-25 17:20:31.254  1865  4306 I Decoder : createOrResetDecoder
,08-25 17:20:31.267  1494  1494 I ConfigService: onCreate
,08-25 17:20:31.268   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 17:20:31.271  4308  4308 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 17:20:31.274  1494  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 17:20:31.274  1494  4320 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 17:20:31.274  1494  4320 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-25 17:20:31.275  1494  4320 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-25 17:20:31.286  1865  4306 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 17:20:31.293  1942  2026 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 17:20:31.307   873  1384 I ActivityManager: Start proc 4321:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-25 17:20:31.307  1942  2026 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 17:20:31.307  1942  2026 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1942
08-25 17:20:31.307  1942  2026 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.307  1942  2026 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 17:20:31.309   873  1997 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 17:20:31.309   873  4326 E DropBoxManagerService: Can't write: system_app_crash
08-25 17:20:31.309   873  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:20:31.309   873  4326 E DropBoxManagerService: 	... 5 more
,08-25 17:20:31.315  1942  2026 I Process : Sending signal. PID: 1942 SIG: 9
,08-25 17:20:31.339  1865  4306 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 17:20:31.341  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-25 17:20:31.341  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 17:20:31.343  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-25 17:20:31.343  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-25 17:20:31.344  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-25 17:20:31.344  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-25 17:20:31.346  1865  4306 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-25 17:20:31.346  1865  4306 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 17:20:31.346  1865  4306 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-25 17:20:31.347  1865  4306 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-25 17:20:31.348  1865  4306 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-25 17:20:31.348  1865  4306 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 17:20:31.369  4308  4308 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 17:20:31.386   873  1995 I ActivityManager: Start proc 4339:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 17:20:31.391  4308  4344 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 17:20:31.408   873  1994 D GraphicsStats: Buffer count: 1
,08-25 17:20:31.408   873  1997 I WindowState: WIN DEATH: Window{2a72673 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 17:20:31.420   873  1994 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1942) has died
,08-25 17:20:31.421   873  1994 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 17:20:31.422   873  1994 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 17:20:31.439   873   886 I ActivityManager: Start proc 4354:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 17:20:31.497  4354  4354 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:31.497  4354  4354 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 17:20:31.497  4354  4354 D AndroidRuntime: Shutting down VM
,08-25 17:20:31.503  4354  4354 E AndroidRuntime: FATAL EXCEPTION: main
08-25 17:20:31.503  4354  4354 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4354
08-25 17:20:31.503  4354  4354 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 17:20:31.503  4354  4354 E AndroidRuntime: 	... 10 more
08-25 17:20:31.505   873  2090 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 17:20:31.505  4354  4354 I Process : Sending signal. PID: 4354 SIG: 9
,08-25 17:20:31.507   873  4366 E DropBoxManagerService: Can't write: system_app_crash
08-25 17:20:31.507   873  4366 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 17:20:31.507   873  4366 E DropBoxManagerService: 	... 5 more
,08-25 17:20:31.516  4339  4339 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 17:20:31.529  1694  4367 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-25 17:20:31.530  1694  4367 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-25 17:20:31.437  4308  4337 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 17:20:31.437  4308  4337 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 17:20:31.536   873  1686 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4354) has died

```
