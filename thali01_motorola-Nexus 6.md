#### Test 808075736be4f0c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 13:11:00.557   875  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 13:11:02.132  3792  3792 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 13:11:02.137  3792  3792 D AndroidRuntime: CheckJNI is OFF
08-17 13:11:02.181  3792  3792 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 13:11:02.232  3792  3792 I Radio-JNI: register_android_hardware_Radio DONE
08-17 13:11:02.254  3792  3792 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 13:11:02.258   875  1928 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 13:11:02.295  1989  2414 W SearchService: Abort, client detached.
08-17 13:11:02.302  1989  2344 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7ad31e1
08-17 13:11:02.302  1989  2350 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 13:11:02.302  1989  1989 I HotwordDetector: Closing mic
08-17 13:11:02.314  3792  3792 D AndroidRuntime: Shutting down VM
08-17 13:11:02.326   875   885 I ActivityManager: Start proc 3801:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 13:11:02.357   377  2352 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 13:11:02.358   377  2352 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 13:11:02.364   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 13:11:02.366  1989  2349 I MicroRecognitionRnrImpl: Detection finished
08-17 13:11:02.367  1989  2347 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 13:11:02.409  3801  3801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 13:11:02.443  3801  3801 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 13:11:02.452  3801  3801 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3676-3680)
08-17 13:11:02.452  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 13:11:02.472  3801  3801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {42f8556}
08-17 13:11:02.472  3801  3801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 13:11:02.472  3801  3801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 13:11:02.482  3801  3801 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 13:11:02.483  3801  3801 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 13:11:02.505  3801  3801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 13:11:02.520  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 13:11:02.520  3801  3801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 13:11:02.520  3801  3801 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 13:11:02.520  3801  3801 I Adreno  : Build Date                       : 10/20/15
08-17 13:11:02.520  3801  3801 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 13:11:02.520  3801  3801 I Adreno  : Local Branch                     : M14
08-17 13:11:02.520  3801  3801 I Adreno  : Remote Branch                    : 
08-17 13:11:02.520  3801  3801 I Adreno  : Remote Branch                    : 
08-17 13:11:02.520  3801  3801 I Adreno  : Reconstruct Branch               : 
,08-17 13:11:02.601   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80dcfa6:true
,08-17 13:11:02.626  3801  3801 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 13:11:02.637  3801  3801 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 13:11:02.696  3801  3839 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 13:11:02.707  3801  3826 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 13:11:02.748  3801  3839 I OpenGLRenderer: Initialized EGL, version 1.4,
,08-17 13:11:02.822   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +508ms
,08-17 13:11:02.833  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 13:11:02.901  3801  3801 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3801
,08-17 13:11:03.025  3801  3801 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 13:11:03.151   875  2012 I ActivityManager: Killing 3240:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 13:11:03.208   875  2012 I ActivityManager: Killing 3153:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 13:11:03.307  3801  3842 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1678837456
,08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 13:11:03.317  3801  3842 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@faee0fa added. We now have 1 listener(s)
,08-17 13:11:03.323  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 13:11:03.323  3801  3842 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:03.325  3801  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:03.326  3801  3842 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 13:11:03.329  3801  3842 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f2d0a1 added. We now have 1 listener(s)
,08-17 13:11:03.329  3801  3842 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:03.336   875  1315 D WifiService: New client listening to asynchronous messages
,08-17 13:11:03.337  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 13:11:03.337  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 13:11:03.337  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 13:11:03.338  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 13:11:03.338  3801  3842 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 13:11:03.342  3801  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:03.346  3801  3842 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-17 13:11:03.351  3801  3842 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:03.351  3801  3842 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:03.351  3801  3842 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 13:11:03.351  3801  3842 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:03.352  3801  3842 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 13:11:03.468  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:03.472  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:03.473  3801  3801 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 13:11:04.520  3801  3851 W jxcore-log: Initializing JXcore engine
,08-17 13:11:04.520  3801  3851 W jxcore-log: JXcore engine is ready
,08-17 13:11:04.594  3851  3851 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8985 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 13:11:04.594  3851  3851 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11613]" dev="sockfs" ino=11613 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 13:11:04.597  3851  3851 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 13:11:04.597  3851  3851 W Thread-321: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26668]" dev="sockfs" ino=26668 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 13:11:04.621  3801  3851 W jxcore-log: Starting JXcore engine
,08-17 13:11:04.757  3801  3851 W jxcore-log: Platform android
08-17 13:11:04.757  3801  3851 W jxcore-log: 
,08-17 13:11:04.757  3801  3851 W jxcore-log: Process ARCH arm
08-17 13:11:04.757  3801  3851 W jxcore-log: 
,08-17 13:11:05.001  3801  3851 I jxcore-log: JXcore Cordova bridge is ready!
08-17 13:11:05.001  3801  3851 I jxcore-log: 
,08-17 13:11:05.002  3801  3851 W jxcore-log: JXcore engine is started
,08-17 13:11:05.015  3801  3842 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 13:11:05.020  3801  3801 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 13:11:06.520  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:06.526  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:06.573  1528  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 13:11:06.573  1528  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 13:11:06.573  1528  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 13:11:06.573  1528  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 13:11:06.602  3557  3854 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 13:11:06.602  3557  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jdm.a(PG:82)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jcs.o(PG:406)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jcs.i(PG:143)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at blb.a(PG:3937)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at czp.a(PG:18188)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at czp.a(PG:9081)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at czq.run(PG:1686)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 13:11:06.602  3557  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jdm.a(PG:77)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	... 12 more
08-17 13:11:06.602  3557  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at fal.a(PG:38)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-17 13:11:06.602  3557  3854 E HttpOperation: 	... 14 more
,08-17 13:11:06.682  1528  2316 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 13:11:06.683  1528  2316 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 13:11:06.683  1528  2316 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 13:11:06.683  1528  2316 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 13:11:06.720  3557  3854 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 13:11:06.720  3557  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jdm.a(PG:82)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jcs.o(PG:406)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jcn.a(PG:1379)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jcs.i(PG:143)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at hec.a(PG:42)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at hee.a(PG:102)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at czr.a(PG:65)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at kka.a(PG:108)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at czp.a(PG:19176)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at czp.a(PG:9081)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at czq.run(PG:1686)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 13:11:06.720  3557  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jdj.a(PG:4091)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jdj.a(PG:1125)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jdm.a(PG:77)
,08-17 13:11:06.720  3557  3854 E HttpOperation: 	... 15 more
08-17 13:11:06.720  3557  3854 E HttpOperation: Caused by: faj: BadAuthentication
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at fal.a(PG:38)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	at jdj.a(PG:4089)
08-17 13:11:06.720  3557  3854 E HttpOperation: 	... 17 more
,08-17 13:11:06.720  3557  3854 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 13:11:06.720  3557  3854 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at hec.a(PG:42)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at hee.a(PG:102)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at czr.a(PG:65)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at kka.a(PG:108)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	... 15 more
08-17 13:11:06.720  3557  3854 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at fal.a(PG:38)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 13:11:06.720  3557  3854 E ExperimentLoader: 	... 17 more
,08-17 13:11:06.824   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 127479, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 13:11:15.165  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 13:11:15.165  3801  3851 I jxcore-log: 
,08-17 13:11:15.168  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 13:11:15.168  3801  3851 I jxcore-log: 
,08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.179  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:15.185  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.187  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 13:11:15.187  3801  3851 I jxcore-log: 
,08-17 13:11:15.189  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 13:11:15.189  3801  3851 I jxcore-log: 
,08-17 13:11:15.528  3801  3851 D ExecuteNativeTests: Running unit tests
,08-17 13:11:15.586  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:15.587  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 added. We now have 2 listener(s)
,08-17 13:11:15.588  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:15.588  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:15.588  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:15.588  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:15.588  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 added. We now have 2 listener(s)
,08-17 13:11:15.588  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:15.589  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:15.602  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.614  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:15.620  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.620  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:15.627  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:15.628  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 13:11:15.629  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 13:11:15.629  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 13:11:15.634  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:15.635  3801  3851 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 13:11:15.639  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 13:11:15.641  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 13:11:15.641  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:15.641  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:15.644  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.646  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.646  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.646  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.646  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.646  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:15.646  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:15.647  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 removed from the list
08-17 13:11:15.647  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.647  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 removed from the list
08-17 13:11:15.647  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.647  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.648  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.648  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.649  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.649  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.649  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.649  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.651  3801  3851 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 13:11:15.651  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.651  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.652  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.652  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.652  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.652  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.652  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.652  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.652  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.652  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.652  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.652  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.652  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.652  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.653  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.653  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.653  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.654  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 13:11:15.659  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 13:11:15.660  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 13:11:15.661  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 13:11:15.661  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.661  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.661  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.661  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:15.661  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.662  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.662  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.662  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.662  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.662  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.662  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.662  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.662  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.662  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.664  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.664  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.664  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.664  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.665  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 13:11:15.667  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.673  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:15.675  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.675  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:15.675  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:15.675  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:15.675  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:15.676  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:15.676  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:15.677  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:15.679  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 13:11:15.679  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 13:11:15.679  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:15.684  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:15.685  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 13:11:15.686  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:15.689  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 13:11:15.694  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-17 13:11:15.694  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:15.694  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:15.696  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:15.697  3801  3851 D BluetoothAdapter: STATE_ON
,08-17 13:11:15.703  2708  2900 D BtGatt.GattService: registerClient() - UUID=ab81109a-61b7-424d-b558-fd6b7477e751
,08-17 13:11:15.704  2708  2758 D BtGatt.GattService: onClientRegistered() - UUID=ab81109a-61b7-424d-b558-fd6b7477e751, clientIf=5
,08-17 13:11:15.705  3801  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 13:11:15.706  2708  2899 D BtGatt.GattService: start scan with filters
,08-17 13:11:15.710  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:15.710  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:15.710  2708  2762 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:15.711  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:15.711  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:15.714  2708  2762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:15.714  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:15.714  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:15.715  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:15.717  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:15.721  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:15.722  2708  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 13:11:15.722  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.723  2708  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 13:11:15.724  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:15.724  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:15.724  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.724  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 13:11:15.724  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.725  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-17 13:11:15.725  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 13:11:15.725  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 13:11:15.725  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 13:11:15.725  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:15.726  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-17 13:11:15.726  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:15.727  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:15.728  2708  2891 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:15.729  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 13:11:15.729  2708  2900 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 13:11:15.729  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.730  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 13:11:15.730  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 13:11:15.730  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 13:11:15.730  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:15.730  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
,08-17 13:11:15.730  2708  2762 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:15.730  2708  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-17 13:11:15.732  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:15.733  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 13:11:15.733  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-17 13:11:15.733  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:15.734  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:15.737  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:15.737  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:15.737  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:15.738  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:15.738  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.738  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-17 13:11:15.738  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.739  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.739  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.739  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.739  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.740  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 13:11:15.741  2708  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 13:11:15.741  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.743  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:15.748  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 13:11:15.748  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.748  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:15.751  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.751  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:15.751  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:15.751  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 13:11:15.751  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:15.751  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:15.751  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:15.754  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:15.755  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 13:11:15.756  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 13:11:15.756  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 13:11:15.758  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 13:11:15.758  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.758  2708  2762 D BtGatt.ScanManager: stopping BLe Batch
08-17 13:11:15.760  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 13:11:15.761  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 13:11:15.761  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 13:11:15.765  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:15.765  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-17 13:11:15.765  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 13:11:15.765  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 13:11:15.765  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.766  2708  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 13:11:15.766  3801  3851 D BluetoothAdapter: STATE_ON
,08-17 13:11:15.768  2708  2899 D BtGatt.GattService: registerClient() - UUID=f060a98b-97d0-4358-ac23-7ca79f35f14b
08-17 13:11:15.768  2708  2758 D BtGatt.GattService: onClientRegistered() - UUID=f060a98b-97d0-4358-ac23-7ca79f35f14b, clientIf=5
08-17 13:11:15.769  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 13:11:15.769  2708  2722 D BtGatt.GattService: start scan with filters
,08-17 13:11:15.773  2708  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 13:11:15.773  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.773  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 13:11:15.773  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 13:11:15.774  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:15.774  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:15.776  2708  2762 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:15.777  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:15.777  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 13:11:15.778  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:15.779  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:15.782  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:15.785  2708  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 13:11:15.785  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.785  2708  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 13:11:15.785  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.785  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 13:11:15.786  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.786  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 13:11:15.786  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.786  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:15.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:15.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 13:11:15.786  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:15.786  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:15.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:15.786  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-17 13:11:15.787  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:15.788  2708  2891 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:15.788  2708  2899 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 13:11:15.789  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:15.789  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:15.789  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:15.789  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:15.789  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 13:11:15.791  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:15.791  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:15.791  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:15.792  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:15.792  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:15.792  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 13:11:15.792  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.793  2708  2762 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:15.793  2708  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 13:11:15.794  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.794  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.794  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:15.794  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:15.794  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:15.794  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
,08-17 13:11:15.794  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.794  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:15.794  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.794  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.794  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.795  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.795  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.796  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.796  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.796  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.796  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.797  3801  3851 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 13:11:15.799  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.805  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:15.805  2708  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 13:11:15.805  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.807  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.808  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:15.808  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:15.808  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:15.808  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-17 13:11:15.808  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:15.808  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:15.811  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:15.812  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 13:11:15.813  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 13:11:15.814  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 13:11:15.814  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.814  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:15.818  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:15.819  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 13:11:15.819  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:15.822  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 13:11:15.822  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.823  2708  2762 D BtGatt.ScanManager: stopping BLe Batch
08-17 13:11:15.823  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:15.823  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:15.823  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:15.823  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:15.827  2708  2900 D BtGatt.GattService: registerClient() - UUID=71445754-dbbe-4216-be86-1928971223ab
,08-17 13:11:15.827  2708  2758 D BtGatt.GattService: onClientRegistered() - UUID=71445754-dbbe-4216-be86-1928971223ab, clientIf=5
08-17 13:11:15.827  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 13:11:15.828  2708  2722 D BtGatt.GattService: start scan with filters
,08-17 13:11:15.830  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 13:11:15.830  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:15.831  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.831  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:15.831  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:15.831  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:15.831  2708  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 13:11:15.834  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:15.834  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:15.834  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 13:11:15.836  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:15.839  2708  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 13:11:15.839  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.840  3801  3851 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:15.840  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.840  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 13:11:15.840  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.840  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 13:11:15.840  2708  2762 D BtGatt.ScanManager: handling starting scan
08-17 13:11:15.840  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.840  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:15.840  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:15.843  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:15.843  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:15.843  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:15.843  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:15.843  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:15.844  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:15.845  2708  2899 D BtGatt.GattService: stopScan() - queue size =1
08-17 13:11:15.846  2708  2720 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 13:11:15.846  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 13:11:15.846  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:15.847  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:15.847  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:15.847  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:15.849  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:15.849  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 13:11:15.849  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 13:11:15.849  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 13:11:15.850  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:15.851  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:15.851  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:15.851  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.852  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:15.852  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 13:11:15.852  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.852  2708  2758 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 13:11:15.852  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.852  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.852  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.852  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.852  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:15.852  2708  2762 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 13:11:15.852  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
,08-17 13:11:15.852  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.852  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.853  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.853  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.853  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.853  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.855  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.855  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.855  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.855  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.856  3801  3851 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 13:11:15.858  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.858  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.858  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:15.858  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.858  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.858  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.859  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.859  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.859  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.859  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.859  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.859  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.859  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.859  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 13:11:15.859  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.859  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.860  2708  2762 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:15.860  2708  2762 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 13:11:15.860  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.860  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.860  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.861  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.862  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 13:11:15.862  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.862  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.862  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:15.863  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.863  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.863  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.863  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.863  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.863  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.863  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.863  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.863  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.864  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.864  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.866  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.866  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:15.866  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.866  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.867  3801  3851 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 13:11:15.867  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.867  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.867  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.867  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:15.867  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.867  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.867  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.868  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.868  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.868  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.868  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.868  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.868  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.868  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.869  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.869  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:15.869  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.869  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.870  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-17 13:11:15.870  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.870  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.870  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.871  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.871  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.871  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.871  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.871  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.871  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.871  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.871  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.871  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.872  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.872  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.873  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.873  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.873  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.873  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.873  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 13:11:15.875  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 13:11:15.876  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 13:11:15.877  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:15.877  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 13:11:15.877  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 13:11:15.878  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.878  2708  2758 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 13:11:15.878  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.878  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.878  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.878  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.878  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.879  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.879  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.879  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.879  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.879  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.879  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.879  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.879  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.879  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.880  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.880  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.880  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.880  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.883  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 13:11:15.883  3801  3851 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 13:11:15.883  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 13:11:15.886  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 13:11:15.886  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:15.888  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 13:11:15.888  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-17 13:11:15.889  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-17 13:11:15.889  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110],
,08-17 13:11:15.889  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-17 13:11:15.889  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-17 13:11:15.889  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-17 13:11:15.890  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 13:11:15.892  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 13:11:15.893  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 13:11:15.893  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 13:11:15.893  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 13:11:15.893  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-17 13:11:15.894  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-17 13:11:15.894  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-17 13:11:15.894  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-17 13:11:15.894  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 13:11:15.894  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-17 13:11:15.895  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-17 13:11:15.895  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-17 13:11:15.895  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-17 13:11:15.895  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 13:11:15.895  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-17 13:11:15.895  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 13:11:15.896  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-17 13:11:15.896  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-17 13:11:15.896  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-17 13:11:15.896  3801  3851 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 13:11:15.896  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-17 13:11:15.896  2708  2758 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 13:11:15.896  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.897  2708  2762 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:15.900  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 13:11:15.900  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 13:11:15.900  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 13:11:15.901  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-17 13:11:15.901  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-17 13:11:15.901  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 13:11:15.901  3801  3851 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:15.902  3801  3851 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 13:11:15.902  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:15.902  3801  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-17 13:11:15.902  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.902  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.903  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:15.903  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.903  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.903  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 13:11:15.903  2708  2758 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 13:11:15.903  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.904  2708  2762 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 13:11:15.905  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.905  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.905  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.905  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.905  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.905  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.905  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.905  3801  3864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:15.905  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.907  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.907  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.907  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.907  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.908  3801  3851 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-17 13:11:15.908  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.909  3801  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-17 13:11:15.910  3801  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 385)
08-17 13:11:15.910  3801  3864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
,08-17 13:11:15.908  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.911  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.911  2708  2888 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-17 13:11:15.912  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.912  3801  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 385)
08-17 13:11:15.912  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.912  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.912  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.912  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.912  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.912  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.912  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.912  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.913  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.913  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.913  2708  2758 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 13:11:15.913  2708  2758 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:15.914  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.914  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.914  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.914  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.916  3801  3851 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 13:11:15.916  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.916  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.917  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:15.917  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.918  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.918  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.918  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.918  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.918  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.918  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.919  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.919  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.919  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.920  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.922  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:15.922  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.922  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.922  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.922  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 13:11:15.923  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-17 13:11:15.923  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 13:11:15.923  3801  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 13:11:15.923  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 13:11:15.923  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 13:11:15.923  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 13:11:15.923  3801  3851 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 13:11:15.923  3801  3851 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-17 13:11:15.923  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 13:11:15.923  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 13:11:15.923  3801  3851 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-17 13:11:15.923  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.924  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.924  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.924  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:15.924  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.924  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.924  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.924  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.924  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.924  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.924  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.924  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.924  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.924  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.926  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.926  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.927  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.927  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.927  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.927  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.927  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:15.927  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.927  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.927  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.927  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.927  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.927  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.927  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.927  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.928  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.928  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.928  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.928  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.928  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.928  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.928  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.928  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.928  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
,08-17 13:11:15.928  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.928  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.928  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop,
08-17 13:11:15.929  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.929  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.929  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.929  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.931  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.931  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.931  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.931  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.932  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 13:11:15.932  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:15.934  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
08-17 13:11:15.934  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 13:11:15.934  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 13:11:15.935  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-17 13:11:15.935  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 13:11:15.935  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:15.935  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.935  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 13:11:15.935  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 13:11:15.935  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 13:11:15.936  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.936  3801  3851 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 13:11:15.936  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.936  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 13:11:15.936  3801  3801 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 13:11:15.936  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:15.936  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:15.936  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 13:11:15.936  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.936  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.936  3801  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 13:11:15.937  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:15.937  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.937  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-17 13:11:15.937  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:15.938  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:15.937  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.938  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:15.938  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.938  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.938  3801  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 13:11:15.938  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 13:11:15.938  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.938  3801  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 13:11:15.939  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.939  3801  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-17 13:11:15.939  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.939  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.939  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:15.939  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.939  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.939  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.939  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-17 13:11:15.939  3801  3801 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 13:11:15.940  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.940  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 13:11:15.940  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.940  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.942  3801  3851 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 13:11:15.942  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 13:11:15.942  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 13:11:15.942  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-17 13:11:15.942  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:15.942  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.943  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.943  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-17 13:11:15.943  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.943  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.943  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
,08-17 13:11:15.943  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.943  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.943  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.943  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.943  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.943  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.943  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.945  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.945  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.945  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.945  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.949  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.950  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.950  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-17 13:11:15.950  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.950  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.951  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.951  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
,08-17 13:11:15.951  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.951  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.951  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.951  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.951  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.951  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.951  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.953  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.953  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:15.953  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.953  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
08-17 13:11:15.954  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:15.954  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:15.954  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:15.954  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:15.954  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:15.955  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:15.955  3801  3851 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b4c8 not in the list
08-17 13:11:15.955  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.955  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.955  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:15.955  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.955  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.955  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:15.955  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:15.956  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:15.957  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:15.957  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:15.957  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c31961 not in the list
,08-17 13:11:15.959  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 13:11:15.959  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 13:11:15.959  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 13:11:15.959  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 13:11:15.959  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 13:11:15.959  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 13:11:15.962  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 13:11:15.962  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 13:11:15.963  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 13:11:15.963  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 13:11:15.963  3801  3851 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 13:11:15.963  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 13:11:15.963  3801  3851 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 13:11:15.964  3801  3851 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 13:11:15.964  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 13:11:15.964  3801  3851 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 13:11:15.965  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 13:11:15.965  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-17 13:11:15.966  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 13:11:15.966  3801  3851 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 13:11:15.967  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:15.967  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8fab5b added. We now have 2 listener(s)
08-17 13:11:15.967  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:15.971  3801  3851 D BluetoothAdapter: enable(): BT is already enabled..!,
08-17 13:11:15.972   875  1954 D WifiService: setWifiEnabled: true pid=3801, uid=10000
08-17 13:11:15.972   875  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:15.973  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:15.973  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c3dff8 added. We now have 3 listener(s)
08-17 13:11:15.973  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:15.985  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:15.985  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b741cd1 added. We now have 4 listener(s)
08-17 13:11:15.986  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:15.988  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-17 13:11:15.988  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bde2336 added. We now have 5 listener(s)
08-17 13:11:15.988  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:15.992   875  1955 D WifiService: setWifiEnabled: false pid=3801, uid=10000,
08-17 13:11:15.993   875  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:16.002  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.006  2708  2754 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 13:11:16.006  2708  2754 D BluetoothAdapterProperties: Setting state to 13
08-17 13:11:16.006  2708  2754 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 13:11:16.007  2708  2754 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 13:11:16.009  2708  2754 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:16.013  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.014  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:16.015  2708  2758 D BluetoothAdapterProperties: Scan Mode:20
08-17 13:11:16.015  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.015  2708  2754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 13:11:16.015  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.016  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:16.018  2708  2708 D BluetoothMapService: onReceive
,08-17 13:11:16.018  2708  2708 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:16.018  2708  2708 D BluetoothMapService: STATE_TURNING_OFF
,08-17 13:11:16.019  2708  2708 D BluetoothMapService: MAP Service closeService in
08-17 13:11:16.019  2708  2708 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 13:11:16.019  2708  2708 D ObexServerSockets0: shutdown(block = true)
,08-17 13:11:16.020  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 13:11:16.020  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 13:11:16.021  2708  2888 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-17 13:11:16.022  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 13:11:16.022  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.024   875  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 13:11:16.024   875  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 13:11:16.024   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 13:11:16.025   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:16.027  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.028  2708  2902 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-17 13:11:16.027  2708  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 13:11:16.030  2708  2708 I BtOppRfcommListener: stopping Accept Thread
,08-17 13:11:16.030  2708  3450 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 13:11:16.031  2708  3450 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 13:11:16.035  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.035  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:16.036   875  1882 D DhcpClient: Clearing IP address
08-17 13:11:16.036   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-17 13:11:16.036  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:16.036  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.039   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:16.040  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.043  1528  2088 V NativeCrypto: Read error: ssl=0xaa27ca00: I/O error during system call, Connection timed out
08-17 13:11:16.043  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.046  1528  2088 V NativeCrypto: SSL shutdown failed: ssl=0xaa27ca00: I/O error during system call, Broken pipe
08-17 13:11:16.047  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.053   875   888 I ActivityManager: Start proc 3869:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 13:11:16.056   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 13:11:16.056   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 13:11:16.058  2708  2708 D HeadsetService: Received stop request...Stopping profile...
08-17 13:11:16.062   396   396 E Parcel  : Reading a NULL string not supported here.
,08-17 13:11:16.062  1361  2116 D BluetoothHeadset: Proxy object disconnected
,08-17 13:11:16.064   875  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-17 13:11:16.065   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 13:11:16.065  2708  2708 D A2dpService: Received stop request...Stopping profile...
,08-17 13:11:16.067   875  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 13:11:16.070  2708  2894 D A2dpStateMachine: Exit Disconnected: -1
,08-17 13:11:16.072   875   875 D BluetoothHeadset: Proxy object disconnected
,08-17 13:11:16.072   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:16.073   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:16.073  1920  1934 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:16.073  2708  2708 D HidService: Received stop request...Stopping profile...
08-17 13:11:16.073  2708  2708 D HidService: Stopping Bluetooth HidService
,08-17 13:11:16.073   875   875 D BluetoothA2dp: Proxy object disconnected
,08-17 13:11:16.073  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,08-17 13:11:16.075  2708  2708 V BluetoothAdapterState: isTurningOff()=true
,08-17 13:11:16.075  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:16.075  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-17 13:11:16.075  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:16.075  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:16.075  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-17 13:11:16.075  1361  1361 D HidProfile: Bluetooth service disconnected,
08-17 13:11:16.075   875  1891 D DhcpClient: Receive thread stopped
,08-17 13:11:16.077  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 13:11:16.077  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 13:11:16.077  2708  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-17 13:11:16.077  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 13:11:16.077  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 13:11:16.077  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:16.077  2708  2758 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 13:11:16.079  2708  2708 D HealthService: Received stop request...Stopping profile...,
08-17 13:11:16.081  2708  2708 D PanService: Received stop request...Stopping profile...
08-17 13:11:16.083  2708  2708 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 13:11:16.083  2708  2708 D BluetoothMapService: stop()
,08-17 13:11:16.083  2708  2708 D BluetoothMapAppObserver: deinitObservers()
,08-17 13:11:16.084  2708  2708 D BluetoothMapAppObserver: removeReceiver()
,08-17 13:11:16.086  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:16.086  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-17 13:11:16.086  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:16.086  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:16.086  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 13:11:16.086  1361  1361 D PanProfile: Bluetooth service disconnected
,08-17 13:11:16.087  1361  1361 D BluetoothMap: Proxy object disconnected
,08-17 13:11:16.087  1361  1361 D MapProfile: Bluetooth service disconnected
,08-17 13:11:16.087  2708  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-17 13:11:16.087  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 13:11:16.087  2708  2708 V BluetoothAdapterState: isTurningOff()=true
,08-17 13:11:16.087  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 13:11:16.087  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-17 13:11:16.087  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:16.087  2708  2882 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:16.087  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:16.087  2708  2882 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:16.087  2708  2882 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:16.088  2708  2882 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:16.088  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 13:11:16.088  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 13:11:16.088  2708  2758 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 13:11:16.088  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:16.088  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:16.088  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:16.088  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:16.088  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 13:11:16.088  2708  2758 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 13:11:16.090  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 13:11:16.090  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:16.090  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:16.090  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:16.090  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:16.091  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 13:11:16.091  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 13:11:16.092  2708  2708 D BluetoothMapService: MAP Service closeService in
08-17 13:11:16.092  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:16.092  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:16.092  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:16.092  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:16.093  2708  2754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 13:11:16.093  2708  2754 D BluetoothAdapterProperties: Setting state to 15
08-17 13:11:16.093  2708  2754 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 13:11:16.093  1361  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-17 13:11:16.094  2708  2754 I BluetoothAdapterState: Entering BleOnState
,08-17 13:11:16.094  2708  2708 D BluetoothMapService: cleanup()
08-17 13:11:16.094  2708  2708 D BluetoothMapService: MAP Service closeService in
08-17 13:11:16.095   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 13:11:16.095   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:16.095   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:16.095   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:16.095  1361  2116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:16.095  1920  2147 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:16.096  1361  1372 D BluetoothPan: onBluetoothStateChange on: false
,08-17 13:11:16.097  1361  2116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 13:11:16.097  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 13:11:16.098  1361  1372 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 13:11:16.099  2708  2754 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 13:11:16.099  2708  2754 D BluetoothAdapterProperties: Setting state to 16
08-17 13:11:16.099  2708  2754 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 13:11:16.099  2708  2754 D BluetoothAdapterProperties: onBleDisable
08-17 13:11:16.100  2708  2754 I BluetoothAdapterState: Entering PendingCommandState
08-17 13:11:16.100  2708  2755 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 13:11:16.100  2708  2882 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 13:11:16.100  2708  2882 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:16.102  2708  2758 D BluetoothAdapterProperties: Scan Mode:20
08-17 13:11:16.114  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:16.114  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:16.115   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:16.115  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.115  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:16.117  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:16.117  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:16.117  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.117  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:16.119  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.120  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.129  3869  3869 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 13:11:16.136   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 13:11:16.136   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-17 13:11:16.137   875  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 13:11:16.137   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 13:11:16.140   875   892 D Tethering: MasterInitialState.processMessage what=3
08-17 13:11:16.141  3435  3435 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@eb863f0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-17 13:11:16.142  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.143  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.145  1989  1989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-17 13:11:16.145   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 13:11:16.149  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:16.149  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:16.150  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.150  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:16.151   875  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 13:11:16.151  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:16.151  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:16.152  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.152  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:16.164  2125  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 13:11:16.166  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 13:11:16.184  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:16.184   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d00f46d:true
,08-17 13:11:16.196   875   886 I ActivityManager: Start proc 3889:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-17 13:11:16.201   373   873 E Netd    : netlink response contains error (No such file or directory)
08-17 13:11:16.202   875  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 13:11:16.216  3869  3869 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 13:11:16.218  3869  3869 D BluetoothMap: Create BluetoothMap proxy object
08-17 13:11:16.224  3869  3869 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 13:11:16.233  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 13:11:16.236  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:16.243   875  1955 I ActivityManager: Killing 2984:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 13:11:16.303  2708  2758 I bt_hci  : shut_down
,08-17 13:11:16.304  2708  2764 D bt_hwcfg: hw_epilog_process
,08-17 13:11:16.305  2708  2764 I bt_vendor: low_power_mode_cb
,08-17 13:11:16.335  2708  2764 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 13:11:16.335  2708  2764 I bt_vendor: epilog_cb
08-17 13:11:16.335  2708  2764 I bt_hci  : epilog_finished_callback
,08-17 13:11:16.340  2708  2758 I bt_hci_h4: hal_close
,08-17 13:11:16.341  2708  2758 I bt_userial_vendor: device fd = 51 close
,08-17 13:11:16.407  3889  3889 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 13:11:16.407  3889  3889 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.407  3889  3889 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.407  3889  3889 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.407  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.408  3889  3889 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.408  3889  3889 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.408  3889  3889 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.408  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.410  3889  3889 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:16.410  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:16.417  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 13:11:16.429  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:16.438  3869  3869 D DockEventReceiver: finishStartingService: stopping service
08-17 13:11:16.439  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:16.447   875  1937 I ActivityManager: Killing 3435:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 13:11:16.599  3889  3907 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 13:11:16.618  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 13:11:16.627  1742  1742 D SystemUpdateService: onCreate
,08-17 13:11:16.631  2708  2755 D bt_stack_manager: event_shut_down_stack finished.
,08-17 13:11:16.631  2708  2754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-17 13:11:16.633  2708  2708 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 13:11:16.633  2708  2754 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-17 13:11:16.633  2708  2708 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 13:11:16.633  2708  2708 D BtGatt.GattService: stop()
08-17 13:11:16.633  2708  2708 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 13:11:16.634  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 13:11:16.636  2708  2708 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:16.636  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:16.636  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:16.636  2708  2708 V BluetoothAdapterState: isBleTurningOff()=true
08-17 13:11:16.636  2708  2754 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 13:11:16.636  2708  2754 D BluetoothAdapterProperties: Setting state to 10
08-17 13:11:16.636  2708  2754 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 13:11:16.637  2708  2754 I BluetoothAdapterState: Entering OffState
08-17 13:11:16.637   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 13:11:16.640  1742  3923 I SystemUpdateService: active receiver: enabled
,08-17 13:11:16.644  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 13:11:16.644  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-17 13:11:16.645  2708  2708 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 13:11:16.646  2708  2755 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-17 13:11:16.646  1742  3923 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-17 13:11:16.646  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-17 13:11:16.647  1742  3923 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 13:11:16.647  1742  3923 I SystemUpdateService: now status is 0 (complete)
08-17 13:11:16.647  1742  3923 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 13:11:16.648  1742  2424 I iu.UploadsManager: num queued entries: 0
08-17 13:11:16.648  1742  2424 I iu.UploadsManager: num updated entries: 0
08-17 13:11:16.648  1742  3923 I SystemUpdateService: file has been verified
08-17 13:11:16.649  1742  3923 I SystemUpdateService: OTA package size = 12249756
,08-17 13:11:16.649  2708  2755 D bt_stack_manager: event_clean_up_stack finished.
,08-17 13:11:16.655  1742  2424 I iu.SyncManager: NEXT; no task
,08-17 13:11:16.657  1742  3923 I SystemUpdateService: showing system update notification
,08-17 13:11:16.662  2708  2708 I art     : System.exit called, status: 0
,08-17 13:11:16.662  2708  2708 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 13:11:16.666  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 13:11:16.668  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 13:11:16.678   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2545149:true
,08-17 13:11:16.683   875  1952 I ActivityManager: Start proc 3926:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 13:11:16.685  1742  1742 D SystemUpdateService: onDestroy
,08-17 13:11:16.712   875   885 I ActivityManager: Process com.android.bluetooth (pid 2708) has died
,08-17 13:11:16.733  3926  3926 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 13:11:16.735  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:16.741  3926  3926 D SprintDMHelper: simOperator: 
08-17 13:11:16.741  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 13:11:16.755   875  3921 I ActivityManager: Start proc 3939:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-17 13:11:16.885   875  1388 I ActivityManager: Start proc 3954:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 13:11:16.888  3075  3953 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 13:11:16.890   875  1954 I ActivityManager: Killing 3483:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 13:11:16.964  3954  3954 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 13:11:17.025  3954  3954 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 13:11:17.025  3954  3954 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 13:11:17.025  3954  3954 I GAv4    :   adb logcat -s GAv4
,08-17 13:11:17.041  3954  3954 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:17.050  3954  3954 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:17.083  3954  3972 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:17.196  3954  3954 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 13:11:17.237  3954  3954 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 13:11:17.250  3954  3954 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 8470-8478)
,08-17 13:11:17.250  3954  3954 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 13:11:17.260  3954  3954 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6017caa}
,08-17 13:11:17.260  3954  3954 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 13:11:17.260  3954  3954 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 13:11:17.270  3954  3954 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 13:11:17.271  3954  3954 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 13:11:17.293  3954  3954 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 13:11:17.309  3954  3954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 13:11:17.309  3954  3954 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 13:11:17.310  3954  3954 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 13:11:17.310  3954  3954 I Adreno  : Build Date                       : 10/20/15
08-17 13:11:17.310  3954  3954 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 13:11:17.310  3954  3954 I Adreno  : Local Branch                     : M14
08-17 13:11:17.310  3954  3954 I Adreno  : Remote Branch                    : 
08-17 13:11:17.310  3954  3954 I Adreno  : Remote Branch                    : 
08-17 13:11:17.310  3954  3954 I Adreno  : Reconstruct Branch               : 
,08-17 13:11:17.374  3954  3954 I NSApplication: Starting up...
,08-17 13:11:17.384  3954  4001 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 13:11:17.424   875  1955 I ActivityManager: Start proc 4006:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver,
,08-17 13:11:17.425   875  1955 I ActivityManager: Killing 1697:android.process.acore/u0a5 (adj 15): empty #17
,08-17 13:11:17.496  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 13:11:17.689   875  1387 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 13:11:17.766   875   886 I ActivityManager: Start proc 4020:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 13:11:17.842  4020  4020 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 13:11:17.893  4020  4020 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 13:11:17.954   875  1955 I ActivityManager: Killing 3669:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 13:11:19.018   875  3921 D WifiService: setWifiEnabled: true pid=3801, uid=10000
,08-17 13:11:19.019   875  3921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:19.037   875  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-17 13:11:19.043  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:19.044  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:19.044  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:19.044  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:19.048  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:19.048  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:19.049  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:19.049  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:19.090   875  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-17 13:11:19.092   875  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 13:11:19.095   875  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 13:11:19.100   875  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 13:11:19.101   875  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 13:11:19.102   875  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 13:11:19.102   875  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 13:11:19.127   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 13:11:19.130   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:19.131   875  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.00 rxSuccessRate=14.25 delta 1000 -> 994
,08-17 13:11:19.132   875  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-17 13:11:19.132   875  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 13:11:19.139   875  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 13:11:19.140   875  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 13:11:19.151   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 13:11:19.151   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:19.176   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 13:11:19.245   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 13:11:19.248  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 13:11:19.669  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 13:11:19.710  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 13:11:19.711  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 13:11:19.717   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 13:11:19.734   875  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 13:11:19.734   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 13:11:19.734   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 13:11:19.759   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:19.782   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:19.784   875  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 13:11:19.806   875  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 13:11:19.812   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 13:11:19.826   875  4053 D DhcpClient: Receive thread started
,08-17 13:11:19.910   875  1314 E native  : do suspend false
,08-17 13:11:19.930   875  1882 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 13:11:19.943   875  4053 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172681, domain null
,08-17 13:11:19.944   875  1882 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172681 seconds
,08-17 13:11:19.947   875  1882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 13:11:19.960   875  4053 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 13:11:19.961   875  1882 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 13:11:19.965   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:19.977   875  1882 D DhcpClient: Scheduling renewal in 86399s
,08-17 13:11:19.983   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 13:11:20.001   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 13:11:20.004   875  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 13:11:20.004   875  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 13:11:20.005   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 13:11:20.012   875  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 13:11:20.014   875  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 13:11:20.110   875  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 13:11:20.111   875  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 13:11:20.116   875  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 13:11:20.120   875  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 13:11:20.124   875  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 13:11:20.135   875  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 13:11:20.141   875  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 13:11:20.141   875  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 13:11:20.142   875  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 13:11:20.142   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 13:11:20.143   875  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 13:11:20.143   875  1316 D ConnectivityService:    accepting network in place of null
,08-17 13:11:20.144   875  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 13:11:20.158   875  4052 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141386, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 13:11:20.204   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:20.250   875  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:817::200e
,08-17 13:11:20.266   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:20.271   875  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 13:11:20.271   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:20.276   875  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 13:11:20.278   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-17 13:11:20.295  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:20.295  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:20.295  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:20.295  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:20.298  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:20.298  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:20.298  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:20.298  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:20.312  1989  1989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-17 13:11:20.314  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 13:11:20.318  1742  1742 D SystemUpdateService: onCreate
,08-17 13:11:20.322  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 13:11:20.324  1742  4063 I SystemUpdateService: active receiver: enabled
,08-17 13:11:20.328  1742  4063 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 13:11:20.331  1742  4063 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 13:11:20.331  1742  4063 I SystemUpdateService: now status is 0 (complete)
,08-17 13:11:20.331  1742  4063 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 13:11:20.331  1742  4063 I SystemUpdateService: file has been verified
08-17 13:11:20.332  1742  4063 I SystemUpdateService: OTA package size = 12249756
,08-17 13:11:20.335   875  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 11:11:20 GMT], X-Android-Received-Millis=[1471432280335], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471432280303]}
,08-17 13:11:20.336   875  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 13:11:20.336   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-17 13:11:20.337   875  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 13:11:20.338   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 13:11:20.339  1742  4063 I SystemUpdateService: showing system update notification
,08-17 13:11:20.350  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 13:11:20.351  1742  2424 I iu.UploadsManager: num queued entries: 0
,08-17 13:11:20.355  1742  2424 I iu.UploadsManager: num updated entries: 0
,08-17 13:11:20.356  1742  2424 I iu.SyncManager: NEXT; no task,
08-17 13:11:20.357  1742  1742 D SystemUpdateService: onDestroy
,08-17 13:11:20.363  1742  4068 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 13:11:20.363  1742  4068 W BaseAppContext: Using Auth Proxy for data requests.
08-17 13:11:20.363  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 13:11:20.364  1742  4068 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 13:11:20.366  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 13:11:20.367  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:20.372  3926  3926 D SprintDMHelper: simOperator: 
,08-17 13:11:20.372  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 13:11:20.378  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:20.380  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:20.410  1528  2316 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 13:11:20.410  1528  2316 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-17 13:11:20.411  1528  2316 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 13:11:20.411  1528  2316 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 13:11:20.430  1742  4068 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-17 13:11:20.488  3075  4070 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 13:11:20.556   875  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-17 13:11:21.272   875  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 13:11:21.758   875  1937 I ActivityManager: Killing 2252:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 13:11:22.026   875  1387 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-17 13:11:22.027   875  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:22.056  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 13:11:22.063   875  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 13:11:22.063   875  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 13:11:22.064   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 13:11:22.064   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:22.082   875  1882 D DhcpClient: Clearing IP address
,08-17 13:11:22.082   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-17 13:11:22.086   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:22.097  1528  4075 V NativeCrypto: Read error: ssl=0x9a67ce00: I/O error during system call, Connection timed out
,08-17 13:11:22.099  1528  4075 V NativeCrypto: SSL shutdown failed: ssl=0x9a67ce00: I/O error during system call, Broken pipe
,08-17 13:11:22.103   875  1388 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-17 13:11:22.103   875  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-17 13:11:22.106   875  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.110,2a00:1450:4001:817::200e
,08-17 13:11:22.107   875  4053 D DhcpClient: Receive thread stopped
08-17 13:11:22.109   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 13:11:22.109   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 13:11:22.115   396   396 E Parcel  : Reading a NULL string not supported here.
08-17 13:11:22.117   875  4051 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:817::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-17 13:11:22.118   875  1314 D WifiStateMachine: Start Disconnecting Watchdog 2,
08-17 13:11:22.119   875  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 13:11:22.119   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 13:11:22.152   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:22.182   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:22.182   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-17 13:11:22.183   875  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 13:11:22.184   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:22.187   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-17 13:11:22.191  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.191  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.191  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.191  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:22.195  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.195  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.195  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.195  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:22.200  1989  1989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-17 13:11:22.201   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 13:11:22.205  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-17 13:11:22.205  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.205  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.206  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.206  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:22.207  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is, Wi-Fi enabled: false
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.207  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.207  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.207  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:22.208  1742  1742 D SystemUpdateService: onCreate
08-17 13:11:22.209  2125  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 13:11:22.210  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 13:11:22.212   875  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 13:11:22.220  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 13:11:22.226  1742  4084 I SystemUpdateService: active receiver: enabled
08-17 13:11:22.227  1742  2424 I iu.UploadsManager: num queued entries: 0
08-17 13:11:22.230  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 13:11:22.231  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 13:11:22.234  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:22.237  3926  3926 D SprintDMHelper: simOperator: 
,08-17 13:11:22.237  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 13:11:22.276  1742  2424 I iu.UploadsManager: num updated entries: 0
,08-17 13:11:22.277   373   873 E Netd    : netlink response contains error (No such file or directory)
08-17 13:11:22.277  1742  2424 I iu.SyncManager: NEXT; no task
08-17 13:11:22.277   875  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 13:11:22.278   875  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 13:11:22.289  3075  4089 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 13:11:22.294  1742  4084 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 13:11:22.295  1742  4084 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 13:11:22.295  1742  4084 I SystemUpdateService: now status is 0 (complete)
,08-17 13:11:22.295  1742  4084 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 13:11:22.295  1742  4084 I SystemUpdateService: file has been verified
,08-17 13:11:22.296  1742  4084 I SystemUpdateService: OTA package size = 12249756
,08-17 13:11:22.301  1742  4084 I SystemUpdateService: showing system update notification
,08-17 13:11:22.314  1742  1742 D SystemUpdateService: onDestroy
,08-17 13:11:25.084   875   892 I ActivityManager: Start proc 4094:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 13:11:25.220  4094  4094 D AdapterServiceConfig: Adding HeadsetService
,08-17 13:11:25.220  4094  4094 D AdapterServiceConfig: Adding A2dpService
08-17 13:11:25.220  4094  4094 D AdapterServiceConfig: Adding HidService
,08-17 13:11:25.220  4094  4094 D AdapterServiceConfig: Adding HealthService
,08-17 13:11:25.221  4094  4094 D AdapterServiceConfig: Adding PanService
,08-17 13:11:25.221  4094  4094 D AdapterServiceConfig: Adding GattService
08-17 13:11:25.221  4094  4094 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 13:11:25.236   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dfb8604:true
,08-17 13:11:25.237  4094  4094 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 13:11:25.246  4094  4094 I bt_bluedroid: init
08-17 13:11:25.246  4094  4106 I BluetoothAdapterState: Entering OffState
,08-17 13:11:25.252  4094  4107 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 13:11:25.252  4094  4107 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 13:11:25.252  4094  4107 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 13:11:25.253  4094  4107 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 13:11:25.255  4094  4094 I bt_bluedroid: get_profile_interface socket
08-17 13:11:25.259  4094  4110 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 13:11:25.261  4094  4094 I bt_bluedroid: get_profile_interface sdp
08-17 13:11:25.262  4094  4110 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 13:11:25.269  4094  4105 I bt_bluedroid: config_hci_snoop_log
,08-17 13:11:25.273   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 13:11:25.285  4094  4106 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 13:11:25.286  4094  4106 D BluetoothAdapterProperties: Setting state to 14
,08-17 13:11:25.286  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 13:11:25.291  4094  4106 D BluetoothBondStateMachine: make
,08-17 13:11:25.296  4094  4111 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 13:11:25.307  4094  4094 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 13:11:25.309  4094  4106 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:25.317  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:25.319  4094  4094 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 13:11:25.320  4094  4094 D BtGatt.GattService: Received start request. Starting profile...
,08-17 13:11:25.321  4094  4094 D BtGatt.GattService: start()
08-17 13:11:25.321  4094  4094 I bt_bluedroid: get_profile_interface gatt
,08-17 13:11:25.324  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:25.324  4094  4094 D BtGatt.AdvertiseManager: advertise manager created
,08-17 13:11:25.333  4094  4094 V BluetoothAdapterState: isTurningOff()=false
,08-17 13:11:25.334  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:25.334  4094  4094 V BluetoothAdapterState: isBleTurningOn()=true
08-17 13:11:25.334  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:25.334  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 13:11:25.335  4094  4106 I bt_bluedroid: enable
08-17 13:11:25.336  4094  4107 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 13:11:25.336  4094  4107 I bt_hci  : start_up
,08-17 13:11:25.344  4094  4107 I bt_vendor: alloc value 0xb3a41189
,08-17 13:11:25.344  4094  4107 I bt_vendor: init
08-17 13:11:25.344  4094  4107 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 13:11:25.344  4094  4107 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 13:11:25.456  4094  4107 D bt_hci  : start_up starting async portion
,08-17 13:11:25.456  4094  4114 I bt_hci  : event_finish_startup
,08-17 13:11:25.457  4094  4114 I bt_hci_h4: hal_open
,08-17 13:11:25.457  4094  4114 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 13:11:25.470  4094  4114 I bt_userial_vendor: device fd = 51 open
,08-17 13:11:25.495  4094  4114 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 13:11:25.527  4094  4114 D bt_hwcfg: Chipset BCM4354A2
,08-17 13:11:25.528  4094  4114 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 13:11:25.529  4094  4114 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 13:11:26.192  4094  4114 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 13:11:26.194  4094  4114 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 13:11:26.194  4094  4114 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 13:11:26.311  4094  4114 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 13:11:26.312  4094  4114 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 13:11:26.341  4094  4114 I bt_hwcfg: vendor lib fwcfg completed
,08-17 13:11:26.342  4094  4114 I bt_vendor: firmware callback
,08-17 13:11:26.342  4094  4114 I bt_hci  : firmware_config_callback
,08-17 13:11:26.353  4094  4116 I bt_btu  : btu_task pending for preload complete event
,08-17 13:11:26.353  4094  4116 I bt_btu_task: Bluetooth chip preload is complete
,08-17 13:11:26.353  4094  4116 I bt_btu  : btu_task received preload complete event
,08-17 13:11:26.365  4094  4116 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 13:11:26.365  4094  4116 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 13:11:26.366  4094  4116 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 13:11:26.366  4094  4116 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 13:11:26.366  4094  4116 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 13:11:26.366  4094  4116 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 13:11:26.367  4094  4116 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 13:11:26.367  4094  4116 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 13:11:26.368  4094  4116 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 13:11:26.368  4094  4116 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 13:11:26.368  4094  4116 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 13:11:26.369  4094  4116 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 13:11:26.369  4094  4116 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 13:11:26.369  4094  4116 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 13:11:26.370  4094  4116 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 13:11:26.504  4094  4116 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bed9d
,08-17 13:11:26.505  4094  4116 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bed9d 
,08-17 13:11:26.516  4094  4110 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 13:11:26.519  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 13:11:26.520  4094  4110 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 13:11:26.524  4094  4110 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 13:11:26.528  4094  4110 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:26.529  4094  4110 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 13:11:26.530  4094  4110 D bt_hci  : do_postload posting postload work item
,08-17 13:11:26.531  4094  4114 I bt_hci  : event_postload
08-17 13:11:26.532  4094  4114 I bt_vendor: sco_config_cb
08-17 13:11:26.532  4094  4114 I bt_hci  : sco_config_callback postload finished.
08-17 13:11:26.536  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.539  4094  4114 I bt_vendor: low_power_mode_cb
08-17 13:11:26.540  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.541  4094  4110 D bt_bte_conf: Device ID record 1 : primary
,08-17 13:11:26.542  4094  4110 D bt_bte_conf:   vendorId            = 000f
,08-17 13:11:26.542  4094  4110 D bt_bte_conf:   vendorIdSource      = 0001
08-17 13:11:26.543  4094  4110 D bt_bte_conf:   product             = 1200
08-17 13:11:26.543  4094  4110 D bt_bte_conf:   version             = 1436
08-17 13:11:26.543  4094  4110 D bt_bte_conf:   clientExecutableURL = 
08-17 13:11:26.544  4094  4110 D bt_bte_conf:   serviceDescription  = 
,08-17 13:11:26.544  4094  4110 D bt_bte_conf:   documentationURL    = 
08-17 13:11:26.544  4094  4110 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 13:11:26.545  4094  4107 D bt_stack_manager: event_start_up_stack finished
08-17 13:11:26.546  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 13:11:26.546  4094  4106 D BluetoothAdapterProperties: Setting state to 15
,08-17 13:11:26.546  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 13:11:26.548  4094  4106 I BluetoothAdapterState: Entering BleOnState
,08-17 13:11:26.551  4094  4106 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 13:11:26.551  4094  4106 D BluetoothAdapterProperties: Setting state to 11
08-17 13:11:26.551  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 13:11:26.559  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.563  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.564  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:26.564  4094  4094 D HeadsetService: Received start request. Starting profile...
,08-17 13:11:26.568  4094  4094 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 13:11:26.568  4094  4094 D HeadsetStateMachine: make
,08-17 13:11:26.579  4094  4094 D HeadsetStateMachine: max_hf_connections = 1
,08-17 13:11:26.579  4094  4094 I bt_bluedroid: get_profile_interface handsfree
,08-17 13:11:26.579  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 13:11:26.579  4094  4110 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 13:11:26.585  4094  4106 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:26.588  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.590  4094  4094 D A2dpService: Received start request. Starting profile...
,08-17 13:11:26.591  4094  4094 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 13:11:26.592  4094  4094 I bt_bluedroid: get_profile_interface avrcp
,08-17 13:11:26.601  4094  4094 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 13:11:26.602  4094  4094 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-17 13:11:26.602  4094  4094 D A2dpStateMachine: make
,08-17 13:11:26.604  4094  4094 I bt_bluedroid: get_profile_interface a2dp
08-17 13:11:26.604  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 13:11:26.612  4094  4125 D A2dpStateMachine: Enter Disconnected: -2
,08-17 13:11:26.612  4094  4094 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 13:11:26.613  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.614  3869  3869 D BluetoothInputDevice: Proxy object connected
,08-17 13:11:26.614  4094  4094 D HidService: Received start request. Starting profile...
,08-17 13:11:26.614  4094  4094 I bt_bluedroid: get_profile_interface hidhost
08-17 13:11:26.614  4094  4110 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a03e5
,08-17 13:11:26.615  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 13:11:26.615  4094  4094 D HidService: setHidService(): set to: null
,08-17 13:11:26.617  4094  4094 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 13:11:26.618  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:26.619  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.620  4094  4094 D HealthService: Received start request. Starting profile...
,08-17 13:11:26.621  4094  4094 I bt_bluedroid: get_profile_interface health
,08-17 13:11:26.624  4094  4094 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 13:11:26.625  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.626  4094  4094 D PanService: Received start request. Starting profile...
,08-17 13:11:26.627  4094  4094 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 13:11:26.627  4094  4094 I bt_bluedroid: get_profile_interface pan
08-17 13:11:26.627  4094  4110 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 13:11:26.615  3869  3869 D HidProfile: Bluetooth service connected
,08-17 13:11:26.630  4094  4122 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 13:11:26.630  4094  4094 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:26.630  4094  4094 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:26.630  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:26.630  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.633  4094  4094 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:26.635  4094  4094 D BluetoothMapService: Received start request. Starting profile...
,08-17 13:11:26.635  3869  3869 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 13:11:26.635  4094  4094 D BluetoothMapService: start()
,08-17 13:11:26.639  4094  4094 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 13:11:26.639  4094  4094 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 13:11:26.639  4094  4094 D BluetoothMapAppObserver: createReceiver()
,08-17 13:11:26.640  4094  4094 D BluetoothMapAppObserver: initObservers()
,08-17 13:11:26.641  4094  4094 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 13:11:26.646  4094  4094 V BluetoothAdapterState: isTurningOff()=false
,08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isTurningOn()=true
08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:26.647  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.648  3869  3869 D PanProfile: Bluetooth service connected
,08-17 13:11:26.649  4094  4094 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:26.649  4094  4094 V BluetoothAdapterState: isTurningOn()=true,
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isTurningOff()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isTurningOff()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:26.650  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:26.651  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-17 13:11:26.651  4094  4106 D BluetoothAdapterProperties: ScanMode =  20
08-17 13:11:26.651  4094  4106 D BluetoothAdapterProperties: State =  11
08-17 13:11:26.652  4094  4110 D BluetoothAdapterProperties: Scan Mode:21
,08-17 13:11:26.652  4094  4110 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 13:11:26.652  4094  4106 D BluetoothAdapterProperties: Setting state to 12
08-17 13:11:26.652  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 13:11:26.652  4094  4106 I BluetoothAdapterState: Entering OnState
08-17 13:11:26.653  1361  2116 D BluetoothMap: onBluetoothStateChange: up=true
08-17 13:11:26.654  1361  1361 D BluetoothMap: Proxy object connected
,08-17 13:11:26.655  1361  1361 D MapProfile: Bluetooth service connected
,08-17 13:11:26.655  1361  1361 D BluetoothMap: getConnectedDevices()
,08-17 13:11:26.655   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 13:11:26.655   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:26.656   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 13:11:26.656  3869  3881 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 13:11:26.656   875   875 D BluetoothA2dp: Proxy object connected
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:26.656  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:26.658  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:26.659  3869  3880 D BluetoothPan: onBluetoothStateChange on: true,
08-17 13:11:26.659   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:26.659  1361  2036 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:26.660  1920  2140 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 13:11:26.661  1361  1372 D BluetoothPan: onBluetoothStateChange on: true
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:26.661  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:26.662  3869  3869 D BluetoothMap: Proxy object connected
,08-17 13:11:26.663  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 13:11:26.663  1361  1361 D PanProfile: Bluetooth service connected,
08-17 13:11:26.663  1361  2116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 13:11:26.663  3869  3869 D MapProfile: Bluetooth service connected
08-17 13:11:26.663  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-17 13:11:26.663  3869  3869 D BluetoothMap: getConnectedDevices()
08-17 13:11:26.664  1361  1361 D BluetoothA2dp: Proxy object connected
08-17 13:11:26.666  3869  3881 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 13:11:26.666  3869  3880 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 13:11:26.666  4094  4094 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 13:11:26.666  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 13:11:26.667  4094  4094 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 13:11:26.668  4094  4094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:26.669  1361  1361 D BluetoothInputDevice: Proxy object connected
08-17 13:11:26.669  1361  2036 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 13:11:26.669  1361  1361 D HidProfile: Bluetooth service connected
08-17 13:11:26.672   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 13:11:26.673  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:26.673  4094  4094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 13:11:26.674  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:26.675  4094  4094 D ObexServerSockets: Succeed to create listening sockets 
08-17 13:11:26.675  4094  4094 D ObexServerSockets0: startAccept()
08-17 13:11:26.675  4094  4094 D ObexServerSockets0: prepareForNewConnect()
,08-17 13:11:26.676  3869  3869 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 13:11:26.677  4094  4094 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 13:11:26.677  4094  4094 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 13:11:26.677  4094  4131 D ObexServerSockets0: Accepting socket connection...
08-17 13:11:26.678  4094  4094 D BluetoothMapService: onReceive
08-17 13:11:26.678  4094  4094 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:26.678  4094  4094 D BluetoothMapService: STATE_ON
08-17 13:11:26.678  4094  4132 D ObexServerSockets0: Accepting socket connection...
08-17 13:11:26.680  3869  3869 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 13:11:26.683  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:26.685  3869  3869 D BluetoothA2dp: Proxy object connected
,08-17 13:11:26.688  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:26.691  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:26.697  1361  1361 D BluetoothPbap: Proxy object connected
,08-17 13:11:26.697  3869  3869 D BluetoothPbap: Proxy object connected
08-17 13:11:26.697  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-17 13:11:26.698  3869  3869 D PbapServerProfile: Bluetooth service connected
,08-17 13:11:26.704  4094  4094 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 13:11:26.704  4094  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 13:11:26.704  4094  4094 D ObexServerSockets0: prepareForNewConnect()
,08-17 13:11:26.715  4094  4140 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:26.716  4094  4140 I BtOppRfcommListener: Accept thread started.
,08-17 13:11:26.757  1361  2116 D BluetoothHeadset: Proxy object connected
,08-17 13:11:26.758  1361  1361 D HeadsetProfile: Bluetooth service connected
08-17 13:11:26.758   875   875 D BluetoothHeadset: Proxy object connected
08-17 13:11:26.758   875   875 D BluetoothHeadset: Proxy object connected
08-17 13:11:26.758   875   875 D BluetoothHeadset: Proxy object connected
08-17 13:11:26.758  1920  2147 D BluetoothHeadset: Proxy object connected
,08-17 13:11:26.760   875   892 D BluetoothHeadset: Proxy object connected
,08-17 13:11:26.760  1361  1372 D BluetoothHeadset: Proxy object connected
08-17 13:11:26.761  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-17 13:11:26.761  1920  2128 D BluetoothHeadset: Proxy object connected
,08-17 13:11:26.782  3869  3881 D BluetoothHeadset: Proxy object connected
08-17 13:11:26.783  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-17 13:11:28.044  4094  4106 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 13:11:28.045  4094  4106 D BluetoothAdapterProperties: Setting state to 13
08-17 13:11:28.045  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 13:11:28.047  4094  4106 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 13:11:28.052  4094  4106 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:28.055  4094  4110 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:28.056  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 13:11:28.060  4094  4094 D BluetoothMapService: onReceive
,08-17 13:11:28.060  4094  4094 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:28.060  4094  4094 D BluetoothMapService: STATE_TURNING_OFF
,08-17 13:11:28.061  4094  4094 D BluetoothMapService: MAP Service closeService in
,08-17 13:11:28.061  4094  4094 D BluetoothMapMasInstance0: MAP Service shutdown
,08-17 13:11:28.061  4094  4094 D ObexServerSockets0: shutdown(block = true)
,08-17 13:11:28.062  4094  4094 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 13:11:28.062  4094  4094 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 13:11:28.062  4094  4131 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 13:11:28.063  4094  4119 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-17 13:11:28.063  4094  4132 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 13:11:28.064  4094  4094 I BtOppRfcommListener: stopping Accept Thread
,08-17 13:11:28.065  4094  4140 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 13:11:28.065  4094  4140 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 13:11:28.066  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:28.067  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:28.068  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:28.068  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:28.072  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:28.072  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:28.073  3801  3801 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:28.073  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:28.076  4094  4094 D HeadsetService: Received stop request...Stopping profile...
08-17 13:11:28.077  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:28.080  1361  1372 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.080   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.081   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.081   875   875 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.081  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.081  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.081  3869  3880 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.081  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.081  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:28.081  1920  1936 D BluetoothHeadset: Proxy object disconnected
08-17 13:11:28.082  4094  4094 D A2dpService: Received stop request...Stopping profile...
08-17 13:11:28.082  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:28.082  4094  4125 D A2dpStateMachine: Exit Disconnected: -1
08-17 13:11:28.084  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 13:11:28.085   875   875 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:28.085  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-17 13:11:28.085  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:28.089  4094  4094 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 13:11:28.089  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 13:11:28.089  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:28.089  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:28.089  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:28.089  4094  4094 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 13:11:28.089  4094  4110 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-17 13:11:28.090  3869  3869 D HeadsetProfile: Bluetooth service disconnected
08-17 13:11:28.090  3869  3869 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:28.090  4094  4094 D HidService: Received stop request...Stopping profile...
08-17 13:11:28.090  4094  4094 D HidService: Stopping Bluetooth HidService
08-17 13:11:28.091  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-17 13:11:28.091  1361  1361 D HidProfile: Bluetooth service disconnected
08-17 13:11:28.092  4094  4094 D HealthService: Received stop request...Stopping profile...
08-17 13:11:28.093  4094  4094 D PanService: Received stop request...Stopping profile...
08-17 13:11:28.094  3869  3869 D DockEventReceiver: finishStartingService: stopping service
08-17 13:11:28.094  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 13:11:28.094  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.094  1361  1361 D PanProfile: Bluetooth service disconnected
08-17 13:11:28.095  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.095  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.095  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:28.095  3869  3869 D BluetoothInputDevice: Proxy object disconnected
08-17 13:11:28.095  3869  3869 D HidProfile: Bluetooth service disconnected
08-17 13:11:28.096  3869  3869 D Blueto,othPan: BluetoothPAN Proxy object disconnected
08-17 13:11:28.096  3869  3869 D PanProfile: Bluetooth service disconnected
08-17 13:11:28.096  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 13:11:28.096  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:28.096  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 13:11:28.096  4094  4116 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:28.096  4094  4116 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:28.096  4094  4116 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:28.096  4094  4116 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:28.097  4094  4094 D BluetoothMapService: Received stop request...Stopping profile...
08-17 13:11:28.097  4094  4094 D BluetoothMapService: stop()
08-17 13:11:28.097  4094  4094 D BluetoothMapAppObserver: deinitObservers()
08-17 13:11:28.097  4094  4094 D BluetoothMapAppObserver: removeReceiver()
08-17 13:11:28.099  1361  1361 D BluetoothMap: Proxy object disconnected
08-17 13:11:28.099  1361  1361 D MapProfile: Bluetooth service disconnected
08-17 13:11:28.099  3869  3869 D BluetoothMap: Proxy object disconnected
08-17 13:11:28.099  3869  3869 D MapProfile: Bluetooth service disconnected
08-17 13:11:28.101  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.101  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.101  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.101  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:28.102  4094  4094 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 13:11:28.102  4094  4110 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 13:11:28.102  4094  4094 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 13:11:28.103  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.103  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.103  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:28.103  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.103  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:28.103  4094  4094 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 13:11:28.103  4094  4110 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 13:11:28.103  4094  4094 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 13:11:28.104  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.104  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.104  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.104  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:28.104  4094  4094 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 13:11:28.104  4094  4094 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 13:11:28.105  4094  4094 D BluetoothMapService: MAP Service closeService in
08-17 13:11:28.105  4094  4094 V BluetoothAdapterState: isTurningOff()=true
08-17 13:11:28.105  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.105  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.105  4094  4094 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:28.106  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-17 13:11:28.106  4094  4106 D BluetoothAdapterProperties: Setting state to 15
,08-17 13:11:28.106  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-17 13:11:28.106  4094  4106 I BluetoothAdapterState: Entering BleOnState
08-17 13:11:28.106  4094  4094 D BluetoothMapService: cleanup()
08-17 13:11:28.106  4094  4094 D BluetoothMapService: MAP Service closeService in
,08-17 13:11:28.106  1361  2116 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 13:11:28.107   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 13:11:28.107   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:28.107   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:28.108  3869  3881 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 13:11:28.108  1361  1361 D BluetoothPbap: Proxy object disconnected
,08-17 13:11:28.108  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-17 13:11:28.108  3869  3880 D BluetoothPan: onBluetoothStateChange on: false
08-17 13:11:28.110   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:28.111  3869  3881 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:28.111  1361  2036 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:28.111  1920  1934 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 13:11:28.112  1361  2116 D BluetoothPan: onBluetoothStateChange on: false
08-17 13:11:28.114  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:28.115  3869  3880 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 13:11:28.115  3869  3881 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 13:11:28.115  3869  4145 D BluetoothMap: onBluetoothStateChange: up=false
08-17 13:11:28.116  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 13:11:28.116  1361  2036 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 13:11:28.117  4094  4106 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 13:11:28.117  4094  4106 D BluetoothAdapterProperties: Setting state to 16
08-17 13:11:28.117  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 13:11:28.117  4094  4106 D BluetoothAdapterProperties: onBleDisable
08-17 13:11:28.118  4094  4106 I BluetoothAdapterState: Entering PendingCommandState
08-17 13:11:28.118  4094  4107 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 13:11:28.118  4094  4116 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 13:11:28.118  4094  4110 D BluetoothAdapterProperties: Scan Mode:20
08-17 13:11:28.118  4094  4116 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 13:11:28.122  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.123  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.124  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:28.124  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.126  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.128  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:28.130  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:28.145   875  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-17 13:11:28.319  4094  4110 I bt_hci  : shut_down
,08-17 13:11:28.320  4094  4114 D bt_hwcfg: hw_epilog_process
08-17 13:11:28.321  4094  4114 I bt_vendor: low_power_mode_cb
,08-17 13:11:28.347  4094  4114 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 13:11:28.347  4094  4114 I bt_vendor: epilog_cb
,08-17 13:11:28.348  4094  4114 I bt_hci  : epilog_finished_callback
08-17 13:11:28.349  4094  4110 I bt_hci_h4: hal_close
,08-17 13:11:28.351  4094  4110 I bt_userial_vendor: device fd = 51 close
,08-17 13:11:28.474  4094  4107 D bt_stack_manager: event_shut_down_stack finished.
,08-17 13:11:28.476  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 13:11:28.481  4094  4094 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 13:11:28.482  4094  4106 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 13:11:28.483  4094  4094 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 13:11:28.483  4094  4094 D BtGatt.GattService: stop()
08-17 13:11:28.484  4094  4094 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 13:11:28.488  4094  4094 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:28.488  4094  4094 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:28.489  4094  4094 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:28.489  4094  4094 V BluetoothAdapterState: isBleTurningOff()=true
08-17 13:11:28.490  4094  4106 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 13:11:28.490  4094  4106 D BluetoothAdapterProperties: Setting state to 10
,08-17 13:11:28.491  4094  4106 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 13:11:28.494   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 13:11:28.495  4094  4106 I BluetoothAdapterState: Entering OffState
,08-17 13:11:28.516  4094  4094 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 13:11:28.517  4094  4094 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 13:11:28.517  4094  4107 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-17 13:11:28.523  4094  4107 D bt_stack_manager: event_clean_up_stack finished.
,08-17 13:11:28.524  4094  4094 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 13:11:28.529  4094  4094 I art     : System.exit called, status: 0
08-17 13:11:28.529  4094  4094 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 13:11:28.589   875   886 I ActivityManager: Process com.android.bluetooth (pid 4094) has died
,08-17 13:11:29.017   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 13:11:29.026  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 13:11:29.042   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 13:11:29.042   875   895 I Adreno  : Build Date                       : 10/20/15
08-17 13:11:29.042   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
,08-17 13:11:29.042   875   895 I Adreno  : Local Branch                     : M14
08-17 13:11:29.042   875   895 I Adreno  : Remote Branch                    : 
08-17 13:11:29.042   875   895 I Adreno  : Remote Branch                    : 
08-17 13:11:29.042   875   895 I Adreno  : Reconstruct Branch               : 
,08-17 13:11:29.089   281   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (336 us)
,08-17 13:11:29.778  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 13:11:29.779  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 13:11:29.820   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 13:11:29.821  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a6665c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@75303a4, 16908290=android.view.AbsSavedState$1@75303a4}, android:focusedViewId=100}]}]
08-17 13:11:29.821  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 13:11:29.821  3801  3801 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 13:11:29.821  3801  3801 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-17 13:11:29.828   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 13:11:29.833   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 13:11:29.833   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-17 13:11:29.834   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 13:11:30.067   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 13:11:30.070   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 13:11:30.077   875  1341 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
,08-17 13:11:30.086   875   895 I DreamManagerService: Entering dreamland.
08-17 13:11:30.087   875   895 I PowerManagerService: Dozing...
08-17 13:11:30.088   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 13:11:30.143   377  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-17 13:11:30.143   377  1323 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 13:11:30.155   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 13:11:30.165   875  1314 E native  : do suspend false
,08-17 13:11:30.175  1907  4153 D NfcService: Discovery configuration equal, not updating.
,08-17 13:11:30.225   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 13:11:30.231   875  1314 E native  : do suspend true
,08-17 13:11:30.275   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-17 13:11:30.276   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 13:11:31.041  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:31.042  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:34.049  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:34.049  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4cb50d added. We now have 6 listener(s)
08-17 13:11:34.050  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:34.054  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:34.054  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae13cc2 added. We now have 7 listener(s)
,08-17 13:11:34.054  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:34.056  3801  3851 I System.out: IsBluetoothEnabled
,08-17 13:11:34.067  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:34.106   875   892 I ActivityManager: Start proc 4159:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 13:11:34.220  4159  4159 D AdapterServiceConfig: Adding HeadsetService
,08-17 13:11:34.220  4159  4159 D AdapterServiceConfig: Adding A2dpService
08-17 13:11:34.220  4159  4159 D AdapterServiceConfig: Adding HidService
,08-17 13:11:34.220  4159  4159 D AdapterServiceConfig: Adding HealthService
08-17 13:11:34.220  4159  4159 D AdapterServiceConfig: Adding PanService
,08-17 13:11:34.221  4159  4159 D AdapterServiceConfig: Adding GattService
08-17 13:11:34.221  4159  4159 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 13:11:34.235  4159  4159 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 13:11:34.235   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1aa3a5c:true
,08-17 13:11:34.240  4159  4159 I bt_bluedroid: init
,08-17 13:11:34.241  4159  4171 I BluetoothAdapterState: Entering OffState
,08-17 13:11:34.246  4159  4172 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 13:11:34.246  4159  4172 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 13:11:34.246  4159  4172 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 13:11:34.247  4159  4172 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 13:11:34.249  4159  4159 I bt_bluedroid: get_profile_interface socket
,08-17 13:11:34.252  4159  4159 I bt_bluedroid: get_profile_interface sdp
,08-17 13:11:34.256  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 13:11:34.257  4159  4170 I bt_bluedroid: config_hci_snoop_log
,08-17 13:11:34.260  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 13:11:34.260   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 13:11:34.271  4159  4171 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 13:11:34.271  4159  4171 D BluetoothAdapterProperties: Setting state to 14
,08-17 13:11:34.273  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 13:11:34.278  4159  4171 D BluetoothBondStateMachine: make
,08-17 13:11:34.284  4159  4176 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 13:11:34.293  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:34.294  4159  4159 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-17 13:11:34.299  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:34.302  4159  4159 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 13:11:34.303  4159  4159 D BtGatt.GattService: Received start request. Starting profile...
,08-17 13:11:34.303  4159  4159 D BtGatt.GattService: start()
,08-17 13:11:34.303  4159  4159 I bt_bluedroid: get_profile_interface gatt
08-17 13:11:34.306  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
08-17 13:11:34.306  4159  4159 D BtGatt.AdvertiseManager: advertise manager created
,08-17 13:11:34.320  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:34.320  4159  4159 V BluetoothAdapterState: isTurningOn()=false
08-17 13:11:34.320  4159  4159 V BluetoothAdapterState: isBleTurningOn()=true
08-17 13:11:34.320  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:34.321  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 13:11:34.322  4159  4171 I bt_bluedroid: enable
,08-17 13:11:34.322  4159  4172 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 13:11:34.323  4159  4172 I bt_hci  : start_up
,08-17 13:11:34.345  4159  4172 I bt_vendor: alloc value 0xb3a41189
08-17 13:11:34.346  4159  4172 I bt_vendor: init
08-17 13:11:34.346  4159  4172 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 13:11:34.346  4159  4172 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 13:11:34.455  4159  4172 D bt_hci  : start_up starting async portion
,08-17 13:11:34.455  4159  4179 I bt_hci  : event_finish_startup
,08-17 13:11:34.456  4159  4179 I bt_hci_h4: hal_open
,08-17 13:11:34.456  4159  4179 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
08-17 13:11:34.463  4159  4179 I bt_userial_vendor: device fd = 51 open
,08-17 13:11:34.496  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 13:11:34.527  4159  4179 D bt_hwcfg: Chipset BCM4354A2
08-17 13:11:34.528  4159  4179 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 13:11:34.529  4159  4179 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 13:11:35.188  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 13:11:35.189  4159  4179 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 13:11:35.190  4159  4179 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 13:11:35.242  2125  2639 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 13:11:35.307  4159  4179 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 13:11:35.309  4159  4179 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 13:11:35.337  4159  4179 I bt_hwcfg: vendor lib fwcfg completed
08-17 13:11:35.338  4159  4179 I bt_vendor: firmware callback
,08-17 13:11:35.338  4159  4179 I bt_hci  : firmware_config_callback
,08-17 13:11:35.350  4159  4182 I bt_btu  : btu_task pending for preload complete event
08-17 13:11:35.351  4159  4182 I bt_btu_task: Bluetooth chip preload is complete
,08-17 13:11:35.351  4159  4182 I bt_btu  : btu_task received preload complete event
,08-17 13:11:35.361  4159  4182 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 13:11:35.361  4159  4182 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 13:11:35.362  4159  4182 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 13:11:35.362  4159  4182 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 13:11:35.362  4159  4182 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 13:11:35.362  4159  4182 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 13:11:35.363  4159  4182 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 13:11:35.363  4159  4182 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 13:11:35.363  4159  4182 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 13:11:35.364  4159  4182 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 13:11:35.364  4159  4182 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 13:11:35.364  4159  4182 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 13:11:35.365  4159  4182 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 13:11:35.365  4159  4182 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 13:11:35.365  4159  4182 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 13:11:35.496  4159  4182 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bed9d
,08-17 13:11:35.496  4159  4182 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bed9d 
,08-17 13:11:35.507  4159  4175 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 13:11:35.508  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 13:11:35.509  4159  4175 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 13:11:35.514  4159  4175 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 13:11:35.518  4159  4175 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:35.519  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 13:11:35.522  4159  4175 D bt_hci  : do_postload posting postload work item
,08-17 13:11:35.522  4159  4179 I bt_hci  : event_postload
08-17 13:11:35.522  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:35.522  4159  4179 I bt_vendor: sco_config_cb
08-17 13:11:35.523  4159  4179 I bt_hci  : sco_config_callback postload finished.
08-17 13:11:35.526  4159  4175 D bt_bte_conf: Device ID record 1 : primary
08-17 13:11:35.527  4159  4175 D bt_bte_conf:   vendorId            = 000f
08-17 13:11:35.527  4159  4175 D bt_bte_conf:   vendorIdSource      = 0001
08-17 13:11:35.527  4159  4175 D bt_bte_conf:   product             = 1200
08-17 13:11:35.527  4159  4175 D bt_bte_conf:   version             = 1436
08-17 13:11:35.528  4159  4175 D bt_bte_conf:   clientExecutableURL = 
08-17 13:11:35.528  4159  4175 D bt_bte_conf:   serviceDescription  = 
08-17 13:11:35.528  4159  4175 D bt_bte_conf:   documentationURL    = 
,08-17 13:11:35.529  4159  4175 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 13:11:35.529  4159  4172 D bt_stack_manager: event_start_up_stack finished
,08-17 13:11:35.532  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 13:11:35.533  4159  4171 D BluetoothAdapterProperties: Setting state to 15
,08-17 13:11:35.534  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 13:11:35.536  4159  4171 I BluetoothAdapterState: Entering BleOnState
,08-17 13:11:35.538  4159  4179 I bt_vendor: low_power_mode_cb
,08-17 13:11:35.539  4159  4171 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 13:11:35.539  4159  4171 D BluetoothAdapterProperties: Setting state to 11
08-17 13:11:35.539  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 13:11:35.544  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:35.547  4159  4159 D HeadsetService: Received start request. Starting profile...
08-17 13:11:35.547  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:35.551  4159  4159 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 13:11:35.551  4159  4159 D HeadsetStateMachine: make
,08-17 13:11:35.555  4159  4171 I BluetoothAdapterState: Entering PendingCommandState
,08-17 13:11:35.561  4159  4159 D HeadsetStateMachine: max_hf_connections = 1
,08-17 13:11:35.561  4159  4159 I bt_bluedroid: get_profile_interface handsfree
08-17 13:11:35.561  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 13:11:35.562  4159  4175 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 13:11:35.566  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:35.566  4159  4159 D A2dpService: Received start request. Starting profile...
,08-17 13:11:35.568  4159  4159 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 13:11:35.568  4159  4159 I bt_bluedroid: get_profile_interface avrcp
,08-17 13:11:35.574  4159  4159 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 13:11:35.574  4159  4159 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 13:11:35.574  4159  4159 D A2dpStateMachine: make
,08-17 13:11:35.575  4159  4159 I bt_bluedroid: get_profile_interface a2dp
,08-17 13:11:35.576  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 13:11:35.578  4159  4191 D A2dpStateMachine: Enter Disconnected: -2
,08-17 13:11:35.578  4159  4159 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 13:11:35.579  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:35.580  4159  4159 D HidService: Received start request. Starting profile...
,08-17 13:11:35.580  4159  4159 I bt_bluedroid: get_profile_interface hidhost
08-17 13:11:35.580  4159  4159 D HidService: setHidService(): set to: null
08-17 13:11:35.580  4159  4175 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a03e5
08-17 13:11:35.580  4159  4175 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 13:11:35.581  4159  4159 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 13:11:35.582  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
08-17 13:11:35.582  4159  4159 D HealthService: Received start request. Starting profile...
,08-17 13:11:35.584  4159  4159 I bt_bluedroid: get_profile_interface health
,08-17 13:11:35.584  4159  4159 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 13:11:35.585  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:35.585  4159  4159 D PanService: Received start request. Starting profile...
08-17 13:11:35.586  4159  4159 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 13:11:35.586  4159  4159 I bt_bluedroid: get_profile_interface pan
,08-17 13:11:35.586  4159  4175 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 13:11:35.590  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:35.590  4159  4159 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
08-17 13:11:35.591  4159  4159 D BluetoothMapService: Received start request. Starting profile...
08-17 13:11:35.591  4159  4159 D BluetoothMapService: start()
,08-17 13:11:35.594  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 13:11:35.595  4159  4159 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 13:11:35.595  4159  4159 D BluetoothMapAppObserver: createReceiver()
,08-17 13:11:35.596  4159  4159 D BluetoothMapAppObserver: initObservers()
,08-17 13:11:35.596  4159  4159 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 13:11:35.605  4159  4189 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 13:11:35.605  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:35.605  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:35.605  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:35.605  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isTurningOn()=true
08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:35.607  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isTurningOn()=true,
,08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isTurningOff()=false
08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
08-17 13:11:35.608  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:35.609  4159  4159 V BluetoothAdapterState: isTurningOff()=false
,08-17 13:11:35.609  4159  4159 V BluetoothAdapterState: isTurningOn()=true
,08-17 13:11:35.609  4159  4159 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 13:11:35.609  4159  4159 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 13:11:35.610  4159  4171 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 13:11:35.610  4159  4171 D BluetoothAdapterProperties: ScanMode =  20
08-17 13:11:35.610  4159  4171 D BluetoothAdapterProperties: State =  11
,08-17 13:11:35.610  4159  4171 D BluetoothAdapterProperties: Setting state to 12
08-17 13:11:35.610  4159  4171 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 13:11:35.611  1361  2116 D BluetoothMap: onBluetoothStateChange: up=true
08-17 13:11:35.612  4159  4171 I BluetoothAdapterState: Entering OnState
08-17 13:11:35.613  4159  4175 D BluetoothAdapterProperties: Scan Mode:21,
08-17 13:11:35.613  4159  4175 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 13:11:35.615   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.616   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:35.616   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:35.617  3869  4145 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:35.618  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:35.619  1361  1361 D BluetoothMap: Proxy object connected
08-17 13:11:35.619  1361  1361 D MapProfile: Bluetooth service connected
08-17 13:11:35.619  1361  1361 D BluetoothMap: getConnectedDevices()
08-17 13:11:35.621   875   875 D BluetoothA2dp: Proxy object connected
08-17 13:11:35.621  3869  3880 D BluetoothPan: onBluetoothStateChange on: true
,08-17 13:11:35.621  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:35.623  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 13:11:35.623  4159  4159 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 13:11:35.623   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 13:11:35.624  3869  3881 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.625  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 13:11:35.627  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 13:11:35.627  4159  4159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:35.628  1920  2147 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:35.628  4159  4159 D ObexServerSockets: Succeed to create listening sockets 
08-17 13:11:35.629  4159  4159 D ObexServerSockets0: startAccept()
,08-17 13:11:35.629  4159  4159 D ObexServerSockets0: prepareForNewConnect()
08-17 13:11:35.629  1361  2036 D BluetoothPan: onBluetoothStateChange on: true
08-17 13:11:35.631  4159  4159 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 13:11:35.631  4159  4159 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 13:11:35.632  4159  4197 D ObexServerSockets0: Accepting socket connection...
08-17 13:11:35.632  4159  4198 D ObexServerSockets0: Accepting socket connection...
08-17 13:11:35.633  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 13:11:35.633  1361  1361 D PanProfile: Bluetooth service connected
,08-17 13:11:35.634  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.634  3869  3869 D BluetoothA2dp: Proxy object connected
08-17 13:11:35.636  1361  1361 D BluetoothA2dp: Proxy object connected
08-17 13:11:35.636  3869  4145 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 13:11:35.637  3869  3881 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 13:11:35.639  3869  3880 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 13:11:35.640  3869  3869 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 13:11:35.640  1361  2116 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 13:11:35.641  3869  3869 D PanProfile: Bluetooth service connected
08-17 13:11:35.641  3869  3869 D BluetoothInputDevice: Proxy object connected
08-17 13:11:35.641  3869  3869 D HidProfile: Bluetooth service connected
,08-17 13:11:35.642  3869  3869 D BluetoothMap: Proxy object connected
,08-17 13:11:35.642  1361  1361 D BluetoothInputDevice: Proxy object connected
08-17 13:11:35.642  3869  3869 D MapProfile: Bluetooth service connected
08-17 13:11:35.642  1361  1361 D HidProfile: Bluetooth service connected
08-17 13:11:35.642  3869  3869 D BluetoothMap: getConnectedDevices()
08-17 13:11:35.643  1361  1372 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 13:11:35.646   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 13:11:35.647  4159  4159 D BluetoothMapService: onReceive
,08-17 13:11:35.647  4159  4159 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:35.647  4159  4159 D BluetoothMapService: STATE_ON
,08-17 13:11:35.647  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:35.652  3869  3869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:35.660  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:35.660  3869  3869 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:35.669  3869  3869 D BluetoothPbap: Proxy object connected
,08-17 13:11:35.669  3869  3869 D PbapServerProfile: Bluetooth service connected
,08-17 13:11:35.673  1361  1361 D BluetoothPbap: Proxy object connected
,08-17 13:11:35.673  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-17 13:11:35.678  4159  4159 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 13:11:35.681  4159  4159 D ObexServerSockets0: prepareForNewConnect()
,08-17 13:11:35.684  4159  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:35.704  4159  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:35.706  4159  4206 I BtOppRfcommListener: Accept thread started.
,08-17 13:11:35.718  1361  1372 D BluetoothHeadset: Proxy object connected
08-17 13:11:35.718  1361  1361 D HeadsetProfile: Bluetooth service connected
08-17 13:11:35.718   875   875 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.718   875   875 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.718   875   875 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.719  3869  3881 D BluetoothHeadset: Proxy object connected
08-17 13:11:35.719  1920  2128 D BluetoothHeadset: Proxy object connected
08-17 13:11:35.719  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-17 13:11:35.724   875   892 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.729  1361  1374 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.729  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-17 13:11:35.729  1920  1936 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.738  3869  4145 D BluetoothHeadset: Proxy object connected
,08-17 13:11:35.739  3869  3869 D HeadsetProfile: Bluetooth service connected
,08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:36.091  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:36.099  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:36.103  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:36.104  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2762ad3 added. We now have 8 listener(s)
,08-17 13:11:36.104  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:36.111   875  1946 D WifiService: setWifiEnabled: false pid=3801, uid=10000
,08-17 13:11:36.111   875  1946 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:36.124  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:36.125   875  1954 D WifiService: setWifiEnabled: true pid=3801, uid=10000
,08-17 13:11:36.126   875  1954 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 13:11:36.140   875  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:36.157  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:36.164  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:36.171   875  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-17 13:11:36.172   875  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 13:11:36.172   875  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 13:11:36.173   875  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 13:11:36.173   875  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 13:11:36.174   875  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 13:11:36.174   875  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 13:11:36.188   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 13:11:36.188   875  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.27 delta 1000 -> 1000
08-17 13:11:36.189   875  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 13:11:36.190   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:36.197   875  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 13:11:36.197   875  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 13:11:36.199   875  1314 E native  : do suspend true
,08-17 13:11:36.200   875  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 13:11:36.206   875  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 13:11:36.227   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 13:11:36.227   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:36.235   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 13:11:36.292   875  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 13:11:36.295  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 13:11:36.723  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 13:11:36.762  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 13:11:36.762  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 13:11:36.767   875  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 13:11:36.773   875  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 13:11:36.774   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:36.774   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 13:11:36.797   875  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:36.807   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:36.808   875  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 13:11:36.819   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 13:11:36.834   875  4214 D DhcpClient: Receive thread started
,08-17 13:11:36.922   875  1314 E native  : do suspend false
,08-17 13:11:36.942   875  1882 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 13:11:36.967   875  4214 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-17 13:11:36.968   875  1882 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 13:11:36.972   875  1882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 13:11:36.995   875  4214 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 13:11:36.996   875  1882 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 13:11:37.001   373   873 D CommandListener: Setting iface cfg
,08-17 13:11:37.012   875  1882 D DhcpClient: Scheduling renewal in 86399s
,08-17 13:11:37.014   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-17 13:11:37.016   875  1314 E native  : do suspend true
,08-17 13:11:37.035   875  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 13:11:37.036   875  1314 D WifiConfigStore: No blacklist allowed without epno enabled
08-17 13:11:37.036   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 13:11:37.038   875  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 13:11:37.038   875  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 13:11:37.090   875  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 13:11:37.090   875  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 13:11:37.091   875  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 13:11:37.092   875  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 13:11:37.093   875  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 13:11:37.100   875  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 13:11:37.104   875  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-17 13:11:37.104   875  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-17 13:11:37.105   875  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 13:11:37.105   875  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 13:11:37.105   875  1316 D ConnectivityService:    accepting network in place of null
,08-17 13:11:37.105   875  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 13:11:37.106   875  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 13:11:37.120   875  4213 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158348, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 13:11:37.136   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:37.144  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:37.147  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:37.157  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 13:11:37.158  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 13:11:37.163  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a6665c Bundle[{}]
,08-17 13:11:37.164  3801  3851 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 13:11:37.164  3801  3851 I io.jxcore.node.LifeCycleMonitor: stop: OK,
,08-17 13:11:37.168  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 13:11:37.169  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 13:11:37.169  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 13:11:37.170  3801  3851 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 13:11:37.176  3801  3851 I System.out: Running OutgoingSocketThread
,08-17 13:11:37.178  3801  4222 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 415)
,08-17 13:11:37.180  3801  4222 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42617
,08-17 13:11:37.180  3801  4222 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 13:11:37.183   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 13:11:37.185   875  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
,08-17 13:11:37.190   875  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 13:11:37.190   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:37.196   875  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 13:11:37.197   875   892 D Tethering: MasterInitialState.processMessage what=3,
,08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:37.213  3801  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:37.217  3801  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:37.223  1989  1989 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-17 13:11:37.227  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-17 13:11:37.232  1742  1742 D SystemUpdateService: onCreate
,08-17 13:11:37.241  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 13:11:37.254  1742  4224 I SystemUpdateService: active receiver: enabled
,08-17 13:11:37.265   875  4212 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 11:11:37 GMT], X-Android-Received-Millis=[1471432297265], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471432297235]}
,08-17 13:11:37.266   875  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 13:11:37.266   875  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 13:11:37.266   875  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 13:11:37.267   875  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 13:11:37.273  1742  4224 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 13:11:37.279  1742  4224 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 13:11:37.279  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 13:11:37.279  1742  4224 I SystemUpdateService: now status is 0 (complete)
08-17 13:11:37.280  1742  4224 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 13:11:37.280  1742  4224 I SystemUpdateService: file has been verified
,08-17 13:11:37.281  1742  4224 I SystemUpdateService: OTA package size = 12249756
,08-17 13:11:37.283  1742  2424 I iu.UploadsManager: num queued entries: 0
,08-17 13:11:37.283  1742  2424 I iu.UploadsManager: num updated entries: 0
,08-17 13:11:37.291  1742  4224 I SystemUpdateService: showing system update notification
,08-17 13:11:37.295  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 13:11:37.296  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 13:11:37.298  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:37.301  1742  4228 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 13:11:37.302  1742  4228 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 13:11:37.303  1742  4228 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 13:11:37.304  3926  3926 D SprintDMHelper: simOperator: 
,08-17 13:11:37.304  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 13:11:37.311  1742  2424 I iu.SyncManager: NEXT; no task
,08-17 13:11:37.313  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:37.314  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 13:11:37.353  1528  1546 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 13:11:37.354  1528  1546 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 13:11:37.354  1528  1546 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 13:11:37.356  1528  1546 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 13:11:37.374  1742  1742 D SystemUpdateService: onDestroy
,08-17 13:11:37.382  1742  4228 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-17 13:11:37.438  3075  4230 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 13:11:38.179  3801  3851 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 416)
,08-17 13:11:38.180  3801  3851 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 416)
,08-17 13:11:38.189   875  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 13:11:38.190  3801  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 421)
,08-17 13:11:38.193  3801  3851 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 13:11:38.194  3801  3851 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-17 13:11:38.198  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:38.198  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb610 added. We now have 2 listener(s)
,08-17 13:11:38.200  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 13:11:38.201  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:38.201  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:38.201  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.202  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9c9509 added. We now have 9 listener(s)
,08-17 13:11:38.202  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:38.202  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:38.208  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:38.217  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:38.220  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:38.221  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:38.222  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:38.222  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ea12f added. We now have 3 listener(s)
,08-17 13:11:38.226  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:38.229  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:38.229  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:38.230  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:38.230  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:38.230  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:38.230  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f91233c added. We now have 10 listener(s)
08-17 13:11:38.231  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:38.231  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:38.231  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:38.232  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:38.232  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:38.232  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.233  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:38.233  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.233  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f8eb610 removed from the list
,08-17 13:11:38.233  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.234  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9c9509 removed from the list
,08-17 13:11:38.234  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:38.234  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.235  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.236  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:38.238  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:38.238  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.238  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:38.238  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9c9509 not in the list
,08-17 13:11:38.239  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.239  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.241  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.241  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.242  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.242  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f91233c removed from the list
08-17 13:11:38.242  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.242  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.243  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.243  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.243  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6ea12f removed from the list
08-17 13:11:38.245  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.245  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f078c5 added. We now have 2 listener(s)
,08-17 13:11:38.247  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:38.247  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.247  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:38.247  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.248  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98da21a added. We now have 9 listener(s)
08-17 13:11:38.248  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-17 13:11:38.248  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:38.252  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:38.257  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:38.260  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:38.261  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:38.261  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:38.261  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeb3728 added. We now have 3 listener(s)
,08-17 13:11:38.263  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:38.263  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:38.263  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:38.263  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:38.263  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4dc41 added. We now have 10 listener(s)
08-17 13:11:38.263  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:38.263  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.264  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:38.264  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-17 13:11:38.264  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:38.264  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:38.271  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:38.273  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 13:11:38.273  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 13:11:38.278  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:38.278  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:38.280  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 13:11:38.281  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:38.286  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:38.286  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 13:11:38.287  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-17 13:11:38.288  3801  3851 D BluetoothAdapter: STATE_ON
,08-17 13:11:38.292  4159  4196 D BtGatt.GattService: registerClient() - UUID=ecaeb684-385b-47e5-9cd4-cb0480e35777
,08-17 13:11:38.293  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=ecaeb684-385b-47e5-9cd4-cb0480e35777, clientIf=5
,08-17 13:11:38.294  3801  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 13:11:38.296  4159  4169 D BtGatt.GattService: start scan with filters
,08-17 13:11:38.302  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 13:11:38.302  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:38.303  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:38.303  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:38.303  4159  4178 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:38.306  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:38.306  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:38.306  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:38.307  4159  4178 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2900730
,08-17 13:11:38.308  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:38.313  3801  3851 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:38.313  4159  4175 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 13:11:38.313  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:38.313  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.313  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 13:11:38.313  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.314  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 13:11:38.314  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:38.314  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:38.314  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:38.314  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:38.314  4159  4178 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 13:11:38.314  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:38.314  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 13:11:38.315  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:38.316  4159  4169 D BtGatt.GattService: stopScan() - queue size =1
08-17 13:11:38.317  4159  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 13:11:38.317  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:38.317  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:38.318  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:38.318  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:38.318  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 13:11:38.319  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:38.319  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:38.319  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:38.319  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:38.320  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:38.322  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:38.322  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:38.322  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:38.325  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:38.325  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:38.325  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:38.325  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.326  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.326  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:38.326  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.326  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f078c5 removed from the list
,08-17 13:11:38.326  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.326  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98da21a removed from the list
08-17 13:11:38.326  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:38.326  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.327  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.327  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.328  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.328  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.328  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:38.328  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98da21a not in the list
08-17 13:11:38.328  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.328  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.331  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:38.331  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.331  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:38.332  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e4dc41 removed from the list
,08-17 13:11:38.332  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:38.332  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.332  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.332  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.332  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeb3728 removed from the list
,08-17 13:11:38.333  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.333  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 13:11:38.333  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@761fb7d added. We now have 2 listener(s)
08-17 13:11:38.333  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.334  4159  4178 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:38.334  4159  4178 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 13:11:38.335  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 13:11:38.335  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.335  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:38.335  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.335  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f065a72 added. We now have 9 listener(s)
08-17 13:11:38.335  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:38.336  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:38.342  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:38.348  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:38.351  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:38.351  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:38.352  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.352  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c340 added. We now have 3 listener(s)
,08-17 13:11:38.353  4159  4175 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 13:11:38.353  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:38.353  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.356  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:38.357  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:38.358  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.358  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:38.359  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.359  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a97d279 added. We now have 10 listener(s)
08-17 13:11:38.359  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:38.359  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.361  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.361  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:38.361  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 13:11:38.361  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:38.362  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:38.363  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 13:11:38.363  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.367  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 13:11:38.367  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 13:11:38.372  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 13:11:38.372  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.373  4159  4178 D BtGatt.ScanManager: stopping BLe Batch
08-17 13:11:38.374  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:38.375  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 13:11:38.375  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:38.380  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 13:11:38.380  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.380  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 13:11:38.381  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:38.381  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:38.382  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 13:11:38.383  3801  3851 D BluetoothAdapter: STATE_ON
,08-17 13:11:38.385  4159  4188 D BtGatt.GattService: registerClient() - UUID=8d0106f1-f2dd-463a-ae86-c4782f16c870
,08-17 13:11:38.385  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=8d0106f1-f2dd-463a-ae86-c4782f16c870, clientIf=5
,08-17 13:11:38.386  3801  3812 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 13:11:38.386  4159  4196 D BtGatt.GattService: start scan with filters
,08-17 13:11:38.389  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 13:11:38.389  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.389  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:38.390  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:38.390  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:38.390  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 13:11:38.391  4159  4178 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:38.393  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:38.393  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:38.393  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:38.396  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:38.399  4159  4175 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 13:11:38.400  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-17 13:11:38.400  4159  4178 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 13:11:38.401  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.401  3801  3851 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 13:11:38.402  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:38.402  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,08-17 13:11:38.402  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:38.402  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:38.402  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.403  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:38.403  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.403  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@761fb7d removed from the list
,08-17 13:11:38.403  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.403  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f065a72 removed from the list
,08-17 13:11:38.403  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:38.403  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:38.404  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.404  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 13:11:38.404  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.404  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-17 13:11:38.405  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:38.406  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.406  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.406  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f065a72 not in the list
08-17 13:11:38.406  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:38.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:38.406  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:38.406  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:38.406  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 13:11:38.407  3801  3851 D BluetoothAdapter: STATE_ON
,08-17 13:11:38.407  4159  4170 D BtGatt.GattService: stopScan() - queue size =1
08-17 13:11:38.407  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 13:11:38.408  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.408  4159  4178 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:38.408  4159  4169 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 13:11:38.408  4159  4178 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 13:11:38.408  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:38.408  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:38.409  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 13:11:38.409  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:38.409  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 13:11:38.410  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:38.410  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:38.410  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:38.410  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:38.410  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.411  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:38.412  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:38.412  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:38.412  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.412  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:38.412  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.412  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a97d279 removed from the list
08-17 13:11:38.412  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.412  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.412  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.412  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.413  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c340 removed from the list
08-17 13:11:38.413  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.413  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba1d35 added. We now have 2 listener(s)
,08-17 13:11:38.415  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 13:11:38.415  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.415  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:38.416  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.416  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@822c5ca added. We now have 9 listener(s)
08-17 13:11:38.416  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:38.417  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:38.419  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:38.424  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:38.426  4159  4175 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 13:11:38.426  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.427  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:38.428  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:38.428  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.429  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eeba58 added. We now have 3 listener(s)
,08-17 13:11:38.430  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 13:11:38.431  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:38.431  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:38.431  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:38.432  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:38.432  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47c57b1 added. We now have 10 listener(s)
,08-17 13:11:38.432  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:38.432  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.432  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:38.432  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 13:11:38.432  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:38.432  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:38.434  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:38.435  3801  3851 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 13:11:38.435  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 13:11:38.436  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 13:11:38.436  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.439  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:38.440  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 13:11:38.440  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:38.444  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:38.444  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:38.444  3801  3851 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 13:11:38.445  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:38.447  4159  4170 D BtGatt.GattService: registerClient() - UUID=95fbcd67-23a4-46a6-a467-3b2e39cfbd53
,08-17 13:11:38.447  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 13:11:38.447  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.448  4159  4178 D BtGatt.ScanManager: stopping BLe Batch
08-17 13:11:38.448  4159  4175 D BtGatt.GattService: onClientRegistered() - UUID=95fbcd67-23a4-46a6-a467-3b2e39cfbd53, clientIf=5
08-17 13:11:38.451  3801  3847 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 13:11:38.451  4159  4169 D BtGatt.GattService: start scan with filters
,08-17 13:11:38.454  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:38.454  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-17 13:11:38.454  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:38.454  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:38.456  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 13:11:38.457  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.457  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 13:11:38.458  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:38.458  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:38.458  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 13:11:38.460  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:38.464  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:38.464  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:38.464  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:38.464  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.465  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.465  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 13:11:38.465  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 13:11:38.465  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba1d35 removed from the list,
08-17 13:11:38.465  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:38.465  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 13:11:38.465  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@822c5ca removed from the list
,08-17 13:11:38.465  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.465  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop,
,08-17 13:11:38.465  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:38.466  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.466  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 13:11:38.466  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.466  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.467  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@822c5ca not in the list
08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:38.467  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 13:11:38.467  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 13:11:38.467  4159  4178 D BtGatt.ScanManager: handling starting scan
08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:38.467  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 13:11:38.468  3801  3851 D BluetoothAdapter: STATE_ON
08-17 13:11:38.468  4159  4169 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:38.469  4159  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 13:11:38.469  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:38.469  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:38.469  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:38.469  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:38.469  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 13:11:38.470  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:38.470  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:38.470  3801  3851 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:38.471  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 13:11:38.471  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.472  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:38.472  3801  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:38.472  3801  3801 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:38.472  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.472  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.472  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.473  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47c57b1 removed from the list
08-17 13:11:38.473  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.473  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:38.473  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.473  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.473  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eeba58 removed from the list
08-17 13:11:38.473  4159  4175 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 13:11:38.473  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.474  4159  4178 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 13:11:38.474  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:38.474  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4dbded added. We now have 2 listener(s)
,08-17 13:11:38.476  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 13:11:38.476  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.476  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:38.476  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.476  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9464422 added. We now have 9 listener(s)
08-17 13:11:38.476  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:38.477  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 13:11:38.479  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:38.480  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 13:11:38.480  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.481  4159  4178 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:38.481  4159  4178 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:38.485  3801  3851 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:38.488  3801  3851 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:38.489  3801  3851 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:38.490  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:38.490  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82e7c70 added. We now have 3 listener(s)
,08-17 13:11:38.491  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:38.493  4159  4175 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 13:11:38.493  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.493  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 13:11:38.493  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:38.493  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:38.493  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:38.493  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4554be9 added. We now have 10 listener(s)
08-17 13:11:38.494  3801  3851 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:38.494  3801  3851 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:38.494  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:38.494  3801  3851 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:38.494  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:38.494  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.494  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:38.494  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 13:11:38.494  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4dbded removed from the list
08-17 13:11:38.494  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.494  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9464422 removed from the list
,08-17 13:11:38.497  3801  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:38.497  3801  3851 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:38.497  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.498  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.498  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:38.499  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.499  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:38.499  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.499  3801  3851 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9464422 not in the list
,08-17 13:11:38.499  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.499  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:38.501  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:38.501  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:38.501  3801  3851 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:38.501  3801  3851 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4554be9 removed from the list
08-17 13:11:38.501  3801  3851 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:38.501  3801  3851 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:38.501  3801  3851 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:38.501  3801  3851 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:38.501  3801  3851 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82e7c70 removed from the list
,08-17 13:11:38.502  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 13:11:38.502  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 13:11:38.502  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 13:11:38.503  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:38.503  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 13:11:38.503  3801  3851 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:38.505  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 13:11:38.505  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 13:11:38.509  3801  4236 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,08-17 13:11:38.509  3801  4236 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
08-17 13:11:38.509  3801  4236 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 13:11:38.511  3801  4237 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
08-17 13:11:38.511  3801  4237 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
,08-17 13:11:38.511  3801  4237 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 13:11:38.513  3801  3851 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 13:11:38.513  3801  3851 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 13:11:38.513  3801  3851 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 13:11:38.513  3801  3851 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 13:11:38.513  3801  3851 D com.test.thalitest.ThaliTestRunner: Total duration: 22929 ms
,08-17 13:11:38.515  4159  4175 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 13:11:38.515  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.515  3801  3851 I jxcore-log: Total number of executed tests:  80
08-17 13:11:38.515  3801  3851 I jxcore-log: 
08-17 13:11:38.515  4159  4178 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:38.515  3801  3851 I jxcore-log: Number of passed tests:  80
08-17 13:11:38.515  3801  3851 I jxcore-log: 
08-17 13:11:38.516  3801  3851 I jxcore-log: Number of failed tests:  0
08-17 13:11:38.516  3801  3851 I jxcore-log: 
08-17 13:11:38.516  3801  3851 I jxcore-log: Number of ignored tests:  0
08-17 13:11:38.516  3801  3851 I jxcore-log: 
08-17 13:11:38.516  3801  3851 I jxcore-log: Total duration:  22929
08-17 13:11:38.516  3801  3851 I jxcore-log: 
,08-17 13:11:38.516  3801  3851 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 13:11:38.516  3801  3851 I jxcore-log: 
,08-17 13:11:38.524  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.524  3801  3851 I jxcore-log: 
08-17 13:11:38.524  4159  4175 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 13:11:38.524  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.524  4159  4178 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 13:11:38.525  3801  3801 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 13:11:38.528  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.528  3801  3851 I jxcore-log: 
08-17 13:11:38.529  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.529  3801  3851 I jxcore-log: 
,08-17 13:11:38.530  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.530  3801  3851 I jxcore-log: 
08-17 13:11:38.531  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.531  3801  3851 I jxcore-log: 
08-17 13:11:38.532  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.532  3801  3851 I jxcore-log: 
08-17 13:11:38.532  4159  4175 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 13:11:38.532  4159  4175 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 13:11:38.534  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.534  3801  3851 I jxcore-log: 
,08-17 13:11:38.536  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.536  3801  3851 I jxcore-log: 
08-17 13:11:38.537  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.537  3801  3851 I jxcore-log: 
,08-17 13:11:38.537  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.537  3801  3851 I jxcore-log: 
,08-17 13:11:38.538  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.538  3801  3851 I jxcore-log: 
,08-17 13:11:38.539  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:38.539  3801  3851 I jxcore-log: 
,08-17 13:11:38.540  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.540  3801  3851 I jxcore-log: 
,08-17 13:11:38.541  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.541  3801  3851 I jxcore-log: 
08-17 13:11:38.541  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.541  3801  3851 I jxcore-log: 
,08-17 13:11:38.542  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.542  3801  3851 I jxcore-log: 
,08-17 13:11:38.543  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.543  3801  3851 I jxcore-log: 
,08-17 13:11:38.543  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.543  3801  3851 I jxcore-log: 
08-17 13:11:38.544  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.544  3801  3851 I jxcore-log: 
,08-17 13:11:38.545  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.545  3801  3851 I jxcore-log: 
,08-17 13:11:38.546  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.546  3801  3851 I jxcore-log: 
,08-17 13:11:38.546  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.546  3801  3851 I jxcore-log: 
08-17 13:11:38.547  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.547  3801  3851 I jxcore-log: 
08-17 13:11:38.547  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.547  3801  3851 I jxcore-log: 
,08-17 13:11:38.548  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.548  3801  3851 I jxcore-log: 
,08-17 13:11:38.548  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:38.548  3801  3851 I jxcore-log: 
08-17 13:11:38.549  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 13:11:38.549  3801  3851 I jxcore-log: 
,08-17 13:11:38.549  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.549  3801  3851 I jxcore-log: 
08-17 13:11:38.550  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.550  3801  3851 I jxcore-log: 
,08-17 13:11:38.551  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.551  3801  3851 I jxcore-log: 
,08-17 13:11:38.551  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.551  3801  3851 I jxcore-log: 
08-17 13:11:38.552  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.552  3801  3851 I jxcore-log: 
,08-17 13:11:38.552  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.552  3801  3851 I jxcore-log: 
08-17 13:11:38.553  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:38.553  3801  3851 I jxcore-log: 
,08-17 13:11:38.822  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:38.825  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:38.825  3801  3851 I jxcore-log: 
,08-17 13:11:38.912  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:38.915  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:38.915  3801  3851 I jxcore-log: 
,08-17 13:11:38.972  3801  3801 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:38.975  3801  3851 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:38.975  3801  3851 I jxcore-log: 
,08-17 13:11:39.112  4238  4238 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 13:11:39.116  4238  4238 D AndroidRuntime: CheckJNI is OFF
,08-17 13:11:39.158  4238  4238 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 13:11:39.208  4238  4238 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 13:11:39.230  4238  4238 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 13:11:39.241   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 13:11:39.242   875   888 I ActivityManager: Killing 3801:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 13:11:39.327   875   885 D GraphicsStats: Buffer count: 2
,08-17 13:11:39.327   875   885 I WindowState: WIN DEATH: Window{53f6e56 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 13:11:39.328   875  1315 D WifiService: Client connection lost with reason: 4
,08-17 13:11:39.410   875   898 W PackageSettings: Skipping PackageSetting{3cf21bd com.example.hello/10273} due to missing metadata
,08-17 13:11:39.441   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-17 13:11:39.442   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-17 13:11:39.442   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-17 13:11:39.442   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 13:11:39.442   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.442   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.442   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 13:11:39.442   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 13:11:39.443   875   888 I ActivityManager:   Force finishing activity ActivityRecord{61f08ff u0 com.test.thalitest/.MainActivity t2}
08-17 13:11:39.447   875   898 I art     : Starting a blocking GC Explicit
08-17 13:11:39.456   875  1928 W ActivityManager: Spurious death for ProcessRecord{46582f1 0:com.test.thalitest/u0a0}, curProc for 3801: null
,08-17 13:11:39.494   875   898 I art     : Explicit concurrent mark sweep GC freed 13892(967KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 737us total 46.400ms
,08-17 13:11:39.545   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-17 13:11:39.549  4238  4238 I art     : System.exit called, status: 0
,08-17 13:11:39.549  4238  4238 I AndroidRuntime: VM exiting with result code 0.
,08-17 13:11:39.562   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 13:11:39.574   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 13:11:39.580  4159  4159 D BluetoothMapAppObserver: onReceive
,08-17 13:11:39.580  4159  4159 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-17 13:11:39.586  3641  3641 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 13:11:39.588   875  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 13:11:39.588  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 13:11:39.594  2125  2298 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 13:11:39.602  1863  4249 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 13:11:39.610  1863  4249 I Decoder : createOrResetDecoder
,08-17 13:11:39.624   875  3921 I ActivityManager: Start proc 4252:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 13:11:39.631  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 13:11:39.649  1528  1528 I ConfigService: onCreate
,08-17 13:11:39.675  1863  4249 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 13:11:39.675  4252  4252 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 13:11:39.688   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 13:11:39.688   875  2012 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3801 uid 10000
08-17 13:11:39.689  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-17 13:11:39.728  1863  4249 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 13:11:39.729   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-17 13:11:39.729   875   887 E PackageManager: Failed to write settings, restoring backup
08-17 13:11:39.729   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-17 13:11:39.729   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 13:11:39.729   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 13:11:39.729   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 13:11:39.729   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 13:11:39.729   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.729   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.729   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.732  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 13:11:39.732  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-17 13:11:39.734  1938  2005 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 13:11:39.734   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-17 13:11:39.734   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 13:11:39.734   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:39.734   875   888 E DropBoxManagerService: 	... 13 more
08-17 13:11:39.735  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-17 13:11:39.735  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history,
08-17 13:11:39.737  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-17 13:11:39.744  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-17 13:11:39.748   875  1955 I ActivityManager: Start proc 4269:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-17 13:11:39.749  1938  2005 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 13:11:39.749  1938  2005 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-17 13:11:39.749  1938  2005 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.749  1938  2005 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.753   875  1928 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-17 13:11:39.753   875  4278 E DropBoxManagerService: Can't write: system_app_crash
08-17 13:11:39.753   875  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270),
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:39.753   875  4278 E DropBoxManagerService: 	... 5 more
,08-17 13:11:39.775  1938  2005 I Process : Sending signal. PID: 1938 SIG: 9
,08-17 13:11:39.780  4252  4252 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 13:11:39.782  1863  4249 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-17 13:11:39.782  1863  4249 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 13:11:39.782  1863  4249 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-17 13:11:39.783  1863  4249 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 13:11:39.783  1863  4249 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 13:11:39.783  1863  4249 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 13:11:39.818  4252  4283 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-17 13:11:39.822   875  1946 I ActivityManager: Start proc 4285:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-17 13:11:39.830   875  1304 W InputDispatcher: channel '205018a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-17 13:11:39.831   875  1304 E InputDispatcher: channel '205018a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-17 13:11:39.831   875   885 I WindowState: WIN DEATH: Window{205018a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 13:11:39.831   875   885 W InputDispatcher: Attempted to unregister already unregistered input channel '205018a com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,08-17 13:11:39.832   875  1954 D GraphicsStats: Buffer count: 1
08-17 13:11:39.842   875  1387 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1938) has died
08-17 13:11:39.843   875  1387 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-17 13:11:39.844   875  1387 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 13:11:39.857  4252  4266 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.857  4252  4266 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.858  4252  4266 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.860   875  1937 I ActivityManager: Start proc 4298:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 13:11:39.891  4285  4285 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-17 13:11:39.905  4298  4298 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:39.905  4298  4298 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 13:11:39.905  4298  4298 D AndroidRuntime: Shutting down VM
08-17 13:11:39.907  1528  1528 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-17 13:11:39.908  1528  1528 D AndroidRuntime: Shutting down VM
,08-17 13:11:39.909  1528  1528 E AndroidRuntime: FATAL EXCEPTION: main
08-17 13:11:39.909  1528  1528 E AndroidRuntime: Process: com.google.process.gapps, PID: 1528
08-17 13:11:39.909  1528  1528 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-17 13:11:39.909  1528  1528 E AndroidRuntime: 	... 8 more
,08-17 13:11:39.916  4298  4298 E AndroidRuntime: FATAL EXCEPTION: main
08-17 13:11:39.916  4298  4298 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4298
08-17 13:11:39.916  4298  4298 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 13:11:39.916  4298  4298 E AndroidRuntime: 	... 10 more
08-17 13:11:39.916   875  4313 E DropBoxManagerService: Can't write: system_app_crash
08-17 13:11:39.916   875  4313 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:39.916   875  4313 E DropBoxManagerService: 	... 5 more
,08-17 13:11:39.919  1528  1528 I Process : Sending signal. PID: 1528 SIG: 9
,08-17 13:11:39.921   875  1954 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 13:11:39.921  4298  4298 I Process : Sending signal. PID: 4298 SIG: 9
08-17 13:11:39.922   875  4314 E DropBoxManagerService: Can't write: system_app_crash
08-17 13:11:39.922   875  4314 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:39.922   875  4314 E DropBoxManagerService: 	... 5 more
,08-17 13:11:39.934   875   885 I ActivityManager: Killing 3693:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-17 13:11:39.963  4252  4266 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-17 13:11:39.967  4252  4283 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.967  4252  4283 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.967  4252  4283 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-17 13:11:39.967  4252  4283 E AndroidRuntime: Process: android.process.acore, PID: 4252
08-17 13:11:39.967  4252  4283 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:39.967  4252  4283 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:39.968  4252  4266 I Process : Sending signal. PID: 4252 SIG: 9
08-17 13:11:39.970   875  1315 D WifiService: Client connection lost with reason: 4
,08-17 13:11:39.970  1742  4310 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8797ea1
,08-17 13:11:39.981   875  3921 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4298) has died
,08-17 13:11:39.983   875  3921 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 13:11:39.987   875  1952 I ActivityManager: Process com.google.process.gapps (pid 1528) early provider death
08-17 13:11:39.987   875  1952 I ActivityManager: Process com.google.process.gapps (pid 1528) has died
08-17 13:11:39.987   875  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-17 13:11:39.987   875  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
,08-17 13:11:39.987   875  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-17 13:11:39.987   875  1952 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 30999ms
,08-17 13:11:39.988   875  4316 E DropBoxManagerService: Can't write: system_app_crash
08-17 13:11:39.988   875  4316 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:39.988   875  4316 E DropBoxManagerService: 	... 5 more
,08-17 13:11:40.003   875  1954 I ActivityManager: Start proc 4317:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-17 13:11:40.004   875  1387 W ActivityManager: Spurious death for ProcessRecord{5cd7446 0:com.google.process.gapps/u0a11}, curProc for 1528: null
,08-17 13:11:40.004  1742  1742 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-17 13:11:40.015   875   888 I ActivityManager: Start proc 4329:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 13:11:40.016   875  1955 I ActivityManager: Process android.process.acore (pid 4252) has died
,08-17 13:11:40.017   875  1955 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40970ms
,08-17 13:11:40.038  4317  4317 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-17 13:11:40.044  4317  4317 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-17 13:11:40.046  4317  4317 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:40.046  4317  4317 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 13:11:40.046  4317  4317 D AndroidRuntime: Shutting down VM
08-17 13:11:40.047  4317  4317 E AndroidRuntime: FATAL EXCEPTION: main
08-17 13:11:40.047  4317  4317 E AndroidRuntime: Process: com.google.process.gapps, PID: 4317
08-17 13:11:40.047  4317  4317 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
0,8-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-17 13:11:40.047  4317  4317 E AndroidRuntime: 	... 10 more
,08-17 13:11:40.050  4317  4317 I Process : Sending signal. PID: 4317 SIG: 9
08-17 13:11:40.052   875  4342 E DropBoxManagerService: Can't write: system_app_crash
08-17 13:11:40.052   875  4342 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 13:11:40.052   875  4342 E DropBoxManagerService: 	... 5 more

```
