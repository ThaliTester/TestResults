#### Test 8149356279477ac_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-16 17:58:07.582   873  1307 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-16 17:58:08.281  3806  3806 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 17:58:08.286  3806  3806 D AndroidRuntime: CheckJNI is OFF
08-16 17:58:08.321  3806  3806 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 17:58:08.389  3806  3806 I Radio-JNI: register_android_hardware_Radio DONE
08-16 17:58:08.415  3806  3806 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 17:58:08.419   873  1701 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 17:58:08.443  1986  2347 W SearchService: Abort, client detached.
08-16 17:58:08.452  1986  1986 I HotwordDetector: Closing mic
08-16 17:58:08.454  1986  2306 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2448f2c
08-16 17:58:08.454  1986  2323 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 17:58:08.467  3806  3806 D AndroidRuntime: Shutting down VM
08-16 17:58:08.489   873  1700 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 17:58:08.507   375  2325 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 17:58:08.513   375  2325 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 17:58:08.521   375  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 17:58:08.524  1986  2319 I MicroRecognitionRnrImpl: Detection finished
08-16 17:58:08.524  1986  2309 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 17:58:08.583  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 17:58:08.614  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 17:58:08.625  3815  3815 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3114-3120)
08-16 17:58:08.625  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:58:08.652  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a5d285}
08-16 17:58:08.652  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:58:08.652  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:58:08.658  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 17:58:08.660  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 17:58:08.684  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 17:58:08.694  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:58:08.694  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:58:08.694  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:58:08.694  3815  3815 I Adreno  : Build Date                       : 10/20/15
08-16 17:58:08.694  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:58:08.694  3815  3815 I Adreno  : Local Branch                     : M14
08-16 17:58:08.694  3815  3815 I Adreno  : Remote Branch                    : 
08-16 17:58:08.694  3815  3815 I Adreno  : Remote Branch                    : 
08-16 17:58:08.694  3815  3815 I Adreno  : Reconstruct Branch               : 
,08-16 17:58:08.755   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f203b83:true
,08-16 17:58:08.838  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 17:58:08.867  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 17:58:08.974  3815  3853 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 17:58:08.988  3815  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 17:58:09.021  3815  3853 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:58:09.078   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +611ms
,08-16 17:58:09.081  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 17:58:09.161  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,08-16 17:58:09.327   873  2973 I ActivityManager: Killing 2963:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 17:58:09.356  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:58:09.375   873  2973 I ActivityManager: Killing 3188:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 17:58:09.542  3815  3855 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700005584
,08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 17:58:09.547  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cbcc0 added. We now have 1 listener(s)
,08-16 17:58:09.550  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 17:58:09.550  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:09.553  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:09.553  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:58:09.559  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a29b9f added. We now have 1 listener(s)
08-16 17:58:09.559  3815  3855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:09.564   873  1308 D WifiService: New client listening to asynchronous messages
,08-16 17:58:09.565  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:09.565  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 17:58:09.566  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 17:58:09.566  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 17:58:09.566  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:58:09.571  3815  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.571  3815  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 17:58:09.578  3815  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.578  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:09.579  3815  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:58:09.579  3815  3855 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:09.581  3815  3855 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:58:09.582  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.585  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.617  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:58:10.145  3815  3825 I art     : Background sticky concurrent mark sweep GC freed 69663(6MB) AllocSpace objects, 18(1604KB) LOS objects, 30% free, 22MB/32MB, paused 677us total 112.286ms
,08-16 17:58:10.504  3815  3863 W jxcore-log: Initializing JXcore engine
,08-16 17:58:10.504  3815  3863 W jxcore-log: JXcore engine is ready
,08-16 17:58:10.583  3863  3863 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 17:58:10.583  3863  3863 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13053]" dev="sockfs" ino=13053 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 17:58:10.583  3863  3863 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 17:58:10.583  3863  3863 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24238]" dev="sockfs" ino=24238 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 17:58:10.600  3815  3863 W jxcore-log: Starting JXcore engine
,08-16 17:58:10.693  3815  3863 W jxcore-log: Platform android
08-16 17:58:10.693  3815  3863 W jxcore-log: 
,08-16 17:58:10.693  3815  3863 W jxcore-log: Process ARCH arm
08-16 17:58:10.693  3815  3863 W jxcore-log: 
,08-16 17:58:10.962  3815  3863 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:58:10.962  3815  3863 I jxcore-log: 
,08-16 17:58:10.962  3815  3863 W jxcore-log: JXcore engine is started
,08-16 17:58:10.971  3815  3855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:58:10.977  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:58:11.541  3554  3868 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:58:11.601  3554  3869 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:58:11.616  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:11.617  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:11.657  1506  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:58:11.657  1506  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:58:11.657  1506  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:11.657  1506  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:11.681  1506  1998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:58:11.681  1506  1998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:58:11.681  1506  1998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:11.681  1506  1998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:11.699  3517  3867 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:58:11.699  3517  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:58:11.699  3517  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	... 12 more
08-16 17:58:11.699  3517  3867 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at fal.a(PG:38)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:58:11.699  3517  3867 E HttpOperation: 	... 14 more
,08-16 17:58:11.729  1506  3610 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:58:11.729  1506  3610 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:58:11.729  1506  3610 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:11.729  1506  3610 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:11.734  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:58:11.734  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:58:11.734  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:11.734  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:11.745  3517  3867 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:58:11.745  3517  3867 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at hec.a(PG:42)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at hee.a(PG:102)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at czr.a(PG:65)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at kka.a(PG:108)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:58:11.745  3517  3867 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	... 15 more
08-16 17:58:11.745  3517  3867 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at fal.a(PG:38)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:58:11.745  3517  3867 E HttpOperation: 	... 17 more
,08-16 17:58:11.745  3517  3867 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:58:11.745  3517  3867 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	... 15 more
08-16 17:58:11.745  3517  3867 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:58:11.745  3517  3867 E ExperimentLoader: 	... 17 more
08-16 17:58:11.746  3554  3869 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:58:11.747  3554  3868 E BooksSync: Soft error
08-16 17:58:11.747  3554  3868 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:58:11.747  3554  3868 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:58:11.747  3554  3868 E BooksSync: Sync error
08-16 17:58:11.747  3554  3868 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:58:11.747  3554  3868 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:58:11.747  3554  3868 I BooksSync: Finished books sync
,08-16 17:58:11.752   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125795, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:58:11.830   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 124770, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:58:13.766  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:13.824  1506  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 17:58:13.824  1506  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 17:58:13.825  1506  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:58:13.825  1506  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:13.865  3476  3476 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 17:58:13.865  3476  3476 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 17:58:13.866  3476  3476 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 17:58:19.249  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:19.251  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:19.262  3762  3879 V GoogleAuthProtoRequest: [314] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:58:19.286  1506  1998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 17:58:19.286  1506  1998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 17:58:19.286  1506  1998 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:19.286  1506  1998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:19.302  3762  3879 W ExperimentUpdateService: [314] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: [314] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 17:58:19.303  3762  3879 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 17:58:21.279  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:58:21.279  3815  3863 I jxcore-log: 
,08-16 17:58:21.281  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:58:21.281  3815  3863 I jxcore-log: 
,08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.294  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:21.296  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:21.299  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:58:21.299  3815  3863 I jxcore-log: 
,08-16 17:58:21.301  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:58:21.301  3815  3863 I jxcore-log: 
,08-16 17:58:21.633  3815  3863 D ExecuteNativeTests: Running unit tests
,08-16 17:58:21.692  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:21.692  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 added. We now have 2 listener(s)
,08-16 17:58:21.693  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:21.694  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:21.694  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:21.694  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:21.694  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 added. We now have 2 listener(s)
08-16 17:58:21.694  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:21.694  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:21.701  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.711  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:21.712  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.713  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:21.715  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:58:21.715  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:58:21.715  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:58:21.716  3815  3863 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 17:58:21.717  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:21.717  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:21.717  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:21.717  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:21.719  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.719  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:21.721  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:21.722  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:58:21.722  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.733  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:21.733  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.733  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:21.733  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:21.733  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 removed from the list
08-16 17:58:21.735  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.735  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 removed from the list
08-16 17:58:21.735  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.735  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.736  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.736  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.737  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:21.737  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.737  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.737  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
,08-16 17:58:21.739  3815  3863 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:58:21.739  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.740  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:21.740  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.740  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.740  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.740  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.740  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.740  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.740  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
,08-16 17:58:21.740  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.740  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.740  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.740  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.740  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.741  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:21.741  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.741  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.741  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
,08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:21.746  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:21.747  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:58:21.747  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.747  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.747  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.748  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.748  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.748  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.748  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.748  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.748  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.748  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.748  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.748  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.748  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.748  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.749  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.749  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.749  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.749  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.750  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:21.751  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.754  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:21.756  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.756  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:21.756  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:21.756  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:21.756  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:21.756  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.756  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:58:21.758  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:21.760  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:21.760  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 17:58:21.760  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:21.765  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:58:21.766  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:58:21.767  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:21.769  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 17:58:21.770  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:58:21.771  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:21.771  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:21.771  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:21.773  3815  3863 D BluetoothAdapter: STATE_ON
08-16 17:58:21.781  2674  2686 D BtGatt.GattService: registerClient() - UUID=ff9ca575-cacb-4e0a-b276-a0353182278d
,08-16 17:58:21.782  2674  2696 D BtGatt.GattService: onClientRegistered() - UUID=ff9ca575-cacb-4e0a-b276-a0353182278d, clientIf=5
08-16 17:58:21.783  3815  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:58:21.784  2674  2853 D BtGatt.GattService: start scan with filters
08-16 17:58:21.787  2674  2699 D BtGatt.ScanManager: handling starting scan
08-16 17:58:21.787  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:21.788  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:21.788  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:21.788  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:21.788  2674  2699 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:21.791  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:21.791  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:21.792  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:21.792  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:58:21.794  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:58:21.796  2674  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:58:21.796  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.797  2674  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:58:21.797  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.798  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:21.798  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.798  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:21.798  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.798  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:21.798  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:21.798  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:21.798  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:21.798  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:21.799  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:21.799  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:21.800  3815  3863 D BluetoothAdapter: STATE_ON
08-16 17:58:21.801  2674  2853 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:58:21.802  2674  3429 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:58:21.802  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:58:21.802  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.803  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:21.803  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:21.803  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:21.803  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:21.803  2674  2699 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:21.803  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:21.803  2674  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:58:21.805  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.805  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:21.805  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:21.806  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:21.807  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:21.808  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.808  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.808  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.808  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:21.808  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.808  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.808  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.808  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.808  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.808  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.808  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.809  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:21.810  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.813  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:21.815  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.815  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:21.815  2674  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:58:21.815  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:58:21.815  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:21.815  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:21.815  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:21.815  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.816  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:58:21.818  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:21.819  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 17:58:21.819  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:21.821  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:58:21.821  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.821  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.823  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:58:21.824  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:58:21.824  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:21.828  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:58:21.828  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.828  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:21.828  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-16 17:58:21.828  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:21.828  2674  2699 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:21.829  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:21.832  2674  2686 D BtGatt.GattService: registerClient() - UUID=7d598e2d-8834-4eb0-8de6-cd7e17deae62
08-16 17:58:21.832  2674  2696 D BtGatt.GattService: onClientRegistered() - UUID=7d598e2d-8834-4eb0-8de6-cd7e17deae62, clientIf=5
08-16 17:58:21.833  3815  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:58:21.833  2674  3429 D BtGatt.GattService: start scan with filters
,08-16 17:58:21.835  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:58:21.835  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.835  2674  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:58:21.836  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:21.836  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:21.837  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:21.837  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:21.839  2674  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:58:21.839  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.840  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:21.840  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:21.840  2674  2699 D BtGatt.ScanManager: handling starting scan
08-16 17:58:21.841  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:21.843  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:21.845  2674  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:58:21.846  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.846  2674  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:58:21.847  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:21.849  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.849  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:21.849  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.849  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:21.850  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.850  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:21.850  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:21.850  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:21.850  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:21.850  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:21.850  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 17:58:21.850  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:21.850  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.850  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:21.851  2674  2699 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:21.851  2674  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:58:21.851  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:21.851  2674  2685 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:58:21.852  2674  3429 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:58:21.852  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:21.852  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:21.852  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:21.852  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:21.852  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:21.853  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.853  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:21.853  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:21.853  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:21.853  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:21.854  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.854  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.854  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.854  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:21.854  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.854  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.855  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.855  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.855  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.855  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.855  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.855  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.855  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.856  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.856  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.856  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.856  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.857  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:21.858  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.859  2674  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:58:21.859  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.862  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:21.863  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:58:21.863  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.863  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.863  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:21.863  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:21.863  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:21.864  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:21.864  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.864  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:21.866  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.868  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.869  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 17:58:21.869  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:21.869  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:58:21.869  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.869  2674  2699 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:21.872  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:21.872  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:58:21.873  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:21.876  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:21.876  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:58:21.876  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.877  2674  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:58:21.877  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:58:21.877  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:21.877  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:21.879  2674  2685 D BtGatt.GattService: registerClient() - UUID=e8f659ab-5483-4bb9-84fd-c6e80199b5e9
08-16 17:58:21.879  2674  2696 D BtGatt.GattService: onClientRegistered() - UUID=e8f659ab-5483-4bb9-84fd-c6e80199b5e9, clientIf=5
08-16 17:58:21.879  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:58:21.879  2674  2853 D BtGatt.GattService: start scan with filters
,08-16 17:58:21.882  2674  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:58:21.883  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.883  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:21.883  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:21.883  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:21.883  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:21.884  2674  2699 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:21.886  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:21.886  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:21.886  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:21.887  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:21.889  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:58:21.889  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.889  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:21.889  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.889  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:21.889  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.889  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:21.889  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:21.889  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:21.889  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:21.889  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:21.889  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:21.889  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:21.890  2674  2696 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:58:21.890  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.890  3815  3863 D BluetoothAdapter: STATE_ON
08-16 17:58:21.890  2674  2699 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:58:21.890  2674  3429 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:58:21.891  2674  2686 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:58:21.891  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:21.891  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:21.891  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:21.891  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:21.891  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:21.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:21.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:21.892  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:21.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:21.893  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.893  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:21.893  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.893  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.893  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:21.893  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.893  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.893  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.894  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.894  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:21.894  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.894  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.894  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.894  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.894  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.895  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.895  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.895  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:58:21.895  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.895  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:21.895  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.895  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.895  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.895  2674  2699 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:21.896  2674  2699 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:58:21.896  3815  3863 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:58:21.896  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.896  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:21.896  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.897  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.897  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.897  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.897  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.897  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.897  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.897  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.897  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.897  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.898  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.898  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.898  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.898  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 17:58:21.898  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.898  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.899  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.899  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.899  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.899  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.899  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.899  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.899  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.899  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.899  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.899  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.899  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.899  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.900  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.900  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:21.900  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:21.900  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
,08-16 17:58:21.900  3815  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 17:58:21.900  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.900  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:21.901  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.901  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:21.901  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.901  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.901  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.901  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:21.901  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.901  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.901  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.901  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.901  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.901  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.902  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.902  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 17:58:21.902  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:21.902  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.902  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 17:58:21.902  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.903  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.903  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:21.903  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:21.903  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.903  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:21.903  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.903  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.903  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list,
08-16 17:58:21.903  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.903  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:58:21.903  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.903  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:58:21.903  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.904  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:21.904  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.904  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:21.904  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.904  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-16 17:58:21.905  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:58:21.906  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:21.906  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:58:21.906  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:58:21.906  2674  2696 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:58:21.906  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.908  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:58:21.908  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.908  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:21.908  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.909  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.909  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.909  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.909  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
,08-16 17:58:21.909  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.909  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.909  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.909  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:58:21.909  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.910  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:21.910  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.911  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.911  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:21.911  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.911  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
,08-16 17:58:21.912  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:58:21.912  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.912  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:21.912  3815  3863 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:21.912  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:21.915  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:21.915  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:21.916  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRem,oveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:21.917  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:21.918  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:21.918  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:58:21.918  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:58:21.918  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:21.918  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:58:21.919  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:21.919  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:21.919  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:58:21.919  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:21.919  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:21.919  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:21.919  2674  2696 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:58:21.919  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.919  2674  2699 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:21.922  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:58:21.922  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:58:21.922  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:58:21.923  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:58:21.923  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:58:21.923  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:58:21.923  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:21.923  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:58:21.923  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Tryin,g to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-16 17:58:21.924  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.924  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.924  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.924  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.924  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.924  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.924  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:58:21.925  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.925  2674  2696 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:58:21.925  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.925  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.925  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.925  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.925  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.925  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.925  2674  2699 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:58:21.925  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.925  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.926  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.926  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.926  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.926  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.926  3815  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:21.926  3815  3863 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:58:21.927  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.927  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.927  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.927  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.927  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.927  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.927  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.927  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.927  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.927  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.927  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.927  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.927  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.927  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.925  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-16 17:58:21.928  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
08-16 17:58:21.928  3815  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
08-16 17:58:21.928  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.928  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.929  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.929  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-16 17:58:21.929  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.929  3815  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:58:21.929  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.929  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.929  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.929  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.929  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.930  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.930  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.930  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.930  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.930  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.930  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.930  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.930  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.930  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.931  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.931  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.931  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.931  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.931  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:58:21.931  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:58:21.931  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:21.931  3815  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:58:21.931  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:21.932  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:58:21.932  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:21.932  3815  3863 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:58:21.932  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:21.932  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:21.932  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:21.932  3815  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:58:21.932  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.932  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.932  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.932  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.932  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.932  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.932  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.932  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.933  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.933  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.933  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.933  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.933  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.933  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.933  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.933  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.933  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.933  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.934  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.934  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.934  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.934  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.934  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.934  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.934  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.934  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.934  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.934  2674  2696 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:58:21.934  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.934  2674  2696 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:21.934  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.934  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.935  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.935  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.935  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.935  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.935  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.935  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.935  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.935  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.935  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.935  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.935  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.935  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.935  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.935  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.935  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.935  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.935  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.936  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.936  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.936  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.936  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.937  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:58:21.937  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.938  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:58:21.938  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:58:21.938  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:21.939  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:58:21.939  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:58:21.939  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.939  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:58:21.939  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.939  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.939  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:21.939  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:21.939  3815  3883 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:58:21.939  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:21.940  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.940  3815  3883 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:58:21.940  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.941  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.941  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.941  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.941  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.941  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:21.941  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.941  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.941  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:58:21.941  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.941  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.941  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:21.941  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.941  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.941  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.941  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.941  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.941  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.941  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.942  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.942  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.942  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.942  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.942  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.942  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.943  3815  3863 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:58:21.943  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:21.944  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:21.945  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:21.945  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.945  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.947  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.948  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.948  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.948  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.948  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.948  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.948  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.948  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.948  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.949  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.949  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.949  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.949  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.949  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.949  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.950  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.952  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.952  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.952  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.952  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.952  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.952  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.952  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.952  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.953  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.953  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.953  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.953  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.953  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.953  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.953  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.953  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.953  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.954  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.954  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:21.954  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:21.954  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:21.954  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:21.954  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.954  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.954  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97d90b7 not in the list
08-16 17:58:21.954  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.954  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.954  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:21.955  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.955  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.955  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:21.955  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:21.955  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:21.955  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:21.955  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:21.956  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1189024 not in the list
08-16 17:58:21.956  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:58:21.956  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:21.956  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:58:21.956  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:21.956  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:58:21.957  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:21.958  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:58:21.958  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:58:21.958  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:58:21.958  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:21.958  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:21.959  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:58:21.959  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:58:21.960  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:58:21.960  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:58:21.960  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:21.960  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8257e66 added. We now have 2 listener(s)
08-16 17:58:21.960  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:21.961  3815  3863 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:58:21.962   873  2133 D WifiService: setWifiEnabled: true pid=3815, uid=10000
08-16 17:58:21.962   873  2133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:58:21.962  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:21.962  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d5e15a7 added. We now have 3 listener(s)
08-16 17:58:21.962  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:21.971  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:21.971  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d24a54 added. We now have 4 listener(s)
08-16 17:58:21.971  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:21.974  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:21.974  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a276dfd added. We now have 5 listener(s)
08-16 17:58:21.975  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:21.978   873  2973 D WifiService: setWifiEnabled: false pid=3815, uid=10000
08-16 17:58:21.978   873  2973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:58:21.984  2674  2692 D BluetoothAdapterState: Current state: ON, message: 23
08-16 17:58:21.987  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:21.989  2674  2692 D BluetoothAdapterProperties: Setting state to 13
08-16 17:58:21.989  2674  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:58:21.990  2674  2692 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:58:21.992  2674  2692 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:58:21.993  2674  2696 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:21.993  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:21.993  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:21.993  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.993  2674  2692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 17:58:21.993  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:21.993  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:21.996  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.997  2674  2674 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:58:21.999  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.999   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:21.999   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:58:22.000  2674  2674 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:58:22.000  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:22.000  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.000  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.002  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:58:22.003   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-16 17:58:22.003   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 17:58:22.004   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:58:22.004   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:22.005  1925  1945 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:22.005   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:22.006  1361  1380 D BluetoothHeadset: Proxy object disconnected
08-16 17:58:22.006  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:22.006  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:22.007  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.007  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:22.007  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:58:22.007  2674  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 17:58:22.007  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 17:58:22.007  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:22.008  2674  2674 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:58:22.008  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:58:22.008  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:58:22.008  2674  2696 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 17:58:22.009  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:22.010  2674  2674 D A2dpService: Received stop request...Stopping profile...
,08-16 17:58:22.011  2674  2858 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:58:22.014   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:22.014  1361  1361 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:22.015  2674  2674 D HidService: Received stop request...Stopping profile...
,08-16 17:58:22.015  2674  2674 D HidService: Stopping Bluetooth HidService
08-16 17:58:22.016   873  1873 D DhcpClient: Clearing IP address
08-16 17:58:22.016  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 17:58:22.016  1361  1361 D HidProfile: Bluetooth service disconnected
,08-16 17:58:22.016   371   871 D CommandListener: Setting iface cfg
08-16 17:58:22.017  2674  2674 D HealthService: Received stop request...Stopping profile...
08-16 17:58:22.019   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:22.020  2674  2674 D PanService: Received stop request...Stopping profile...
08-16 17:58:22.021  2674  2674 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:58:22.021  2674  2674 D BluetoothMapService: stop()
,08-16 17:58:22.022  2674  2674 D BluetoothMapAppObserver: deinitObservers()
08-16 17:58:22.022  2674  2674 D BluetoothMapAppObserver: removeReceiver()
08-16 17:58:22.023  1506  2467 V NativeCrypto: Read error: ssl=0x9ab20200: I/O error during system call, Connection timed out
08-16 17:58:22.023  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:58:22.023  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 17:58:22.023  1361  1361 D BluetoothMap: Proxy object disconnected
08-16 17:58:22.023  1361  1361 D MapProfile: Bluetooth service disconnected
08-16 17:58:22.024  1506  2467 V NativeCrypto: SSL shutdown failed: ssl=0x9ab20200: I/O error during system call, Broken pipe
08-16 17:58:22.025   873  1876 D DhcpClient: Receive thread stopped
08-16 17:58:22.026   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:58:22.026   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 17:58:22.030   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 17:58:22.030   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-16 17:58:22.033  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:22.033  2674  2674 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:58:22.033  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:58:22.033  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.035  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:22.035  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:22.036  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.036  2674  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 17:58:22.036  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:22.036  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:22.036  2674  2815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:22.036  2674  2815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:22.036  2674  2815 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:22.036  2674  2815 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:22.036  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.038  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:58:22.038  2674  2696 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 17:58:22.039  2674  2674 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 17:58:22.039  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:22.039  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:22.039  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:22.039  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.040  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:22.040  2674  2696 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 17:58:22.040  2674  2674 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.040  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.041  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.041  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:22.041  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:58:22.041  2674  2674 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:58:22.043  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:22.043  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:22.044  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.044  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:22.046  2674  2674 D BluetoothMapService: MAP Service closeService in
08-16 17:58:22.046  2674  2674 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 17:58:22.046  2674  2674 D ObexServerSockets0: shutdown(block = true)
,08-16 17:58:22.046  2674  2879 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 17:58:22.047  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:58:22.047  2674  2880 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 17:58:22.047  2674  2848 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:58:22.047  2674  2674 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:58:22.047  2674  2674 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:22.047  2674  2674 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:58:22.047  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.047  2674  2674 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:22.048  2674  2692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 17:58:22.048  2674  2692 D BluetoothAdapterProperties: Setting state to 15
08-16 17:58:22.048  2674  2674 D BluetoothMapService: cleanup()
08-16 17:58:22.048  2674  2674 D BluetoothMapService: MAP Service closeService in
,08-16 17:58:22.048  2674  2674 I BtOppRfcommListener: stopping Accept Thread
08-16 17:58:22.048   873  2133 I ActivityManager: Start proc 3887:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 17:58:22.048  2674  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:58:22.048  2674  3418 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:58:22.049  2674  3418 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:58:22.049   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:22.050   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:22.050  1361  2025 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:58:22.050   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 17:58:22.050   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:58:22.051  2674  2692 I BluetoothAdapterState: Entering BleOnState
08-16 17:58:22.052  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:58:22.054  1361  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:22.055  1361  2025 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:58:22.055   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:22.055  1925  1945 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:22.056  1361  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:22.056  1361  1380 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:58:22.056   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:22.057  2674  2692 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 17:58:22.057  2674  2692 D BluetoothAdapterProperties: Setting state to 16
08-16 17:58:22.057  2674  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:58:22.058  2674  2692 D BluetoothAdapterProperties: onBleDisable
08-16 17:58:22.058  2674  2692 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:58:22.059  2674  2696 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:22.060  2674  2693 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 17:58:22.060  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:22.061  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:22.062  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:22.062  2674  2815 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:58:22.062  2674  2815 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:22.063  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:22.082   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:22.102  3887  3887 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 17:58:22.110   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:22.111   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-16 17:58:22.111   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:22.111   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:22.112  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:22.112   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:22.117  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:22.117  3361  3361 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2af0df9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 17:58:22.118  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:22.125   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba87114:true
,08-16 17:58:22.126  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:22.140   873  1944 I ActivityManager: Start proc 3904:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 17:58:22.166  3887  3887 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 17:58:22.171  3904  3904 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 17:58:22.173   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:58:22.174  3887  3887 D BluetoothMap: Create BluetoothMap proxy object
,08-16 17:58:22.174   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 17:58:22.176   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 17:58:22.178  2006  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:58:22.179   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:58:22.180  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:22.180  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:22.181  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.181  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:22.183  3887  3887 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 17:58:22.184  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:22.184  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:22.185  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:22.185  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:22.200  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:22.207   873   884 I ActivityManager: Killing 3361:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 17:58:22.263  2674  2696 I bt_hci  : shut_down
,08-16 17:58:22.264  2674  2700 D bt_hwcfg: hw_epilog_process
,08-16 17:58:22.313  2674  2700 I bt_vendor: low_power_mode_cb
,08-16 17:58:22.344  2674  2700 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:58:22.344  2674  2700 I bt_vendor: epilog_cb
,08-16 17:58:22.344  2674  2700 I bt_hci  : epilog_finished_callback
,08-16 17:58:22.352  2674  2696 I bt_hci_h4: hal_close
,08-16 17:58:22.353  2674  2696 I bt_userial_vendor: device fd = 51 close
,08-16 17:58:22.391  3904  3904 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.391  3904  3904 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.391  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	,at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.392  3904  3904 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206),
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:22.392  3904  3904 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:22.396  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:22.403  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:22.412  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:22.422   873  1383 I ActivityManager: Killing 3432:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 17:58:22.442  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:22.481  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:58:22.493  1704  1704 D SystemUpdateService: onCreate
,08-16 17:58:22.507  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:58:22.510  2674  2693 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:58:22.511  2674  2692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 17:58:22.516  2674  2692 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:58:22.516  2674  2674 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:58:22.517  1704  3937 I SystemUpdateService: active receiver: enabled
,08-16 17:58:22.517  2674  2674 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 17:58:22.517  2674  2674 D BtGatt.GattService: stop()
08-16 17:58:22.518  2674  2674 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:58:22.525  2674  2674 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:22.526  2674  2674 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:22.526  2674  2674 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:22.526  2674  2674 V BluetoothAdapterState: isBleTurningOff()=true
08-16 17:58:22.527  2674  2692 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 17:58:22.527  2674  2692 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:22.527  2674  2692 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 17:58:22.528  2674  2692 I BluetoothAdapterState: Entering OffState
,08-16 17:58:22.538   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 17:58:22.539  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:58:22.542  1704  2434 I iu.UploadsManager: num queued entries: 0
,08-16 17:58:22.542  1704  2434 I iu.UploadsManager: num updated entries: 0
,08-16 17:58:22.547  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 17:58:22.548  2674  2674 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 17:58:22.548  2674  2674 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 17:58:22.549  2674  2693 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 17:58:22.551  2674  2693 D bt_stack_manager: event_clean_up_stack finished.
,08-16 17:58:22.551  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 17:58:22.552  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 17:58:22.553  1704  2434 I iu.SyncManager: NEXT; no task
,08-16 17:58:22.555  2674  2674 I art     : System.exit called, status: 0
08-16 17:58:22.555  2674  2674 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:58:22.567   873  1944 I ActivityManager: Start proc 3940:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 17:58:22.566  1704  3937 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:58:22.577  1704  3937 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 17:58:22.577  1704  3937 I SystemUpdateService: now status is 0 (complete)
08-16 17:58:22.577  1704  3937 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 17:58:22.577  1704  3937 I SystemUpdateService: file has been verified
08-16 17:58:22.578  1704  3937 I SystemUpdateService: OTA package size = 12249756
,08-16 17:58:22.583  1704  3937 I SystemUpdateService: showing system update notification
,08-16 17:58:22.599   873  1944 I ActivityManager: Process com.android.bluetooth (pid 2674) has died
,08-16 17:58:22.625  1704  1704 D SystemUpdateService: onDestroy
,08-16 17:58:22.637  3904  3929 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:58:22.646  3940  3940 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 17:58:22.652  3940  3940 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:22.659  3940  3940 D SprintDMHelper: simOperator: 
,08-16 17:58:22.659  3940  3940 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:58:22.671   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d01bf12:true
,08-16 17:58:22.675   873   883 I ActivityManager: Start proc 3954:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 17:58:22.776  2390  3968 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 17:58:22.786   873  1701 I ActivityManager: Start proc 3969:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 17:58:22.789   873   883 I ActivityManager: Killing 1722:android.process.acore/u0a5 (adj 15): empty #17
,08-16 17:58:22.870  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 17:58:22.948  3969  3969 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 17:58:22.948  3969  3969 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:58:22.948  3969  3969 I GAv4    :   adb logcat -s GAv4
,08-16 17:58:22.973  3969  3969 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:58:22.980  3969  3969 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,08-16 17:58:22.995  3969  3987 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:58:23.098  3969  3969 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 17:58:23.136  3969  3969 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 17:58:23.145  3969  3969 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7637-7639)
,08-16 17:58:23.145  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:58:23.154  3969  3969 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4726769}
,08-16 17:58:23.155  3969  3969 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:58:23.155  3969  3969 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:58:23.168  3969  3969 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:58:23.170  3969  3969 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:58:23.188  3969  3969 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 17:58:23.200  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:58:23.200  3969  3969 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:58:23.201  3969  3969 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:58:23.201  3969  3969 I Adreno  : Build Date                       : 10/20/15
08-16 17:58:23.201  3969  3969 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:58:23.201  3969  3969 I Adreno  : Local Branch                     : M14
08-16 17:58:23.201  3969  3969 I Adreno  : Remote Branch                    : 
08-16 17:58:23.201  3969  3969 I Adreno  : Remote Branch                    : 
08-16 17:58:23.201  3969  3969 I Adreno  : Reconstruct Branch               : 
,08-16 17:58:23.270  3969  3969 I NSApplication: Starting up...
,08-16 17:58:23.281  3969  4015 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 17:58:23.310   873  1701 I ActivityManager: Start proc 4020:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-16 17:58:23.311   873  1701 I ActivityManager: Killing 3637:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 17:58:23.390  4020  4020 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 17:58:23.571   873  1699 I ActivityManager: Killing 3654:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 17:58:24.996   873  1379 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,08-16 17:58:24.996   873  1379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:58:25.012   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:58:25.022  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:25.023  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:25.023  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:25.023  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:25.027  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:25.027  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:25.028  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:25.028  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:25.050   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-16 17:58:25.052   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 17:58:25.053   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 17:58:25.053   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:58:25.054   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 17:58:25.054   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 17:58:25.054   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 17:58:25.074   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 17:58:25.074   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.88 rxSuccessRate=15.88 delta 1000 -> 994
,08-16 17:58:25.075   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:25.077   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-16 17:58:25.077   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:58:25.082   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 17:58:25.082   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:25.083   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:58:25.084   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:58:25.096   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:58:25.150   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:58:25.151  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:58:25.566  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:58:25.605  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:58:25.606  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 17:58:25.614   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:58:25.624   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 17:58:25.625   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:58:25.625   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:58:25.638   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:25.649   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:25.651   873  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:58:25.664   873  1309 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 17:58:25.666   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:58:25.690   873  4046 D DhcpClient: Receive thread started
,08-16 17:58:25.775   873  1307 E native  : do suspend false
,08-16 17:58:25.796   873  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:58:25.810   873  4046 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-16 17:58:25.812   873  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-16 17:58:25.815   873  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:58:25.828   873  4046 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:58:25.829   873  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:58:25.834   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:25.846   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:58:25.851   873  1873 D DhcpClient: Scheduling renewal in 86399s
,08-16 17:58:25.864   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE],
,08-16 17:58:25.868   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
08-16 17:58:25.869   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:58:25.869   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 17:58:25.872   873  1309 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 17:58:25.886   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:58:25.928   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 17:58:25.928   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 17:58:25.929   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 17:58:25.931   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 17:58:25.933   873  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 17:58:25.947   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 17:58:25.951   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 17:58:25.951   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 17:58:25.952   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 17:58:25.952   873  1309 D ConnectivityService:    accepting network in place of null
,08-16 17:58:25.952   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 17:58:25.953   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:58:25.953   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:58:25.964   873  4045 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140459, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:58:26.009   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:26.030   873  4044 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.19.206,2a00:1450:4001:810::200e
,08-16 17:58:26.059   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:26.064   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 17:58:26.064   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:26.068   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 17:58:26.073   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:26.087  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:26.088  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:26.088  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:26.088  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:26.092  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:26.092  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:26.092  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:26.092  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:26.096  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 17:58:26.099   873  4044 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:58:26 GMT], X-Android-Received-Millis=[1471363106098], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471363106074]}
08-16 17:58:26.100  1704  1704 D SystemUpdateService: onCreate
08-16 17:58:26.100   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 17:58:26.101   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 17:58:26.101   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:58:26.102   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 17:58:26.104  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-16 17:58:26.115  1704  4057 I SystemUpdateService: active receiver: enabled
08-16 17:58:26.118  1704  4057 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-16 17:58:26.121  1704  4057 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-16 17:58:26.121  1704  4057 I SystemUpdateService: now status is 0 (complete)
08-16 17:58:26.121  1704  4057 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:58:26.121  1704  4057 I SystemUpdateService: file has been verified
08-16 17:58:26.121  1704  4057 I SystemUpdateService: OTA package size = 12249756
08-16 17:58:26.123  1704  4057 I SystemUpdateService: showing system update notification
08-16 17:58:26.132  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:58:26.136  1704  4062 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 17:58:26.136  1704  2434 I iu.UploadsManager: num queued entries: 0
08-16 17:58:26.137  1704  4062 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:58:26.139  1704  2434 I iu.UploadsManager: num updated entries: 0
08-16 17:58:26.139  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 17:58:26.140  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 17:58:26.141  1704  4062 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 17:58:26.141  1704  1704 D SystemUpdateService: onDestroy
08-16 17:58:26.143  3940  3940 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-16 17:58:26.147  1704  2434 I iu.SyncManager: NEXT; no task
08-16 17:58:26.148  3940  3940 D SprintDMHelper: simOperator: 
08-16 17:58:26.148  3940  3940 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-16 17:58:26.148  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 17:58:26.150  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:26.179  1506  3611 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 17:58:26.179  1506  3611 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 17:58:26.179  1506  3611 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:26.179  1506  3611 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:26.193  1704  4062 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-16 17:58:26.256  2390  4064 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:58:27.065   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 17:58:27.585   873  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-16 17:58:27.798   873  1944 I ActivityManager: Killing 2202:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 17:58:28.003   873  2973 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,08-16 17:58:28.003   873  2973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:58:28.039  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 17:58:28.043   873  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 17:58:28.043   873  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 17:58:28.043   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:58:28.044   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:28.062   873  1873 D DhcpClient: Clearing IP address
,08-16 17:58:28.062   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:28.066   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:28.075  1506  4068 V NativeCrypto: Read error: ssl=0x9b77f800: I/O error during system call, Connection timed out
,08-16 17:58:28.079   873  4046 D DhcpClient: Receive thread stopped
,08-16 17:58:28.081  1506  4068 V NativeCrypto: SSL shutdown failed: ssl=0x9b77f800: I/O error during system call, Broken pipe
,08-16 17:58:28.085   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 17:58:28.086   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 17:58:28.090   873  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 17:58:28.092   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:58:28.096   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 17:58:28.099   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:28.105   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:58:28.109  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.109  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:28.109   873  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 17:58:28.109  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:28.109  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:28.110  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.110  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:28.110  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:28.110  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-16 17:58:28.111   873  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 17:58:28.114  2006  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:28.158   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:28.185   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:28.186   873  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 17:58:28.186   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:28.190   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:28.194  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.194  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:28.195  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.195  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:28.200  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:58:28.213  1704  1704 D SystemUpdateService: onCreate
,08-16 17:58:28.220  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:58:28.229  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:58:28.232  1704  2434 I iu.UploadsManager: num queued entries: 0
08-16 17:58:28.234  1704  4078 I SystemUpdateService: active receiver: enabled
08-16 17:58:28.238  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 17:58:28.239  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:58:28.242  3940  3940 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:28.246  3940  3940 D SprintDMHelper: simOperator: 
,08-16 17:58:28.246  3940  3940 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:58:28.255  1704  2434 I iu.UploadsManager: num updated entries: 0,
,08-16 17:58:28.265   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:58:28.268   873  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 17:58:28.276  1704  4078 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:58:28.276  2390  4083 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 17:58:28.280  1704  2434 I iu.SyncManager: NEXT; no task
,08-16 17:58:28.284  1704  4078 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 17:58:28.284  1704  4078 I SystemUpdateService: now status is 0 (complete)
08-16 17:58:28.284  1704  4078 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:58:28.284  1704  4078 I SystemUpdateService: file has been verified
,08-16 17:58:28.284  1704  4078 I SystemUpdateService: OTA package size = 12249756
,08-16 17:58:28.289  1704  4078 I SystemUpdateService: showing system update notification
,08-16 17:58:28.298  1704  1704 D SystemUpdateService: onDestroy
,08-16 17:58:31.060   873   890 I ActivityManager: Start proc 4085:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 17:58:31.203  4085  4085 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:58:31.204  4085  4085 D AdapterServiceConfig: Adding A2dpService
,08-16 17:58:31.205  4085  4085 D AdapterServiceConfig: Adding HidService
,08-16 17:58:31.206  4085  4085 D AdapterServiceConfig: Adding HealthService
,08-16 17:58:31.206  4085  4085 D AdapterServiceConfig: Adding PanService
08-16 17:58:31.207  4085  4085 D AdapterServiceConfig: Adding GattService
,08-16 17:58:31.207  4085  4085 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 17:58:31.235   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f0d36e7:true
,08-16 17:58:31.236  4085  4085 D BluetoothAdapterState: make() - Creating AdapterState,
,08-16 17:58:31.241  4085  4085 I bt_bluedroid: init
,08-16 17:58:31.241  4085  4097 I BluetoothAdapterState: Entering OffState
,08-16 17:58:31.243  4085  4098 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:58:31.243  4085  4098 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 17:58:31.243  4085  4098 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:58:31.243  4085  4098 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:58:31.243  4085  4085 I bt_bluedroid: get_profile_interface socket,
,08-16 17:58:31.245  4085  4085 I bt_bluedroid: get_profile_interface sdp
08-16 17:58:31.248  4085  4096 I bt_bluedroid: config_hci_snoop_log
,08-16 17:58:31.249  4085  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 17:58:31.250  4085  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:58:31.250   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:58:31.260  4085  4097 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 17:58:31.261  4085  4097 D BluetoothAdapterProperties: Setting state to 14
,08-16 17:58:31.261  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 17:58:31.265  4085  4097 D BluetoothBondStateMachine: make
,08-16 17:58:31.268  4085  4102 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:58:31.274  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:58:31.274  4085  4085 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:58:31.277  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:31.278  4085  4085 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:58:31.278  4085  4085 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:58:31.279  4085  4085 D BtGatt.GattService: start()
,08-16 17:58:31.279  4085  4085 I bt_bluedroid: get_profile_interface gatt
08-16 17:58:31.280  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:31.280  4085  4085 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:58:31.287  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:31.287  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:31.287  4085  4085 V BluetoothAdapterState: isBleTurningOn()=true
08-16 17:58:31.288  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:31.288  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 17:58:31.289  4085  4097 I bt_bluedroid: enable
08-16 17:58:31.289  4085  4098 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 17:58:31.289  4085  4098 I bt_hci  : start_up
,08-16 17:58:31.295  4085  4098 I bt_vendor: alloc value 0xb39a6189
08-16 17:58:31.295  4085  4098 I bt_vendor: init
08-16 17:58:31.295  4085  4098 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:58:31.295  4085  4098 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:58:31.404  4085  4098 D bt_hci  : start_up starting async portion
,08-16 17:58:31.405  4085  4105 I bt_hci  : event_finish_startup
08-16 17:58:31.405  4085  4105 I bt_hci_h4: hal_open
,08-16 17:58:31.405  4085  4105 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:58:31.418  4085  4105 I bt_userial_vendor: device fd = 51 open
,08-16 17:58:31.445  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:58:31.477  4085  4105 D bt_hwcfg: Chipset BCM4354A2
,08-16 17:58:31.477  4085  4105 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 17:58:31.478  4085  4105 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:58:32.154  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:58:32.156  4085  4105 D bt_hwcfg: Settlement delay -- 100 ms
08-16 17:58:32.156  4085  4105 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:58:32.273  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:58:32.275  4085  4105 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:58:32.303  4085  4105 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:58:32.303  4085  4105 I bt_vendor: firmware callback
08-16 17:58:32.304  4085  4105 I bt_hci  : firmware_config_callback
,08-16 17:58:32.314  4085  4107 I bt_btu  : btu_task pending for preload complete event
,08-16 17:58:32.314  4085  4107 I bt_btu_task: Bluetooth chip preload is complete
,08-16 17:58:32.315  4085  4107 I bt_btu  : btu_task received preload complete event
,08-16 17:58:32.328  4085  4107 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:58:32.328  4085  4107 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 17:58:32.329  4085  4107 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:58:32.329  4085  4107 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:58:32.329  4085  4107 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:58:32.329  4085  4107 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 17:58:32.330  4085  4107 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:58:32.330  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:58:32.330  4085  4107 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 17:58:32.330  4085  4107 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:58:32.331  4085  4107 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:58:32.331  4085  4107 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:58:32.331  4085  4107 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 17:58:32.331  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:58:32.332  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:58:32.470  4085  4107 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3923d9d
,08-16 17:58:32.470  4085  4107 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3923d9d 
,08-16 17:58:32.482  4085  4101 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 17:58:32.485  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:58:32.486  4085  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:58:32.489  4085  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:58:32.492  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:58:32.492  4085  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:32.493  4085  4101 D bt_hci  : do_postload posting postload work item
,08-16 17:58:32.493  4085  4105 I bt_hci  : event_postload
08-16 17:58:32.493  4085  4105 I bt_vendor: sco_config_cb
,08-16 17:58:32.493  4085  4105 I bt_hci  : sco_config_callback postload finished.
,08-16 17:58:32.497  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.499  4085  4101 D bt_bte_conf: Device ID record 1 : primary
,08-16 17:58:32.499  4085  4101 D bt_bte_conf:   vendorId            = 000f
08-16 17:58:32.500  4085  4101 D bt_bte_conf:   vendorIdSource      = 0001
08-16 17:58:32.500  4085  4101 D bt_bte_conf:   product             = 1200
08-16 17:58:32.500  4085  4101 D bt_bte_conf:   version             = 1436
08-16 17:58:32.500  4085  4101 D bt_bte_conf:   clientExecutableURL = 
,08-16 17:58:32.501  4085  4101 D bt_bte_conf:   serviceDescription  = 
,08-16 17:58:32.501  4085  4101 D bt_bte_conf:   documentationURL    = 
08-16 17:58:32.501  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.501  4085  4101 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:58:32.502  4085  4098 D bt_stack_manager: event_start_up_stack finished
,08-16 17:58:32.502  4085  4105 I bt_vendor: low_power_mode_cb
,08-16 17:58:32.502  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 17:58:32.503  4085  4097 D BluetoothAdapterProperties: Setting state to 15
,08-16 17:58:32.504  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:58:32.505  4085  4097 I BluetoothAdapterState: Entering BleOnState
08-16 17:58:32.511  4085  4097 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 17:58:32.512  4085  4097 D BluetoothAdapterProperties: Setting state to 11
08-16 17:58:32.512  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 17:58:32.525  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.526  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:32.527  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.527  4085  4085 D HeadsetService: Received start request. Starting profile...
08-16 17:58:32.530  4085  4085 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:58:32.531  4085  4085 D HeadsetStateMachine: make
,08-16 17:58:32.539  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:58:32.541  4085  4085 D HeadsetStateMachine: max_hf_connections = 1
,08-16 17:58:32.541  4085  4085 I bt_bluedroid: get_profile_interface handsfree
08-16 17:58:32.542  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:58:32.542  4085  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 17:58:32.547  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:32.548  4085  4085 D A2dpService: Received start request. Starting profile...
,08-16 17:58:32.551  4085  4085 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:58:32.552  4085  4085 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:58:32.559  4085  4085 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:58:32.559  4085  4085 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 17:58:32.559  4085  4085 D A2dpStateMachine: make
,08-16 17:58:32.561  4085  4085 I bt_bluedroid: get_profile_interface a2dp
,08-16 17:58:32.562  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 17:58:32.566  4085  4116 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:58:32.566  4085  4085 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:58:32.568  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:32.569  3887  3887 D BluetoothInputDevice: Proxy object connected
,08-16 17:58:32.570  3887  3887 D HidProfile: Bluetooth service connected
,08-16 17:58:32.571  4085  4085 D HidService: Received start request. Starting profile...
,08-16 17:58:32.571  4085  4085 I bt_bluedroid: get_profile_interface hidhost
08-16 17:58:32.571  4085  4101 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39053e5
,08-16 17:58:32.571  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 17:58:32.571  4085  4085 D HidService: setHidService(): set to: null
08-16 17:58:32.573  4085  4085 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:58:32.574  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:32.574  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:32.575  4085  4085 D HealthService: Received start request. Starting profile...
,08-16 17:58:32.576  4085  4085 I bt_bluedroid: get_profile_interface health
08-16 17:58:32.577  4085  4085 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:58:32.578  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:32.579  3887  3887 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:58:32.579  4085  4085 D PanService: Received start request. Starting profile...
08-16 17:58:32.579  4085  4085 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:58:32.579  4085  4085 I bt_bluedroid: get_profile_interface pan
08-16 17:58:32.580  3887  3887 D PanProfile: Bluetooth service connected
08-16 17:58:32.581  4085  4101 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:58:32.589  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:32.590  4085  4085 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:58:32.590  4085  4085 D BluetoothMapService: start()
,08-16 17:58:32.591  3887  3887 D BluetoothMap: Proxy object connected
08-16 17:58:32.591  3887  3887 D MapProfile: Bluetooth service connected
08-16 17:58:32.591  3887  3887 D BluetoothMap: getConnectedDevices()
,08-16 17:58:32.592  3887  3887 D BluetoothMap: Bluetooth is Not enabled
08-16 17:58:32.593  4085  4085 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 17:58:32.594  4085  4085 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 17:58:32.595  4085  4085 D BluetoothMapAppObserver: createReceiver()
,08-16 17:58:32.596  4085  4085 D BluetoothMapAppObserver: initObservers()
,08-16 17:58:32.596  4085  4085 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:58:32.604  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:32.604  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:32.604  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:32.604  4085  4114 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:58:32.604  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:32.606  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:32.607  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:58:32.608  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.608  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:32.608  4085  4085 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:58:32.608  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:32.608  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:32.609  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 17:58:32.609  4085  4097 D BluetoothAdapterProperties: ScanMode =  20
,08-16 17:58:32.609  4085  4097 D BluetoothAdapterProperties: State =  11
08-16 17:58:32.615  4085  4101 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:58:32.615  4085  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:58:32.615  4085  4097 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:58:32.615  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:58:32.616   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:32.616   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:32.616  4085  4097 I BluetoothAdapterState: Entering OnState
08-16 17:58:32.616  3887  3897 D BluetoothPan: onBluetoothStateChange on: true
,08-16 17:58:32.617  1361  2025 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:58:32.619  1361  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.619  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:32.621  1361  2025 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:58:32.621  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 17:58:32.622  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:32.622  1361  1361 D HidProfile: Bluetooth service connected
08-16 17:58:32.623  4085  4085 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:58:32.624  4085  4085 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 17:58:32.624  1361  1381 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:58:32.626   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:32.626  4085  4085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.626  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:32.626  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:32.627  1361  1361 D PanProfile: Bluetooth service connected
08-16 17:58:32.627  3887  3899 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:58:32.629  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:32.629  4085  4085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:32.629  1925  2220 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:32.630  1361  2025 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:58:32.630  4085  4085 D ObexServerSockets: Succeed to create listening sockets 
08-16 17:58:32.630  3887  3897 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:32.630  4085  4085 D ObexServerSockets0: startAccept()
08-16 17:58:32.630  4085  4085 D ObexServerSockets0: prepareForNewConnect()
08-16 17:58:32.631  1361  1380 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:58:32.633  3887  3899 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:58:32.633  1361  1361 D BluetoothMap: Proxy object connected
08-16 17:58:32.635  1361  1361 D MapProfile: Bluetooth service connected
08-16 17:58:32.635  1361  1361 D BluetoothMap: getConnectedDevices()
08-16 17:58:32.635   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:32.638  4085  4085 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 17:58:32.638  4085  4085 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 17:58:32.639   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 17:58:32.642  3887  3887 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 17:58:32.642  4085  4122 D ObexServerSockets0: Accepting socket connection...
08-16 17:58:32.643  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.645  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:32.645  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 17:58:32.645   873   873 D BluetoothA2dp: Proxy object connected
08-16 17:58:32.645  4085  4085 D BluetoothMapService: onReceive
08-16 17:58:32.646  4085  4085 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:32.646  4085  4085 D BluetoothMapService: STATE_ON
08-16 17:58:32.648  3887  3887 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 17:58:32.648  4085  4123 D ObexServerSockets0: Accepting socket connection...
08-16 17:58:32.656  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:32.658  3887  3887 D BluetoothA2dp: Proxy object connected
08-16 17:58:32.662  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:32.673  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:32.678  1361  1361 D BluetoothPbap: Proxy object connected
08-16 17:58:32.679  1361  1361 D PbapServerProfile: Bluetooth service connected
08-16 17:58:32.679  3887  3887 D BluetoothPbap: Proxy object connected
08-16 17:58:32.679  3887  3887 D PbapServerProfile: Bluetooth service connected
08-16 17:58:32.681  4085  4085 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:58:32.681  4085  4085 D ObexServerSockets0: prepareForNewConnect()
,08-16 17:58:32.692  4085  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:32.712  4085  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:32.713  4085  4132 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:32.717   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:58:32.717   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:58:32.717  1925  2241 D BluetoothHeadset: Proxy object connected
,08-16 17:58:32.718   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:58:32.718  1361  2025 D BluetoothHeadset: Proxy object connected
08-16 17:58:32.718  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:32.730  1925  1945 D BluetoothHeadset: Proxy object connected
,08-16 17:58:32.731  1361  1380 D BluetoothHeadset: Proxy object connected
08-16 17:58:32.731  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:32.738   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:58:32.750  3887  3897 D BluetoothHeadset: Proxy object connected
08-16 17:58:32.752  3887  3887 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:33.958   873  1309 D ConnectivityService: handlePromptUnvalidated 101
,08-16 17:58:34.025  4085  4097 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 17:58:34.026  4085  4097 D BluetoothAdapterProperties: Setting state to 13
,08-16 17:58:34.027  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 17:58:34.029  4085  4097 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:58:34.036  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:58:34.040  4085  4085 D BluetoothMapService: onReceive
08-16 17:58:34.040  4085  4085 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:34.040  4085  4085 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:58:34.042  4085  4085 D BluetoothMapService: MAP Service closeService in
08-16 17:58:34.043  4085  4085 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 17:58:34.043  4085  4085 D ObexServerSockets0: shutdown(block = true)
08-16 17:58:34.044  4085  4122 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 17:58:34.048  4085  4085 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:58:34.049  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:34.049  4085  4123 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:34.049  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:34.050  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:34.051  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:34.052  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:34.052  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 17:58:34.056  4085  4110 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:58:34.056  4085  4085 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:58:34.057  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:34.057  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:34.058  4085  4085 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:58:34.060  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:34.060  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:34.063  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:34.064  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:34.065   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:34.065   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:34.065  1925  1937 D BluetoothHeadset: Proxy object disconnected
08-16 17:58:34.066  4085  4085 I BtOppRfcommListener: stopping Accept Thread
08-16 17:58:34.066   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:58:34.066  4085  4132 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:58:34.066  1361  1380 D BluetoothHeadset: Proxy object disconnected
08-16 17:58:34.067  4085  4132 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:58:34.067  3887  3899 D BluetoothHeadset: Proxy object disconnected
08-16 17:58:34.068  4085  4085 D A2dpService: Received stop request...Stopping profile...
08-16 17:58:34.068  4085  4116 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:58:34.069  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-16 17:58:34.071   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:34.071  1361  1361 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:34.071  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:34.072  4085  4085 D HidService: Received stop request...Stopping profile...
08-16 17:58:34.072  4085  4085 D HidService: Stopping Bluetooth HidService
08-16 17:58:34.073  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-16 17:58:34.073  1361  1361 D HidProfile: Bluetooth service disconnected
08-16 17:58:34.073  4085  4085 D HealthService: Received stop request...Stopping profile...
,08-16 17:58:34.078  3887  3887 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:58:34.078  3887  3887 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:34.078  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:34.079  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:34.079  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.079  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:34.079  3887  3887 D BluetoothInputDevice: Proxy object disconnected
08-16 17:58:34.079  3887  3887 D HidProfile: Bluetooth service disconnected
08-16 17:58:34.079  4085  4085 D PanService: Received stop request...Stopping profile...
08-16 17:58:34.080  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:58:34.080  1361  1361 D PanProfile: Bluetooth service disconnected
08-16 17:58:34.081  4085  4085 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:58:34.081  4085  4085 D BluetoothMapService: stop()
,08-16 17:58:34.081  4085  4085 D BluetoothMapAppObserver: deinitObservers()
08-16 17:58:34.081  4085  4085 D BluetoothMapAppObserver: removeReceiver()
08-16 17:58:34.082  1361  1361 D BluetoothMap: Proxy object disconnected
,08-16 17:58:34.082  1361  1361 D MapProfile: Bluetooth service disconnected
,08-16 17:58:34.084  4085  4085 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:58:34.084  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 17:58:34.084  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:34.085  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:34.085  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:58:34.084  4085  4085 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:58:34.085  4085  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
08-16 17:58:34.086  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:34.086  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:34.086  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.086  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:34.087  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 17:58:34.087  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:34.088  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:34.088  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:58:34.088  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 17:58:34.088  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:58:34.088  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:34.088  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-16 17:58:34.088  4085  4085 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:58:34.089  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.089  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:34.089  4085  4085 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 17:58:34.089  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 17:58:34.089  4085  4085 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 17:58:34.090  4085  4085 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:58:34.090  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:34.090  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.090  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:34.091  4085  4085 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:34.091  4085  4101 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 17:58:34.092  4085  4085 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 17:58:34.092  4085  4085 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:58:34.092  4085  4085 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:58:34.092  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.092  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:34.092  4085  4085 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:58:34.092  4085  4085 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:58:34.093  4085  4085 D BluetoothMapService: MAP Service closeService in
08-16 17:58:34.093  4085  4085 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:58:34.093  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:34.093  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:34.093  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:34.094  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 17:58:34.094  4085  4097 D BluetoothAdapterProperties: Setting state to 15
08-16 17:58:34.094  4085  4085 D BluetoothMapService: cleanup()
08-16 17:58:34.094  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:58:34.094  4085  4085 D BluetoothMapService: MAP Service closeService in
,08-16 17:58:34.094  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:34.094   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.094   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.095  3887  3897 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:58:34.095  4085  4097 I BluetoothAdapterState: Entering BleOnState
,08-16 17:58:34.096  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:34.097  1361  2025 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:58:34.097  1361  1361 D BluetoothPbap: Proxy object disconnected
08-16 17:58:34.097  3887  3887 D BluetoothMap: Proxy object disconnected
08-16 17:58:34.097  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-16 17:58:34.098  1361  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:58:34.097  3887  3887 D MapProfile: Bluetooth service disconnected
08-16 17:58:34.100  3887  3887 D BluetoothPbap: Proxy object disconnected
,08-16 17:58:34.100  3887  3887 D PbapServerProfile: Bluetooth service disconnected
08-16 17:58:34.103  1361  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:34.103  1361  2025 D BluetoothPan: onBluetoothStateChange on: false
,08-16 17:58:34.103   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:34.104  3887  3899 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:58:34.105  1925  2220 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.106  1361  4137 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.106  3887  3899 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.106  3887  3897 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:34.107  3887  3899 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:58:34.107  1361  1381 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:58:34.108  3887  3897 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:58:34.108   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:58:34.108  4085  4097 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 17:58:34.108  4085  4097 D BluetoothAdapterProperties: Setting state to 16
08-16 17:58:34.109  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:58:34.109  4085  4097 D BluetoothAdapterProperties: onBleDisable
08-16 17:58:34.111  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:58:34.111  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:34.111  4085  4098 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 17:58:34.112  4085  4107 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:58:34.112  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:58:34.112  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:34.113  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:34.114  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:34.114  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:34.115  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:34.118  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:34.125  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:34.312  4085  4101 I bt_hci  : shut_down
08-16 17:58:34.313  4085  4105 D bt_hwcfg: hw_epilog_process
,08-16 17:58:34.314  4085  4105 I bt_vendor: low_power_mode_cb
,08-16 17:58:34.334  4085  4105 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:58:34.334  4085  4105 I bt_vendor: epilog_cb
,08-16 17:58:34.334  4085  4105 I bt_hci  : epilog_finished_callback
,08-16 17:58:34.344  4085  4101 I bt_hci_h4: hal_close
,08-16 17:58:34.345  4085  4101 I bt_userial_vendor: device fd = 51 close
,08-16 17:58:34.478  4085  4098 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:58:34.479  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 17:58:34.485  4085  4085 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:58:34.485  4085  4097 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:58:34.487  4085  4085 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:58:34.487  4085  4085 D BtGatt.GattService: stop()
08-16 17:58:34.487  4085  4085 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:58:34.493  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:34.493  4085  4085 V BluetoothAdapterState: isTurningOn()=false,
08-16 17:58:34.494  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:58:34.494  4085  4085 V BluetoothAdapterState: isBleTurningOff()=true
08-16 17:58:34.495  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 17:58:34.496  4085  4097 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:34.496  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 17:58:34.498  4085  4097 I BluetoothAdapterState: Entering OffState
08-16 17:58:34.500   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 17:58:34.521  4085  4085 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 17:58:34.522  4085  4085 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 17:58:34.522  4085  4085 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:58:34.525  4085  4098 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 17:58:34.537  4085  4098 D bt_stack_manager: event_clean_up_stack finished.
,08-16 17:58:34.540  4085  4085 I art     : System.exit called, status: 0
,08-16 17:58:34.540  4085  4085 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:58:34.600   873  1699 I ActivityManager: Process com.android.bluetooth (pid 4085) has died
,08-16 17:58:35.633   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 17:58:35.646  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 17:58:35.659   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:58:35.659   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 17:58:35.659   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:58:35.659   873   893 I Adreno  : Local Branch                     : M14
08-16 17:58:35.659   873   893 I Adreno  : Remote Branch                    : 
08-16 17:58:35.659   873   893 I Adreno  : Remote Branch                    : 
08-16 17:58:35.659   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 17:58:35.704   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (235 us)
,08-16 17:58:36.311  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:58:36.312  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:58:36.363  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@670f683 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a4c6543, 16908290=android.view.AbsSavedState$1@a4c6543}, android:focusedViewId=100}]}]
,08-16 17:58:36.364  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 17:58:36.364  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:58:36.364  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-16 17:58:36.363   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 17:58:36.376   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 17:58:36.380   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 17:58:36.381   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-16 17:58:36.381   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 17:58:36.621   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 17:58:36.626   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 17:58:36.632   873  1331 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
08-16 17:58:36.638   873   893 I DreamManagerService: Entering dreamland.
,08-16 17:58:36.639   873   893 I PowerManagerService: Dozing...
,08-16 17:58:36.640   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 17:58:36.696   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 17:58:36.696   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 17:58:36.706   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:58:36.717   873  1307 E native  : do suspend false
,08-16 17:58:36.722  1913  4143 D NfcService: Discovery configuration equal, not updating.
,08-16 17:58:36.749   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:58:36.754   873  1307 E native  : do suspend true
,08-16 17:58:36.834   375  1315 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 17:58:36.834   375  1315 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 17:58:37.022  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:58:37.022  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:38.249  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:38.266  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:38.272  1506  1506 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:58:38.329  1506  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 17:58:38.329  1506  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 17:58:38.330  1506  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:38.330  1506  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:38.375  3476  3476 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 17:58:38.376  3476  3476 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 17:58:38.377  3476  3476 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 17:58:40.026  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:40.026  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e33b7c0 added. We now have 6 listener(s)
,08-16 17:58:40.026  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:40.029  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:40.029  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c81ecf9 added. We now have 7 listener(s)
08-16 17:58:40.029  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:40.030  3815  3863 I System.out: IsBluetoothEnabled
,08-16 17:58:40.038  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:40.063   873   890 I ActivityManager: Start proc 4151:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 17:58:40.192  4151  4151 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:58:40.193  4151  4151 D AdapterServiceConfig: Adding A2dpService
08-16 17:58:40.193  4151  4151 D AdapterServiceConfig: Adding HidService
,08-16 17:58:40.193  4151  4151 D AdapterServiceConfig: Adding HealthService
08-16 17:58:40.193  4151  4151 D AdapterServiceConfig: Adding PanService
08-16 17:58:40.193  4151  4151 D AdapterServiceConfig: Adding GattService
,08-16 17:58:40.194  4151  4151 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 17:58:40.209   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@be36b69:true
,08-16 17:58:40.209  4151  4151 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 17:58:40.216  4151  4151 I bt_bluedroid: init
,08-16 17:58:40.217  4151  4163 I BluetoothAdapterState: Entering OffState
08-16 17:58:40.220  4151  4164 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:58:40.220  4151  4164 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 17:58:40.220  4151  4164 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:58:40.220  4151  4164 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:58:40.221  4151  4151 I bt_bluedroid: get_profile_interface socket
,08-16 17:58:40.224  4151  4151 I bt_bluedroid: get_profile_interface sdp
08-16 17:58:40.227  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:58:40.230  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:58:40.232  4151  4162 I bt_bluedroid: config_hci_snoop_log
,08-16 17:58:40.236   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:58:40.245  4151  4163 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 17:58:40.246  4151  4163 D BluetoothAdapterProperties: Setting state to 14
,08-16 17:58:40.246  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 17:58:40.250  4151  4163 D BluetoothBondStateMachine: make
,08-16 17:58:40.254  4151  4168 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:58:40.260  4151  4163 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:58:40.262  4151  4151 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:58:40.265  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:40.266  4151  4151 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:58:40.267  4151  4151 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:58:40.267  4151  4151 D BtGatt.GattService: start()
,08-16 17:58:40.267  4151  4151 I bt_bluedroid: get_profile_interface gatt
,08-16 17:58:40.268  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:40.268  4151  4151 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:58:40.276  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:40.276  4151  4151 V BluetoothAdapterState: isTurningOn()=false
08-16 17:58:40.276  4151  4151 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 17:58:40.277  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:40.277  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 17:58:40.277  4151  4163 I bt_bluedroid: enable
08-16 17:58:40.277  4151  4164 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 17:58:40.278  4151  4164 I bt_hci  : start_up
,08-16 17:58:40.287  4151  4164 I bt_vendor: alloc value 0xb39a6189
,08-16 17:58:40.287  4151  4164 I bt_vendor: init
08-16 17:58:40.287  4151  4164 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:58:40.288  4151  4164 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:58:40.397  4151  4164 D bt_hci  : start_up starting async portion
,08-16 17:58:40.398  4151  4171 I bt_hci  : event_finish_startup
,08-16 17:58:40.398  4151  4171 I bt_hci_h4: hal_open
08-16 17:58:40.398  4151  4171 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:58:40.408  4151  4171 I bt_userial_vendor: device fd = 51 open
,08-16 17:58:40.439  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:58:40.470  4151  4171 D bt_hwcfg: Chipset BCM4354A2
,08-16 17:58:40.471  4151  4171 D bt_hwcfg: Target name = [BCM4354A2]
08-16 17:58:40.472  4151  4171 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:58:41.133  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:58:41.135  4151  4171 D bt_hwcfg: Settlement delay -- 100 ms
08-16 17:58:41.135  4151  4171 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:58:41.251  4151  4171 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:58:41.253  4151  4171 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:58:41.282  4151  4171 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:58:41.283  4151  4171 I bt_vendor: firmware callback
,08-16 17:58:41.283  4151  4171 I bt_hci  : firmware_config_callback
,08-16 17:58:41.294  4151  4174 I bt_btu  : btu_task pending for preload complete event
,08-16 17:58:41.294  4151  4174 I bt_btu_task: Bluetooth chip preload is complete
,08-16 17:58:41.294  4151  4174 I bt_btu  : btu_task received preload complete event
,08-16 17:58:41.307  4151  4174 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:58:41.308  4151  4174 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:58:41.308  4151  4174 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 17:58:41.308  4151  4174 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:58:41.309  4151  4174 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:58:41.309  4151  4174 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 17:58:41.309  4151  4174 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:58:41.309  4151  4174 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:58:41.310  4151  4174 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:58:41.310  4151  4174 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 17:58:41.310  4151  4174 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:58:41.310  4151  4174 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:58:41.310  4151  4174 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:58:41.311  4151  4174 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:58:41.311  4151  4174 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:58:41.350  2006  2629 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 17:58:41.446  4151  4174 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3923d9d
,08-16 17:58:41.447  4151  4174 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3923d9d 
,08-16 17:58:41.457  4151  4167 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-16 17:58:41.460  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 17:58:41.461  4151  4167 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 17:58:41.464  4151  4167 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:58:41.467  4151  4167 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:58:41.468  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:58:41.468  4151  4167 D bt_hci  : do_postload posting postload work item
08-16 17:58:41.469  4151  4171 I bt_hci  : event_postload
,08-16 17:58:41.469  4151  4171 I bt_vendor: sco_config_cb
08-16 17:58:41.469  4151  4171 I bt_hci  : sco_config_callback postload finished.
08-16 17:58:41.472  4151  4167 D bt_bte_conf: Device ID record 1 : primary
,08-16 17:58:41.472  4151  4167 D bt_bte_conf:   vendorId            = 000f
08-16 17:58:41.472  4151  4167 D bt_bte_conf:   vendorIdSource      = 0001
08-16 17:58:41.472  4151  4167 D bt_bte_conf:   product             = 1200
,08-16 17:58:41.472  4151  4167 D bt_bte_conf:   version             = 1436
,08-16 17:58:41.472  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:41.473  4151  4167 D bt_bte_conf:   clientExecutableURL = 
,08-16 17:58:41.473  4151  4167 D bt_bte_conf:   serviceDescription  = 
08-16 17:58:41.473  4151  4167 D bt_bte_conf:   documentationURL    = 
08-16 17:58:41.473  4151  4167 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 17:58:41.474  4151  4164 D bt_stack_manager: event_start_up_stack finished
08-16 17:58:41.475  4151  4171 I bt_vendor: low_power_mode_cb
08-16 17:58:41.475  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 17:58:41.476  4151  4163 D BluetoothAdapterProperties: Setting state to 15
08-16 17:58:41.476  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:58:41.479  4151  4163 I BluetoothAdapterState: Entering BleOnState
,08-16 17:58:41.486  4151  4163 D BluetoothAdapterState: Current state: BLE ON, message: 1,
08-16 17:58:41.486  4151  4163 D BluetoothAdapterProperties: Setting state to 11,
08-16 17:58:41.486  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 17:58:41.495  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:41.500  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:41.501  4151  4151 D HeadsetService: Received start request. Starting profile...
,08-16 17:58:41.504  4151  4151 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:58:41.505  4151  4151 D HeadsetStateMachine: make
,08-16 17:58:41.513  4151  4163 I BluetoothAdapterState: Entering PendingCommandState,
08-16 17:58:41.513  4151  4151 D HeadsetStateMachine: max_hf_connections = 1
,08-16 17:58:41.513  4151  4151 I bt_bluedroid: get_profile_interface handsfree
08-16 17:58:41.513  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:58:41.514  4151  4167 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
,08-16 17:58:41.518  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:41.518  4151  4151 D A2dpService: Received start request. Starting profile...
,08-16 17:58:41.520  4151  4151 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:58:41.520  4151  4151 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:58:41.525  4151  4151 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:58:41.525  4151  4151 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:58:41.526  4151  4151 D A2dpStateMachine: make
,08-16 17:58:41.526  4151  4151 I bt_bluedroid: get_profile_interface a2dp
,08-16 17:58:41.527  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 17:58:41.528  4151  4183 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:58:41.530  4151  4151 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:58:41.531  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:41.531  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:41.532  4151  4151 D HidService: Received start request. Starting profile...
,08-16 17:58:41.532  4151  4151 I bt_bluedroid: get_profile_interface hidhost
08-16 17:58:41.533  4151  4151 D HidService: setHidService(): set to: null
,08-16 17:58:41.533  4151  4167 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39053e5
,08-16 17:58:41.533  4151  4151 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:58:41.533  4151  4167 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 17:58:41.534  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:41.534  4151  4151 D HealthService: Received start request. Starting profile...
,08-16 17:58:41.536  4151  4151 I bt_bluedroid: get_profile_interface health
08-16 17:58:41.537  4151  4151 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 17:58:41.538  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
08-16 17:58:41.538  4151  4151 D PanService: Received start request. Starting profile...
08-16 17:58:41.538  4151  4151 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:58:41.538  4151  4151 I bt_bluedroid: get_profile_interface pan
08-16 17:58:41.539  4151  4167 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:58:41.542  4151  4151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:41.542  4151  4151 D BluetoothMapService: Received start request. Starting profile...
08-16 17:58:41.542  4151  4151 D BluetoothMapService: start()
,08-16 17:58:41.544  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 17:58:41.545  4151  4151 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 17:58:41.545  4151  4151 D BluetoothMapAppObserver: createReceiver()
,08-16 17:58:41.546  4151  4151 D BluetoothMapAppObserver: initObservers()
,08-16 17:58:41.546  4151  4151 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:58:41.553  4151  4181 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:58:41.553  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:41.554  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:41.554  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:41.554  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:41.556  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:41.556  4151  4151 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:58:41.556  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:41.557  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isTurningOn()=true
08-16 17:58:41.559  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:58:41.560  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:58:41.560  4151  4151 V BluetoothAdapterState: isTurningOff()=false
08-16 17:58:41.560  4151  4151 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:58:41.560  4151  4151 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:58:41.560  4151  4151 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:58:41.560  4151  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 17:58:41.560  4151  4163 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:58:41.560  4151  4163 D BluetoothAdapterProperties: State =  11
,08-16 17:58:41.562  4151  4167 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:58:41.562  4151  4163 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:58:41.562  4151  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:58:41.563  4151  4167 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:58:41.563   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:58:41.563   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:58:41.563  3887  3897 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:58:41.563  4151  4163 I BluetoothAdapterState: Entering OnState
,08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:41.565  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:41.566  1361  2025 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:58:41.567  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-16 17:58:41.567  1361  4137 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:41.569  1361  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:58:41.571  1361  1361 D BluetoothInputDevice: Proxy object connected
08-16 17:58:41.571  1361  1361 D HidProfile: Bluetooth service connected
,08-16 17:58:41.572  3887  3887 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:58:41.572  3887  3887 D PanProfile: Bluetooth service connected
08-16 17:58:41.574  1361  4137 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:58:41.574  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener,
08-16 17:58:41.574  1361  1361 D BluetoothA2dp: Proxy object connected
08-16 17:58:41.576   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:41.576  3887  3897 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:58:41.576   873   873 D BluetoothA2dp: Proxy object connected
,08-16 17:58:41.577  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:58:41.577  1361  1361 D PanProfile: Bluetooth service connected
,08-16 17:58:41.577  4151  4151 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 17:58:41.578  1925  2220 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:41.579  1361  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:58:41.580  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:41.583  4151  4151 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:41.584  4151  4151 D ObexServerSockets: Succeed to create listening sockets 
08-16 17:58:41.584  3887  3899 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:58:41.584  4151  4151 D ObexServerSockets0: startAccept()
,08-16 17:58:41.585  4151  4151 D ObexServerSockets0: prepareForNewConnect()
08-16 17:58:41.585  3887  3897 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:41.587  3887  3899 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:58:41.588  4151  4151 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 17:58:41.588  4151  4151 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 17:58:41.590  4151  4189 D ObexServerSockets0: Accepting socket connection...
08-16 17:58:41.590  1361  2025 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:58:41.591  4151  4190 D ObexServerSockets0: Accepting socket connection...
,08-16 17:58:41.592  3887  3897 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:58:41.592  1361  1361 D BluetoothMap: Proxy object connected
08-16 17:58:41.592  1361  1361 D MapProfile: Bluetooth service connected
08-16 17:58:41.593  1361  1361 D BluetoothMap: getConnectedDevices()
,08-16 17:58:41.594   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:58:41.596  3887  3887 D BluetoothA2dp: Proxy object connected
,08-16 17:58:41.597   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 17:58:41.598  4151  4151 D BluetoothMapService: onReceive
08-16 17:58:41.598  4151  4151 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:41.598  4151  4151 D BluetoothMapService: STATE_ON
08-16 17:58:41.599  3887  3887 D BluetoothInputDevice: Proxy object connected
08-16 17:58:41.599  3887  3887 D HidProfile: Bluetooth service connected
08-16 17:58:41.600  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:41.602  3887  3887 D BluetoothMap: Proxy object connected
,08-16 17:58:41.603  3887  3887 D MapProfile: Bluetooth service connected
,08-16 17:58:41.603  3887  3887 D BluetoothMap: getConnectedDevices()
,08-16 17:58:41.608  3887  3887 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:41.615  1506  1506 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:41.615  3887  3887 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:41.628  3887  3887 D BluetoothPbap: Proxy object connected
,08-16 17:58:41.628  4151  4151 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:58:41.628  1361  1361 D BluetoothPbap: Proxy object connected
08-16 17:58:41.628  4151  4151 D ObexServerSockets0: prepareForNewConnect()
08-16 17:58:41.628  1361  1361 D PbapServerProfile: Bluetooth service connected
08-16 17:58:41.629  3887  3887 D PbapServerProfile: Bluetooth service connected
,08-16 17:58:41.635  4151  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:41.650  4151  4200 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:41.652  4151  4200 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:41.664   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.664   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:58:41.665  1925  2241 D BluetoothHeadset: Proxy object connected
08-16 17:58:41.665   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.665  1361  1380 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.665  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:41.666  3887  3897 D BluetoothHeadset: Proxy object connected
08-16 17:58:41.666  3887  3887 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:41.679  1925  1945 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.679  1361  4137 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.680  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:41.685  3887  4188 D BluetoothHeadset: Proxy object connected
,08-16 17:58:41.685  3887  3887 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:41.695   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:42.060  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:42.067  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:42.070  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:42.071  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1bf43e added. We now have 8 listener(s)
08-16 17:58:42.071  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:42.077   873  1953 D WifiService: setWifiEnabled: false pid=3815, uid=10000
08-16 17:58:42.077   873  1953 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:58:42.089  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:58:42.090   873  1379 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,08-16 17:58:42.091   873  1379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:58:42.105   873  1307 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:42.120  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:42.125   873  1307 D WifiConfigStore: loaded 0 passpoint configs
,08-16 17:58:42.126   873  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 17:58:42.127   873  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 17:58:42.128   873  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 17:58:42.128   873  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 17:58:42.128   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 17:58:42.128   873  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-16 17:58:42.131  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:42.144   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 17:58:42.144   873  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.22 rxSuccessRate=0.29 delta 1000 -> 1000
,08-16 17:58:42.145   873  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:58:42.145   371   871 D CommandListener: Setting iface cfg
08-16 17:58:42.146   873  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-16 17:58:42.146   873  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:58:42.157   873  1307 E native  : do suspend true
,08-16 17:58:42.157   873  1306 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:58:42.163   873  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:58:42.170   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-16 17:58:42.171   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:42.190   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:58:42.233   873  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:58:42.234  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:58:42.668  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:58:42.705  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:58:42.707  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 17:58:42.710   873  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:58:42.725   873  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 17:58:42.726   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:42.726   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:58:42.752   873  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:42.767   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:42.769   873  1307 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:58:42.777   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:58:42.812   873  4208 D DhcpClient: Receive thread started
,08-16 17:58:42.897   873  1307 E native  : do suspend false
,08-16 17:58:42.918   873  1873 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:58:42.931   873  4208 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 17:58:42.932   873  1873 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 17:58:42.935   873  1873 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:58:42.948   873  4208 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:58:42.949   873  1873 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:58:42.954   371   871 D CommandListener: Setting iface cfg
,08-16 17:58:42.965   873  1873 D DhcpClient: Scheduling renewal in 86399s
,08-16 17:58:42.970   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:58:42.973   873  1307 E native  : do suspend true
,08-16 17:58:42.997   873  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 17:58:43.000   873  1307 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:58:43.002   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 17:58:43.005   873  1309 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 17:58:43.014   873  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:58:43.085   873  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:58:43.085   873  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 17:58:43.088   873  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 17:58:43.089   873  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 17:58:43.090   873  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 17:58:43.100   873  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 17:58:43.107   873  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 17:58:43.108   873  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 17:58:43.108   873  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 17:58:43.108   873  1309 D ConnectivityService:    accepting network in place of null
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:43.108  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:43.109   873  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 17:58:43.110   873  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:58:43.110   873  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 17:58:43.111  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:43.114  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}],
08-16 17:58:43.115  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:58:43.115   873  4207 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:58:43.117  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@670f683 Bundle[{}]
,08-16 17:58:43.117  3815  3863 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:58:43.118  3815  3863 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 17:58:43.118  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:58:43.119  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:58:43.119  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 17:58:43.120  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:58:43.124  3815  3863 I System.out: Running OutgoingSocketThread
,08-16 17:58:43.125  3815  4213 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-16 17:58:43.125  3815  4213 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42722
08-16 17:58:43.126  3815  4213 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:58:43.141   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:43.169   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:58:43.175   873  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 17:58:43.175   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:43.177   873  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 17:58:43.179   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 17:58:43.182   873  4206 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:814::200e
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:43.205  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:43.206  1704  1704 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 17:58:43.207  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:43.213  1704  1704 D SystemUpdateService: onCreate
,08-16 17:58:43.217  1704  1704 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:58:43.233  1704  4218 I SystemUpdateService: active receiver: enabled
,08-16 17:58:43.237  1704  1704 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:58:43.242  1704  2434 I iu.UploadsManager: num queued entries: 0
08-16 17:58:43.243  1704  2434 I iu.UploadsManager: num updated entries: 0
,08-16 17:58:43.243  1704  2434 I iu.SyncManager: NEXT; no task
,08-16 17:58:43.247  1704  4218 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:58:43.248  1704  1704 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:58:43.249  1704  1704 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:58:43.251  3940  3940 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:43.255  1704  4221 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 17:58:43.255  1704  4221 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 17:58:43.256  3940  3940 D SprintDMHelper: simOperator: 
08-16 17:58:43.256  3940  3940 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:58:43.260   873  4206 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:58:43 GMT], X-Android-Received-Millis=[1471363123259], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471363123229]}
,08-16 17:58:43.262   873  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 17:58:43.263   873  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-16 17:58:43.263   873  1309 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 17:58:43.264   873  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:58:43.271  1704  4221 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:58:43.299  1704  4218 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 17:58:43.299  1704  4218 I SystemUpdateService: now status is 0 (complete)
08-16 17:58:43.299  1704  4218 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:58:43.300  1704  4218 I SystemUpdateService: file has been verified
,08-16 17:58:43.300  1704  4218 I SystemUpdateService: OTA package size = 12249756
,08-16 17:58:43.313  1704  4218 I SystemUpdateService: showing system update notification
,08-16 17:58:43.334  1704  1704 D SystemUpdateService: onDestroy
,08-16 17:58:43.346  1506  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 17:58:43.346  1506  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 17:58:43.346  1506  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:58:43.346  1506  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:58:43.365  1704  4221 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-16 17:58:43.397  2390  4224 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:58:44.126  3815  3863 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-16 17:58:44.127  3815  3863 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-16 17:58:44.136  3815  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-16 17:58:44.139  3815  3863 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 17:58:44.139  3815  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-16 17:58:44.143  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:44.144  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546129f added. We now have 2 listener(s)
,08-16 17:58:44.146  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:58:44.146  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.146  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:44.146  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:44.146  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c8fec added. We now have 9 listener(s)
08-16 17:58:44.146  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:44.147  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:44.152  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:44.163  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:44.166  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:44.166  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:44.167  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.167  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edf164a added. We now have 3 listener(s)
,08-16 17:58:44.169  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:44.169  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:44.169  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.169  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:44.169  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50339bb added. We now have 10 listener(s)
08-16 17:58:44.169  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:44.170  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:44.170  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:44.170  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:44.170  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:44.170  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.170  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.170  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.170  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@546129f removed from the list
08-16 17:58:44.170  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.170  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c8fec removed from the list
08-16 17:58:44.172  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.172  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:58:44.172  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.173  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.173  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.174  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.174  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 17:58:44.174  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.175  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7c8fec not in the list
,08-16 17:58:44.175  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.175  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.177   873  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-16 17:58:44.187  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:44.188  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:44.189  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.189  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.189  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50339bb removed from the list
08-16 17:58:44.190  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:44.190  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:44.190  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.190  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.191  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edf164a removed from the list
,08-16 17:58:44.193  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.193  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f98bed8 added. We now have 2 listener(s)
,08-16 17:58:44.199  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:44.199  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:44.199  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.200  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.200  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f4231 added. We now have 9 listener(s)
08-16 17:58:44.200  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.201  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:44.204  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:44.212  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:44.215  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.215  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:44.215  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.216  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a1b697 added. We now have 3 listener(s)
,08-16 17:58:44.217  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:44.218  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.218  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:44.218  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.218  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f46f084 added. We now have 10 listener(s)
08-16 17:58:44.218  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:44.218  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:44.218  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:58:44.218  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.218  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:44.219  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.219  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:44.222  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:58:44.223  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:44.225  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:44.227  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:44.228  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:58:44.228  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:44.232  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:44.233  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:44.233  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:44.233  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:44.237  4151  4161 D BtGatt.GattService: registerClient() - UUID=ed415c59-660f-4d41-b897-eac5564c311e
,08-16 17:58:44.238  4151  4167 D BtGatt.GattService: onClientRegistered() - UUID=ed415c59-660f-4d41-b897-eac5564c311e, clientIf=5
,08-16 17:58:44.239  3815  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:58:44.240  4151  4192 D BtGatt.GattService: start scan with filters
,08-16 17:58:44.245  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:44.245  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:44.245  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:58:44.245  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:44.245  4151  4170 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:44.248  4151  4170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f4012e7
,08-16 17:58:44.248  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:44.248  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:44.248  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:44.252  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:44.253  4151  4167 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:58:44.253  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:58:44.254  4151  4170 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:58:44.260  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:44.260  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:44.260  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:58:44.261  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.261  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:44.261  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:58:44.261  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.261  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:44.261  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:44.262  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:44.262  4151  4170 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:44.262  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:44.262  4151  4170 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:58:44.263  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:58:44.263  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:44.265  3815  3863 D BluetoothAdapter: STATE_ON
08-16 17:58:44.266  4151  4180 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:44.268  4151  4162 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:58:44.268  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:44.268  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:44.268  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:58:44.268  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 17:58:44.269  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:44.270  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-16 17:58:44.270  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:44.270  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:58:44.270  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:44.270  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.272  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 17:58:44.272  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:44.273  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:44.275  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 17:58:44.275  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:44.276  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:44.276  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:44.276  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:44.276  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.276  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-16 17:58:44.276  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f98bed8 removed from the list
,08-16 17:58:44.276  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.276  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f4231 removed from the list
08-16 17:58:44.276  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:58:44.276  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.277  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.278  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.278  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:44.279  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.279  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.279  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13f4231 not in the list
08-16 17:58:44.279  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:44.279  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.280  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.280  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.280  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.280  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f46f084 removed from the list
08-16 17:58:44.280  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:44.280  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.280  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.280  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.280  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9a1b697 removed from the list
08-16 17:58:44.281  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.281  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68490f0 added. We now have 2 listener(s)
08-16 17:58:44.282  4151  4167 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:58:44.282  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.283  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:58:44.284  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.284  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.284  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.284  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43b0669 added. We now have 9 listener(s)
08-16 17:58:44.284  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.285  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:44.288  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.291  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:58:44.291  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:44.293  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:44.297  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.298  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:44.298  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.298  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ee18f added. We now have 3 listener(s)
08-16 17:58:44.302  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:58:44.302  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.302  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.302  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.302  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb9cc1c added. We now have 10 listener(s)
08-16 17:58:44.302  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.303  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:44.303  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.303  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:58:44.303  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:44.303  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.304  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:44.304  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:44.304  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:44.304  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:58:44.304  4151  4170 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:44.305  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.308  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 17:58:44.308  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:44.314  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:58:44.314  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:58:44.314  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.315  4151  4170 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:58:44.316  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:58:44.316  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:44.321  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:44.321  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:44.321  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:44.322  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:44.323  4151  4167 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:58:44.323  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.324  4151  4191 D BtGatt.GattService: registerClient() - UUID=b8399db4-a658-4740-b73d-e01fb0676dd0
08-16 17:58:44.325  4151  4167 D BtGatt.GattService: onClientRegistered() - UUID=b8399db4-a658-4740-b73d-e01fb0676dd0, clientIf=5
08-16 17:58:44.326  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:58:44.326  4151  4161 D BtGatt.GattService: start scan with filters
08-16 17:58:44.330  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:44.330  4151  4170 D BtGatt.ScanManager: handling starting scan
08-16 17:58:44.330  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:44.331  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:44.331  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:44.336  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:44.336  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:44.336  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:44.339  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:58:44.339  4151  4167 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:58:44.339  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.340  4151  4170 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:58:44.343  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:44.343  3815  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 17:58:44.344  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:44.344  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:44.344  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:44.345  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:44.345  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.345  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:44.345  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.346  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68490f0 removed from the list
08-16 17:58:44.346  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.346  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43b0669 removed from the list
08-16 17:58:44.346  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:44.346  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.348  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.348  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:58:44.348  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.348  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.349  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:58:44.349  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.349  4151  4170 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:44.350  4151  4170 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:58:44.350  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.351  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@43b0669 not in the list
08-16 17:58:44.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:44.351  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:44.351  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:44.353  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:44.355  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:44.357  3815  3863 D BluetoothAdapter: STATE_ON
08-16 17:58:44.358  4151  4161 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:58:44.359  4151  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:58:44.360  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:44.360  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:44.360  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:44.360  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:44.360  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:58:44.361  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:44.361  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:44.362  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:44.362  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:44.363  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.365  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb9cc1c removed from the list
08-16 17:58:44.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:44.365  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:44.365  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.365  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.366  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.366  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25ee18f removed from the list
08-16 17:58:44.366  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:44.366  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:44.367  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.367  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da58e08 added. We now have 2 listener(s)
08-16 17:58:44.369  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:58:44.369  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.369  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.369  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.369  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f419a1 added. We now have 9 listener(s)
08-16 17:58:44.370  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.370  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:44.371  4151  4167 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:58:44.371  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.379  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:44.381  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:58:44.381  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:44.393  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:44.398  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:44.398  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:44.399  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:44.399  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b477387 added. We now have 3 listener(s)
08-16 17:58:44.400  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:58:44.400  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:58:44.400  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:58:44.401  4151  4170 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:44.401  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:44.401  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:44.401  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.401  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40982b4 added. We now have 10 listener(s)
,08-16 17:58:44.401  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.401  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:58:44.401  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:44.401  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:44.402  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.402  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:44.405  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:44.408  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:58:44.408  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:44.408  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:44.409  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:58:44.409  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.410  4151  4170 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:58:44.412  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:44.412  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:58:44.412  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
08-16 17:58:44.415  4151  4167 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:58:44.416  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 17:58:44.417  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:44.418  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:58:44.418  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:44.419  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:44.423  4151  4161 D BtGatt.GattService: registerClient() - UUID=793639f6-8252-48d4-9b6d-9014b351c8dd
,08-16 17:58:44.423  4151  4167 D BtGatt.GattService: onClientRegistered() - UUID=793639f6-8252-48d4-9b6d-9014b351c8dd, clientIf=5
,08-16 17:58:44.424  3815  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:58:44.424  4151  4191 D BtGatt.GattService: start scan with filters
,08-16 17:58:44.429  4151  4170 D BtGatt.ScanManager: handling starting scan
08-16 17:58:44.429  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:44.429  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:44.429  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:58:44.429  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:44.432  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:44.432  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:44.432  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:44.435  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:44.439  4151  4167 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:58:44.439  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.439  4151  4170 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:58:44.443  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:44.444  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:44.444  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:44.444  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:44.444  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:44.444  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:44.445  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.445  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da58e08 removed from the list
08-16 17:58:44.445  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.445  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f419a1 removed from the list
,08-16 17:58:44.445  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:44.445  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.445  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:58:44.445  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:58:44.446  4151  4170 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:58:44.446  4151  4170 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:58:44.446  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:44.446  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 17:58:44.446  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.446  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:44.447  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.448  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:44.448  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.448  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f419a1 not in the list
,08-16 17:58:44.448  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:58:44.448  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:44.448  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:44.449  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:58:44.449  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:44.451  3815  3863 D BluetoothAdapter: STATE_ON
,08-16 17:58:44.451  4151  4161 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:44.452  4151  4180 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:58:44.452  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:44.452  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:44.452  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:58:44.452  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:44.452  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:44.453  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:44.453  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:44.453  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:44.453  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:44.453  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.454  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:44.454  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.454  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 17:58:44.454  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40982b4 removed from the list
08-16 17:58:44.454  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 17:58:44.454  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:44.454  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.454  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.454  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:44.454  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b477387 removed from the list
08-16 17:58:44.454  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:44.454  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:44.455  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:44.455  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b161620 added. We now have 2 listener(s)
08-16 17:58:44.456  4151  4167 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:58:44.456  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.456  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:44.456  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.456  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:44.456  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.456  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe55bd9 added. We now have 9 listener(s)
,08-16 17:58:44.456  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.456  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:44.458  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:44.461  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:58:44.461  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:44.461  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:44.463  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:44.463  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:44.464  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.465  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:44.466  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:44.466  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3814c7f added. We now have 3 listener(s)
08-16 17:58:44.467  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:58:44.467  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:44.467  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:44.467  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:44.467  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c96744c added. We now have 10 listener(s)
08-16 17:58:44.467  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:44.468  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:44.468  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:44.468  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:44.468  4151  4167 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:58:44.468  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.468  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:44.468  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.468  4151  4170 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:44.468  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:44.468  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:44.468  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b161620 removed from the list,
08-16 17:58:44.468  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.468  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe55bd9 removed from the list
08-16 17:58:44.469  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:44.469  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.469  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.469  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.470  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.470  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.470  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:44.470  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe55bd9 not in the list
,08-16 17:58:44.470  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.470  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:44.471  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:44.471  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:44.471  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:44.471  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c96744c removed from the list
08-16 17:58:44.471  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:44.471  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:44.471  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:44.471  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:44.471  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3814c7f removed from the list
,08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:58:44.472  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:44.474  4151  4167 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:58:44.474  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.475  4151  4170 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:58:44.477  3815  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-16 17:58:44.477  3815  4230 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-16 17:58:44.478  3815  4230 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:58:44.480  4151  4167 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:58:44.480  4151  4167 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:58:44.482  3815  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
08-16 17:58:44.482  3815  4231 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-16 17:58:44.482  3815  4231 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-16 17:58:44.483  3815  3863 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-16 17:58:44.483  3815  3863 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 17:58:44.483  3815  3863 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:58:44.483  3815  3863 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:58:44.484  3815  3863 D com.test.thalitest.ThaliTestRunner: Total duration: 22793 ms
08-16 17:58:44.485  3815  3863 I jxcore-log: Total number of executed tests:  80
08-16 17:58:44.485  3815  3863 I jxcore-log: 
08-16 17:58:44.485  3815  3863 I jxcore-log: Number of passed tests:  80
08-16 17:58:44.485  3815  3863 I jxcore-log: 
,08-16 17:58:44.485  3815  3863 I jxcore-log: Number of failed tests:  0
08-16 17:58:44.485  3815  3863 I jxcore-log: 
08-16 17:58:44.486  3815  3863 I jxcore-log: Number of ignored tests:  0
08-16 17:58:44.486  3815  3863 I jxcore-log: 
08-16 17:58:44.486  3815  3863 I jxcore-log: Total duration:  22793
08-16 17:58:44.486  3815  3863 I jxcore-log: 
08-16 17:58:44.486  3815  3863 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:58:44.486  3815  3863 I jxcore-log: 
,08-16 17:58:44.489  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.489  3815  3863 I jxcore-log: 
08-16 17:58:44.491  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.491  3815  3863 I jxcore-log: 
08-16 17:58:44.492  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.492  3815  3863 I jxcore-log: 
08-16 17:58:44.493  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.493  3815  3863 I jxcore-log: 
08-16 17:58:44.494  3815  3815 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:58:44.494  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.494  3815  3863 I jxcore-log: 
08-16 17:58:44.495  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.495  3815  3863 I jxcore-log: 
08-16 17:58:44.497  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.497  3815  3863 I jxcore-log: 
08-16 17:58:44.499  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.499  3815  3863 I jxcore-log: 
08-16 17:58:44.500  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.500  3815  3863 I jxcore-log: 
08-16 17:58:44.500  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.500  3815  3863 I jxcore-log: 
08-16 17:58:44.501  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.501  3815  3863 I jxcore-log: 
08-16 17:58:44.502  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:44.502  3815  3863 I jxcore-log: 
08-16 17:58:44.503  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.503  3815  3863 I jxcore-log: 
08-16 17:58:44.504  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.504  3815  3863 I jxcore-log: 
,08-16 17:58:44.504  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.504  3815  3863 I jxcore-log: 
08-16 17:58:44.505  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.505  3815  3863 I jxcore-log: 
08-16 17:58:44.506  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.506  3815  3863 I jxcore-log: 
08-16 17:58:44.506  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.506  3815  3863 I jxcore-log: 
08-16 17:58:44.507  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.507  3815  3863 I jxcore-log: 
08-16 17:58:44.508  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.508  3815  3863 I jxcore-log: 
08-16 17:58:44.508  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.508  3815  3863 I jxcore-log: 
,08-16 17:58:44.509  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.509  3815  3863 I jxcore-log: 
,08-16 17:58:44.510  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.510  3815  3863 I jxcore-log: 
,08-16 17:58:44.511  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:44.511  3815  3863 I jxcore-log: 
,08-16 17:58:44.511  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.511  3815  3863 I jxcore-log: 
,08-16 17:58:44.512  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:44.512  3815  3863 I jxcore-log: 
,08-16 17:58:44.513  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.513  3815  3863 I jxcore-log: 
,08-16 17:58:44.513  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.513  3815  3863 I jxcore-log: 
,08-16 17:58:44.514  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.514  3815  3863 I jxcore-log: 
,08-16 17:58:44.515  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.515  3815  3863 I jxcore-log: 
,08-16 17:58:44.515  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.515  3815  3863 I jxcore-log: 
,08-16 17:58:44.516  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:44.516  3815  3863 I jxcore-log: 
,08-16 17:58:44.774  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:44.776  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:44.776  3815  3863 I jxcore-log: 
,08-16 17:58:44.866  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:44.870  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:44.870  3815  3863 I jxcore-log: 
,08-16 17:58:44.955  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:44.958  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:44.958  3815  3863 I jxcore-log: 
,08-16 17:58:45.205  4232  4232 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 17:58:45.210  4232  4232 D AndroidRuntime: CheckJNI is OFF
,08-16 17:58:45.253  4232  4232 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 17:58:45.301  4232  4232 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 17:58:45.324  4232  4232 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:58:45.333   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 17:58:45.334   873   886 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 17:58:45.463   873   883 I WindowState: WIN DEATH: Window{bb8f6a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:58:45.463   873  1308 D WifiService: Client connection lost with reason: 4
,08-16 17:58:45.464   873  1383 D GraphicsStats: Buffer count: 2
,08-16 17:58:45.475   873   896 W PackageSettings: Skipping PackageSetting{6fa538 com.example.hello/10273} due to missing metadata
,08-16 17:58:45.511   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 17:58:45.511   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-16 17:58:45.513   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 17:58:45.513   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 17:58:45.513   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.513   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.513   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:58:45.513   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 17:58:45.514   873   886 I ActivityManager:   Force finishing activity ActivityRecord{87fbef6 u0 com.test.thalitest/.MainActivity t2}
,08-16 17:58:45.518   873   896 I art     : Starting a blocking GC Explicit
,08-16 17:58:45.525   873  1383 W ActivityManager: Spurious death for ProcessRecord{3756835 0:com.test.thalitest/u0a0}, curProc for 3815: null
,08-16 17:58:45.557   873   896 I art     : Explicit concurrent mark sweep GC freed 14891(1016KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 653us total 38.532ms
,08-16 17:58:45.581   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 17:58:45.585  4232  4232 I art     : System.exit called, status: 0
,08-16 17:58:45.585  4232  4232 I AndroidRuntime: VM exiting with result code 0.
,08-16 17:58:45.589   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 17:58:45.621   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-16 17:58:45.628  4151  4151 D BluetoothMapAppObserver: onReceive
08-16 17:58:45.628  4151  4151 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 17:58:45.631  2006  2269 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:58:45.644   873  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:58:45.634  1856  1856 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 17:58:45.653  3623  3623 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 17:58:45.655  1856  4246 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 17:58:45.657  1856  4246 I Decoder : createOrResetDecoder
,08-16 17:58:45.676  1925  1925 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 17:58:45.686   873  1701 I ActivityManager: Start proc 4247:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 17:58:45.709  1506  1506 I ConfigService: onCreate
,08-16 17:58:45.718  1506  4259 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 17:58:45.718  1506  4259 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 17:58:45.718  1506  4259 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-16 17:58:45.721  1506  4259 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 17:58:45.737  1856  4246 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 17:58:45.737   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:58:45.757   873  2973 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
,08-16 17:58:45.759  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-16 17:58:45.767  4247  4247 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 17:58:45.771  1938  2035 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 17:58:45.773   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 17:58:45.773   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 17:58:45.773   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 17:58:45.773   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 17:58:45.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 17:58:45.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 17:58:45.773   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 17:58:45.773   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.773   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.773   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:45.779   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 17:58:45.779   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 17:58:45.779   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:58:45.779   873   886 E DropBoxManagerService: 	... 13 more
,08-16 17:58:45.790   873  1383 I ActivityManager: Start proc 4261:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
,08-16 17:58:45.791  1938  2035 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 17:58:45.791  1938  2035 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-16 17:58:45.791  1938  2035 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.791  1938  2035 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:45.793   873   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:58:45.794   873  4266 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:58:45.794   873  4266 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:58:45.794   873  4266 E DropBoxManagerService: 	... 5 more
,08-16 17:58:45.819  1938  2035 I Process : Sending signal. PID: 1938 SIG: 9
,08-16 17:58:45.822  1856  4246 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 17:58:45.824  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 17:58:45.824  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 17:58:45.826  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 17:58:45.826  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 17:58:45.828  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-16 17:58:45.828  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-16 17:58:45.829  1856  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-16 17:58:45.830  1856  4246 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 17:58:45.830  1856  4246 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-16 17:58:45.830  1856  4246 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 17:58:45.830  1856  4246 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 17:58:45.830  1856  4246 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 17:58:45.885  4247  4247 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 17:58:45.889   873  2973 D GraphicsStats: Buffer count: 1
08-16 17:58:45.891   873  1295 W InputDispatcher: channel '972d75c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-16 17:58:45.891   873  1700 I WindowState: WIN DEATH: Window{972d75c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-16 17:58:45.891   873  1295 E InputDispatcher: channel '972d75c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-16 17:58:45.891   873  1700 W InputDispatcher: Attempted to unregister already unregistered input channel '972d75c com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,08-16 17:58:45.907   873  1944 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1938) has died
,08-16 17:58:45.907   873  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 17:58:45.910   873  1944 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 17:58:45.929   873   886 I ActivityManager: Start proc 4281:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:58:45.931   873  1307 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-16 17:58:45.947   873  1699 I ActivityManager: Start proc 4293:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 17:58:45.952  4247  4296 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 17:58:45.956  4247  4276 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.956  4247  4276 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
,08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.956  4247  4276 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:45.973  1704  4280 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 17:58:45.975  1704  4280 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 17:58:45.978  4281  4281 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:45.978  4281  4281 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:58:45.978  4281  4281 D AndroidRuntime: Shutting down VM
,08-16 17:58:45.987  4281  4281 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:58:45.987  4281  4281 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4281
08-16 17:58:45.987  4281  4281 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:58:45.987  4281  4281 E AndroidRuntime: 	... 10 more
,08-16 17:58:45.989   873  1383 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:58:45.989  4281  4281 I Process : Sending signal. PID: 4281 SIG: 9
08-16 17:58:45.990   873  4306 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:58:45.990   873  4306 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:58:45.990   873  4306 E DropBoxManagerService: 	... 5 more
08-16 17:58:45.999  1704  4280 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 17:58:45.999  1704  4280 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 17:58:46.005  4293  4293 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 17:58:46.020  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 17:58:46.020  1506  1506 D AndroidRuntime: Shutting down VM
08-16 17:58:46.021  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main,
08-16 17:58:46.021  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
08-16 17:58:46.021  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 17:58:46.021  1506  1506 E AndroidRuntime: 	... 8 more
,08-16 17:58:46.023  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
08-16 17:58:46.023   873   886 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2600)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:58:46.023   873  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:58:46.023   873  4310 E DropBoxManagerService: 	... 5 more
08-16 17:58:46.024   873   886 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
08-16 17:58:46.024   873   886 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:58:46.024   873   886 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 17:58:46.046  4247  4276 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 17:58:46.050  4247  4296 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:46.050  4247  4296 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:46.051  4247  4296 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 17:58:46.051  4247  4296 E AndroidRuntime: Process: android.process.acore, PID: 4247
08-16 17:58:46.051  4247  4296 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:58:46.051  4247  4296 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:58:46.053  4247  4276 I Process : Sending signal. PID: 4247 SIG: 9
,08-16 17:58:46.063   873  1308 D WifiService: Client connection lost with reason: 4
,08-16 17:58:46.082   873   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
,08-16 17:58:46.082   873   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-16 17:58:46.082   873   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
,08-16 17:58:46.082   873   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,08-16 17:58:46.094   873   886 I ActivityManager: Start proc 4313:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,08-16 17:58:46.094   873  1383 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4281) has died
,08-16 17:58:46.096   873  1383 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
