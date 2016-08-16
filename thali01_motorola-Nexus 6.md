#### Test 81492074ffbc155_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 17:43:39.489   872  1880 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121900, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 17:43:40.203  3865  3865 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 17:43:40.208  3865  3865 D AndroidRuntime: CheckJNI is OFF
08-16 17:43:40.244  3865  3865 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 17:43:40.286  3865  3865 I Radio-JNI: register_android_hardware_Radio DONE
08-16 17:43:40.306  3865  3865 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 17:43:40.311   872  2012 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 17:43:40.360  1993  2008 W SearchService: Abort, client detached.
08-16 17:43:40.364  3865  3865 D AndroidRuntime: Shutting down VM
08-16 17:43:40.366  1993  1993 I HotwordDetector: Closing mic
08-16 17:43:40.367  1993  2309 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@501baae
08-16 17:43:40.367  1993  2323 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 17:43:40.398   872  3133 I ActivityManager: Start proc 3875:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 17:43:40.428   374  2325 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 17:43:40.430   374  2325 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 17:43:40.435   374  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 17:43:40.436  1993  2321 I MicroRecognitionRnrImpl: Detection finished
08-16 17:43:40.436  1993  2314 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 17:43:40.480  3875  3875 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 17:43:40.500  3875  3875 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 17:43:40.508  3875  3875 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2915-2920)
08-16 17:43:40.508  3875  3875 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:43:40.530  3875  3875 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b7d53f1}
08-16 17:43:40.530  3875  3875 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:43:40.530  3875  3875 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:43:40.536  3875  3875 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 17:43:40.537  3875  3875 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 17:43:40.575  3875  3875 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 17:43:40.592  3875  3875 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:43:40.592  3875  3875 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:43:40.592  3875  3875 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:43:40.592  3875  3875 I Adreno  : Build Date                       : 10/20/15
08-16 17:43:40.592  3875  3875 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:43:40.592  3875  3875 I Adreno  : Local Branch                     : M14
08-16 17:43:40.592  3875  3875 I Adreno  : Remote Branch                    : 
08-16 17:43:40.592  3875  3875 I Adreno  : Remote Branch                    : 
08-16 17:43:40.592  3875  3875 I Adreno  : Reconstruct Branch               : 
,08-16 17:43:40.675   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a9095e:true
,08-16 17:43:40.720  3875  3875 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 17:43:40.739  3875  3875 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 17:43:40.758   872  1317 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 17:43:40.807  3875  3913 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 17:43:40.816  3875  3900 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 17:43:40.856  3875  3913 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:43:40.924   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +551ms
,08-16 17:43:40.931  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 17:43:40.980  3875  3875 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3875
,08-16 17:43:41.112  3875  3875 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:43:41.192   872   883 I ActivityManager: Killing 3052:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 17:43:41.228   872   883 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-16 17:43:41.333  3875  3916 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1690629840
,08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 17:43:41.349  3875  3916 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a72199c added. We now have 1 listener(s)
,08-16 17:43:41.354  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 17:43:41.356  3875  3916 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:43:41.357  3875  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:41.357  3875  3916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 17:43:41.364  3875  3916 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5aad32b added. We now have 1 listener(s)
08-16 17:43:41.364  3875  3916 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:41.367   872  1318 D WifiService: New client listening to asynchronous messages
,08-16 17:43:41.368  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:41.368  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
,08-16 17:43:41.371  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 17:43:41.371  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 17:43:41.371  3875  3916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:43:41.377  3875  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:41.377  3875  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-16 17:43:41.385  3875  3916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:41.385  3875  3916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:41.386  3875  3916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:43:41.386  3875  3916 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:41.388  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:41.388  3875  3916 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:43:41.390  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:41.535  3875  3875 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:43:42.215  3875  3923 W jxcore-log: Initializing JXcore engine
,08-16 17:43:42.216  3875  3923 W jxcore-log: JXcore engine is ready
,08-16 17:43:42.252  3923  3923 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8930 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 17:43:42.252  3923  3923 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12124]" dev="sockfs" ino=12124 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 17:43:42.252  3923  3923 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 17:43:42.252  3923  3923 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26898]" dev="sockfs" ino=26898 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 17:43:42.270  3875  3923 W jxcore-log: Starting JXcore engine
,08-16 17:43:42.350  3875  3923 W jxcore-log: Platform android
08-16 17:43:42.350  3875  3923 W jxcore-log: 
,08-16 17:43:42.350  3875  3923 W jxcore-log: Process ARCH arm
08-16 17:43:42.350  3875  3923 W jxcore-log: 
,08-16 17:43:42.620  3875  3923 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:43:42.620  3875  3923 I jxcore-log: 
,08-16 17:43:42.621  3875  3923 W jxcore-log: JXcore engine is started
,08-16 17:43:42.630  3875  3916 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:43:42.633  3875  3875 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:43:45.334  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:43:45.336  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:43:45.356  1532  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:43:45.356  1532  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:43:45.356  1532  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:43:45.356  1532  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:45.369  2985  3927 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:43:45.369  2985  3927 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:43:45.369  2985  3927 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	... 12 more
08-16 17:43:45.369  2985  3927 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at fal.a(PG:38)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:43:45.369  2985  3927 E HttpOperation: 	... 14 more
,08-16 17:43:45.439  1532  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-16 17:43:45.439  1532  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:43:45.439  1532  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:43:45.440  1532  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:45.453  2985  3927 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:43:45.453  2985  3927 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at hec.a(PG:42)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at hee.a(PG:102)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at czr.a(PG:65)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at kka.a(PG:108)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:43:45.453  2985  3927 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	... 15 more
08-16 17:43:45.453  2985  3927 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at fal.a(PG:38)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:43:45.453  2985  3927 E HttpOperation: 	... 17 more
,08-16 17:43:45.453  2985  3927 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:43:45.453  2985  3927 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	... 15 more
08-16 17:43:45.453  2985  3927 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:43:45.453  2985  3927 E ExperimentLoader: 	... 17 more
,08-16 17:43:45.554   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 127511, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:43:45.582  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:43:45.616  1532  2054 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 17:43:45.616  1532  2054 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 17:43:45.617  1532  2054 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:43:45.617  1532  2054 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:45.640  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 17:43:45.640  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 17:43:45.640  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 17:43:52.904  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:43:52.904  3875  3923 I jxcore-log: 
,08-16 17:43:52.907  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:43:52.907  3875  3923 I jxcore-log: 
,08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:52.920  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:52.924  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:52.926  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:43:52.926  3875  3923 I jxcore-log: 
,08-16 17:43:52.928  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:43:52.928  3875  3923 I jxcore-log: 
,08-16 17:43:53.257  3875  3923 D ExecuteNativeTests: Running unit tests
,08-16 17:43:53.316  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:53.316  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 added. We now have 2 listener(s)
,08-16 17:43:53.317  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:43:53.317  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:43:53.317  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:53.317  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:43:53.318  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be added. We now have 2 listener(s)
08-16 17:43:53.318  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:53.319  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:43:53.324  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.336  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:53.340  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:53.340  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:53.342  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:43:53.342  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:53.342  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:53.343  3875  3923 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 17:43:53.344  3875  3923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:53.344  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:53.344  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:53.344  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:53.344  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.345  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.346  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.346  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.346  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.346  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:53.346  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:53.347  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 removed from the list
,08-16 17:43:53.347  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.347  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be removed from the list
08-16 17:43:53.348  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.349  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.349  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:53.350  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:53.350  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:53.357  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:53.357  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.358  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:53.358  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
,08-16 17:43:53.364  3875  3923 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 17:43:53.365  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.366  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.366  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.367  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:53.367  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:43:53.367  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.367  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.368  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.368  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.368  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.368  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.369  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.369  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.369  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.369  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:53.371  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.372  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:43:53.372  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.372  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
,08-16 17:43:53.380  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:53.381  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:53.382  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:53.383  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:53.383  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.383  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.383  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.383  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.383  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:53.383  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.383  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.383  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.383  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.383  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.383  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.383  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.383  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.384  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.385  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.385  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.385  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.385  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
,08-16 17:43:53.386  3875  3923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:43:53.387  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.395  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:53.396  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.397  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:53.397  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:53.397  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:53.397  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:53.397  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:53.397  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:53.399  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.402  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:43:53.402  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:43:53.403  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.409  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:53.411  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:43:53.411  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:53.416  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 17:43:53.419  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:53.419  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:53.419  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:53.420  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:43:53.421  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:43:53.426  2606  2619 D BtGatt.GattService: registerClient() - UUID=a8266ff5-9b78-43cb-9bb3-61c0147c4e0e
,08-16 17:43:53.427  2606  2638 D BtGatt.GattService: onClientRegistered() - UUID=a8266ff5-9b78-43cb-9bb3-61c0147c4e0e, clientIf=5
,08-16 17:43:53.428  3875  3886 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:43:53.429  2606  2717 D BtGatt.GattService: start scan with filters
,08-16 17:43:53.434  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-16 17:43:53.434  2606  2643 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:53.434  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:53.434  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:43:53.434  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:43:53.436  2606  2643 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:43:53.437  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:53.438  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:53.438  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:53.439  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:53.444  2606  2638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:43:53.444  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.445  2606  2643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:43:53.445  3875  3923 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:53.449  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:53.450  3875  3923 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:53.450  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:53.450  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:53.450  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:43:53.450  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:43:53.451  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:53.451  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:43:53.452  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:43:53.452  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:53.452  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-16 17:43:53.452  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.453  2606  2643 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:53.453  2606  2643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:43:53.454  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:53.454  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:43:53.455  3875  3923 D BluetoothAdapter: STATE_ON
08-16 17:43:53.456  2606  2717 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:43:53.457  2606  2718 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-16 17:43:53.457  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:53.457  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:53.458  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:53.458  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:53.458  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:43:53.460  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.460  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:43:53.460  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:53.461  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:43:53.462  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:53.463  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:53.463  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:53.464  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.464  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.464  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.464  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:53.464  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.464  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.465  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.466  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.466  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.466  3875  3923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:43:53.466  2606  2638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:43:53.466  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.470  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.476  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:53.477  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:43:53.477  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.480  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:53.480  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:53.481  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:43:53.481  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:53.481  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:43:53.481  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.481  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:53.484  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.485  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:43:53.485  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:43:53.486  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.487  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:43:53.487  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.487  2606  2643 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:53.491  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:53.492  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:43:53.492  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:53.494  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:43:53.494  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.494  2606  2643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:43:53.497  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:43:53.497  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:53.497  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:53.498  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:43:53.501  2606  2638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:43:53.501  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.501  2606  2717 D BtGatt.GattService: registerClient() - UUID=ac83764e-af09-4b94-b9a7-1f5f281ecc27
,08-16 17:43:53.503  2606  2638 D BtGatt.GattService: onClientRegistered() - UUID=ac83764e-af09-4b94-b9a7-1f5f281ecc27, clientIf=5
08-16 17:43:53.503  3875  3887 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:43:53.504  2606  2718 D BtGatt.GattService: start scan with filters
,08-16 17:43:53.509  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:43:53.509  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:53.509  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:53.509  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:43:53.509  2606  2643 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:53.513  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:53.513  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:43:53.513  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:53.516  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:53.516  2606  2638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:43:53.516  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.517  2606  2643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:43:53.519  3875  3923 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:53.523  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:53.523  3875  3923 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:53.523  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:43:53.523  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.523  2606  2643 D BtGatt.ScanManager: Starting BLE batch scan,
08-16 17:43:53.523  2606  2643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:43:53.524  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:53.524  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:43:53.524  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.524  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:53.524  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:43:53.524  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:53.524  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:43:53.524  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:53.525  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:43:53.525  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:53.526  3875  3923 D BluetoothAdapter: STATE_ON
08-16 17:43:53.526  2606  2717 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:43:53.527  2606  2718 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:43:53.528  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:53.528  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:43:53.528  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:53.528  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:53.528  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:53.529  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.529  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:53.530  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:43:53.530  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:43:53.530  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:53.532  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:53.532  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:53.532  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.532  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:43:53.532  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.533  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:53.533  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.533  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.533  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
,08-16 17:43:53.536  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.536  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:53.536  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:53.536  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.537  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.537  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.537  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:43:53.537  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list,
08-16 17:43:53.538  3875  3923 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:43:53.539  2606  2638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:43:53.539  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 17:43:53.540  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.547  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:53.547  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:43:53.547  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:43:53.550  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:53.550  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:53.551  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:43:53.552  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:53.552  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:53.552  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:53.552  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:43:53.553  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.556  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:43:53.556  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:53.557  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.557  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:43:53.557  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.558  2606  2643 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:53.562  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:53.563  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:43:53.563  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:53.567  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:43:53.567  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.568  2606  2643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:43:53.568  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:53.569  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:53.569  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:43:53.570  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:43:53.573  2606  2718 D BtGatt.GattService: registerClient() - UUID=0317a885-cce4-4aa9-b6ec-edfb1fe977aa
,08-16 17:43:53.574  2606  2638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:43:53.574  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.574  2606  2638 D BtGatt.GattService: onClientRegistered() - UUID=0317a885-cce4-4aa9-b6ec-edfb1fe977aa, clientIf=5
08-16 17:43:53.575  3875  3886 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:43:53.575  2606  2617 D BtGatt.GattService: start scan with filters
,08-16 17:43:53.579  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:43:53.579  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:43:53.579  2606  2643 D BtGatt.ScanManager: handling starting scan
08-16 17:43:53.579  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:53.579  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:53.583  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:43:53.584  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:53.584  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:53.587  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:43:53.587  2606  2638 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:43:53.587  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.588  2606  2643 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:43:53.591  3875  3923 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:53.591  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.591  3875  3923 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:53.591  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.591  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:53.591  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.591  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:53.592  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:53.592  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:53.592  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:43:53.592  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:43:53.592  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:53.592  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:53.593  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:43:53.595  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:43:53.595  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.595  2606  2643 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:53.596  2606  2643 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:43:53.600  2606  2617 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:53.601  2606  2717 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:43:53.602  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:53.602  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:53.602  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:53.602  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 17:43:53.602  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:43:53.604  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.604  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:43:53.604  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:43:53.604  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:43:53.605  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:53.607  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:43:53.607  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:53.607  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:53.608  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:53.608  3875  3923 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:53.608  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.609  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:43:53.609  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.609  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.609  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:53.609  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.610  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.610  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.610  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.610  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.611  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.611  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.613  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.613  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.613  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.613  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.614  3875  3923 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:43:53.615  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.616  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.616  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.616  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.616  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.617  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.617  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.617  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.617  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.617  2606  2638 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:43:53.617  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.617  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.617  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.617  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetoot,hManager: release: 1 listener(s) left
08-16 17:43:53.617  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.618  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.619  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.619  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.620  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.620  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.622  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:43:53.622  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.622  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.622  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.623  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.623  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.623  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.623  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.623  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.623  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.623  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.624  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.624  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.624  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.624  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.625  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:43:53.625  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.625  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.625  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.626  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.626  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.626  3875  3923 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:43:53.626  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.627  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.627  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.627  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.627  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.627  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.627  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.627  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.627  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.627  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.627  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.628  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.628  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.628  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.629  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.629  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.629  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.629  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.630  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:43:53.630  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.630  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.630  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.630  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.630  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.630  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.630  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.630  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.630  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.631  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.631  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.631  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.631  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.631  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.632  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.632  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.632  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.632  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.633  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:43:53.633  2606  2638 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:43:53.634  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.634  2606  2643 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:43:53.634  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:53.634  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:53.634  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:53.635  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:43:53.635  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:53.635  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.635  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.635  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.635  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.635  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.635  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.636  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.636  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.636  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.636  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.636  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.636  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.636  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.636  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.637  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.637  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.637  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.637  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.638  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:53.638  3875  3923 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:43:53.638  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:53.642  2606  2638 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:43:53.642  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.643  2606  2643 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:43:53.645  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:53.647  3875  3923 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:43:53.647  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:43:53.647  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:53.647  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:43:53.647  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:43:53.648  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:43:53.649  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:43:53.649  2606  2638 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:43:53.650  2606  2638 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:53.650  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:53.651  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:43:53.651  3875  3923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:53.651  3875  3923 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:43:53.652  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:53.652  3875  3923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:53.652  3875  3923 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:43:53.652  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:53.652  3875  3923 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:53.652  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:53.655  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:43:53.656  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:43:53.656  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:43:53.657  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:43:53.657  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:43:53.657  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:43:53.657  3875  3923 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:53.657  3875  3923 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:43:53.658  3875  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-16 17:43:53.658  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.658  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.658  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.658  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.658  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.659  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.659  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-16 17:43:53.660  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.660  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.660  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.660  3875  3940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:43:53.660  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.660  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.661  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.661  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.661  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.661  3875  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-16 17:43:53.661  3875  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
08-16 17:43:53.662  3875  3941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
08-16 17:43:53.662  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.662  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.662  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.662  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.663  3875  3923 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:43:53.663  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.663  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.663  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.663  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.663  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.664  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.664  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.664  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.664  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.664  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.664  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.665  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.665  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.665  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.666  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.666  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.666  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.666  3875  3940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-16 17:43:53.666  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.666  3875  3923 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:43:53.667  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.667  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.667  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.667  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.667  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.667  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.667  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.667  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.667  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.667  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.667  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.667  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.667  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.668  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.668  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.668  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.669  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.669  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.669  3875  3923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:43:53.669  3875  3923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:43:53.669  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:53.669  3875  3923 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:43:53.669  3875  3923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:53.670  3875  3923 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:43:53.670  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:53.670  3875  3923 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:43:53.670  3875  3923 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:53.670  3875  3923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:43:53.670  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:53.670  3875  3923 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:43:53.670  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.670  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.670  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.670  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.670  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.670  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.671  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.671  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.671  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.671  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.671  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.671  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.671  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.671  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.672  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.672  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.672  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.672  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.673  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.673  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.673  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.673  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.673  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.673  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.673  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.673  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.673  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.673  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.673  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.673  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.673  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.673  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.673  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.674  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.674  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.674  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.674  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.674  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.674  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.674  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.674  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.674  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.674  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.674  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.674  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.674  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.674  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.675  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.676  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.676  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.676  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.677  3875  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:43:53.677  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:53.678  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:43:53.678  3875  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:43:53.678  3875  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:43:53.679  3875  3875 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:43:53.679  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:43:53.679  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:53.681  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.681  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:43:53.681  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:43:53.681  3875  3942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:43:53.681  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:43:53.681  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.681  3875  3923 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:43:53.681  3875  3875 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:43:53.681  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.682  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.682  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:53.682  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:53.682  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:53.682  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.682  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.683  3875  3942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:43:53.683  3875  3942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:43:53.683  3875  3942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:43:53.684  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.684  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:53.684  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.684  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:53.684  3875  3875 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:43:53.684  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.684  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:53.684  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.684  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.685  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.685  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.685  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.685  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.685  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.685  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.685  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.685  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.685  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.686  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.686  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.688  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.688  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.688  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.688  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.689  3875  3923 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:43:53.690  3875  3923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:53.690  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:53.690  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:53.690  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.690  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.690  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.690  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.690  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.691  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.691  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.691  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.691  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.691  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.691  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.691  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.691  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.691  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.693  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.693  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.693  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.693  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
,08-16 17:43:53.697  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.697  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.697  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.697  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.698  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.698  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.698  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.698  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.698  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.698  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.698  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.698  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.698  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.699  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.700  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.700  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.700  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.700  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.701  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:53.701  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:53.701  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:53.702  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:53.702  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.702  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.702  3875  3923 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@662f379 not in the list
08-16 17:43:53.702  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.702  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.702  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:53.702  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.702  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.703  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:53.703  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:53.704  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:53.704  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:53.704  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:53.704  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e6b8be not in the list
08-16 17:43:53.706  3875  3923 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:43:53.706  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:53.706  3875  3923 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:43:53.706  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:53.706  3875  3923 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:43:53.706  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:53.708   872   881 I art     : Background partial concurrent mark sweep GC freed 39931(2MB) AllocSpace objects, 11(236KB) LOS objects, 33% free, 29MB/43MB, paused 1.331ms total 114.492ms
08-16 17:43:53.711  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:43:53.711  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:43:53.712  3875  3923 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:43:53.712  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:53.712  3875  3923 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:43:53.712  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:53.712  3875  3923 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:43:53.712  3875  3923 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:43:53.713  3875  3923 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:43:53.714  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:53.714  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe8c170 added. We now have 2 listener(s)
08-16 17:43:53.714  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:53.716  3875  3923 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:43:53.716   872  2012 D WifiService: setWifiEnabled: true pid=3875, uid=10000
08-16 17:43:53.716   872  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:43:53.717  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:53.717  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daaace9 added. We now have 3 listener(s)
08-16 17:43:53.717  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:53.723  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:53.723  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@790cd6e added. We now have 4 listener(s)
08-16 17:43:53.723  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:53.724  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:53.724  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8532c0f added. We now have 5 listener(s)
08-16 17:43:53.724  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:53.727   872  3133 D WifiService: setWifiEnabled: false pid=3875, uid=10000
08-16 17:43:53.727   872  3133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 17:43:53.730  2606  2634 D BluetoothAdapterState: Current state: ON, message: 23
08-16 17:43:53.730  2606  2634 D BluetoothAdapterProperties: Setting state to 13
08-16 17:43:53.730  2606  2634 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:43:53.731  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:53.732  2606  2634 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:43:53.733  2606  2606 D BluetoothMapService: onReceive
08-16 17:43:53.733  2606  2606 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:53.733  2606  2606 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:43:53.733  2606  2606 D BluetoothMapService: MAP Service closeService in
08-16 17:43:53.733  2606  2606 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 17:43:53.733  2606  2606 D ObexServerSockets0: shutdown(block = true)
08-16 17:43:53.735  2606  2634 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:43:53.736  2606  2720 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 17:43:53.736  2606  2606 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:43:53.736  2606  2606 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:43:53.736  2606  2721 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 17:43:53.737  2606  2606 I BtOppRfcommListener: stopping Accept Thread
08-16 17:43:53.737  2606  2706 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:43:53.737  2606  3403 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:43:53.737  2606  3403 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:43:53.738  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 17:43:53.738  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.738  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:53.739  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.739  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.740   872  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:43:53.740   872  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 17:43:53.740   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:43:53.740   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:43:53.740  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:53.743  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.745  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.747   872  1883 D DhcpClient: Clearing IP address
08-16 17:43:53.747   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:53.747  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:53.747  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:53.748  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.748  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:53.750   370   870 D CommandListener: Setting iface cfg
08-16 17:43:53.750  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.752   872  1884 D DhcpClient: Receive thread stopped
,08-16 17:43:53.756  1532  2088 V NativeCrypto: Read error: ssl=0xaedb6c00: I/O error during system call, Connection timed out
,08-16 17:43:53.757  1532  2088 V NativeCrypto: SSL shutdown failed: ssl=0xaedb6c00: I/O error during system call, Broken pipe
,08-16 17:43:53.760   872   885 I ActivityManager: Start proc 3948:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-16 17:43:53.760  2606  2638 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:53.760   872   882 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-16 17:43:53.761  2606  2634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 17:43:53.761   872  1878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-16 17:43:53.766  2606  2606 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:43:53.766  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.769  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.770   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 17:43:53.770   872   872 D BluetoothHeadset: Proxy object disconnected
,08-16 17:43:53.770   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 17:43:53.771  1373  1385 D BluetoothHeadset: Proxy object disconnected
08-16 17:43:53.771  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-16 17:43:53.771  1924  2055 D BluetoothHeadset: Proxy object disconnected
08-16 17:43:53.772   872  1878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-16 17:43:53.772  2606  2606 D A2dpService: Received stop request...Stopping profile...
08-16 17:43:53.772  2606  2711 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:43:53.772   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-16 17:43:53.772   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-16 17:43:53.773   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
08-16 17:43:53.775  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:53.775   872   872 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:53.776  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.776  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.776  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:43:53.776  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:43:53.776  2606  2606 D HidService: Received stop request...Stopping profile...
08-16 17:43:53.777   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:43:53.777   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 17:43:53.776  2606  2606 D HidService: Stopping Bluetooth HidService
08-16 17:43:53.779   394   394 E Parcel  : Reading a NULL string not supported here.
,08-16 17:43:53.779   872  1317 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-16 17:43:53.780   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:43:53.782   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:53.787   872  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-16 17:43:53.788  2606  2606 D HealthService: Received stop request...Stopping profile...
,08-16 17:43:53.790  2606  2606 D PanService: Received stop request...Stopping profile...
,08-16 17:43:53.792   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:43:53.794  2606  2606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:43:53.794  2606  2606 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:43:53.794  2606  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 17:43:53.794  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.794  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.794  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.794  2606  2638 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 17:43:53.794  2606  2606 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:43:53.794  2606  2606 D BluetoothMapService: stop()
08-16 17:43:53.795  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:53.795  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:53.796  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-16 17:43:53.796  1373  1373 D HidProfile: Bluetooth service disconnected
08-16 17:43:53.796  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:53.796  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:53.797  2606  2606 D BluetoothMapAppObserver: deinitObservers()
08-16 17:43:53.797  2606  2606 D BluetoothMapAppObserver: removeReceiver()
08-16 17:43:53.798  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:53.798  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:53.798  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:53.799  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:53.799  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.799  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.800  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:43:53.800  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:43:53.800  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:43:53.801  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.801  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.801  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:43:53.801  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:43:53.801  1373  1373 D PanProfile: Bluetooth service disconnected
08-16 17:43:53.801  2606  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 17:43:53.801  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.801  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.801  2606  2606 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:43:53.801  2606  2699 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:53.801  2606  2699 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:53.801  2606  2638 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:43:53.801  2606  2699 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:53.801  2606  2699 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:53.802  2606  2606 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:43:53.802  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.802  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.802  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:43:53.802  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:43:53.803  2606  2606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:43:53.803  2606  2638 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 17:43:53.803  2606  2606 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:43:53.803  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.803  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.803  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false,
08-16 17:43:53.803  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:43:53.804  2606  2606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:43:53.804  2606  2606 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:43:53.804  2606  2606 D BluetoothMapService: MAP Service closeService in
08-16 17:43:53.804  2606  2606 V BluetoothAdapterState: isTurningOff()=true
08-16 17:43:53.804  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:53.804  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:43:53.805  2606  2606 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:43:53.805   872  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:43:53.805  2606  2634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 17:43:53.805  2606  2634 D BluetoothAdapterProperties: Setting state to 15
08-16 17:43:53.805  2606  2634 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:43:53.806  1373  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:53.806   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:43:53.806  1373  3874 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:43:53.806  2606  2634 I BluetoothAdapterState: Entering BleOnState
08-16 17:43:53.806   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:53.807  1924  2055 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:43:53.807   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:43:53.807  2606  2606 D BluetoothMapService: cleanup()
08-16 17:43:53.807  2606  2606 D BluetoothMapService: MAP Service closeService in
08-16 17:43:53.807  1373  2017 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:43:53.808   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:43:53.808  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:43:53.808  1373  3874 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:43:53.808  2089  2336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:53.809  1373  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:43:53.809  2606  2634 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 17:43:53.809  2606  2634 D BluetoothAdapterProperties: Setting state to 16
08-16 17:43:53.809  2606  2634 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:43:53.810  2606  2634 D BluetoothAdapterProperties: onBleDisable
08-16 17:43:53.810  2606  2634 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:43:53.810  2606  2635 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 17:43:53.814  2606  2699 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:43:53.814  2606  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:43:53.814  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.814  2606  2638 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:43:53.815  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.816  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.816  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.819   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 17:43:53.828  3948  3948 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-16 17:43:53.840  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:43:53.842   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-16 17:43:53.843   872  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 17:43:53.843   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:53.845   872   889 D Tethering: MasterInitialState.processMessage what=3
08-16 17:43:53.849  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:43:53.850  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:53.852  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:53.855  3405  3405 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@10a9fa5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 17:43:53.858   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@65c3edf:true
,08-16 17:43:53.862   872  2106 I ActivityManager: Start proc 3967:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 17:43:53.869  3948  3948 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 17:43:53.870  3948  3948 D BluetoothMap: Create BluetoothMap proxy object
,08-16 17:43:53.875  3948  3948 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 17:43:53.881  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:53.885   872  1386 I ActivityManager: Killing 3405:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 17:43:53.899   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:43:53.900  3967  3967 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-16 17:43:53.900   872  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 17:43:53.900   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:43:54.022  2606  2638 I bt_hci  : shut_down
,08-16 17:43:54.042  2606  2644 I bt_vendor: low_power_mode_cb
,08-16 17:43:54.048  2606  2644 D bt_hwcfg: hw_epilog_process
,08-16 17:43:54.066  2606  2644 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:43:54.066  2606  2644 I bt_vendor: epilog_cb
,08-16 17:43:54.066  2606  2644 I bt_hci  : epilog_finished_callback
,08-16 17:43:54.072  2606  2638 I bt_hci_h4: hal_close
,08-16 17:43:54.073  2606  2638 I bt_userial_vendor: device fd = 51 close
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
,08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.123  3967  3967 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:43:54.123  3967  3967 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:43:54.162   872  2012 I ActivityManager: Start proc 4000:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 17:43:54.163   872  2012 I ActivityManager: Killing 3558:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 17:43:54.185  3875  3875 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:43:54.254  2606  2635 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:43:54.255  2606  2634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 17:43:54.260  2606  2606 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:54.261  2606  2606 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 17:43:54.261  2606  2606 D BtGatt.GattService: stop()
,08-16 17:43:54.261  2606  2634 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:43:54.261  2606  2606 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:43:54.263  2606  2606 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:43:54.263  2606  2606 V BluetoothAdapterState: isTurningOn()=false
08-16 17:43:54.264  2606  2606 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:43:54.264  2606  2606 V BluetoothAdapterState: isBleTurningOff()=true
08-16 17:43:54.264  2606  2634 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 17:43:54.265  2606  2634 D BluetoothAdapterProperties: Setting state to 10
,08-16 17:43:54.265  2606  2634 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 17:43:54.268   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-16 17:43:54.268  4000  4000 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 17:43:54.268  2606  2634 I BluetoothAdapterState: Entering OffState
,08-16 17:43:54.287  2606  2606 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 17:43:54.287  2606  2606 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 17:43:54.287  2606  2606 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:43:54.288  2606  2635 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 17:43:54.291  2606  2635 D bt_stack_manager: event_clean_up_stack finished.
,08-16 17:43:54.299  2606  2606 I art     : System.exit called, status: 0
,08-16 17:43:54.299  2606  2606 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:43:54.354   872  1722 I ActivityManager: Process com.android.bluetooth (pid 2606) has died
,08-16 17:43:54.533  4000  4020 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 17:43:54.533  4000  4020 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 17:43:54.541  4000  4020 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 17:43:54.541  4000  4020 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 17:43:54.642  4000  4020 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 17:43:54.642  4000  4020 I Babel_SMS: MmsConfig.loadFromResources
,08-16 17:43:54.655  4000  4020 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:43:54.656  4000  4020 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 17:43:54.675  4000  4000 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:54.682  4000  4000 I Babel_Crash: startup - clean
,08-16 17:43:54.707  3967  3996 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:43:54.710  4000  4000 I Babel_telephony: TeleModule.launchCompleted
,08-16 17:43:54.720   872  1386 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 17:43:54.728  4000  4000 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 17:43:54.735  4000  4000 W Babel   : BAM#gBA: invalid account id: -1
,08-16 17:43:54.735  4000  4000 W Babel   : BAM#gBA: invalid account id: -1
,08-16 17:43:54.735  4000  4000 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 17:43:54.747  4000  4025 I Babel   : deleted: false for 0
,08-16 17:43:54.757   872  2258 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 17:43:54.805   872  3133 I ActivityManager: Start proc 4027:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-16 17:43:54.810  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:54.912  4027  4027 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 17:43:54.945  4000  4000 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:43:54.951  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:54.958  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:54.974  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:54.986  4000  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:54.993   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@104e0b7:true
,08-16 17:43:54.996  4000  4000 I vclib   : onServiceConnected
,08-16 17:43:55.006  4027  4027 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 17:43:55.032  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:55.074   872  2012 I ActivityManager: Start proc 4052:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 17:43:55.075  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:55.079   872  1722 I ActivityManager: Killing 3584:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-16 17:43:55.181  4052  4052 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:43:55.182  4052  4052 D AdapterServiceConfig: Adding A2dpService
,08-16 17:43:55.183  4052  4052 D AdapterServiceConfig: Adding HidService
08-16 17:43:55.184  4052  4052 D AdapterServiceConfig: Adding HealthService
,08-16 17:43:55.184  4052  4052 D AdapterServiceConfig: Adding PanService
,08-16 17:43:55.185  4052  4052 D AdapterServiceConfig: Adding GattService
08-16 17:43:55.185  4052  4052 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 17:43:55.190   872  1723 I ActivityManager: Killing 3455:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 17:43:55.223  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:55.247  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:43:55.251  1753  1753 D SystemUpdateService: onCreate
,08-16 17:43:55.253  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:43:55.260  1753  4064 I SystemUpdateService: active receiver: enabled
,08-16 17:43:55.269  1753  4064 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:43:55.270  1753  4064 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 17:43:55.270  1753  4064 I SystemUpdateService: now status is 0 (complete)
,08-16 17:43:55.270  1753  4064 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:43:55.271  1753  4064 I SystemUpdateService: file has been verified
08-16 17:43:55.271  1753  4064 I SystemUpdateService: OTA package size = 12249756
,08-16 17:43:55.274  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:43:55.278  1753  2422 I iu.UploadsManager: num queued entries: 0
,08-16 17:43:55.280  1753  2422 I iu.UploadsManager: num updated entries: 0
,08-16 17:43:55.281  1753  4064 I SystemUpdateService: showing system update notification
,08-16 17:43:55.287  1753  2422 I iu.SyncManager: NEXT; no task
,08-16 17:43:55.296  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:43:55.300  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:43:55.322   872   883 I ActivityManager: Start proc 4066:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 17:43:55.324  1753  1753 D SystemUpdateService: onDestroy
,08-16 17:43:55.357  4066  4066 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 17:43:55.360  4066  4066 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:55.365  4066  4066 D SprintDMHelper: simOperator: 
08-16 17:43:55.365  4066  4066 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:43:55.386   872   883 I ActivityManager: Start proc 4078:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 17:43:55.387   872   883 I ActivityManager: Killing 3490:android.process.acore/u0a5 (adj 15): empty #17
,08-16 17:43:55.526   872  1722 I ActivityManager: Start proc 4093:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 17:43:55.529  4000  4092 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 17:43:55.536   872  1723 I ActivityManager: Killing 3661:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 17:43:55.597  4093  4093 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 17:43:55.657  4093  4093 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 17:43:55.657  4093  4093 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:43:55.657  4093  4093 I GAv4    :   adb logcat -s GAv4
,08-16 17:43:55.678  4093  4093 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:55.686  4093  4093 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:55.718  4093  4110 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:43:55.832  4093  4093 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 17:43:55.869  4093  4093 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 17:43:55.877  4093  4093 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8286-8289)
,08-16 17:43:55.877  4093  4093 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:43:55.891  4093  4093 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f9bbc15}
,08-16 17:43:55.892  4093  4093 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:43:55.893  4093  4093 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:43:55.904  4093  4093 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:43:55.906  4093  4093 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:43:55.924  4093  4093 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 17:43:55.941  4093  4093 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:43:55.941  4093  4093 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:43:55.942  4093  4093 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:43:55.942  4093  4093 I Adreno  : Build Date                       : 10/20/15
08-16 17:43:55.942  4093  4093 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:43:55.942  4093  4093 I Adreno  : Local Branch                     : M14
08-16 17:43:55.942  4093  4093 I Adreno  : Remote Branch                    : 
08-16 17:43:55.942  4093  4093 I Adreno  : Remote Branch                    : 
08-16 17:43:55.942  4093  4093 I Adreno  : Reconstruct Branch               : 
,08-16 17:43:55.998  4093  4139 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 17:43:56.016  4093  4093 I NSApplication: Starting up...
,08-16 17:43:56.054   872  1723 I ActivityManager: Start proc 4144:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 17:43:56.055   872  1723 I ActivityManager: Killing 3676:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 17:43:56.123  4144  4144 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 17:43:56.338   872  2258 I ActivityManager: Killing 2211:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 17:43:56.743   872   883 D WifiService: setWifiEnabled: true pid=3875, uid=10000
,08-16 17:43:56.743   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:43:56.760   872  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:43:56.768  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:56.769  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:56.769  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:56.769  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:56.773  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:56.773  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:56.774  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:56.774  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:56.793   872  1317 D WifiConfigStore: loaded 0 passpoint configs
,08-16 17:43:56.794   872  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 17:43:56.795   872  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 17:43:56.796   872  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:43:56.796   872  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 17:43:56.797   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 17:43:56.797   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 17:43:56.813   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 17:43:56.815   872  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=12.00 rxSuccessRate=16.38 delta 1000 -> 994
,08-16 17:43:56.816   370   870 D CommandListener: Setting iface cfg
,08-16 17:43:56.817   872  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 17:43:56.817   872  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:43:56.823   872  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:43:56.829   872  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:43:56.833   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 17:43:56.834   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:56.871   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:43:56.937   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:43:56.942  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:43:57.358  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:43:57.402  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:43:57.404  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 17:43:57.410   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:43:57.429   872  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:43:57.430   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:43:57.430   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:43:57.457   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:57.473   370   870 D CommandListener: Setting iface cfg
,08-16 17:43:57.474   872  1317 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:43:57.496   872  1319 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-16 17:43:57.499   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:43:57.504   872  4170 D DhcpClient: Receive thread started
,08-16 17:43:57.590   872  1317 E native  : do suspend false
,08-16 17:43:57.612   872  1883 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:43:57.625   872  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172683, domain null
,08-16 17:43:57.627   872  1883 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172683 seconds
,08-16 17:43:57.630   872  1883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:43:57.643   872  4170 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:43:57.644   872  1883 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:43:57.649   370   870 D CommandListener: Setting iface cfg
,08-16 17:43:57.661   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:43:57.661   872  1883 D DhcpClient: Scheduling renewal in 86399s
,08-16 17:43:57.676   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 17:43:57.677   872  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:43:57.678   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:43:57.678   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 17:43:57.680   872  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:43:57.691   872  1319 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 17:43:57.728   872  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 17:43:57.728   872  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 17:43:57.730   872  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 17:43:57.731   872  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 17:43:57.732   872  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 17:43:57.739   872  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 17:43:57.743   872  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 17:43:57.743   872  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 17:43:57.743   872  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 17:43:57.743   872  1319 D ConnectivityService:    accepting network in place of null
08-16 17:43:57.743   872  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 17:43:57.744   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:43:57.744   872  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:43:57.754   872  4169 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140166, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:43:57.797   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:43:57.826   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,08-16 17:43:57.829   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:43:57.835   872  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 17:43:57.835   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:57.846   872  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 17:43:57.848  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:57.848  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:57.848  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:57.848  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:57.850  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:57.850  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:57.850  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:57.851  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:57.851   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:43:57.866  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:43:57.869  1753  1753 D SystemUpdateService: onCreate
,08-16 17:43:57.874  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:43:57.882  1753  4181 I SystemUpdateService: active receiver: enabled
,08-16 17:43:57.886  1753  4181 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:43:57.890  1753  4181 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 17:43:57.890  1753  4181 I SystemUpdateService: now status is 0 (complete)
08-16 17:43:57.890  1753  4181 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 17:43:57.890  1753  4181 I SystemUpdateService: file has been verified
,08-16 17:43:57.891  1753  4181 I SystemUpdateService: OTA package size = 12249756
,08-16 17:43:57.895  1753  4181 I SystemUpdateService: showing system update notification
,08-16 17:43:57.899  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:43:57.902   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:43:57 GMT], X-Android-Received-Millis=[1471362237901], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471362237873]}
,08-16 17:43:57.902   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:43:57.903   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-16 17:43:57.903   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:43:57.903  1753  2422 I iu.UploadsManager: num queued entries: 0
08-16 17:43:57.903  1753  2422 I iu.UploadsManager: num updated entries: 0
08-16 17:43:57.904  1753  2422 I iu.SyncManager: NEXT; no task
08-16 17:43:57.905   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:43:57.908  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 17:43:57.909  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 17:43:57.911  1753  4186 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 17:43:57.911  1753  4186 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 17:43:57.913  1753  4186 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:43:57.960   872   884 I ActivityManager: Start proc 4189:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-16 17:43:57.966  4066  4066 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:57.970  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:43:57.972  1753  1753 D SystemUpdateService: onDestroy
,08-16 17:43:57.976  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:43:57.981  4066  4066 D SprintDMHelper: simOperator: 
08-16 17:43:57.982  4066  4066 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:43:57.989  4189  4189 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-16 17:43:58.027  1532  2378 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 17:43:58.027  1532  2378 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 17:43:58.027  1532  2378 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:43:58.027  1532  2378 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:58.045  1753  4186 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-16 17:43:58.080  4189  4189 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 17:43:58.089  4189  4189 I BooksApp: Created application version: 3.6.9 (30609)
,08-16 17:43:58.125  4189  4212 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:43:58.138  4000  4201 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:43:58.273  4189  4219 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:43:58.353  1532  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:43:58.354  1532  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:43:58.354  1532  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:43:58.354  1532  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:58.427  1532  2161 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:43:58.428  1532  2161 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 17:43:58.428  1532  2161 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:43:58.428  1532  2161 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:43:58.459  4189  4219 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:43:58.464  4189  4212 E BooksSync: Soft error
08-16 17:43:58.464  4189  4212 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:43:58.464  4189  4212 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:43:58.466  4189  4212 E BooksSync: Sync error
08-16 17:43:58.466  4189  4212 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:43:58.466  4189  4212 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:43:58.467  4189  4212 I BooksSync: Finished books sync
,08-16 17:43:58.485   872   882 I ActivityManager: Killing 3699:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-16 17:43:58.487   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 129078, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:43:58.836   872  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 17:43:59.647   872   882 I ActivityManager: Killing 3618:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-16 17:43:59.753   872  2012 D WifiService: setWifiEnabled: false pid=3875, uid=10000
08-16 17:43:59.753   872  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:43:59.794  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 17:43:59.803   872  1317 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 17:43:59.804   872  1317 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 17:43:59.804   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:43:59.805   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:59.830   872  1883 D DhcpClient: Clearing IP address
,08-16 17:43:59.831   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:59.837   370   870 D CommandListener: Setting iface cfg
,08-16 17:43:59.845  1532  4204 V NativeCrypto: Read error: ssl=0x9aca0400: I/O error during system call, Connection timed out
,08-16 17:43:59.850  1532  4204 V NativeCrypto: SSL shutdown failed: ssl=0x9aca0400: I/O error during system call, Broken pipe
,08-16 17:43:59.857   872  3133 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-16 17:43:59.857   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-16 17:43:59.860   872  4168 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-16 17:43:59.861   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-16 17:43:59.862   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 17:43:59.867   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 17:43:59.869   872  4170 D DhcpClient: Receive thread stopped
08-16 17:43:59.877   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 17:43:59.877   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-16 17:43:59.879   394   394 E Parcel  : Reading a NULL string not supported here.
08-16 17:43:59.879   872  1317 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 17:43:59.881   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:43:59.884   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:59.886   872  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 17:43:59.895   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:43:59.899  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:59.899  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:59.899  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:59.899  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:59.900   872  1317 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 17:43:59.900  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:59.900  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:59.900  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:59.900  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:59.902  2089  2336 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:59.922   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:43:59.948   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:43:59.949   872  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 17:43:59.949   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:43:59.951   872   889 D Tethering: MasterInitialState.processMessage what=3
08-16 17:43:59.954  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:59.955  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:59.963  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:43:59.966  1753  1753 D SystemUpdateService: onCreate
,08-16 17:43:59.969  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:43:59.981  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:43:59.985  1753  2422 I iu.UploadsManager: num queued entries: 0
,08-16 17:43:59.986  1753  2422 I iu.UploadsManager: num updated entries: 0
,08-16 17:43:59.989  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:43:59.990  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:43:59.992  4066  4066 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:59.995  4066  4066 D SprintDMHelper: simOperator: 
08-16 17:43:59.995  4066  4066 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:44:00.024  4000  4233 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 17:44:00.026   370   870 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:44:00.027   872  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 17:44:00.027   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:44:00.031  1753  4229 I SystemUpdateService: active receiver: enabled,
,08-16 17:44:00.034  1753  2422 I iu.SyncManager: NEXT; no task
,08-16 17:44:00.036  1753  4229 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:44:00.038  1753  4229 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 17:44:00.038  1753  4229 I SystemUpdateService: now status is 0 (complete)
,08-16 17:44:00.038  1753  4229 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:44:00.038  1753  4229 I SystemUpdateService: file has been verified
,08-16 17:44:00.038  1753  4229 I SystemUpdateService: OTA package size = 12249756
,08-16 17:44:00.045  1753  4229 I SystemUpdateService: showing system update notification
,08-16 17:44:00.057  1753  1753 D SystemUpdateService: onDestroy
,08-16 17:44:02.813   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@94d1b0d:true
,08-16 17:44:02.814  4052  4052 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 17:44:02.821  4052  4052 I bt_bluedroid: init
,08-16 17:44:02.822  4052  4238 I BluetoothAdapterState: Entering OffState
,08-16 17:44:02.827  4052  4239 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:44:02.827  4052  4239 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:44:02.828  4052  4239 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 17:44:02.828  4052  4239 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:44:02.830  4052  4052 I bt_bluedroid: get_profile_interface socket
,08-16 17:44:02.833  4052  4242 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 17:44:02.834  4052  4052 I bt_bluedroid: get_profile_interface sdp
,08-16 17:44:02.836  4052  4242 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:44:02.840  4052  4062 I bt_bluedroid: config_hci_snoop_log
,08-16 17:44:02.844   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:44:02.855  4052  4238 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 17:44:02.855  4052  4238 D BluetoothAdapterProperties: Setting state to 14
08-16 17:44:02.856  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 17:44:02.860  4052  4238 D BluetoothBondStateMachine: make
,08-16 17:44:02.865  4052  4243 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:44:02.876  4052  4238 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:44:02.877  4052  4052 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:44:02.885  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:02.888  4052  4052 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:44:02.890  4052  4052 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:44:02.890  4052  4052 D BtGatt.GattService: start()
,08-16 17:44:02.890  4052  4052 I bt_bluedroid: get_profile_interface gatt
08-16 17:44:02.891  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:02.892  4052  4052 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:44:02.900  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:02.901  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:02.901  4052  4052 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 17:44:02.901  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:02.902  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 17:44:02.903  4052  4238 I bt_bluedroid: enable
08-16 17:44:02.904  4052  4239 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 17:44:02.905  4052  4239 I bt_hci  : start_up
,08-16 17:44:02.925  4052  4239 I bt_vendor: alloc value 0xb3969189
08-16 17:44:02.925  4052  4239 I bt_vendor: init
08-16 17:44:02.926  4052  4239 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:44:02.926  4052  4239 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:44:03.034  4052  4239 D bt_hci  : start_up starting async portion
08-16 17:44:03.035  4052  4246 I bt_hci  : event_finish_startup
08-16 17:44:03.035  4052  4246 I bt_hci_h4: hal_open
08-16 17:44:03.035  4052  4246 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:44:03.041  4052  4246 I bt_userial_vendor: device fd = 51 open
,08-16 17:44:03.075  4052  4246 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:44:03.084  4189  4209 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 17:44:03.107  4052  4246 D bt_hwcfg: Chipset BCM4354A2
,08-16 17:44:03.107  4052  4246 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 17:44:03.108  4052  4246 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:44:03.785  4052  4246 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:44:03.786  4052  4246 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 17:44:03.787  4052  4246 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:44:03.903  4052  4246 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:44:03.905  4052  4246 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:44:03.934  4052  4246 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:44:03.934  4052  4246 I bt_vendor: firmware callback
08-16 17:44:03.934  4052  4246 I bt_hci  : firmware_config_callback
,08-16 17:44:03.946  4052  4250 I bt_btu  : btu_task pending for preload complete event
,08-16 17:44:03.946  4052  4250 I bt_btu_task: Bluetooth chip preload is complete
08-16 17:44:03.947  4052  4250 I bt_btu  : btu_task received preload complete event
,08-16 17:44:03.960  4052  4250 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:44:03.960  4052  4250 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:44:03.960  4052  4250 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:44:03.961  4052  4250 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:44:03.961  4052  4250 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 17:44:03.961  4052  4250 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:44:03.962  4052  4250 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:44:03.962  4052  4250 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 17:44:03.962  4052  4250 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:44:03.962  4052  4250 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 17:44:03.963  4052  4250 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:44:03.963  4052  4250 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:44:03.963  4052  4250 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 17:44:03.963  4052  4250 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:44:03.964  4052  4250 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:44:04.106  4052  4250 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-16 17:44:04.106  4052  4250 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-16 17:44:04.116  4052  4242 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 17:44:04.118  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:44:04.119  4052  4242 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:44:04.124  4052  4242 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:44:04.127  4052  4242 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:44:04.128  4052  4242 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:44:04.128  4052  4242 D bt_hci  : do_postload posting postload work item
08-16 17:44:04.129  4052  4246 I bt_hci  : event_postload
08-16 17:44:04.129  4052  4246 I bt_vendor: sco_config_cb
08-16 17:44:04.129  4052  4246 I bt_hci  : sco_config_callback postload finished.
,08-16 17:44:04.133  4052  4242 D bt_bte_conf: Device ID record 1 : primary
08-16 17:44:04.133  4052  4242 D bt_bte_conf:   vendorId            = 000f
08-16 17:44:04.133  4052  4242 D bt_bte_conf:   vendorIdSource      = 0001
,08-16 17:44:04.133  4052  4242 D bt_bte_conf:   product             = 1200
08-16 17:44:04.134  4052  4242 D bt_bte_conf:   version             = 1436
08-16 17:44:04.134  4052  4242 D bt_bte_conf:   clientExecutableURL = 
,08-16 17:44:04.134  4052  4242 D bt_bte_conf:   serviceDescription  = 
08-16 17:44:04.134  4052  4242 D bt_bte_conf:   documentationURL    = 
,08-16 17:44:04.135  4052  4242 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:44:04.135  4052  4239 D bt_stack_manager: event_start_up_stack finished
,08-16 17:44:04.136  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:04.139  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
,08-16 17:44:04.140  4052  4246 I bt_vendor: low_power_mode_cb
,08-16 17:44:04.140  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.141  4052  4238 D BluetoothAdapterProperties: Setting state to 15
,08-16 17:44:04.141  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:44:04.142  4052  4238 I BluetoothAdapterState: Entering BleOnState
,08-16 17:44:04.145  4052  4238 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 17:44:04.146  4052  4238 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:44:04.146  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 17:44:04.152  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:04.153  4052  4052 D HeadsetService: Received start request. Starting profile...
08-16 17:44:04.157  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:04.159  4052  4052 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:44:04.160  4052  4052 D HeadsetStateMachine: make
08-16 17:44:04.161  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.167  4052  4238 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:44:04.169  4052  4052 D HeadsetStateMachine: max_hf_connections = 1
,08-16 17:44:04.169  4052  4052 I bt_bluedroid: get_profile_interface handsfree
,08-16 17:44:04.169  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:44:04.170  4052  4242 E bt_btif : btif_hf_upstreams_evt: Invalid index 32771
,08-16 17:44:04.176  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:04.177  4052  4052 D A2dpService: Received start request. Starting profile...
,08-16 17:44:04.178  4052  4052 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:44:04.178  4052  4052 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:44:04.184  4052  4052 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:44:04.185  4052  4052 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:44:04.185  4052  4052 D A2dpStateMachine: make
,08-16 17:44:04.187  4052  4052 I bt_bluedroid: get_profile_interface a2dp
,08-16 17:44:04.187  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 17:44:04.189  4052  4259 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:44:04.190  4052  4052 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:44:04.191  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:04.193  4052  4052 D HidService: Received start request. Starting profile...
,08-16 17:44:04.193  3948  3948 D BluetoothInputDevice: Proxy object connected
08-16 17:44:04.193  4052  4052 I bt_bluedroid: get_profile_interface hidhost
08-16 17:44:04.193  4052  4242 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
08-16 17:44:04.193  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 17:44:04.194  4052  4052 D HidService: setHidService(): set to: null
08-16 17:44:04.194  3948  3948 D HidProfile: Bluetooth service connected
08-16 17:44:04.195  4052  4052 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:44:04.195  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:04.196  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:44:04.197  4052  4052 D HealthService: Received start request. Starting profile...
,08-16 17:44:04.199  4052  4052 I bt_bluedroid: get_profile_interface health
,08-16 17:44:04.200  4052  4052 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:44:04.201  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:04.202  4052  4052 D PanService: Received start request. Starting profile...
08-16 17:44:04.202  3948  3948 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:44:04.202  4052  4052 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:44:04.202  4052  4052 I bt_bluedroid: get_profile_interface pan
08-16 17:44:04.202  3948  3948 D PanProfile: Bluetooth service connected
08-16 17:44:04.203  4052  4242 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:44:04.205  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:04.208  3948  3948 D BluetoothMap: Proxy object connected
,08-16 17:44:04.208  4052  4052 D BluetoothMapService: Received start request. Starting profile...
08-16 17:44:04.208  4052  4052 D BluetoothMapService: start()
08-16 17:44:04.209  3948  3948 D MapProfile: Bluetooth service connected
,08-16 17:44:04.209  3948  3948 D BluetoothMap: getConnectedDevices()
,08-16 17:44:04.210  4052  4052 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 17:44:04.210  3948  3948 D BluetoothMap: Bluetooth is Not enabled
,08-16 17:44:04.211  4052  4052 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 17:44:04.211  4052  4052 D BluetoothMapAppObserver: createReceiver()
08-16 17:44:04.212  4052  4052 D BluetoothMapAppObserver: initObservers()
08-16 17:44:04.212  4052  4052 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:44:04.219  4052  4257 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 17:44:04.220  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:04.220  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:04.220  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.220  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.222  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:04.224  4052  4052 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:04.225  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:04.226  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-16 17:44:04.226  4052  4238 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:44:04.226  4052  4238 D BluetoothAdapterProperties: State =  11
,08-16 17:44:04.226  4052  4238 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:44:04.226  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:44:04.227  4052  4242 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:44:04.227  4052  4242 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:44:04.227  4052  4238 I BluetoothAdapterState: Entering OnState
,08-16 17:44:04.227  3948  3961 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:44:04.228  3948  3959 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:44:04.228  1373  1387 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:04.231   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:44:04.232  1373  2017 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:04.232  1373  1373 D BluetoothA2dp: Proxy object connected
08-16 17:44:04.232   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:04.232  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:44:04.233   872   872 D BluetoothA2dp: Proxy object connected
08-16 17:44:04.233  3948  3960 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:44:04.235  3948  3959 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:44:04.236  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:04.236  1924  1934 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:04.237   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:44:04.237  1373  1387 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:44:04.239  4052  4052 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 17:44:04.239  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:44:04.239  1373  1373 D PanProfile: Bluetooth service connected
08-16 17:44:04.239  4052  4052 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-16 17:44:04.240   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:04.241  4052  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:04.240  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:04.241  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:44:04.243  1373  1373 D BluetoothInputDevice: Proxy object connected
,08-16 17:44:04.243  1373  1373 D HidProfile: Bluetooth service connected
08-16 17:44:04.244  1373  3874 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:44:04.244  4052  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:44:04.245  4052  4052 D ObexServerSockets: Succeed to create listening sockets 
08-16 17:44:04.245  4052  4052 D ObexServerSockets0: startAccept()
,08-16 17:44:04.245  4052  4052 D ObexServerSockets0: prepareForNewConnect()
08-16 17:44:04.245  1373  1387 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:44:04.247  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:44:04.247  4052  4052 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 17:44:04.247  4052  4052 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 17:44:04.249  1373  1373 D BluetoothMap: Proxy object connected
,08-16 17:44:04.249  1373  1373 D MapProfile: Bluetooth service connected
08-16 17:44:04.249  1373  1373 D BluetoothMap: getConnectedDevices()
08-16 17:44:04.249  4052  4265 D ObexServerSockets0: Accepting socket connection...
,08-16 17:44:04.249  4052  4266 D ObexServerSockets0: Accepting socket connection...
,08-16 17:44:04.251   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:44:04.252  4052  4052 D BluetoothMapService: onReceive
08-16 17:44:04.252  4052  4052 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:44:04.252  4052  4052 D BluetoothMapService: STATE_ON
08-16 17:44:04.253  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.254  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.255  3948  3948 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 17:44:04.259  3948  3948 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 17:44:04.265  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:44:04.267  3948  3948 D BluetoothA2dp: Proxy object connected
,08-16 17:44:04.272  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:44:04.276  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:44:04.277  1373  1373 D BluetoothPbap: Proxy object connected
08-16 17:44:04.277  1373  1373 D PbapServerProfile: Bluetooth service connected
08-16 17:44:04.278  3948  3948 D BluetoothPbap: Proxy object connected
08-16 17:44:04.278  4052  4052 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 17:44:04.278  4052  4052 D ObexServerSockets0: prepareForNewConnect()
08-16 17:44:04.278  3948  3948 D PbapServerProfile: Bluetooth service connected
,08-16 17:44:04.287  4052  4271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:04.310  4052  4275 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:04.311  4052  4275 I BtOppRfcommListener: Accept thread started.
,08-16 17:44:04.333   872   872 D BluetoothHeadset: Proxy object connected
08-16 17:44:04.333   872   872 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.333   872   872 D BluetoothHeadset: Proxy object connected
08-16 17:44:04.334  1373  1385 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.334  1373  1373 D HeadsetProfile: Bluetooth service connected
08-16 17:44:04.334  1924  2164 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.337  1924  1935 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.337   872   889 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.341   872   889 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.362  3948  3959 D BluetoothHeadset: Proxy object connected
,08-16 17:44:04.362  3948  3948 D HeadsetProfile: Bluetooth service connected
,08-16 17:44:05.749   872  1319 D ConnectivityService: handlePromptUnvalidated 101
,08-16 17:44:05.771  4052  4238 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 17:44:05.771  4052  4238 D BluetoothAdapterProperties: Setting state to 13
08-16 17:44:05.772  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:44:05.773  4052  4238 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:44:05.778  4052  4238 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:44:05.784  4052  4242 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:44:05.785  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 17:44:05.788  4052  4052 D BluetoothMapService: onReceive
,08-16 17:44:05.789  4052  4052 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:05.789  4052  4052 D BluetoothMapService: STATE_TURNING_OFF
08-16 17:44:05.790  4052  4052 D BluetoothMapService: MAP Service closeService in
,08-16 17:44:05.790  4052  4052 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 17:44:05.790  4052  4052 D ObexServerSockets0: shutdown(block = true)
,08-16 17:44:05.791  4052  4265 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 17:44:05.795  4052  4052 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 17:44:05.796  4052  4252 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:44:05.796  4052  4052 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:44:05.797  4052  4266 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 17:44:05.798  4052  4052 I BtOppRfcommListener: stopping Accept Thread
08-16 17:44:05.798  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:05.799  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:05.799  4052  4275 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:44:05.800  4052  4275 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:44:05.800  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:44:05.803  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:44:05.803  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:05.806  4052  4052 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:44:05.810  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:05.810  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:44:05.810   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 17:44:05.811   872   872 D BluetoothHeadset: Proxy object disconnected
,08-16 17:44:05.811   872   872 D BluetoothHeadset: Proxy object disconnected
08-16 17:44:05.811  1373  1385 D BluetoothHeadset: Proxy object disconnected
08-16 17:44:05.812  3948  3961 D BluetoothHeadset: Proxy object disconnected
08-16 17:44:05.812  1924  2055 D BluetoothHeadset: Proxy object disconnected
08-16 17:44:05.813  4052  4052 D A2dpService: Received stop request...Stopping profile...
,08-16 17:44:05.812  3875  3875 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:44:05.813  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:44:05.814  4052  4259 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:44:05.816   872   872 D BluetoothA2dp: Proxy object disconnected
08-16 17:44:05.817  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:05.818  4052  4052 D HidService: Received stop request...Stopping profile...
08-16 17:44:05.818  4052  4052 D HidService: Stopping Bluetooth HidService
,08-16 17:44:05.819  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:05.822  4052  4052 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:44:05.822  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:05.822  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:44:05.822  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:05.825  4052  4052 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:44:05.825  4052  4052 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:44:05.825  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:44:05.825  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 17:44:05.825  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:44:05.825  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:44:05.825  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:44:05.826  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:44:05.826  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-16 17:44:05.826  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-16 17:44:05.826  1373  1373 D HidProfile: Bluetooth service disconnected
08-16 17:44:05.827  4052  4242 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 17:44:05.828  4052  4052 D HealthService: Received stop request...Stopping profile...
,08-16 17:44:05.829  4052  4052 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:44:05.829  4052  4052 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:44:05.829  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:05.829  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:05.829  4052  4052 D PanService: Received stop request...Stopping profile...
,08-16 17:44:05.830  3948  3948 D DockEventReceiver: finishStartingService: stopping service
08-16 17:44:05.830  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:44:05.830  1373  1373 D PanProfile: Bluetooth service disconnected
,08-16 17:44:05.831  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 17:44:05.831  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:44:05.831  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:44:05.831  4052  4250 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:44:05.832  3948  3948 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:44:05.832  4052  4250 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:44:05.832  4052  4250 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:44:05.832  4052  4250 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 17:44:05.832  3948  3948 D BluetoothA2dp: Proxy object disconnected
08-16 17:44:05.832  3948  3948 D BluetoothInputDevice: Proxy object disconnected
08-16 17:44:05.832  3948  3948 D HidProfile: Bluetooth service disconnected
,08-16 17:44:05.833  3948  3948 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:44:05.833  3948  3948 D PanProfile: Bluetooth service disconnected
08-16 17:44:05.833  4052  4052 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:44:05.833  4052  4052 D BluetoothMapService: stop()
08-16 17:44:05.834  4052  4052 D BluetoothMapAppObserver: deinitObservers()
,08-16 17:44:05.834  4052  4052 D BluetoothMapAppObserver: removeReceiver()
08-16 17:44:05.835  1373  1373 D BluetoothMap: Proxy object disconnected
08-16 17:44:05.835  1373  1373 D MapProfile: Bluetooth service disconnected
,08-16 17:44:05.836  4052  4052 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:44:05.836  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:05.836  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:44:05.836  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:05.836  4052  4052 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:44:05.836  4052  4242 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-16 17:44:05.836  4052  4052 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:44:05.837  3948  3948 D BluetoothMap: Proxy object disconnected
,08-16 17:44:05.837  3948  3948 D MapProfile: Bluetooth service disconnected
08-16 17:44:05.838  1373  1373 D BluetoothPbap: Proxy object disconnected
,08-16 17:44:05.838  1373  1373 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:44:05.838  3948  3948 D BluetoothPbap: Proxy object disconnected
08-16 17:44:05.838  3948  3948 D PbapServerProfile: Bluetooth service disconnected
08-16 17:44:05.839  4052  4052 V BluetoothAdapterState: isTurningOff()=true
08-16 17:44:05.839  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:05.839  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:05.839  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:05.839  4052  4052 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 17:44:05.839  4052  4052 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:44:05.839  4052  4052 V BluetoothAdapterState: isTurningOff()=true
08-16 17:44:05.840  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:05.840  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:44:05.840  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:05.840  4052  4052 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:44:05.840  4052  4052 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:44:05.840  4052  4242 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 17:44:05.842  4052  4052 D BluetoothMapService: MAP Service closeService in
08-16 17:44:05.842  4052  4052 V BluetoothAdapterState: isTurningOff()=true
08-16 17:44:05.842  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:05.843  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:05.843  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:05.843  4052  4052 D BluetoothMapService: cleanup()
08-16 17:44:05.843  4052  4052 D BluetoothMapService: MAP Service closeService in
08-16 17:44:05.844  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 17:44:05.844  4052  4238 D BluetoothAdapterProperties: Setting state to 15
08-16 17:44:05.844  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:44:05.845  4052  4238 I BluetoothAdapterState: Entering BleOnState
08-16 17:44:05.845  3948  3960 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:44:05.845  3948  3959 D BluetoothPan: onBluetoothStateChange on: false
,08-16 17:44:05.846  1373  3874 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:44:05.846  3948  3961 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:44:05.846   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:44:05.846  1373  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:44:05.847   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:44:05.847  3948  3960 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:44:05.847  3948  3959 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:44:05.848  1924  1934 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:44:05.848   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 17:44:05.848  1373  2017 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:44:05.849  3948  3961 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:44:05.849   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:44:05.849  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:44:05.849  1373  3874 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:44:05.850  1373  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:44:05.850  4052  4238 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 17:44:05.850  4052  4238 D BluetoothAdapterProperties: Setting state to 16
,08-16 17:44:05.850  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:44:05.851  4052  4238 D BluetoothAdapterProperties: onBleDisable
08-16 17:44:05.851  4052  4239 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 17:44:05.852  4052  4238 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:44:05.852  4052  4250 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:44:05.852  4052  4250 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:44:05.855  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:05.856  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:05.856  4052  4242 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:44:05.858  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:44:05.858  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:05.859  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:05.861  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:44:05.862  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:44:06.053  4052  4242 I bt_hci  : shut_down
,08-16 17:44:06.053  4052  4246 D bt_hwcfg: hw_epilog_process
08-16 17:44:06.055  4052  4246 I bt_vendor: low_power_mode_cb
,08-16 17:44:06.077  4052  4246 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:44:06.077  4052  4246 I bt_vendor: epilog_cb
08-16 17:44:06.077  4052  4246 I bt_hci  : epilog_finished_callback
,08-16 17:44:06.088  4052  4242 I bt_hci_h4: hal_close
,08-16 17:44:06.090  4052  4242 I bt_userial_vendor: device fd = 51 close
,08-16 17:44:06.244  4052  4239 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:44:06.245  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 17:44:06.249  4052  4238 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:44:06.249  4052  4052 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:44:06.250  4052  4052 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:44:06.250  4052  4052 D BtGatt.GattService: stop()
08-16 17:44:06.250  4052  4052 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:44:06.252  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:06.252  4052  4052 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:44:06.252  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:06.252  4052  4052 V BluetoothAdapterState: isBleTurningOff()=true
08-16 17:44:06.253  4052  4238 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 17:44:06.253  4052  4238 D BluetoothAdapterProperties: Setting state to 10
08-16 17:44:06.253  4052  4238 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 17:44:06.254  4052  4238 I BluetoothAdapterState: Entering OffState
08-16 17:44:06.255   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 17:44:06.271  4052  4052 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 17:44:06.271  4052  4052 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 17:44:06.271  4052  4052 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:44:06.273  4052  4239 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 17:44:06.279  4052  4239 D bt_stack_manager: event_clean_up_stack finished.
,08-16 17:44:06.281  4052  4052 I art     : System.exit called, status: 0
,08-16 17:44:06.281  4052  4052 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:44:06.346   872  2106 I ActivityManager: Process com.android.bluetooth (pid 4052) has died
,08-16 17:44:06.451  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:06.463  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:06.466  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:06.521  1532  2161 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 17:44:06.521  1532  2161 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 17:44:06.522  1532  2161 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:44:06.522  1532  2161 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:44:06.576  3507  3507 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 17:44:06.577  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 17:44:06.581  3507  3507 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 17:44:07.709   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 17:44:07.717  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 17:44:07.725   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:44:07.725   872   892 I Adreno  : Build Date                       : 10/20/15
08-16 17:44:07.725   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:44:07.725   872   892 I Adreno  : Local Branch                     : M14
08-16 17:44:07.725   872   892 I Adreno  : Remote Branch                    : 
08-16 17:44:07.725   872   892 I Adreno  : Remote Branch                    : 
08-16 17:44:07.725   872   892 I Adreno  : Reconstruct Branch               : 
,08-16 17:44:07.769   283   308 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (289 us)
,08-16 17:44:08.162  3507  3543 D Finsky  : [292] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-16 17:44:08.182  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:08.231  1532  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-16 17:44:08.231  1532  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-16 17:44:08.232  1532  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:44:08.232  1532  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:44:08.294  3507  3543 D Finsky  : [292] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-16 17:44:08.366   872   881 I art     : Background partial concurrent mark sweep GC freed 35444(2MB) AllocSpace objects, 6(208KB) LOS objects, 33% free, 28MB/43MB, paused 1.262ms total 110.974ms
,08-16 17:44:08.439  3875  3875 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:44:08.439  3875  3875 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:44:08.477   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 17:44:08.479  3875  3875 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@91ae14f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5f82ea5, 16908290=android.view.AbsSavedState$1@5f82ea5}, android:focusedViewId=100}]}]
,08-16 17:44:08.479  3875  3875 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 17:44:08.479  3875  3875 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:44:08.479  3875  3875 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:44:08.493   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 17:44:08.496   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 17:44:08.498   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-16 17:44:08.499   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 17:44:08.512   872   881 I art     : Background partial concurrent mark sweep GC freed 2531(139KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 1.180ms total 100.258ms
,08-16 17:44:08.735   283   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 17:44:08.740   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 17:44:08.742   872  1342 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
08-16 17:44:08.745   872   892 I DreamManagerService: Entering dreamland.
,08-16 17:44:08.746   872   892 I PowerManagerService: Dozing...
,08-16 17:44:08.749   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 17:44:08.767  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:44:08.767  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:08.816   374  1326 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 17:44:08.816   374  1326 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-16 17:44:08.826   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:44:08.834  1910  4290 D NfcService: Discovery configuration equal, not updating.
,08-16 17:44:08.837   872  1317 E native  : do suspend false
,08-16 17:44:08.858   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:44:08.861   872  1317 E native  : do suspend true
,08-16 17:44:08.957   374  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 17:44:08.958   374  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 17:44:11.774  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:11.775  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@180527a added. We now have 6 listener(s)
08-16 17:44:11.775  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:11.780  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:11.780  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1207a2b added. We now have 7 listener(s)
08-16 17:44:11.781  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:11.783  3875  3923 I System.out: IsBluetoothEnabled
,08-16 17:44:11.792  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:11.834   872   889 I ActivityManager: Start proc 4298:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 17:44:11.943  4298  4298 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:44:11.943  4298  4298 D AdapterServiceConfig: Adding A2dpService
08-16 17:44:11.944  4298  4298 D AdapterServiceConfig: Adding HidService
08-16 17:44:11.945  4298  4298 D AdapterServiceConfig: Adding HealthService
,08-16 17:44:11.945  4298  4298 D AdapterServiceConfig: Adding PanService
08-16 17:44:11.946  4298  4298 D AdapterServiceConfig: Adding GattService
08-16 17:44:11.947  4298  4298 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 17:44:11.969   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4111a3a:true
08-16 17:44:11.969  4298  4298 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 17:44:11.974  4298  4298 I bt_bluedroid: init
,08-16 17:44:11.975  4298  4310 I BluetoothAdapterState: Entering OffState
,08-16 17:44:11.977  4298  4311 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:44:11.977  4298  4311 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:44:11.977  4298  4311 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 17:44:11.977  4298  4311 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:44:11.978  4298  4298 I bt_bluedroid: get_profile_interface socket
,08-16 17:44:11.981  4298  4298 I bt_bluedroid: get_profile_interface sdp
,08-16 17:44:11.984  4298  4314 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:44:11.986  4298  4309 I bt_bluedroid: config_hci_snoop_log
08-16 17:44:11.987  4298  4314 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:44:11.988   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:44:11.996  4298  4310 D BluetoothAdapterState: Current state: OFF, message: 0
08-16 17:44:11.997  4298  4310 D BluetoothAdapterProperties: Setting state to 14
,08-16 17:44:11.997  4298  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-16 17:44:12.001  4298  4310 D BluetoothBondStateMachine: make
,08-16 17:44:12.005  4298  4315 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:44:12.014  4298  4310 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:44:12.014  4298  4298 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:44:12.020  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:12.021  4298  4298 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:44:12.023  4298  4298 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:44:12.024  4298  4298 D BtGatt.GattService: start()
,08-16 17:44:12.024  4298  4298 I bt_bluedroid: get_profile_interface gatt
08-16 17:44:12.025  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:12.026  4298  4298 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:44:12.037  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:12.037  4298  4298 V BluetoothAdapterState: isTurningOn()=false
08-16 17:44:12.037  4298  4298 V BluetoothAdapterState: isBleTurningOn()=true
08-16 17:44:12.037  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:12.038  4298  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 17:44:12.038  4298  4310 I bt_bluedroid: enable
08-16 17:44:12.039  4298  4311 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 17:44:12.039  4298  4311 I bt_hci  : start_up
,08-16 17:44:12.053  4298  4311 I bt_vendor: alloc value 0xb39c3189
,08-16 17:44:12.053  4298  4311 I bt_vendor: init
08-16 17:44:12.054  4298  4311 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:44:12.054  4298  4311 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:44:12.160  4298  4311 D bt_hci  : start_up starting async portion
,08-16 17:44:12.161  4298  4318 I bt_hci  : event_finish_startup
08-16 17:44:12.161  4298  4318 I bt_hci_h4: hal_open
08-16 17:44:12.161  4298  4318 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:44:12.169  4298  4318 I bt_userial_vendor: device fd = 51 open
,08-16 17:44:12.202  4298  4318 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:44:12.234  4298  4318 D bt_hwcfg: Chipset BCM4354A2
,08-16 17:44:12.234  4298  4318 D bt_hwcfg: Target name = [BCM4354A2]
08-16 17:44:12.235  4298  4318 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:44:12.898  4298  4318 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:44:12.900  4298  4318 D bt_hwcfg: Settlement delay -- 100 ms
08-16 17:44:12.900  4298  4318 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:44:13.016  4298  4318 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:44:13.018  4298  4318 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:44:13.047  4298  4318 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:44:13.048  4298  4318 I bt_vendor: firmware callback
08-16 17:44:13.048  4298  4318 I bt_hci  : firmware_config_callback
,08-16 17:44:13.060  4298  4320 I bt_btu  : btu_task pending for preload complete event
,08-16 17:44:13.060  4298  4320 I bt_btu_task: Bluetooth chip preload is complete
08-16 17:44:13.060  4298  4320 I bt_btu  : btu_task received preload complete event
,08-16 17:44:13.071  4298  4320 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:44:13.071  4298  4320 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 17:44:13.071  4298  4320 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 17:44:13.072  4298  4320 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:44:13.072  4298  4320 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:44:13.072  4298  4320 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 17:44:13.073  4298  4320 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:44:13.073  4298  4320 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:44:13.073  4298  4320 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 17:44:13.074  4298  4320 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:44:13.074  4298  4320 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:44:13.074  4298  4320 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 17:44:13.075  4298  4320 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:44:13.075  4298  4320 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:44:13.075  4298  4320 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:44:13.209  4298  4320 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3940d9d
,08-16 17:44:13.209  4298  4320 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3940d9d 
,08-16 17:44:13.220  4298  4314 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 17:44:13.222  4298  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:44:13.223  4298  4314 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:44:13.226  4298  4314 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:44:13.229  4298  4314 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:44:13.232  4298  4314 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:44:13.232  4298  4314 D bt_hci  : do_postload posting postload work item
,08-16 17:44:13.232  4298  4318 I bt_hci  : event_postload
08-16 17:44:13.232  4298  4318 I bt_vendor: sco_config_cb
08-16 17:44:13.232  4298  4318 I bt_hci  : sco_config_callback postload finished.
,08-16 17:44:13.234  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:13.236  4298  4314 D bt_bte_conf: Device ID record 1 : primary
,08-16 17:44:13.237  4298  4314 D bt_bte_conf:   vendorId            = 000f
08-16 17:44:13.237  4298  4314 D bt_bte_conf:   vendorIdSource      = 0001
08-16 17:44:13.237  4298  4314 D bt_bte_conf:   product             = 1200
,08-16 17:44:13.237  4298  4314 D bt_bte_conf:   version             = 1436
,08-16 17:44:13.237  4298  4314 D bt_bte_conf:   clientExecutableURL = 
08-16 17:44:13.237  4298  4314 D bt_bte_conf:   serviceDescription  = 
08-16 17:44:13.238  4298  4314 D bt_bte_conf:   documentationURL    = 
,08-16 17:44:13.238  4298  4314 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 17:44:13.239  4298  4318 I bt_vendor: low_power_mode_cb
,08-16 17:44:13.239  4298  4311 D bt_stack_manager: event_start_up_stack finished
,08-16 17:44:13.241  4298  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 17:44:13.242  4298  4310 D BluetoothAdapterProperties: Setting state to 15
08-16 17:44:13.242  4298  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:44:13.245  4298  4310 I BluetoothAdapterState: Entering BleOnState
,08-16 17:44:13.249  4298  4310 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 17:44:13.249  4298  4310 D BluetoothAdapterProperties: Setting state to 11
08-16 17:44:13.249  4298  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 17:44:13.254  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:13.255  4298  4298 D HeadsetService: Received start request. Starting profile...
,08-16 17:44:13.259  4298  4298 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:44:13.260  4298  4298 D HeadsetStateMachine: make
,08-16 17:44:13.266  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:13.275  4298  4298 D HeadsetStateMachine: max_hf_connections = 1,
08-16 17:44:13.275  4298  4298 I bt_bluedroid: get_profile_interface handsfree
,08-16 17:44:13.275  4298  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:44:13.275  4298  4314 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 17:44:13.281  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:13.282  4298  4298 D A2dpService: Received start request. Starting profile...
,08-16 17:44:13.283  4298  4298 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:44:13.283  4298  4298 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:44:13.289  4298  4310 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:44:13.291  4298  4298 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:44:13.292  4298  4298 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:44:13.292  4298  4298 D A2dpStateMachine: make
,08-16 17:44:13.293  4298  4298 I bt_bluedroid: get_profile_interface a2dp
08-16 17:44:13.294  4298  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 17:44:13.296  4298  4328 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:44:13.298  4298  4298 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:44:13.299  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:13.299  4298  4298 D HidService: Received start request. Starting profile...
,08-16 17:44:13.300  4298  4298 I bt_bluedroid: get_profile_interface hidhost
08-16 17:44:13.300  4298  4314 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39223e5
08-16 17:44:13.300  4298  4314 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 17:44:13.300  4298  4298 D HidService: setHidService(): set to: null
,08-16 17:44:13.303  4298  4298 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:44:13.303  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:44:13.304  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
,08-16 17:44:13.305  4298  4298 D HealthService: Received start request. Starting profile...
,08-16 17:44:13.306  4298  4298 I bt_bluedroid: get_profile_interface health
08-16 17:44:13.307  4298  4298 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:13.307  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.307  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:13.307  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:13.309  4298  4298 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 17:44:13.309  4298  4326 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 17:44:13.310  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:13.311  4298  4298 D PanService: Received start request. Starting profile...
,08-16 17:44:13.311  4298  4298 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:44:13.311  4298  4298 I bt_bluedroid: get_profile_interface pan
,08-16 17:44:13.312  4298  4314 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:44:13.314  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:13.315  4298  4298 D BluetoothMapService: Received start request. Starting profile...
08-16 17:44:13.315  4298  4298 D BluetoothMapService: start()
,08-16 17:44:13.317  4298  4298 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 17:44:13.318  4298  4298 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 17:44:13.318  4298  4298 D BluetoothMapAppObserver: createReceiver()
,08-16 17:44:13.319  4298  4298 D BluetoothMapAppObserver: initObservers()
08-16 17:44:13.319  4298  4298 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:44:13.325  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:13.325  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:13.326  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:13.327  4298  4298 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:13.327  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.327  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:44:13.327  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isTurningOff()=false
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isTurningOn()=true
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:44:13.328  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:44:13.329  4298  4310 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 17:44:13.329  4298  4310 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:44:13.329  4298  4310 D BluetoothAdapterProperties: State =  11
,08-16 17:44:13.336  4298  4314 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:44:13.336  4298  4314 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:44:13.336  4298  4310 D BluetoothAdapterProperties: Setting state to 12
08-16 17:44:13.336  4298  4310 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:44:13.337  3948  3959 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:44:13.337  4298  4310 I BluetoothAdapterState: Entering OnState
08-16 17:44:13.340  3948  3960 D BluetoothPan: onBluetoothStateChange on: true
,08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:13.342  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:13.343  1373  3874 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:13.344  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:44:13.345  3948  3959 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:44:13.345  4298  4298 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:44:13.345  4298  4298 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 17:44:13.346   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:44:13.347  3948  3948 D BluetoothInputDevice: Proxy object connected
08-16 17:44:13.347  1373  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:44:13.347  3948  3948 D HidProfile: Bluetooth service connected
08-16 17:44:13.347   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:13.347  4298  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:44:13.348  3948  3960 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:44:13.350  3948  3961 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:44:13.350  4298  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:44:13.350  3948  3948 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:44:13.350  3948  3948 D PanProfile: Bluetooth service connected
08-16 17:44:13.351  4298  4298 D ObexServerSockets: Succeed to create listening sockets 
08-16 17:44:13.352  4298  4298 D ObexServerSockets0: startAccept()
08-16 17:44:13.352  4298  4298 D ObexServerSockets0: prepareForNewConnect()
08-16 17:44:13.353  1924  2055 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:13.353   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:13.354  1373  1387 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:44:13.354  4298  4298 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 17:44:13.355  4298  4298 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 17:44:13.356   872   872 D BluetoothA2dp: Proxy object connected
08-16 17:44:13.357  1373  1373 D BluetoothA2dp: Proxy object connected
08-16 17:44:13.357  4298  4336 D ObexServerSockets0: Accepting socket connection...
08-16 17:44:13.359  3948  3961 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:44:13.360   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:44:13.360  1373  2017 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:44:13.360  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:44:13.360  1373  1373 D PanProfile: Bluetooth service connected
08-16 17:44:13.360  3948  3948 D BluetoothA2dp: Proxy object connected
08-16 17:44:13.362  1373  1373 D BluetoothInputDevice: Proxy object connected
08-16 17:44:13.362  1373  1385 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:44:13.362  1373  1373 D HidProfile: Bluetooth service connected
,08-16 17:44:13.364  3948  3948 D BluetoothMap: Proxy object connected
08-16 17:44:13.364  3948  3948 D MapProfile: Bluetooth service connected
08-16 17:44:13.364  1373  3874 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:44:13.364  3948  3948 D BluetoothMap: getConnectedDevices()
08-16 17:44:13.365  4298  4335 D ObexServerSockets0: Accepting socket connection...
08-16 17:44:13.368  1373  1373 D BluetoothMap: Proxy object connected
08-16 17:44:13.368  1373  1373 D MapProfile: Bluetooth service connected
08-16 17:44:13.369  1373  1373 D BluetoothMap: getConnectedDevices()
,08-16 17:44:13.370  4298  4298 D BluetoothMapService: onReceive
08-16 17:44:13.370  4298  4298 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:44:13.370  4298  4298 D BluetoothMapService: STATE_ON
08-16 17:44:13.371   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 17:44:13.373  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:13.379  3948  3948 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:44:13.389  1532  1532 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:44:13.396  3948  3948 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:44:13.399  4298  4298 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 17:44:13.399  4298  4298 D ObexServerSockets0: prepareForNewConnect()
,08-16 17:44:13.400  3948  3948 D BluetoothPbap: Proxy object connected
,08-16 17:44:13.400  3948  3948 D PbapServerProfile: Bluetooth service connected
,08-16 17:44:13.411  4298  4341 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:13.413  1373  1373 D BluetoothPbap: Proxy object connected
,08-16 17:44:13.414  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-16 17:44:13.431  4298  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:13.432  4298  4345 I BtOppRfcommListener: Accept thread started.
,08-16 17:44:13.448   872   872 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.448   872   872 D BluetoothHeadset: Proxy object connected
08-16 17:44:13.448   872   872 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.449  1373  3874 D BluetoothHeadset: Proxy object connected
08-16 17:44:13.449  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-16 17:44:13.449  3948  3959 D BluetoothHeadset: Proxy object connected
08-16 17:44:13.449  3948  3948 D HeadsetProfile: Bluetooth service connected
08-16 17:44:13.450  1924  1935 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.453  1924  2055 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.454   872   889 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.460  3948  3960 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.460  3948  3948 D HeadsetProfile: Bluetooth service connected
08-16 17:44:13.460   872   889 D BluetoothHeadset: Proxy object connected
,08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:13.813  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:13.820  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:13.824  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:13.824  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@84f4e88 added. We now have 8 listener(s)
,08-16 17:44:13.825  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:13.834   872  3133 D WifiService: setWifiEnabled: false pid=3875, uid=10000
,08-16 17:44:13.834   872  3133 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:44:13.847  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:13.849   872  2106 D WifiService: setWifiEnabled: true pid=3875, uid=10000
08-16 17:44:13.849   872  2106 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:44:13.860   872  1317 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:13.878  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:44:13.886  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:13.891   872  1317 D WifiConfigStore: loaded 0 passpoint configs
08-16 17:44:13.892   872  1317 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 17:44:13.893   872  1317 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-16 17:44:13.894   872  1317 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:44:13.894   872  1317 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 17:44:13.894   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 17:44:13.894   872  1317 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 17:44:13.915   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 17:44:13.915   872  1317 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.24 rxSuccessRate=0.30 delta 1000 -> 1000
08-16 17:44:13.916   872  1317 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:44:13.917   370   870 D CommandListener: Setting iface cfg
,08-16 17:44:13.926   872  1316 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 17:44:13.926   872  1316 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:44:13.930   872  1317 E native  : do suspend true
,08-16 17:44:13.945   872  1316 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:44:13.946   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-16 17:44:13.946   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:44:13.946   872  1316 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:44:13.958   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:44:14.034   872  1317 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:44:14.038  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:44:14.465  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:44:14.508  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:44:14.509  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-16 17:44:14.511   872  1317 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 17:44:14.519   872  1317 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:44:14.519   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:44:14.520   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:44:14.536   872  1317 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:44:14.544   370   870 D CommandListener: Setting iface cfg
,08-16 17:44:14.545   872  1317 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:44:14.553   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:44:14.604   872  4353 D DhcpClient: Receive thread started
,08-16 17:44:14.696   872  1317 E native  : do suspend false
,08-16 17:44:14.717   872  1883 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:44:14.732   872  4353 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-16 17:44:14.733   872  1883 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-16 17:44:14.736   872  1883 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:44:14.749   872  4353 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:44:14.750   872  1883 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:44:14.755   370   870 D CommandListener: Setting iface cfg
,08-16 17:44:14.768   872  1883 D DhcpClient: Scheduling renewal in 86399s
,08-16 17:44:14.771   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:44:14.774   872  1317 E native  : do suspend true
,08-16 17:44:14.794   872  1317 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 17:44:14.795   872  1317 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:44:14.796   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 17:44:14.798   872  1317 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:44:14.798   872  1319 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 17:44:14.849   872  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 17:44:14.849   872  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 17:44:14.851   872  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 17:44:14.852   872  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 17:44:14.853   872  1319 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 17:44:14.860   872  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:14.864  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:14.866  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:14.867   872  1319 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-16 17:44:14.867   872  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 17:44:14.867   872  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-16 17:44:14.867   872  1317 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 17:44:14.867   872  1319 D ConnectivityService:    accepting network in place of null
,08-16 17:44:14.868   872  1317 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:44:14.869   872  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:44:14.871  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:44:14.872  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:44:14.874  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@91ae14f Bundle[{}]
,08-16 17:44:14.875  3875  3923 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:44:14.875  3875  3923 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 17:44:14.876  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:44:14.877  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:44:14.877  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 17:44:14.878  3875  3923 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:44:14.879   872  4352 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:44:14.883  3875  3923 I System.out: Running OutgoingSocketThread
,08-16 17:44:14.885  3875  4358 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 424)
,08-16 17:44:14.886  3875  4358 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49140
,08-16 17:44:14.887  3875  4358 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:44:14.922   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:44:14.948   872  4351 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.206,2a00:1450:4001:817::200e
,08-16 17:44:14.955   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:44:14.963   872  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 17:44:14.963   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:14.965   872  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 17:44:14.967   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:44:14.988  2089  2660 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 17:44:15.000  1753  1753 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:15.007  3875  3875 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:15.010  1753  1753 D SystemUpdateService: onCreate
,08-16 17:44:15.010  3875  3875 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:15.013  1753  1753 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:44:15.027  1753  4363 I SystemUpdateService: active receiver: enabled
,08-16 17:44:15.030   872  4351 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:44:14 GMT], X-Android-Received-Millis=[1471362255029], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471362254997]}
,08-16 17:44:15.034   872  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:44:15.035   872  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 17:44:15.035   872  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 17:44:15.036   872  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:44:15.038  1753  1753 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:44:15.040  1753  2422 I iu.UploadsManager: num queued entries: 0
,08-16 17:44:15.040  1753  2422 I iu.UploadsManager: num updated entries: 0
08-16 17:44:15.041  1753  2422 I iu.SyncManager: NEXT; no task
,08-16 17:44:15.035  1753  4363 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:44:15.050  1753  1753 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:44:15.051  1753  1753 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:44:15.053  4066  4066 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:15.059  1753  4367 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 17:44:15.059  1753  4367 W BaseAppContext: Using Auth Proxy for data requests.
08-16 17:44:15.060  1753  4363 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 17:44:15.060  1753  4363 I SystemUpdateService: now status is 0 (complete)
08-16 17:44:15.060  4066  4066 D SprintDMHelper: simOperator: 
08-16 17:44:15.060  4066  4066 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:44:15.063  1753  4367 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:44:15.060  1753  4363 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 17:44:15.073  1753  4363 I SystemUpdateService: file has been verified
08-16 17:44:15.074  1753  4363 I SystemUpdateService: OTA package size = 12249756
,08-16 17:44:15.081  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:15.083  1532  1532 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:44:15.097  1753  4363 I SystemUpdateService: showing system update notification
,08-16 17:44:15.133  1532  2161 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 17:44:15.133  1532  2161 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 17:44:15.134  1753  1753 D SystemUpdateService: onDestroy
08-16 17:44:15.135  1532  2161 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:44:15.136  1532  2161 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:44:15.161  1753  4367 E MDM     : [182] SitrepService.a: Error sending sitrep.
,08-16 17:44:15.185  4000  4369 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:44:15.887  3875  3923 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 425)
,08-16 17:44:15.887  3875  3923 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 425)
,08-16 17:44:15.898  3875  3923 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-16 17:44:15.900  3875  3923 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 17:44:15.901  3875  3923 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 431)
,08-16 17:44:15.905  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:44:15.905  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e21021 added. We now have 2 listener(s)
,08-16 17:44:15.907  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:15.907  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:15.907  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:15.908  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:15.908  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b11c46 added. We now have 9 listener(s)
08-16 17:44:15.908  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:15.909  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:15.914  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:15.921  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:15.925  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:15.925  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:15.925  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:15.925  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cecb34 added. We now have 3 listener(s)
,08-16 17:44:15.927  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:44:15.927  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:15.927  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:15.927  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:15.928  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e8d5d added. We now have 10 listener(s)
,08-16 17:44:15.928  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:15.928  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:44:15.928  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:15.928  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:15.928  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:15.929  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:15.929  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:15.929  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:15.929  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e21021 removed from the list
08-16 17:44:15.929  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:15.929  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b11c46 removed from the list
,08-16 17:44:15.931  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:15.931  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:15.931  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:15.933  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:15.933  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:15.937  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:15.937  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:15.937  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:15.937  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:15.938  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b11c46 not in the list
08-16 17:44:15.938  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:15.938  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:15.941  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:44:15.941  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:15.941  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:15.941  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e8d5d removed from the list
08-16 17:44:15.942  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:15.942  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:15.942  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:15.942  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:15.943  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cecb34 removed from the list
08-16 17:44:15.945  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:44:15.945  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd2b6d2 added. We now have 2 listener(s)
,08-16 17:44:15.951  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:44:15.951  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:15.951  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:15.952  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:15.952  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d803a3 added. We now have 9 listener(s)
08-16 17:44:15.952  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:15.953  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:15.957  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:15.964   872  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:15.964  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:15.967  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:15.967  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:44:15.968  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:15.968  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cba259 added. We now have 3 listener(s)
,08-16 17:44:15.970  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:44:15.970  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:15.970  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:15.970  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:15.971  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1016e1e added. We now have 10 listener(s)
08-16 17:44:15.971  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:15.971  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:44:15.971  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:44:15.971  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:44:15.971  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:15.971  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:15.973  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:15.976  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:44:15.976  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:44:15.979  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:15.982  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:44:15.983  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:44:15.983  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:15.988  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:44:15.988  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:15.988  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:44:15.989  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:44:15.993  4298  4337 D BtGatt.GattService: registerClient() - UUID=9d1e5c12-fb45-4d24-8888-bbc611ccf819
,08-16 17:44:15.994  4298  4314 D BtGatt.GattService: onClientRegistered() - UUID=9d1e5c12-fb45-4d24-8888-bbc611ccf819, clientIf=5
08-16 17:44:15.995  3875  3886 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:44:15.998  4298  4308 D BtGatt.GattService: start scan with filters
,08-16 17:44:16.002  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:44:16.002  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:16.002  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:16.002  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:44:16.003  4298  4317 D BtGatt.ScanManager: handling starting scan
,08-16 17:44:16.007  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:16.007  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:44:16.007  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:44:16.008  4298  4317 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca8a8f3
08-16 17:44:16.008  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:16.012  3875  3923 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:44:16.012  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:44:16.012  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:44:16.012  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.013  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:44:16.013  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:44:16.013  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:44:16.013  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:44:16.013  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:44:16.013  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:16.013  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:44:16.015  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:44:16.016  4298  4309 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:44:16.017  4298  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:44:16.017  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.017  4298  4333 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:44:16.017  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:44:16.018  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:44:16.018  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:44:16.018  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:16.018  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:44:16.018  4298  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:44:16.019  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:16.019  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:44:16.020  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:16.020  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:44:16.020  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:16.022  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:16.022  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:16.022  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:16.026  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:44:16.026  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:16.027  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:44:16.028  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.029  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:16.030  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:16.030  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:44:16.030  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:44:16.031  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd2b6d2 removed from the list
08-16 17:44:16.031  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.031  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.032  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d803a3 removed from the list
,08-16 17:44:16.032  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:16.032  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.032  4298  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:16.033  4298  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:44:16.033  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:16.033  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.035  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.035  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.035  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.035  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d803a3 not in the list
,08-16 17:44:16.035  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.035  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:16.036  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:44:16.036  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.037  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.037  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1016e1e removed from the list
08-16 17:44:16.037  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.037  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:16.037  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:16.037  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.037  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cba259 removed from the list
08-16 17:44:16.038  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.038  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d24e2a added. We now have 2 listener(s)
08-16 17:44:16.040  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:16.040  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:16.041  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:16.041  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:16.041  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd8441b added. We now have 9 listener(s)
08-16 17:44:16.041  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:16.042  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:16.047  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:16.053  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:16.055  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:16.055  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:44:16.057  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.058  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e4391 added. We now have 3 listener(s)
08-16 17:44:16.058  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:16.058  4298  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:44:16.059  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.061  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:44:16.061  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:16.061  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:16.062  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:16.062  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:16.062  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1f22f6 added. We now have 10 listener(s)
08-16 17:44:16.062  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:16.062  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:44:16.064  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:16.064  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:44:16.064  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:44:16.064  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:16.064  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:16.068  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:44:16.068  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:44:16.072  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:44:16.073  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:44:16.073  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:44:16.074  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.075  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:16.079  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:44:16.079  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:16.079  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:44:16.080  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:44:16.083  4298  4337 D BtGatt.GattService: registerClient() - UUID=d083560e-2548-4484-a023-2470d140c79b
,08-16 17:44:16.083  4298  4314 D BtGatt.GattService: onClientRegistered() - UUID=d083560e-2548-4484-a023-2470d140c79b, clientIf=5
,08-16 17:44:16.084  3875  3944 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:44:16.084  4298  4308 D BtGatt.GattService: start scan with filters
,08-16 17:44:16.090  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:44:16.090  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.090  4298  4317 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:44:16.092  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:44:16.093  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:16.093  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:16.093  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:44:16.097  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:16.097  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:44:16.097  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:44:16.098  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:44:16.098  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.098  4298  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 17:44:16.100  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:16.104  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:44:16.105  3875  3923 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 17:44:16.105  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:16.105  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:44:16.105  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:16.105  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:16.105  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.105  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:44:16.106  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.106  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d24e2a removed from the list
,08-16 17:44:16.106  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.106  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd8441b removed from the list
08-16 17:44:16.106  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:44:16.106  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:16.107  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.107  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 17:44:16.107  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.107  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:16.109  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.109  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:44:16.110  4298  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:44:16.110  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:16.110  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.110  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd8441b not in the list
,08-16 17:44:16.110  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:44:16.110  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:44:16.110  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:44:16.111  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:16.111  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:44:16.112  4298  4317 D BtGatt.ScanManager: handling starting scan
08-16 17:44:16.112  3875  3923 D BluetoothAdapter: STATE_ON
,08-16 17:44:16.113  4298  4309 D BtGatt.GattService: stopScan() - queue size =0
08-16 17:44:16.114  4298  4333 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:44:16.115  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:44:16.115  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:44:16.115  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:44:16.116  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:16.116  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:44:16.118  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:16.118  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:44:16.118  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:16.119  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:44:16.120  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.121  4298  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:44:16.121  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.121  4298  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:44:16.122  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.122  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:16.123  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.123  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.123  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:16.123  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1f22f6 removed from the list
08-16 17:44:16.123  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.123  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:44:16.123  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.124  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.124  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.124  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e4391 removed from the list
08-16 17:44:16.125  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.126  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f927882 added. We now have 2 listener(s)
08-16 17:44:16.129  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:44:16.129  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.129  4298  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:16.129  4298  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:44:16.130  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:16.131  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:16.131  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:44:16.131  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:16.132  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a11b93 added. We now have 9 listener(s)
08-16 17:44:16.132  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:16.132  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:16.135  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:16.139  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:16.141  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:16.141  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:16.141  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.142  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18cd3c9 added. We now have 3 listener(s)
08-16 17:44:16.143  4298  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:44:16.143  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:16.143  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:16.144  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:16.144  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:16.143  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.144  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:16.144  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f39ace added. We now have 10 listener(s)
08-16 17:44:16.144  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:16.144  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:16.144  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:44:16.144  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:44:16.144  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:16.144  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:16.146  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:16.148  3875  3923 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:44:16.149  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:44:16.151  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:44:16.151  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.154  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:44:16.154  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:44:16.154  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:16.158  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:44:16.159  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:16.159  3875  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:44:16.159  3875  3923 D BluetoothAdapter: STATE_ON
08-16 17:44:16.160  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:44:16.160  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.160  4298  4317 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:44:16.162  4298  4309 D BtGatt.GattService: registerClient() - UUID=8d325d70-9d64-42db-a5dc-28554cc9c133
,08-16 17:44:16.163  4298  4314 D BtGatt.GattService: onClientRegistered() - UUID=8d325d70-9d64-42db-a5dc-28554cc9c133, clientIf=5
08-16 17:44:16.163  3875  3944 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:44:16.163  4298  4337 D BtGatt.GattService: start scan with filters
,08-16 17:44:16.166  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:44:16.166  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:16.166  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:16.167  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:44:16.167  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:44:16.167  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.167  4298  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:44:16.170  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:16.170  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:16.170  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:44:16.172  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:16.173  4298  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:44:16.173  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.174  4298  4317 D BtGatt.ScanManager: handling starting scan
,08-16 17:44:16.177  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:16.177  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:16.177  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:16.178  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:16.178  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:16.178  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:44:16.178  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:44:16.178  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f927882 removed from the list
08-16 17:44:16.178  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.179  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a11b93 removed from the list
08-16 17:44:16.179  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:16.179  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:16.179  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.180  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:44:16.180  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.180  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:16.181  4298  4314 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:44:16.181  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a11b93 not in the list
08-16 17:44:16.181  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:44:16.181  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:44:16.181  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:44:16.181  4298  4317 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:16.181  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:44:16.182  3875  3923 D BluetoothAdapter: STATE_ON
08-16 17:44:16.183  4298  4337 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:44:16.183  4298  4308 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:44:16.184  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:44:16.184  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:44:16.184  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:44:16.184  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:16.184  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:44:16.185  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:16.185  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:44:16.186  3875  3923 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:16.186  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:44:16.187  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:16.187  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:44:16.187  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.187  4298  4317 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:16.187  4298  4317 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:44:16.188  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.188  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.189  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.189  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f39ace removed from the list
08-16 17:44:16.189  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.189  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.189  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.189  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.189  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18cd3c9 removed from the list
,08-16 17:44:16.190  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.190  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3295da added. We now have 2 listener(s)
,08-16 17:44:16.191  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:44:16.191  3875  3875 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:16.192  3875  3875 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:16.192  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:16.192  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:16.192  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:16.193  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:16.193  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6a0b added. We now have 9 listener(s)
08-16 17:44:16.193  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:16.193  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:44:16.199  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:16.205  4298  4314 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:44:16.205  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:44:16.206  3875  3923 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:44:16.209  3875  3923 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:44:16.209  3875  3923 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:16.209  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:16.209  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8463301 added. We now have 3 listener(s)
08-16 17:44:16.211  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:44:16.211  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:16.211  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:16.211  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:16.211  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3435a6 added. We now have 10 listener(s)
08-16 17:44:16.211  3875  3923 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:16.211  3875  3923 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:16.211  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:16.212  3875  3923 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:16.212  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.212  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.212  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:16.212  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.212  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3295da removed from the list
08-16 17:44:16.212  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.212  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6a0b removed from the list
08-16 17:44:16.212  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:16.212  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:44:16.213  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.213  3875  3923 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:16.213  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.213  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.213  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:16.216  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.216  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.217  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.217  3875  3923 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bce6a0b not in the list
,08-16 17:44:16.217  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:16.217  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.218  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:16.218  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:16.218  3875  3923 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:16.218  3875  3923 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3435a6 removed from the list
08-16 17:44:16.218  3875  3923 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:16.218  3875  3923 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:16.219  3875  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:16.219  3875  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:16.219  3875  3923 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8463301 removed from the list
08-16 17:44:16.219  3875  3875 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:16.219  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:16.220  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:16.220  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:44:16.220  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:44:16.220  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:44:16.220  3875  3923 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:16.220  4298  4314 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:44:16.220  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.220  4298  4317 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:44:16.226  3875  4375 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
08-16 17:44:16.227  3875  4375 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
08-16 17:44:16.227  3875  4375 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:16.228  4298  4314 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 17:44:16.228  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:44:16.229  4298  4317 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:44:16.230  3875  4376 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: My test thread name)
,08-16 17:44:16.230  3875  4376 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: My test thread name)
08-16 17:44:16.230  3875  4376 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:16.232  3875  3923 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 17:44:16.232  3875  3923 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-16 17:44:16.232  3875  3923 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:44:16.232  3875  3923 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:44:16.232  3875  3923 D com.test.thalitest.ThaliTestRunner: Total duration: 22917 ms
08-16 17:44:16.233  4298  4314 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:44:16.234  4298  4314 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:44:16.234  3875  3923 I jxcore-log: Total number of executed tests:  80
08-16 17:44:16.234  3875  3923 I jxcore-log: 
08-16 17:44:16.234  3875  3923 I jxcore-log: Number of passed tests:  80
08-16 17:44:16.234  3875  3923 I jxcore-log: 
08-16 17:44:16.234  3875  3923 I jxcore-log: Number of failed tests:  0
08-16 17:44:16.234  3875  3923 I jxcore-log: 
,08-16 17:44:16.234  3875  3923 I jxcore-log: Number of ignored tests:  0
08-16 17:44:16.234  3875  3923 I jxcore-log: 
08-16 17:44:16.234  3875  3923 I jxcore-log: Total duration:  22917
08-16 17:44:16.234  3875  3923 I jxcore-log: 
,08-16 17:44:16.235  3875  3923 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:44:16.235  3875  3923 I jxcore-log: 
,08-16 17:44:16.238  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.238  3875  3923 I jxcore-log: 
08-16 17:44:16.240  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.240  3875  3923 I jxcore-log: 
08-16 17:44:16.241  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.241  3875  3923 I jxcore-log: 
08-16 17:44:16.242  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.242  3875  3923 I jxcore-log: 
08-16 17:44:16.243  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.243  3875  3923 I jxcore-log: 
08-16 17:44:16.243  3875  3875 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:44:16.244  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.244  3875  3923 I jxcore-log: 
08-16 17:44:16.245  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.245  3875  3923 I jxcore-log: 
08-16 17:44:16.247  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.247  3875  3923 I jxcore-log: 
08-16 17:44:16.247  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.247  3875  3923 I jxcore-log: 
08-16 17:44:16.248  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:16.248  3875  3923 I jxcore-log: 
08-16 17:44:16.249  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:16.249  3875  3923 I jxcore-log: 
08-16 17:44:16.250  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:16.250  3875  3923 I jxcore-log: 
08-16 17:44:16.251  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.251  3875  3923 I jxcore-log: 
08-16 17:44:16.252  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.252  3875  3923 I jxcore-log: 
08-16 17:44:16.253  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.253  3875  3923 I jxcore-log: 
08-16 17:44:16.254  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.254  3875  3923 I jxcore-log: 
08-16 17:44:16.254  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.254  3875  3923 I jxcore-log: 
08-16 17:44:16.255  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.255  3875  3923 I jxcore-log: 
08-16 17:44:16.255  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.255  3875  3923 I jxcore-log: 
,08-16 17:44:16.256  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.256  3875  3923 I jxcore-log: 
08-16 17:44:16.257  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.257  3875  3923 I jxcore-log: 
08-16 17:44:16.258  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:16.258  3875  3923 I jxcore-log: 
08-16 17:44:16.258  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:16.258  3875  3923 I jxcore-log: 
,08-16 17:44:16.259  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:16.259  3875  3923 I jxcore-log: 
,08-16 17:44:16.260  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.260  3875  3923 I jxcore-log: 
08-16 17:44:16.261  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.261  3875  3923 I jxcore-log: 
,08-16 17:44:16.262  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.262  3875  3923 I jxcore-log: 
08-16 17:44:16.263  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.263  3875  3923 I jxcore-log: 
,08-16 17:44:16.263  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.263  3875  3923 I jxcore-log: 
08-16 17:44:16.264  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:16.264  3875  3923 I jxcore-log: 
,08-16 17:44:16.522  3875  3875 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:44:16.525  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:16.525  3875  3923 I jxcore-log: 
,08-16 17:44:16.624  3875  3875 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:16.627  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:16.627  3875  3923 I jxcore-log: 
,08-16 17:44:16.692  3875  3875 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:16.695  3875  3923 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:16.695  3875  3923 I jxcore-log: 
,08-16 17:44:16.884  4377  4377 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 17:44:16.889  4377  4377 D AndroidRuntime: CheckJNI is OFF
,08-16 17:44:16.932  4377  4377 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 17:44:16.980  4377  4377 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 17:44:17.003  4377  4377 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:44:17.015   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 17:44:17.016   872   885 I ActivityManager: Killing 3875:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 17:44:17.120   872   883 I WindowState: WIN DEATH: Window{e58860e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:44:17.122   872  2012 D GraphicsStats: Buffer count: 2
,08-16 17:44:17.122   872  1318 D WifiService: Client connection lost with reason: 4
,08-16 17:44:17.137   872   896 W PackageSettings: Skipping PackageSetting{6d7cf94 com.example.hello/10273} due to missing metadata
,08-16 17:44:17.169   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 17:44:17.169   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-16 17:44:17.170   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-16 17:44:17.170   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 17:44:17.170   872   885 E ActivityManager: ,	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 17:44:17.170   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.170   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.170   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:17.170   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46),
08-16 17:44:17.170   872   885 I ActivityManager:   Force finishing activity ActivityRecord{21eb357 u0 com.test.thalitest/.MainActivity t2}
,08-16 17:44:17.173   872   896 I art     : Starting a blocking GC Explicit
,08-16 17:44:17.178   872   882 W ActivityManager: Spurious death for ProcessRecord{7f29157 0:com.test.thalitest/u0a0}, curProc for 3875: null
,08-16 17:44:17.212   872   896 I art     : Explicit concurrent mark sweep GC freed 14159(984KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 662us total 37.499ms
,08-16 17:44:17.238   872   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 17:44:17.242  4377  4377 I art     : System.exit called, status: 0
,08-16 17:44:17.243  4377  4377 I AndroidRuntime: VM exiting with result code 0.
,08-16 17:44:17.299   872   896 I ActivityManager: Start proc 4389:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-16 17:44:17.299   872   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 17:44:17.334   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-16 17:44:17.340  4298  4298 D BluetoothMapAppObserver: onReceive
08-16 17:44:17.340  4298  4298 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 17:44:17.344  2089  2292 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:44:17.349  1864  1864 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 17:44:17.361   872  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:44:17.363  3647  3647 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 17:44:17.364  1864  4402 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 17:44:17.371  1864  4402 I Decoder : createOrResetDecoder
,08-16 17:44:17.389  1924  1924 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 17:44:17.408   872   882 I ActivityManager: Start proc 4405:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 17:44:17.409   872  1315 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-16 17:44:17.412  1532  1532 I ConfigService: onCreate
,08-16 17:44:17.417  1532  4411 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 17:44:17.417  1532  4411 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 17:44:17.417  1532  4411 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-16 17:44:17.423  1532  4411 W SQLiteOpenHelper: Opened config.db in read-only mode,
08-16 17:44:17.432   872  2258 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3875 uid 10000
,08-16 17:44:17.446   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:44:17.448  1864  1864 I Keyboard.Facilitator: onFinishInput()
,08-16 17:44:17.456  1864  4402 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 17:44:17.473  4405  4405 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 17:44:17.478  1936  2015 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-16 17:44:17.479   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 17:44:17.479   872   884 E PackageManager: Failed to write settings, restoring backup
08-16 17:44:17.479   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 17:44:17.479   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 17:44:17.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 17:44:17.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 17:44:17.479   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 17:44:17.479   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.479   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.479   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:44:17.484   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-16 17:44:17.484   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 17:44:17.484   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:44:17.484   872   885 E DropBoxManagerService: 	... 13 more
,08-16 17:44:17.492   872  1722 I ActivityManager: Start proc 4419:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 17:44:17.492  1936  2015 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 17:44:17.492  1936  2015 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1936
08-16 17:44:17.492  1936  2015 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.492  1936  2015 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:17.494   872  2106 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 17:44:17.495   872  4425 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:44:17.495   872  4425 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:44:17.495   872  4425 E DropBoxManagerService: 	... 5 more
,08-16 17:44:17.498  1936  2015 I Process : Sending signal. PID: 1936 SIG: 9
,08-16 17:44:17.502  1864  4402 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-16 17:44:17.504  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 17:44:17.504  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 17:44:17.509  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 17:44:17.509  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-16 17:44:17.511  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-16 17:44:17.512  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 17:44:17.519  1864  4402 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 17:44:17.519  1864  4402 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 17:44:17.519  1864  4402 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 17:44:17.519  1864  4402 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 17:44:17.519  1864  4402 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 17:44:17.519  1864  4402 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 17:44:17.542  4405  4405 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 17:44:17.558   872   883 I WindowState: WIN DEATH: Window{eadd12d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 17:44:17.558   872  1386 D GraphicsStats: Buffer count: 1
,08-16 17:44:17.563   872  3133 I ActivityManager: Start proc 4437:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 17:44:17.572  4405  4436 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 17:44:17.573   872  1554 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1936) has died
08-16 17:44:17.573   872  1554 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 17:44:17.574   872  1554 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 17:44:17.585  4405  4436 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.585  4405  4436 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:44:17.587  4405  4436 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 17:44:17.587  4405  4436 E AndroidRuntime: Process: android.process.acore, PID: 4405
08-16 17:44:17.587  4405  4436 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.587  4405  4436 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:44:17.594   872   885 I ActivityManager: Start proc 4449:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:44:17.601  4405  4436 I Process : Sending signal. PID: 4405 SIG: 9
,08-16 17:44:17.604   872  4459 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:44:17.604   872  4459 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:44:17.604   872  4459 E DropBoxManagerService: 	... 5 more
,08-16 17:44:17.612   281   281 E lowmemorykiller: Error writing /proc/4405/oom_score_adj; errno=22
,08-16 17:44:17.619  4437  4437 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 17:44:17.638  1532  1532 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 17:44:17.639  1532  1532 D AndroidRuntime: Shutting down VM
08-16 17:44:17.639  1532  1532 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:44:17.639  1532  1532 E AndroidRuntime: Process: com.google.process.gapps, PID: 1532
08-16 17:44:17.639  1532  1532 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 17:44:17.639  1532  1532 E AndroidRuntime: 	... 8 more
,08-16 17:44:17.642  4449  4449 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:44:17.642  4449  4449 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:44:17.642  4449  4449 D AndroidRuntime: Shutting down VM
08-16 17:44:17.642   872  4465 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:44:17.642   872  4465 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:44:17.642   872  4465 E DropBoxManagerService: 	... 5 more
,08-16 17:44:17.643  1532  1532 I Process : Sending signal. PID: 1532 SIG: 9
,08-16 17:44:17.647  4449  4449 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:44:17.647  4449  4449 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4449
08-16 17:44:17.647  4449  4449 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:44:17.647  4449  4449 E AndroidRuntime: 	... 10 more
,08-16 17:44:17.649   872  1723 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 17:44:17.649  4449  4449 I Process : Sending signal. PID: 4449 SIG: 9
08-16 17:44:17.650   872  4466 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:44:17.650   872  4466 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:44:17.650   872  4466 E DropBoxManagerService: 	... 5 more
,08-16 17:44:17.664   281   281 E lowmemorykiller: Error writing /proc/4405/oom_score_adj; errno=22
,08-16 17:44:17.672   281   281 E lowmemorykiller: Error writing /proc/4405/oom_score_adj; errno=22
,08-16 17:44:17.673   872  2106 I ActivityManager: Killing 1993:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-16 17:44:17.682   872  1317 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-16 17:44:17.694   872  1318 D WifiService: Client connection lost with reason: 4
,08-16 17:44:17.696  1753  4467 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@3670a15
,08-16 17:44:17.720   872  1318 D WifiService: Client connection lost with reason: 4
,08-16 17:44:17.720   872  2258 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4449) has died
,08-16 17:44:17.722   872  2258 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 17:44:17.725   872  1722 I ActivityManager: Process com.google.process.gapps (pid 1532) has died
,08-16 17:44:17.725   872  1722 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-16 17:44:17.725   872  1722 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-16 17:44:17.725   872  1722 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-16 17:44:17.726   872  1722 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,08-16 17:44:17.739   872   885 I ActivityManager: Start proc 4470:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:44:17.740   872   883 I ActivityManager: Process android.process.acore (pid 4405) has died

```
