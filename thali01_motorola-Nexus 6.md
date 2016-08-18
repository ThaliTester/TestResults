#### Test 80807573fdd3b64_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-18 11:56:52.475   875  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-18 11:56:53.222  3822  3822 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-18 11:56:53.227  3822  3822 D AndroidRuntime: CheckJNI is OFF
08-18 11:56:53.270  3822  3822 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-18 11:56:53.317  3822  3822 I Radio-JNI: register_android_hardware_Radio DONE
08-18 11:56:53.340  3822  3822 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 11:56:53.344   875  2047 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 11:56:53.381  2011  2037 W SearchService: Abort, client detached.
08-18 11:56:53.390  2011  2352 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@812ef80
08-18 11:56:53.390  2011  2361 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-18 11:56:53.389  2011  2011 I HotwordDetector: Closing mic
08-18 11:56:53.392  3822  3822 D AndroidRuntime: Shutting down VM
08-18 11:56:53.412   875  2040 I ActivityManager: Start proc 3831:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-18 11:56:53.452   377  2363 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-18 11:56:53.453   377  2363 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-18 11:56:53.458   377  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-18 11:56:53.461  2011  2360 I MicroRecognitionRnrImpl: Detection finished
08-18 11:56:53.461  2011  2359 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-18 11:56:53.489  3831  3831 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-18 11:56:53.510  3831  3831 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-18 11:56:53.516  3831  3831 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3985-3987)
08-18 11:56:53.517  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:56:53.528  3831  3831 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce4a549}
08-18 11:56:53.528  3831  3831 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:56:53.528  3831  3831 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 11:56:53.533  3831  3831 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 11:56:53.534  3831  3831 E SysUtils: ApplicationContext is null in ApplicationStatus
08-18 11:56:53.545  3831  3831 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-18 11:56:53.554  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:56:53.554  3831  3831 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:56:53.555  3831  3831 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 11:56:53.555  3831  3831 I Adreno  : Build Date                       : 10/20/15
08-18 11:56:53.555  3831  3831 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 11:56:53.555  3831  3831 I Adreno  : Local Branch                     : M14
08-18 11:56:53.555  3831  3831 I Adreno  : Remote Branch                    : 
08-18 11:56:53.555  3831  3831 I Adreno  : Remote Branch                    : 
08-18 11:56:53.555  3831  3831 I Adreno  : Reconstruct Branch               : 
08-18 11:56:53.596   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58232aa:true
08-18 11:56:53.624  3831  3831 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-18 11:56:53.635  3831  3831 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-18 11:56:53.666  3831  3869 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-18 11:56:53.673  3831  3856 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-18 11:56:53.702  3831  3869 I OpenGLRenderer: Initialized EGL, version 1.4
,08-18 11:56:53.751   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +357ms
,08-18 11:56:53.753  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-18 11:56:53.794  3831  3831 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3831
,08-18 11:56:53.894  3831  3831 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 11:56:54.096  3831  3871 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700595408
,08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-18 11:56:54.102  3831  3871 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1663d4 added. We now have 1 listener(s)
,08-18 11:56:54.106  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-18 11:56:54.107  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:56:54.108  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:56:54.108  3831  3871 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 11:56:54.111  3831  3871 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ac6cc3 added. We now have 1 listener(s)
,08-18 11:56:54.111  3831  3871 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:56:54.116   875  1313 D WifiService: New client listening to asynchronous messages
08-18 11:56:54.116  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:56:54.116  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-18 11:56:54.117  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 11:56:54.117  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-18 11:56:54.117  3831  3871 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-18 11:56:54.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:56:54.123  3831  3871 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-18 11:56:54.133  3831  3871 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:56:54.133  3831  3871 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:56:54.133  3831  3871 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 11:56:54.133  3831  3871 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 11:56:54.135  3831  3871 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 11:56:54.136  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:56:54.139  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:56:54.190   875  2010 I ActivityManager: Killing 3573:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-18 11:56:54.216   875  2010 I ActivityManager: Killing 2247:com.google.android.talk/u0a61 (adj 15): empty #18
,08-18 11:56:54.312  3831  3831 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 11:56:55.106  3831  3880 W jxcore-log: Initializing JXcore engine
,08-18 11:56:55.107  3831  3880 W jxcore-log: JXcore engine is ready
,08-18 11:56:55.155  3880  3880 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-18 11:56:55.155  3880  3880 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11783]" dev="sockfs" ino=11783 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-18 11:56:55.155  3880  3880 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-18 11:56:55.155  3880  3880 W Thread-337: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[26190]" dev="sockfs" ino=26190 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-18 11:56:55.169  3831  3880 W jxcore-log: Starting JXcore engine
,08-18 11:56:55.271  3831  3880 W jxcore-log: Platform android
08-18 11:56:55.271  3831  3880 W jxcore-log: 
,08-18 11:56:55.271  3831  3880 W jxcore-log: Process ARCH arm
08-18 11:56:55.271  3831  3880 W jxcore-log: 
,08-18 11:56:55.682  3831  3880 I jxcore-log: JXcore Cordova bridge is ready!
08-18 11:56:55.682  3831  3880 I jxcore-log: 
08-18 11:56:55.683  3831  3880 W jxcore-log: JXcore engine is started
,08-18 11:56:55.688  3831  3871 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-18 11:56:55.693  3831  3831 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-18 11:56:56.046   875  1887 D NetlinkSocketObserver: NeighborEvent{elapsedMs=126517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 11:56:57.592  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:56:57.598  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:56:57.650  1509  2298 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 11:56:57.651  1509  2298 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-18 11:56:57.651  1509  2298 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 11:56:57.652  1509  2298 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:56:57.681  3554  3885 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-18 11:56:57.681  3554  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jdm.a(PG:82)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jcs.o(PG:406)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jcn.a(PG:1379)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jcs.i(PG:143)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at blb.a(PG:3937)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at czp.a(PG:18188)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at czp.a(PG:9081)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at czq.run(PG:1686)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 11:56:57.681  3554  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jdj.a(PG:4091)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jdj.a(PG:1125)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jdm.a(PG:77)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	... 12 more
08-18 11:56:57.681  3554  3885 E HttpOperation: Caused by: faj: BadAuthentication
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at fal.a(PG:38)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	at jdj.a(PG:4089)
08-18 11:56:57.681  3554  3885 E HttpOperation: 	... 14 more
,08-18 11:56:57.733  1509  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-18 11:56:57.733  1509  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-18 11:56:57.734  1509  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 11:56:57.734  1509  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:56:57.754  3554  3885 E HttpOperation: [getmobileexperiments] Unexpected exception
08-18 11:56:57.754  3554  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jdm.a(PG:82)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jcs.o(PG:406)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jcn.a(PG:1379)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jcs.i(PG:143)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at hec.a(PG:42)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at hee.a(PG:102)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at czr.a(PG:65)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at kka.a(PG:108)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at czp.a(PG:19176)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at czp.a(PG:9081)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at czq.run(PG:1686)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-18 11:56:57.754  3554  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jdj.a(PG:4091)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jdj.a(PG:1125)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jdm.a(PG:77)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	... 15 more
08-18 11:56:57.754  3554  3885 E HttpOperation: Caused by: faj: BadAuthentication
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at fal.a(PG:38)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	at jdj.a(PG:4089)
08-18 11:56:57.754  3554  3885 E HttpOperation: 	... 17 more
,08-18 11:56:57.755  3554  3885 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-18 11:56:57.755  3554  3885 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jdm.a(PG:82)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jcs.o(PG:406)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jcn.a(PG:1379)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jcs.i(PG:143)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at hec.a(PG:42)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at hee.a(PG:102)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at czr.a(PG:65)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at kka.a(PG:108)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at czp.a(PG:19176)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at czp.a(PG:9081)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at czq.run(PG:1686)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jdj.a(PG:4091)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jdj.a(PG:1125)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jdm.a(PG:77)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	... 15 more
08-18 11:56:57.755  3554  3885 E ExperimentLoader: Caused by: faj: BadAuthentication
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at fal.a(PG:38)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	at jdj.a(PG:4089)
08-18 11:56:57.755  3554  3885 E ExperimentLoader: 	... 17 more
,08-18 11:56:57.871   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 127824, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-18 11:56:58.606  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:56:58.638  1509  2298 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-18 11:56:58.638  1509  2298 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-18 11:56:58.638  1509  2298 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 11:56:58.638  1509  2298 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:56:58.663  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-18 11:56:58.664  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 11:56:58.664  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-18 11:57:05.677  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-18 11:57:05.677  3831  3880 I jxcore-log: 
,08-18 11:57:05.679  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-18 11:57:05.679  3831  3880 I jxcore-log: 
,08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:05.689  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:05.692  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:05.694  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-18 11:57:05.694  3831  3880 I jxcore-log: 
,08-18 11:57:05.696  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-18 11:57:05.696  3831  3880 I jxcore-log: 
,08-18 11:57:06.036  3831  3880 D ExecuteNativeTests: Running unit tests
,08-18 11:57:06.094  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 11:57:06.094  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 added. We now have 2 listener(s)
,08-18 11:57:06.095  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 11:57:06.095  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 11:57:06.095  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:06.095  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:06.096  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 added. We now have 2 listener(s)
08-18 11:57:06.096  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:06.096  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:57:06.098  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.108  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:06.113  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:06.114  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 11:57:06.116  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.121  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.121  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-18 11:57:06.121  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-18 11:57:06.122  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-18 11:57:06.126  3831  3880 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-18 11:57:06.127  3831  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-18 11:57:06.127  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-18 11:57:06.128  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 11:57:06.128  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 11:57:06.131  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.132  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.133  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.135  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.135  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.135  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.137  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:06.137  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 removed from the list
08-18 11:57:06.137  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.137  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 removed from the list
08-18 11:57:06.137  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.137  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.138  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.138  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.140  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.140  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:06.140  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.140  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.142  3831  3880 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-18 11:57:06.143  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.143  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.143  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 11:57:06.144  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.144  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.144  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.144  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.144  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.144  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.144  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop,
08-18 11:57:06.144  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.145  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.145  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.145  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.146  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.146  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.146  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.146  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 11:57:06.150  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-18 11:57:06.151  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-18 11:57:06.152  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-18 11:57:06.152  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-18 11:57:06.152  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-18 11:57:06.152  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 11:57:06.152  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 11:57:06.152  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.152  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.152  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:06.152  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.152  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.152  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.152  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.152  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.152  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop,
08-18 11:57:06.152  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.152  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.153  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.153  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.153  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.153  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.153  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.154  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.154  3831  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 11:57:06.156  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.161  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:06.163  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.163  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:06.164  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 11:57:06.164  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 11:57:06.164  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 11:57:06.164  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.164  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 11:57:06.167  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.168  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 11:57:06.168  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 11:57:06.169  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.175  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 11:57:06.178  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 11:57:06.178  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 11:57:06.182  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-18 11:57:06.185  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-18 11:57:06.185  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 11:57:06.185  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 11:57:06.186  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-18 11:57:06.187  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:06.191  2678  2810 D BtGatt.GattService: registerClient() - UUID=88388332-d019-4fe0-b5ff-bccac92448ba
08-18 11:57:06.192  2678  2697 D BtGatt.GattService: onClientRegistered() - UUID=88388332-d019-4fe0-b5ff-bccac92448ba, clientIf=5
,08-18 11:57:06.193  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 11:57:06.194  2678  2820 D BtGatt.GattService: start scan with filters
,08-18 11:57:06.198  2678  2700 D BtGatt.ScanManager: handling starting scan
,08-18 11:57:06.198  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 11:57:06.198  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 11:57:06.199  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-18 11:57:06.199  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 11:57:06.199  2678  2700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:06.201  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:06.202  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 11:57:06.202  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 11:57:06.203  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 11:57:06.205  3831  3880 I io.jxcore.node.ConnectionHelper: start: OK
,08-18 11:57:06.207  2678  2697 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 11:57:06.207  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:06.208  2678  2700 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 11:57:06.209  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.209  3831  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 11:57:06.210  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 11:57:06.210  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 11:57:06.210  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.210  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 11:57:06.210  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 11:57:06.210  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 11:57:06.210  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 11:57:06.210  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 11:57:06.210  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:06.211  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 11:57:06.211  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:06.211  2678  2689 D BtGatt.GattService: stopScan() - queue size =1
08-18 11:57:06.212  2678  2810 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 11:57:06.212  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 11:57:06.212  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 11:57:06.212  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 11:57:06.212  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:06.212  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 11:57:06.213  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.213  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-18 11:57:06.214  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:06.214  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 11:57:06.214  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.215  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:06.215  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:06.215  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 11:57:06.215  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.215  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.216  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.216  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.216  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.216  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.216  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.216  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.216  3831  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 11:57:06.217  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.218  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 11:57:06.218  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.218  2678  2700 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:06.218  2678  2700 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.226  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:06.229  2678  2697 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 11:57:06.229  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.229  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.230  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 11:57:06.231  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.231  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 11:57:06.231  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 11:57:06.232  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 11:57:06.232  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:06.232  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 11:57:06.233  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.234  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 11:57:06.234  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 11:57:06.237  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 11:57:06.237  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:06.238  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 11:57:06.238  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 11:57:06.239  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 11:57:06.243  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 11:57:06.243  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 11:57:06.243  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.243  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 11:57:06.243  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-18 11:57:06.244  2678  2700 D BtGatt.ScanManager: stopping BLe Batch
,08-18 11:57:06.244  3831  3880 D BluetoothAdapter: STATE_ON
08-18 11:57:06.246  2678  2689 D BtGatt.GattService: registerClient() - UUID=ba7ef87b-52b1-49fb-89b2-8119e141b762
,08-18 11:57:06.246  2678  2697 D BtGatt.GattService: onClientRegistered() - UUID=ba7ef87b-52b1-49fb-89b2-8119e141b762, clientIf=5
08-18 11:57:06.246  3831  3881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 11:57:06.247  2678  2810 D BtGatt.GattService: start scan with filters
,08-18 11:57:06.251  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 11:57:06.251  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 11:57:06.251  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-18 11:57:06.251  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 11:57:06.252  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 11:57:06.252  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:06.252  2678  2700 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-18 11:57:06.254  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 11:57:06.255  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 11:57:06.255  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:06.255  2678  2697 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 11:57:06.255  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.257  2678  2700 D BtGatt.ScanManager: handling starting scan
,08-18 11:57:06.257  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-18 11:57:06.261  3831  3880 I io.jxcore.node.ConnectionHelper: start: OK,
,08-18 11:57:06.263  2678  2697 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 11:57:06.263  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:06.264  2678  2700 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 11:57:06.265  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 11:57:06.265  3831  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-18 11:57:06.265  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 11:57:06.265  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 11:57:06.265  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.265  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 11:57:06.266  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 11:57:06.266  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 11:57:06.266  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 11:57:06.266  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 11:57:06.266  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:06.266  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 11:57:06.267  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:06.268  2678  2820 D BtGatt.GattService: stopScan() - queue size =1
08-18 11:57:06.268  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 11:57:06.268  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.268  2678  2700 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:06.268  2678  2689 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 11:57:06.269  2678  2700 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 11:57:06.269  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 11:57:06.269  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 11:57:06.269  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 11:57:06.269  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:06.269  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 11:57:06.271  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.271  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 11:57:06.271  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:06.271  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 11:57:06.272  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.274  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.274  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.274  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:06.274  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.274  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:06.274  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.274  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.274  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.274  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.274  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.274  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.275  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.275  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.276  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.276  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.276  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.277  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.277  2678  2697 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 11:57:06.277  3831  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-18 11:57:06.277  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.281  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.284  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:06.284  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 11:57:06.285  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.286  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.286  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:06.286  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 11:57:06.286  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 11:57:06.286  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-18 11:57:06.286  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.286  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 11:57:06.290  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 11:57:06.290  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 11:57:06.290  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.291  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.295  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 11:57:06.295  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.296  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 11:57:06.296  2678  2700 D BtGatt.ScanManager: stopping BLe Batch
08-18 11:57:06.296  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 11:57:06.296  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 11:57:06.299  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 11:57:06.299  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 11:57:06.299  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-18 11:57:06.299  3831  3880 D BluetoothAdapter: STATE_ON
08-18 11:57:06.301  2678  2810 D BtGatt.GattService: registerClient() - UUID=1c2dde9c-b612-45e3-82da-240fbe83830f
08-18 11:57:06.301  2678  2697 D BtGatt.GattService: onClientRegistered() - UUID=1c2dde9c-b612-45e3-82da-240fbe83830f, clientIf=5
08-18 11:57:06.303  3831  3881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 11:57:06.303  2678  2690 D BtGatt.GattService: start scan with filters
08-18 11:57:06.305  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 11:57:06.305  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 11:57:06.305  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 11:57:06.305  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-18 11:57:06.305  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 11:57:06.306  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.306  2678  2700 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 11:57:06.309  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:06.309  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:06.309  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 11:57:06.311  2678  2697 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 11:57:06.312  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-18 11:57:06.312  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.314  2678  2700 D BtGatt.ScanManager: handling starting scan
08-18 11:57:06.314  3831  3880 I io.jxcore.node.ConnectionHelper: start: OK
08-18 11:57:06.314  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.314  3831  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 11:57:06.315  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.315  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 11:57:06.315  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.316  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 11:57:06.317  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 11:57:06.317  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 11:57:06.317  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 11:57:06.317  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 11:57:06.318  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:06.318  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 11:57:06.318  3831  3880 D BluetoothAdapter: STATE_ON
08-18 11:57:06.318  2678  2690 D BtGatt.GattService: stopScan() - queue size =1
08-18 11:57:06.319  2678  2820 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 11:57:06.319  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 11:57:06.319  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 11:57:06.319  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 11:57:06.319  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:06.319  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-18 11:57:06.320  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.320  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-18 11:57:06.320  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:06.320  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 11:57:06.320  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.322  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:06.323  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:06.323  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.323  2678  2697 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 11:57:06.326  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.326  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.326  2678  2700 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-18 11:57:06.327  3831  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-18 11:57:06.327  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.327  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.327  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.327  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.327  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:06.327  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.327  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.328  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.328  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.328  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.328  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.328  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.329  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.329  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.329  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.329  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.330  3831  3880 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-18 11:57:06.330  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.330  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.330  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.330  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.330  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.330  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.330  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.330  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.330  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.330  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.330  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.330  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.330  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.330  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.331  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.331  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.331  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.331  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.332  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 11:57:06.332  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.332  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.332  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.332  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.332  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.332  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.332  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.332  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.332  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.332  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.332  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.332  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.333  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.333  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.334  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.334  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.334  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.334  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.335  3831  3880 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-18 11:57:06.335  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.335  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.335  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.335  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.335  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.335  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.335  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.335  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.335  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.335  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 11:57:06.338  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.335  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.341  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.341  2678  2700 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:06.341  2678  2700 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 11:57:06.341  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.343  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.343  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.344  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.344  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.345  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.345  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.345  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-18 11:57:06.345  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.345  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.345  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.345  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.345  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.346  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.346  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.346  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.346  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.346  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.346  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.346  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.346  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.346  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.346  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.346  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.347  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.347  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.347  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 11:57:06.348  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 11:57:06.348  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 11:57:06.348  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-18 11:57:06.348  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-18 11:57:06.348  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-18 11:57:06.349  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.352  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.352  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.352  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.352  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.352  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.352  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.352  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.352  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.352  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.352  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.352  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.352  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.352  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.355  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.355  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.355  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.355  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.357  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 11:57:06.357  3831  3880 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 11:57:06.358  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-18 11:57:06.364  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 11:57:06.364  3831  3880 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-18 11:57:06.364  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-18 11:57:06.365  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-18 11:57:06.367  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-18 11:57:06.367  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-18 11:57:06.367  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-18 11:57:06.368  3831  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 11:57:06.368  2678  2697 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 11:57:06.368  3831  3880 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-18 11:57:06.368  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.368  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-18 11:57:06.369  3831  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-18 11:57:06.369  3831  3880 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-18 11:57:06.369  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-18 11:57:06.369  3831  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-18 11:57:06.369  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-18 11:57:06.373  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-18 11:57:06.374  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-18 11:57:06.374  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-18 11:57:06.374  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-18 11:57:06.374  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-18 11:57:06.375  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-18 11:57:06.375  3831  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-18 11:57:06.375  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 11:57:06.375  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.376  3831  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
08-18 11:57:06.375  3831  3880 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-18 11:57:06.378  3831  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 11:57:06.380  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.380  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.380  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.380  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.380  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.380  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.380  2678  2697 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 11:57:06.380  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.380  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-18 11:57:06.381  2678  2700 D BtGatt.ScanManager: stopping BLe Batch
08-18 11:57:06.382  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.382  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.383  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.383  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.383  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.383  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.383  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.383  3831  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
08-18 11:57:06.383  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.383  3831  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 402)
,08-18 11:57:06.383  2678  2807 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-18 11:57:06.383  3831  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 402)
,08-18 11:57:06.383  3831  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
08-18 11:57:06.383  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.384  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.384  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.384  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.384  3831  3880 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-18 11:57:06.385  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.385  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.385  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-18 11:57:06.385  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:06.385  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.385  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.385  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.385  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.385  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.385  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.385  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.385  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.386  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.386  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.387  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.387  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.387  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.387  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.388  3831  3880 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-18 11:57:06.388  2678  2697 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 11:57:06.388  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.388  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.388  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.388  2678  2700 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 11:57:06.388  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.388  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.389  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.389  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.389  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.389  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.389  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.389  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.389  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.389  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.389  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.389  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.390  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.390  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.390  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.390  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-18 11:57:06.391  3831  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-18 11:57:06.391  3831  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-18 11:57:06.391  3831  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-18 11:57:06.391  3831  3880 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-18 11:57:06.391  3831  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-18 11:57:06.391  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 11:57:06.391  3831  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-18 11:57:06.392  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 11:57:06.392  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.392  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.392  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.392  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.392  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.392  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.392  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.392  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.392  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.392  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.392  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.392  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.393  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.394  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.394  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:06.394  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.394  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.394  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.394  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.394  2678  2697 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 11:57:06.394  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.394  2678  2697 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:06.394  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.395  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.395  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.395  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.395  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.395  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.395  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.395  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.395  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.395  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.395  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.395  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.395  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.395  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.395  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.396  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.396  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.396  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.396  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.396  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.396  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.396  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 11:57:06.396  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.396  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.396  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.396  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.397  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.397  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.397  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.397  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.398  3831  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-18 11:57:06.399  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:06.399  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-18 11:57:06.400  3831  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-18 11:57:06.400  3831  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-18 11:57:06.400  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-18 11:57:06.400  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-18 11:57:06.400  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 11:57:06.401  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.401  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-18 11:57:06.401  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-18 11:57:06.401  3831  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 11:57:06.401  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-18 11:57:06.401  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.401  3831  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-18 11:57:06.401  3831  3831 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-18 11:57:06.401  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.401  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.401  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 11:57:06.402  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-18 11:57:06.402  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 11:57:06.402  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.402  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:06.403  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.403  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:06.403  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:06.403  3831  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-18 11:57:06.403  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:06.403  3831  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-18 11:57:06.403  3831  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-18 11:57:06.403  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.403  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.404  3831  3831 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-18 11:57:06.404  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.404  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.404  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.404  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.404  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.404  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.404  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.404  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.404  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 11:57:06.404  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.404  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.404  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.404  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.406  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.406  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:06.406  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.406  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.407  3831  3880 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-18 11:57:06.407  3831  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-18 11:57:06.407  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-18 11:57:06.407  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-18 11:57:06.407  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.408  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.408  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.408  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.408  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.408  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.408  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.408  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.408  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.408  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.408  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.408  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.408  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.408  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.410  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:06.410  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.410  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:06.410  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.413  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.413  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.413  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:06.413  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:06.413  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.413  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.414  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.414  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.414  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.414  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:06.414  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:06.414  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.414  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.414  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.415  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.415  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.415  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.415  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.416  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:06.416  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:06.416  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 11:57:06.416  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:06.416  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.416  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.416  3831  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ea8f83 not in the list
08-18 11:57:06.417  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.417  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
08-18 11:57:06.417  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 11:57:06.417  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.417  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.417  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:06.417  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:06.418  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:06.418  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:06.418  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:06.418  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb3500 not in the list
,08-18 11:57:06.419  3831  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-18 11:57:06.419  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 11:57:06.419  3831  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-18 11:57:06.419  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-18 11:57:06.419  3831  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-18 11:57:06.419  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-18 11:57:06.421  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-18 11:57:06.421  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-18 11:57:06.421  3831  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-18 11:57:06.421  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 11:57:06.421  3831  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-18 11:57:06.421  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-18 11:57:06.421  3831  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-18 11:57:06.422  3831  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-18 11:57:06.422  3831  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-18 11:57:06.422  3831  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-18 11:57:06.423  3831  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-18 11:57:06.423  3831  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-18 11:57:06.423  3831  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-18 11:57:06.423  3831  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-18 11:57:06.424  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:06.424  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ecdfe2 added. We now have 2 listener(s)
08-18 11:57:06.424  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:06.426  3831  3880 D BluetoothAdapter: enable(): BT is already enabled..!
08-18 11:57:06.427   875   885 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,08-18 11:57:06.427   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 11:57:06.427  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:06.428  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5de5f73 added. We now have 3 listener(s)
08-18 11:57:06.428  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:06.434  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:06.434  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b5de30 added. We now have 4 listener(s)
08-18 11:57:06.434  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:06.436  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:06.437  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e426aa9 added. We now have 5 listener(s)
08-18 11:57:06.437  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:06.438   875  2143 D WifiService: setWifiEnabled: false pid=3831, uid=10000
08-18 11:57:06.439   875  2143 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-18 11:57:06.443  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:06.447  2678  2693 D BluetoothAdapterState: Current state: ON, message: 23
08-18 11:57:06.447  2678  2693 D BluetoothAdapterProperties: Setting state to 13
08-18 11:57:06.448  2678  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 11:57:06.448  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.448  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:06.448  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.448  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.449  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:06.449  2678  2693 D BluetoothAdapterProperties: onBluetoothDisable()
08-18 11:57:06.450  2678  2693 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:06.452  2678  2697 D BluetoothAdapterProperties: Scan Mode:20
08-18 11:57:06.453  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.453  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:06.454  2678  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-18 11:57:06.454  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.454  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:06.455  2678  2678 D HeadsetService: Received stop request...Stopping profile...
,08-18 11:57:06.458  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-18 11:57:06.458  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.460   875  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-18 11:57:06.460   875  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-18 11:57:06.460   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 11:57:06.460   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-18 11:57:06.461   875   875 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:06.461  1945  2097 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:06.462  2678  2678 D A2dpService: Received stop request...Stopping profile...
,08-18 11:57:06.463  2678  2813 D A2dpStateMachine: Exit Disconnected: -1
08-18 11:57:06.464   875   875 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:06.464   875   875 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:06.465  1364  2075 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:06.465  1364  1364 D HeadsetProfile: Bluetooth service disconnected
08-18 11:57:06.467   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-18 11:57:06.467   875  1896 D DhcpClient: Clearing IP address
08-18 11:57:06.469  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:06.469  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:06.469  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.469   875   875 D BluetoothA2dp: Proxy object disconnected
08-18 11:57:06.469   373   873 D CommandListener: Setting iface cfg
08-18 11:57:06.469  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:06.471  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-18 11:57:06.471  2678  2678 D HidService: Received stop request...Stopping profile...
08-18 11:57:06.472  2678  2678 D HidService: Stopping Bluetooth HidService
08-18 11:57:06.472  1509  2488 V NativeCrypto: Read error: ssl=0x9b1c8c00: I/O error during system call, Connection timed out
08-18 11:57:06.472  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-18 11:57:06.472  1364  1364 D HidProfile: Bluetooth service disconnected
,08-18 11:57:06.474  1509  2488 V NativeCrypto: SSL shutdown failed: ssl=0x9b1c8c00: I/O error during system call, Broken pipe
08-18 11:57:06.474   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-18 11:57:06.474   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-18 11:57:06.476  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.476   875  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
08-18 11:57:06.477   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 11:57:06.477   396   396 E Parcel  : Reading a NULL string not supported here.
08-18 11:57:06.480  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:06.481  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.481  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:06.481  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:06.481   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-18 11:57:06.482   875  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-18 11:57:06.482  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-18 11:57:06.483  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:06.483  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:06.483  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:06.483  2678  2697 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-18 11:57:06.483  2678  2697 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-18 11:57:06.483  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-18 11:57:06.484  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:06.484  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.484  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.484  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:06.485  2678  2678 D HealthService: Received stop request...Stopping profile...
,08-18 11:57:06.488  2678  2678 D PanService: Received stop request...Stopping profile...
,08-18 11:57:06.498   875  1902 D DhcpClient: Receive thread stopped
,08-18 11:57:06.499   875   888 I ActivityManager: Start proc 3901:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-18 11:57:06.500  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-18 11:57:06.501  1364  1364 D PanProfile: Bluetooth service disconnected
,08-18 11:57:06.501   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-18 11:57:06.502  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:06.502  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:06.502  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.502  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.502  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:06.502  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:06.502  2678  2791 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 11:57:06.502  2678  2791 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 11:57:06.502  2678  2791 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 11:57:06.502  2678  2791 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 11:57:06.503  2678  2697 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000,
08-18 11:57:06.504  2678  2678 D BluetoothMapService: Received stop request...Stopping profile...
08-18 11:57:06.504  2678  2678 D BluetoothMapService: stop()
08-18 11:57:06.504  2678  2678 D BluetoothMapAppObserver: deinitObservers()
08-18 11:57:06.504  2678  2678 D BluetoothMapAppObserver: removeReceiver()
08-18 11:57:06.506  1364  1364 D BluetoothMap: Proxy object disconnected
08-18 11:57:06.506  1364  1364 D MapProfile: Bluetooth service disconnected
,08-18 11:57:06.506   875  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-18 11:57:06.507  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:06.507  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:06.507  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-18 11:57:06.507  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isTurningOff()=true
,08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:06.508  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:06.508  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-18 11:57:06.508  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:06.508  2678  2697 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 11:57:06.508  2678  2697 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-18 11:57:06.508  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isTurningOff()=true
,08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.508  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:06.509  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 11:57:06.509  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 11:57:06.510  2678  2678 D BluetoothMapService: MAP Service closeService in
08-18 11:57:06.510  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:06.510  2678  2678 D BluetoothMapMasInstance0: MAP Service shutdown
,08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:06.510  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:06.511  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:06.510  2678  2678 D ObexServerSockets0: shutdown(block = true)
,08-18 11:57:06.511  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:06.511  2678  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-18 11:57:06.512  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.513  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.514  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 11:57:06.514  2678  2826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-18 11:57:06.514  2678  2807 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-18 11:57:06.515  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 11:57:06.515  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:06.515  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.515  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.515  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:06.515  2678  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-18 11:57:06.515  2678  2693 D BluetoothAdapterProperties: Setting state to 15
08-18 11:57:06.515  2678  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 11:57:06.516  2678  2693 I BluetoothAdapterState: Entering BleOnState
08-18 11:57:06.516   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:06.516   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:06.516  2678  2678 D BluetoothMapService: cleanup()
08-18 11:57:06.516  2678  2678 D BluetoothMapService: MAP Service closeService in
08-18 11:57:06.516  1364  2075 D BluetoothPan: onBluetoothStateChange on: false
08-18 11:57:06.516  2678  2678 I BtOppRfcommListener: stopping Accept Thread
08-18 11:57:06.517   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:06.517  1364  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 11:57:06.517  2678  3437 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 11:57:06.517  1364  1376 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:06.517  2678  3437 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 11:57:06.517  1364  2075 D BluetoothMap: onBluetoothStateChange: up=false
08-18 11:57:06.518   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-18 11:57:06.518  1945  1958 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:06.518  1364  1387 D BluetoothPbap: onBluetoothStateChange: up=false
08-18 11:57:06.519  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-18 11:57:06.519  2678  2693 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-18 11:57:06.519  2678  2693 D BluetoothAdapterProperties: Setting state to 16
08-18 11:57:06.519  2678  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-18 11:57:06.520  2678  2693 D BluetoothAdapterProperties: onBleDisable
08-18 11:57:06.520  2678  2693 I BluetoothAdapterState: Entering PendingCommandState
08-18 11:57:06.520  2678  2694 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-18 11:57:06.522  2678  2791 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-18 11:57:06.522  2678  2791 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:06.522  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.523  2678  2697 D BluetoothAdapterProperties: Scan Mode:20
08-18 11:57:06.524  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.525  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.530  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.535   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:06.536  1888  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 11:57:06.563   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-18 11:57:06.563   875  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-18 11:57:06.563   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 11:57:06.566   875   892 D Tethering: MasterInitialState.processMessage what=3
08-18 11:57:06.567  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:06.568  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:06.588  3901  3901 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-18 11:57:06.611   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-18 11:57:06.612   875  1314 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-18 11:57:06.716  3901  3926 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-18 11:57:06.716  3901  3926 I Babel_SMS: MmsConfig.loadMmsSettings
,08-18 11:57:06.725  3901  3926 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-18 11:57:06.726  3901  3926 I Babel_SMS: MmsConfig.loadFromDatabase
,08-18 11:57:06.726  2678  2697 I bt_hci  : shut_down
,08-18 11:57:06.736  2678  2702 I bt_vendor: low_power_mode_cb
,08-18 11:57:06.742  2678  2702 D bt_hwcfg: hw_epilog_process
,08-18 11:57:06.755  2678  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-18 11:57:06.755  3901  3926 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-18 11:57:06.755  3901  3926 I Babel_SMS: MmsConfig.loadFromResources
,08-18 11:57:06.755  2678  2702 I bt_vendor: epilog_cb
,08-18 11:57:06.755  2678  2702 I bt_hci  : epilog_finished_callback
08-18 11:57:06.757  3901  3926 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-18 11:57:06.757  3901  3926 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-18 11:57:06.764  2678  2697 I bt_hci_h4: hal_close
,08-18 11:57:06.765  2678  2697 I bt_userial_vendor: device fd = 51 close
,08-18 11:57:06.790  3901  3901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 11:57:06.792  3901  3901 I Babel_Crash: startup - clean
,08-18 11:57:06.813  3901  3901 I Babel_telephony: TeleModule.launchCompleted
,08-18 11:57:06.824   875  2021 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-18 11:57:06.840  3901  3901 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-18 11:57:06.850  3901  3901 W Babel   : BAM#gBA: invalid account id: -1
,08-18 11:57:06.850  3901  3901 W Babel   : BAM#gBA: invalid account id: -1
08-18 11:57:06.850  3901  3901 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-18 11:57:06.854   875  2010 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null,
,08-18 11:57:06.859  3901  3931 I Babel   : deleted: false for 0
,08-18 11:57:06.904  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 11:57:06.907   875  2143 I ActivityManager: Start proc 3933:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-18 11:57:06.928  3901  3901 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 11:57:06.930  2678  2694 D bt_stack_manager: event_shut_down_stack finished.
08-18 11:57:06.930  2678  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-18 11:57:06.935  2678  2678 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 11:57:06.936  2678  2693 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-18 11:57:06.936  2678  2678 D BtGatt.GattService: Received stop request...Stopping profile...
,08-18 11:57:06.936  2678  2678 D BtGatt.GattService: stop()
08-18 11:57:06.936  2678  2678 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 11:57:06.940  2678  2678 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:06.940  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:06.940  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:06.940  2678  2678 V BluetoothAdapterState: isBleTurningOff()=true
08-18 11:57:06.941  2678  2693 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-18 11:57:06.941  2678  2693 D BluetoothAdapterProperties: Setting state to 10
08-18 11:57:06.941  2678  2693 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-18 11:57:06.942  2678  2693 I BluetoothAdapterState: Entering OffState
08-18 11:57:06.943   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-18 11:57:06.951  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-18 11:57:06.951  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-18 11:57:06.951  2678  2678 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-18 11:57:06.952  2678  2694 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 11:57:06.953  2678  2694 D bt_stack_manager: event_clean_up_stack finished.
,08-18 11:57:06.963  2678  2678 I art     : System.exit called, status: 0
08-18 11:57:06.963  2678  2678 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 11:57:06.984  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-18 11:57:07.037   875  2010 I ActivityManager: Process com.android.bluetooth (pid 2678) has died
,08-18 11:57:07.039   875  2010 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
08-18 11:57:07.046  3901  3901 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-18 11:57:07.052  3901  3901 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 11:57:07.067  3901  3901 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 11:57:07.072  3901  3901 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 11:57:07.088  3901  3901 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-18 11:57:07.099  3933  3933 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-18 11:57:07.104   875  1396 I ActivityManager: Killing 2976:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-18 11:57:07.176  3901  3901 I vclib   : onServiceConnected
,08-18 11:57:07.216   875  2040 I ActivityManager: Start proc 3959:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-18 11:57:07.220   875  2021 I ActivityManager: Killing 3640:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-18 11:57:07.272  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-18 11:57:07.284  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 11:57:07.289   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@51fc370:true
,08-18 11:57:07.324   875   885 I ActivityManager: Start proc 3971:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-18 11:57:07.342  3959  3959 D LocalBluetoothProfileManager: Adding local MAP profile
,08-18 11:57:07.345  3959  3959 D BluetoothMap: Create BluetoothMap proxy object
,08-18 11:57:07.351  3959  3959 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-18 11:57:07.377  3959  3959 D DockEventReceiver: finishStartingService: stopping service
,08-18 11:57:07.380   875  2143 I ActivityManager: Killing 3658:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-18 11:57:07.428  3971  3971 D AdapterServiceConfig: Adding HeadsetService
,08-18 11:57:07.428  3971  3971 D AdapterServiceConfig: Adding A2dpService
08-18 11:57:07.428  3971  3971 D AdapterServiceConfig: Adding HidService
,08-18 11:57:07.429  3971  3971 D AdapterServiceConfig: Adding HealthService
08-18 11:57:07.429  3971  3971 D AdapterServiceConfig: Adding PanService
,08-18 11:57:07.429  3971  3971 D AdapterServiceConfig: Adding GattService
08-18 11:57:07.429  3971  3971 D AdapterServiceConfig: Adding BluetoothMapService
,08-18 11:57:07.437  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 11:57:07.447   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a820ff:true
,08-18 11:57:07.448  3959  3959 D BluetoothPbap: Proxy object connected
08-18 11:57:07.448  3959  3959 D PbapServerProfile: Bluetooth service connected
,08-18 11:57:07.450  3959  3959 D BluetoothPbap: Proxy object disconnected
08-18 11:57:07.450  3959  3959 D PbapServerProfile: Bluetooth service disconnected
,08-18 11:57:07.483   875  1403 I ActivityManager: Start proc 3986:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-18 11:57:07.486   875  1403 I ActivityManager: Killing 3499:android.process.acore/u0a5 (adj 15): empty #17
,08-18 11:57:07.557  3986  3986 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-18 11:57:07.717  3986  3986 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 11:57:07.717  3986  3986 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 11:57:07.717  3986  3986 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 11:57:07.717  3986  3986 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.717  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-18 11:57:07.718  3986  3986 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.k.d(PG:583)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:170)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:07.718  3986  3986 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:07.718  3986  3986 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.File.exists(File.java:361)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.718  3986  3986 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:07.718  3986  3986 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:07.718  3986  3986 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:07.724  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 11:57:07.733  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 11:57:07.750  3959  3959 D DockEventReceiver: finishStartingService: stopping service
08-18 11:57:07.755   875  2010 I ActivityManager: Killing 3688:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-18 11:57:07.842  1695  1695 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 11:57:07.845  1695  2453 I iu.UploadsManager: num queued entries: 0
,08-18 11:57:07.848  1695  2453 I iu.UploadsManager: num updated entries: 0
08-18 11:57:07.850  1695  2453 I iu.SyncManager: NEXT; no task
,08-18 11:57:07.852  1695  1695 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 11:57:07.854  1695  1695 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 11:57:07.885   875  2143 I ActivityManager: Start proc 4015:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-18 11:57:07.981  4015  4015 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
08-18 11:57:07.984  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:07.988  4015  4015 D SprintDMHelper: simOperator: 
08-18 11:57:07.988  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 11:57:08.010   875  2040 I ActivityManager: Start proc 4029:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-18 11:57:08.025  3986  4007 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-18 11:57:08.066   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@71147ef:true
,08-18 11:57:08.138   875  1396 I ActivityManager: Start proc 4044:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-18 11:57:08.141  3901  4043 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-18 11:57:08.144   875  2144 I ActivityManager: Killing 3703:com.android.musicfx/u0a18 (adj 15): empty #17
,08-18 11:57:08.211  4044  4044 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-18 11:57:08.266  4044  4044 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-18 11:57:08.266  4044  4044 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-18 11:57:08.266  4044  4044 I GAv4    :   adb logcat -s GAv4
,08-18 11:57:08.280  4044  4044 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-18 11:57:08.287  4044  4044 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-18 11:57:08.324  4044  4061 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-18 11:57:08.430  4044  4044 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-18 11:57:08.473  4044  4044 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-18 11:57:08.487  4044  4044 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8953-8958)
08-18 11:57:08.488  4044  4044 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-18 11:57:08.500  4044  4044 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c68bed}
08-18 11:57:08.501  4044  4044 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:57:08.501  4044  4044 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-18 11:57:08.510  4044  4044 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 11:57:08.512  4044  4044 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-18 11:57:08.532  4044  4044 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-18 11:57:08.545  4044  4044 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:57:08.545  4044  4044 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:57:08.545  4044  4044 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 11:57:08.545  4044  4044 I Adreno  : Build Date                       : 10/20/15
08-18 11:57:08.545  4044  4044 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 11:57:08.545  4044  4044 I Adreno  : Local Branch                     : M14
08-18 11:57:08.545  4044  4044 I Adreno  : Remote Branch                    : 
08-18 11:57:08.545  4044  4044 I Adreno  : Remote Branch                    : 
08-18 11:57:08.545  4044  4044 I Adreno  : Reconstruct Branch               : 
,08-18 11:57:08.611  4044  4044 I NSApplication: Starting up...
,08-18 11:57:08.622  4044  4090 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-18 11:57:08.644   875  2040 I ActivityManager: Start proc 4095:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-18 11:57:08.645   875  2040 I ActivityManager: Killing 2118:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-18 11:57:08.728  4095  4095 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-18 11:57:08.915   875  2144 I ActivityManager: Killing 3620:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-18 11:57:09.452   875  1882 D WifiService: setWifiEnabled: true pid=3831, uid=10000
,08-18 11:57:09.452   875  1882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 11:57:09.465   875  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-18 11:57:09.471  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:09.471  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:09.471  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:09.472  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:09.474  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:09.475  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:09.475  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:09.475  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:09.481   875  1312 D WifiConfigStore: loaded 0 passpoint configs
08-18 11:57:09.482   875  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-18 11:57:09.483   875  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-18 11:57:09.484   875  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-18 11:57:09.484   875  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-18 11:57:09.484   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-18 11:57:09.485   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 11:57:09.508   875  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.62 rxSuccessRate=12.00 delta 1000 -> 994
,08-18 11:57:09.508   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 11:57:09.511   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:09.515   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-18 11:57:09.515   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:09.515   875  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-18 11:57:09.515   875  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-18 11:57:09.522   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 11:57:09.574   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
08-18 11:57:09.576   875  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-18 11:57:09.577   875  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-18 11:57:09.578  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 11:57:09.995  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 11:57:10.032  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-18 11:57:10.033  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-18 11:57:10.039   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 11:57:10.048   875  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 11:57:10.048   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-18 11:57:10.048   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:10.077   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:10.093   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:10.095   875  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,08-18 11:57:10.115   875  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-18 11:57:10.119   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 11:57:10.144   875  4119 D DhcpClient: Receive thread started
,08-18 11:57:10.226   875  1312 E native  : do suspend false
,08-18 11:57:10.246   875  1896 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 11:57:10.259   875  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-18 11:57:10.262   875  1896 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-18 11:57:10.266   875  1896 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 11:57:10.281   875  4119 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 11:57:10.282   875  1896 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-18 11:57:10.291   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:10.302   875  1896 D DhcpClient: Scheduling renewal in 86399s
,08-18 11:57:10.302   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 11:57:10.325   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 11:57:10.329   875  1312 D WifiConfigStore: No blacklist allowed without epno enabled
08-18 11:57:10.329   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.332   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-18 11:57:10.337   875  1314 D ConnectivityService: Adding iface wlan0 to network 101
,08-18 11:57:10.350   875  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-18 11:57:10.411   875  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-18 11:57:10.411   875  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-18 11:57:10.412   875  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
,08-18 11:57:10.413   875  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-18 11:57:10.414   875  1314 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-18 11:57:10.422   875  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.428   875  1314 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-18 11:57:10.428   875  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.428   875  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.429   875  1314 D ConnectivityService:    accepting network in place of null
08-18 11:57:10.429   875  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-18 11:57:10.429   875  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-18 11:57:10.431   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 11:57:10.443   875  4118 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140913, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 11:57:10.476   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:10.506   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:10.513   875  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-18 11:57:10.514   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:10.518   875  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:80a::200e
,08-18 11:57:10.520   875  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.521   875   892 D Tethering: MasterInitialState.processMessage what=3
08-18 11:57:10.531  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:10.532  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:10.532  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:10.532  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:10.540  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:10.540  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:10.540  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:10.540  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:10.563  1695  1695 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 11:57:10.565  1695  2453 I iu.UploadsManager: num queued entries: 0
,08-18 11:57:10.565  1695  2453 I iu.UploadsManager: num updated entries: 0
,08-18 11:57:10.566  1695  2453 I iu.SyncManager: NEXT; no task
,08-18 11:57:10.573  1695  1695 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 11:57:10.574  1695  1695 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 11:57:10.576  1695  4132 I MDM     : [170] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 11:57:10.576  1695  4132 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 11:57:10.578  1695  4132 V GoogleAuthProtoRequest: [170] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 11:57:10.579  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:10.584  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:10.586  4015  4015 D SprintDMHelper: simOperator: 
,08-18 11:57:10.586  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-18 11:57:10.586  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:10.597   875  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 09:57:10 GMT], X-Android-Received-Millis=[1471514230596], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471514230568]}
,08-18 11:57:10.599   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 11:57:10.600   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-18 11:57:10.600   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:10.601   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-18 11:57:10.627  1509  3081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-18 11:57:10.628  1509  3081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-18 11:57:10.628  1509  3081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 11:57:10.628  1509  3081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:57:10.652  1695  4132 E MDM     : [170] SitrepService.a: Error sending sitrep.
,08-18 11:57:10.719  3901  4134 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 11:57:11.513   875  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-18 11:57:12.458   875   885 D WifiService: setWifiEnabled: false pid=3831, uid=10000
08-18 11:57:12.458   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 11:57:12.486  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-18 11:57:12.489   875  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-18 11:57:12.489   875  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-18 11:57:12.489   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 11:57:12.490   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:12.511   875  1896 D DhcpClient: Clearing IP address
,08-18 11:57:12.512   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:12.516   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-18 11:57:12.518  1509  4140 V NativeCrypto: Read error: ssl=0x9b1c8c00: I/O error during system call, Connection timed out
,08-18 11:57:12.519   875  4119 D DhcpClient: Receive thread stopped
,08-18 11:57:12.522  1509  4140 V NativeCrypto: SSL shutdown failed: ssl=0x9b1c8c00: I/O error during system call, Broken pipe
,08-18 11:57:12.527   875  2010 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-18 11:57:12.528   875  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-18 11:57:12.535   875  4117 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-18 11:57:12.535   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-18 11:57:12.536   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-18 11:57:12.536   875  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-18 11:57:12.544   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-18 11:57:12.546   373   873 D CommandListener: Clearing all IP addresses on wlan0
,08-18 11:57:12.546   396   396 E Parcel  : Reading a NULL string not supported here.,
,08-18 11:57:12.554   875  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-18 11:57:12.563   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 11:57:12.567  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:12.567  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:12.567  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:12.567  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:12.568  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:12.568  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:12.568  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:12.568  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:12.573  1888  2314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-18 11:57:12.576   875  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-18 11:57:12.597   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:12.627   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:12.628   875  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-18 11:57:12.629   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-18 11:57:12.630   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-18 11:57:12.633  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:12.634  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:12.647  1695  1695 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-18 11:57:12.650  1695  2453 I iu.UploadsManager: num queued entries: 0
,08-18 11:57:12.650  1695  2453 I iu.UploadsManager: num updated entries: 0
,08-18 11:57:12.652  1695  2453 I iu.SyncManager: NEXT; no task
,08-18 11:57:12.652  1695  1695 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 11:57:12.654  1695  1695 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 11:57:12.656  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:12.660  4015  4015 D SprintDMHelper: simOperator: 
08-18 11:57:12.660  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 11:57:12.673  3901  4155 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-18 11:57:12.696   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-18 11:57:12.697   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 11:57:13.046   875  2021 I ActivityManager: Killing 3725:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-18 11:57:15.506  3971  3971 D BluetoothAdapterState: make() - Creating AdapterState
,08-18 11:57:15.511  3971  3971 I bt_bluedroid: init
,08-18 11:57:15.511  3971  4159 I BluetoothAdapterState: Entering OffState
,08-18 11:57:15.514  3971  4160 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-18 11:57:15.514  3971  4160 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-18 11:57:15.514  3971  4160 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-18 11:57:15.514  3971  4160 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 11:57:15.515  3971  3971 I bt_bluedroid: get_profile_interface socket
,08-18 11:57:15.518  3971  3971 I bt_bluedroid: get_profile_interface sdp
,08-18 11:57:15.524  3971  3982 I bt_bluedroid: config_hci_snoop_log
,08-18 11:57:15.525  3971  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 11:57:15.526   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-18 11:57:15.528  3971  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 11:57:15.533  3971  4159 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 11:57:15.534  3971  4159 D BluetoothAdapterProperties: Setting state to 14
,08-18 11:57:15.534  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 11:57:15.537  3971  4159 D BluetoothBondStateMachine: make
,08-18 11:57:15.542  3971  4164 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 11:57:15.549  3971  3971 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 11:57:15.550  3971  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:15.553  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
,08-18 11:57:15.554  3971  3971 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 11:57:15.555  3971  3971 D BtGatt.GattService: Received start request. Starting profile...
08-18 11:57:15.555  3971  3971 D BtGatt.GattService: start()
,08-18 11:57:15.555  3971  3971 I bt_bluedroid: get_profile_interface gatt
08-18 11:57:15.556  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
08-18 11:57:15.556  3971  3971 D BtGatt.AdvertiseManager: advertise manager created
,08-18 11:57:15.564  3971  3971 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:15.564  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:15.564  3971  3971 V BluetoothAdapterState: isBleTurningOn()=true
08-18 11:57:15.564  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:15.565  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-18 11:57:15.566  3971  4159 I bt_bluedroid: enable
,08-18 11:57:15.566  3971  4160 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-18 11:57:15.566  3971  4160 I bt_hci  : start_up
,08-18 11:57:15.573  3971  4160 I bt_vendor: alloc value 0xb3939189
,08-18 11:57:15.573  3971  4160 I bt_vendor: init
08-18 11:57:15.573  3971  4160 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-18 11:57:15.573  3971  4160 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 11:57:15.682  3971  4160 D bt_hci  : start_up starting async portion
,08-18 11:57:15.682  3971  4167 I bt_hci  : event_finish_startup
08-18 11:57:15.683  3971  4167 I bt_hci_h4: hal_open
,08-18 11:57:15.684  3971  4167 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 11:57:15.694  3971  4167 I bt_userial_vendor: device fd = 51 open
,08-18 11:57:15.722  3971  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 11:57:15.755  3971  4167 D bt_hwcfg: Chipset BCM4354A2
08-18 11:57:15.755  3971  4167 D bt_hwcfg: Target name = [BCM4354A2]
,08-18 11:57:15.756  3971  4167 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 11:57:16.403  3971  4167 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-18 11:57:16.406  3971  4167 D bt_hwcfg: Settlement delay -- 100 ms
,08-18 11:57:16.406  3971  4167 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 11:57:16.523  3971  4167 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 11:57:16.526  3971  4167 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 11:57:16.549  3971  4167 I bt_hwcfg: vendor lib fwcfg completed
,08-18 11:57:16.549  3971  4167 I bt_vendor: firmware callback
,08-18 11:57:16.550  3971  4167 I bt_hci  : firmware_config_callback
,08-18 11:57:16.572  3971  4171 I bt_btu  : btu_task pending for preload complete event
,08-18 11:57:16.573  3971  4171 I bt_btu_task: Bluetooth chip preload is complete
08-18 11:57:16.573  3971  4171 I bt_btu  : btu_task received preload complete event
,08-18 11:57:16.584  3971  4171 I         : BTE_InitTraceLevels -- TRC_HCI
08-18 11:57:16.584  3971  4171 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-18 11:57:16.584  3971  4171 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-18 11:57:16.585  3971  4171 I         : BTE_InitTraceLevels -- TRC_AVDT
08-18 11:57:16.585  3971  4171 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-18 11:57:16.585  3971  4171 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 11:57:16.585  3971  4171 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 11:57:16.586  3971  4171 I         : BTE_InitTraceLevels -- TRC_BTM
08-18 11:57:16.586  3971  4171 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 11:57:16.586  3971  4171 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 11:57:16.586  3971  4171 I         : BTE_InitTraceLevels -- TRC_SDP
08-18 11:57:16.587  3971  4171 I         : BTE_InitTraceLevels -- TRC_GATT
,08-18 11:57:16.587  3971  4171 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 11:57:16.587  3971  4171 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-18 11:57:16.587  3971  4171 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 11:57:16.710  3971  4171 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
08-18 11:57:16.710  3971  4171 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-18 11:57:16.720  3971  4163 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-18 11:57:16.721  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-18 11:57:16.721  3971  4163 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-18 11:57:16.728  3971  4163 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 11:57:16.733  3971  4163 D BluetoothAdapterProperties: Scan Mode:20
,08-18 11:57:16.733  3971  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 11:57:16.735  3971  4163 D bt_hci  : do_postload posting postload work item
08-18 11:57:16.735  3971  4167 I bt_hci  : event_postload
08-18 11:57:16.735  3971  4167 I bt_vendor: sco_config_cb
08-18 11:57:16.735  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:16.735  3971  4167 I bt_hci  : sco_config_callback postload finished.
08-18 11:57:16.739  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:16.745  3971  4167 I bt_vendor: low_power_mode_cb
,08-18 11:57:16.747  3971  4163 D bt_bte_conf: Device ID record 1 : primary
,08-18 11:57:16.747  3971  4163 D bt_bte_conf:   vendorId            = 000f
,08-18 11:57:16.748  3971  4163 D bt_bte_conf:   vendorIdSource      = 0001
,08-18 11:57:16.749  3971  4163 D bt_bte_conf:   product             = 1200
08-18 11:57:16.749  3971  4163 D bt_bte_conf:   version             = 1436
08-18 11:57:16.749  3971  4163 D bt_bte_conf:   clientExecutableURL = 
08-18 11:57:16.749  3971  4163 D bt_bte_conf:   serviceDescription  = 
,08-18 11:57:16.749  3971  4163 D bt_bte_conf:   documentationURL    = 
08-18 11:57:16.749  3971  4163 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-18 11:57:16.750  3971  4160 D bt_stack_manager: event_start_up_stack finished
,08-18 11:57:16.750  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-18 11:57:16.750  3971  4159 D BluetoothAdapterProperties: Setting state to 15
,08-18 11:57:16.750  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-18 11:57:16.751  3971  4159 I BluetoothAdapterState: Entering BleOnState
,08-18 11:57:16.756  3971  4159 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-18 11:57:16.756  3971  4159 D BluetoothAdapterProperties: Setting state to 11
08-18 11:57:16.756  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-18 11:57:16.759  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481,
08-18 11:57:16.761  3971  3971 D HeadsetService: Received start request. Starting profile...
08-18 11:57:16.764  3971  3971 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-18 11:57:16.764  3971  3971 D HeadsetStateMachine: make
08-18 11:57:16.766  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:16.768  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:16.780  3971  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:16.781  3971  3971 D HeadsetStateMachine: max_hf_connections = 1
,08-18 11:57:16.781  3971  3971 I bt_bluedroid: get_profile_interface handsfree
,08-18 11:57:16.782  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 11:57:16.782  3971  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 11:57:16.786  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
,08-18 11:57:16.786  3971  3971 D A2dpService: Received start request. Starting profile...
08-18 11:57:16.787  3971  3971 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-18 11:57:16.787  3971  3971 I bt_bluedroid: get_profile_interface avrcp
,08-18 11:57:16.792  3971  3971 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 11:57:16.792  3971  3971 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 11:57:16.792  3971  3971 D A2dpStateMachine: make
,08-18 11:57:16.794  3971  3971 I bt_bluedroid: get_profile_interface a2dp
08-18 11:57:16.794  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-18 11:57:16.797  3971  3971 I BluetoothHidServiceJni: classInitNative: succeeds
,08-18 11:57:16.797  3971  4180 D A2dpStateMachine: Enter Disconnected: -2
08-18 11:57:16.798  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
08-18 11:57:16.799  3971  3971 D HidService: Received start request. Starting profile...
08-18 11:57:16.799  3971  3971 I bt_bluedroid: get_profile_interface hidhost
08-18 11:57:16.799  3971  4163 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
,08-18 11:57:16.799  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-18 11:57:16.799  3971  3971 D HidService: setHidService(): set to: null
08-18 11:57:16.801  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 11:57:16.802  3959  3959 D BluetoothInputDevice: Proxy object connected
08-18 11:57:16.802  3959  3959 D HidProfile: Bluetooth service connected
,08-18 11:57:16.804  3971  3971 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-18 11:57:16.806  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
,08-18 11:57:16.807  3971  3971 D HealthService: Received start request. Starting profile...
,08-18 11:57:16.809  3971  3971 I bt_bluedroid: get_profile_interface health
,08-18 11:57:16.810  3971  3971 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 11:57:16.812  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
,08-18 11:57:16.813  3959  3959 D BluetoothPan: BluetoothPAN Proxy object connected
,08-18 11:57:16.814  3959  3959 D PanProfile: Bluetooth service connected
08-18 11:57:16.814  3971  3971 D PanService: Received start request. Starting profile...
,08-18 11:57:16.814  3971  3971 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 11:57:16.814  3971  3971 I bt_bluedroid: get_profile_interface pan
,08-18 11:57:16.815  3971  4163 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-18 11:57:16.820  3971  3971 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@996b481
,08-18 11:57:16.822  3959  3959 D BluetoothMap: Proxy object connected
,08-18 11:57:16.822  3971  3971 D BluetoothMapService: Received start request. Starting profile...
08-18 11:57:16.822  3971  3971 D BluetoothMapService: start()
,08-18 11:57:16.822  3959  3959 D MapProfile: Bluetooth service connected
,08-18 11:57:16.823  3959  3959 D BluetoothMap: getConnectedDevices()
08-18 11:57:16.824  3959  3959 D BluetoothMap: Bluetooth is Not enabled
,08-18 11:57:16.826  3971  3971 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-18 11:57:16.828  3971  3971 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-18 11:57:16.828  3971  3971 D BluetoothMapAppObserver: createReceiver()
,08-18 11:57:16.830  3971  3971 D BluetoothMapAppObserver: initObservers()
,08-18 11:57:16.830  3971  3971 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 11:57:16.836  3971  3971 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:16.837  3971  3971 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:16.837  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:16.837  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:16.837  3971  4177 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isTurningOff()=false,
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:16.838  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isTurningOn()=true
08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isTurningOn()=true
08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false,
,08-18 11:57:16.839  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:16.840  3971  3971 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:16.840  3971  3971 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:16.840  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:16.840  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:16.840  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 11:57:16.840  3971  4159 D BluetoothAdapterProperties: ScanMode =  20
08-18 11:57:16.840  3971  4159 D BluetoothAdapterProperties: State =  11
08-18 11:57:16.840  3971  4159 D BluetoothAdapterProperties: Setting state to 12
,08-18 11:57:16.840  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 11:57:16.841  3971  4159 I BluetoothAdapterState: Entering OnState
08-18 11:57:16.841  3959  3970 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 11:57:16.842  3971  4163 D BluetoothAdapterProperties: Scan Mode:21
08-18 11:57:16.843  3971  4163 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 11:57:16.843   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:16.843   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 11:57:16.843  1364  1376 D BluetoothPan: onBluetoothStateChange on: true
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:16.848  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:16.848  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 11:57:16.849  1364  1364 D PanProfile: Bluetooth service connected
08-18 11:57:16.849  3959  3969 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 11:57:16.849   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:16.850  1364  2075 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 11:57:16.852  1364  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 11:57:16.852  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:16.852  1364  1376 D BluetoothMap: onBluetoothStateChange: up=true
08-18 11:57:16.853  1364  1364 D BluetoothA2dp: Proxy object connected
08-18 11:57:16.854  3959  3970 D BluetoothPan: onBluetoothStateChange on: true
08-18 11:57:16.854   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 11:57:16.854  1364  1364 D BluetoothMap: Proxy object connected
,08-18 11:57:16.854  1364  1364 D MapProfile: Bluetooth service connected
08-18 11:57:16.854  1364  1364 D BluetoothMap: getConnectedDevices()
08-18 11:57:16.855   875   875 D BluetoothA2dp: Proxy object connected
08-18 11:57:16.855  3959  3969 D BluetoothMap: onBluetoothStateChange: up=true
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:16.855  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:16.855  1945  1960 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:16.856  1364  2075 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 11:57:16.857  1364  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 11:57:16.857  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:16.858  1364  1364 D BluetoothInputDevice: Proxy object connected
08-18 11:57:16.858  1364  1364 D HidProfile: Bluetooth service connected
08-18 11:57:16.859  3971  3971 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-18 11:57:16.860  3971  3971 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-18 11:57:16.861   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-18 11:57:16.861  3971  3971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 11:57:16.862  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:16.863  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:16.863  3959  3959 D LocalBluetoothProfileManager: Adding local A2DP profile
08-18 11:57:16.864  3971  3971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-18 11:57:16.864  3971  3971 D ObexServerSockets: Succeed to create listening sockets 
08-18 11:57:16.864  3971  3971 D ObexServerSockets0: startAccept()
08-18 11:57:16.864  3971  3971 D ObexServerSockets0: prepareForNewConnect()
08-18 11:57:16.866  3971  3971 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-18 11:57:16.866  3971  3971 D BluetoothSdpJni: SDP Create record success - handle: 0
08-18 11:57:16.867  3971  3971 D BluetoothMapService: onReceive
08-18 11:57:16.867  3971  3971 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 11:57:16.867  3959  3959 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-18 11:57:16.867  3971  4187 D ObexServerSockets0: Accepting socket connection...
08-18 11:57:16.867  3971  3971 D BluetoothMapService: STATE_ON
08-18 11:57:16.868  3971  4188 D ObexServerSockets0: Accepting socket connection...
08-18 11:57:16.879  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 11:57:16.884  3959  3959 D BluetoothA2dp: Proxy object connected
,08-18 11:57:16.893  3971  3971 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 11:57:16.893  3971  3971 D ObexServerSockets0: prepareForNewConnect()
,08-18 11:57:16.896  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 11:57:16.900  1364  1364 D BluetoothPbap: Proxy object connected
08-18 11:57:16.900  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-18 11:57:16.903  3971  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:16.906  3959  3959 D DockEventReceiver: finishStartingService: stopping service
,08-18 11:57:16.907  3959  3959 D BluetoothPbap: Proxy object connected
,08-18 11:57:16.907  3959  3959 D PbapServerProfile: Bluetooth service connected
,08-18 11:57:16.925  3971  4196 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:16.927  3971  4196 I BtOppRfcommListener: Accept thread started.
,08-18 11:57:16.944   875   875 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.944  1945  2097 D BluetoothHeadset: Proxy object connected
08-18 11:57:16.945   875   875 D BluetoothHeadset: Proxy object connected
08-18 11:57:16.945   875   875 D BluetoothHeadset: Proxy object connected
08-18 11:57:16.945  1364  2075 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.945  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:16.950   875   892 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.952  1364  1376 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.953  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:16.956  1945  1960 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.971  3959  3970 D BluetoothHeadset: Proxy object connected
,08-18 11:57:16.972  3959  3959 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:18.434   875  1314 D ConnectivityService: handlePromptUnvalidated 101
,08-18 11:57:18.476  3971  4159 D BluetoothAdapterState: Current state: ON, message: 23
,08-18 11:57:18.477  3971  4159 D BluetoothAdapterProperties: Setting state to 13
08-18 11:57:18.477  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-18 11:57:18.479  3971  4159 D BluetoothAdapterProperties: onBluetoothDisable()
,08-18 11:57:18.483  3971  4159 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:18.494  3971  3971 D BluetoothMapService: onReceive
,08-18 11:57:18.495  3971  3971 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 11:57:18.495  3971  3971 D BluetoothMapService: STATE_TURNING_OFF
,08-18 11:57:18.496  3971  3971 D BluetoothMapService: MAP Service closeService in
,08-18 11:57:18.496  3971  3971 D BluetoothMapMasInstance0: MAP Service shutdown
,08-18 11:57:18.499  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:18.499  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:18.498  3971  3971 D ObexServerSockets0: shutdown(block = true),
08-18 11:57:18.502  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:18.502  3971  4187 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-18 11:57:18.502  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:18.506  3971  3971 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 11:57:18.507  3971  3971 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-18 11:57:18.507  3971  4188 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-18 11:57:18.507  3971  3971 I BtOppRfcommListener: stopping Accept Thread
08-18 11:57:18.508  3971  4196 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-18 11:57:18.508  3971  4174 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-18 11:57:18.509  3971  4196 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-18 11:57:18.512  3971  4163 D BluetoothAdapterProperties: Scan Mode:20
08-18 11:57:18.513  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-18 11:57:18.514  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:18.514  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:18.516  3831  3831 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-18 11:57:18.516  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:18.517  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-18 11:57:18.517  3971  3971 D HeadsetService: Received stop request...Stopping profile...
08-18 11:57:18.521  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:18.524  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:18.524  3959  3969 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:18.525   875   875 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:18.525  1945  1958 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:18.526   875   875 D BluetoothHeadset: Proxy object disconnected
,08-18 11:57:18.526   875   875 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:18.526  1364  1387 D BluetoothHeadset: Proxy object disconnected
08-18 11:57:18.527  3971  3971 V BluetoothAdapterState: isTurningOff()=true
,08-18 11:57:18.527  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.527  1364  1364 D HeadsetProfile: Bluetooth service disconnected
08-18 11:57:18.527  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:18.529  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.530  3971  3971 D A2dpService: Received stop request...Stopping profile...
08-18 11:57:18.530  3971  4180 D A2dpStateMachine: Exit Disconnected: -1
,08-18 11:57:18.533   875   875 D BluetoothA2dp: Proxy object disconnected
,08-18 11:57:18.534  1364  1364 D BluetoothA2dp: Proxy object disconnected
,08-18 11:57:18.535  3971  3971 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-18 11:57:18.535  3971  3971 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-18 11:57:18.535  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-18 11:57:18.536  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:18.536  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:18.536  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:18.536  3971  3971 D HidService: Received stop request...Stopping profile...
,08-18 11:57:18.536  3971  3971 D HidService: Stopping Bluetooth HidService
08-18 11:57:18.536  3971  4163 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-18 11:57:18.537  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-18 11:57:18.537  1364  1364 D HidProfile: Bluetooth service disconnected
,08-18 11:57:18.538  3971  3971 D HealthService: Received stop request...Stopping profile...
08-18 11:57:18.539  3971  3971 D PanService: Received stop request...Stopping profile...
08-18 11:57:18.540  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 11:57:18.540  1364  1364 D PanProfile: Bluetooth service disconnected
,08-18 11:57:18.541  3971  3971 D BluetoothMapService: Received stop request...Stopping profile...
08-18 11:57:18.541  3971  3971 D BluetoothMapService: stop()
08-18 11:57:18.543  3971  3971 D BluetoothMapAppObserver: deinitObservers()
,08-18 11:57:18.543  3959  3959 D DockEventReceiver: finishStartingService: stopping service
08-18 11:57:18.543  3971  3971 D BluetoothMapAppObserver: removeReceiver()
,08-18 11:57:18.544  3959  3959 D HeadsetProfile: Bluetooth service disconnected
08-18 11:57:18.544  3959  3959 D BluetoothA2dp: Proxy object disconnected
08-18 11:57:18.544  3959  3959 D BluetoothInputDevice: Proxy object disconnected
08-18 11:57:18.545  3959  3959 D HidProfile: Bluetooth service disconnected
08-18 11:57:18.545  3959  3959 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-18 11:57:18.545  3959  3959 D PanProfile: Bluetooth service disconnected
08-18 11:57:18.545  3971  3971 V BluetoothAdapterState: isTurningOff()=true
,08-18 11:57:18.545  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.545  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:18.545  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.546  1364  1364 D BluetoothMap: Proxy object disconnected
08-18 11:57:18.547  1364  1364 D MapProfile: Bluetooth service disconnected
08-18 11:57:18.547  3959  3959 D BluetoothMap: Proxy object disconnected
08-18 11:57:18.547  3959  3959 D MapProfile: Bluetooth service disconnected
,08-18 11:57:18.551  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-18 11:57:18.551  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:18.551  3971  3971 V BluetoothAdapterState: isTurningOff()=true
,08-18 11:57:18.551  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-18 11:57:18.551  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.552  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:18.552  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.552  3971  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 11:57:18.552  3971  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-18 11:57:18.552  3971  3971 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-18 11:57:18.552  3971  4171 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-18 11:57:18.552  3971  4163 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 11:57:18.552  3971  4171 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-18 11:57:18.553  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 11:57:18.554  3971  3971 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-18 11:57:18.554  3971  3971 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:18.554  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.554  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:18.555  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.555  3971  3971 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-18 11:57:18.555  3971  4163 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-18 11:57:18.555  3971  3971 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-18 11:57:18.556  3971  3971 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:18.556  3971  3971 V BluetoothAdapterState: isTurningOn()=false
,08-18 11:57:18.556  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:18.556  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.556  3971  3971 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-18 11:57:18.556  3971  3971 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-18 11:57:18.557  3971  3971 D BluetoothMapService: MAP Service closeService in
08-18 11:57:18.557  3971  3971 V BluetoothAdapterState: isTurningOff()=true
08-18 11:57:18.557  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.557  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:18.557  3971  3971 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:18.558  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-18 11:57:18.558  3971  4159 D BluetoothAdapterProperties: Setting state to 15
08-18 11:57:18.558  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-18 11:57:18.559  3971  4159 I BluetoothAdapterState: Entering BleOnState
08-18 11:57:18.559  3959  3969 D BluetoothPbap: onBluetoothStateChange: up=false
,08-18 11:57:18.559  3971  3971 D BluetoothMapService: cleanup()
08-18 11:57:18.559   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 11:57:18.560   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:18.559  3971  3971 D BluetoothMapService: MAP Service closeService in
,08-18 11:57:18.560  1364  1376 D BluetoothPan: onBluetoothStateChange on: false
,08-18 11:57:18.562  3959  3970 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-18 11:57:18.563  1364  1364 D BluetoothPbap: Proxy object disconnected
,08-18 11:57:18.563  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,08-18 11:57:18.564   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:18.564  1364  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 11:57:18.565  1364  1387 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:18.566  1364  2075 D BluetoothMap: onBluetoothStateChange: up=false
08-18 11:57:18.567  3959  3969 D BluetoothPan: onBluetoothStateChange on: false
08-18 11:57:18.568   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 11:57:18.568  3959  3970 D BluetoothHeadset: onBluetoothStateChange: up=false
08-18 11:57:18.568  3959  3969 D BluetoothMap: onBluetoothStateChange: up=false
08-18 11:57:18.569  1945  2097 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-18 11:57:18.570  3959  3970 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-18 11:57:18.571  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=false
,08-18 11:57:18.572  1364  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-18 11:57:18.573  3971  4159 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-18 11:57:18.573  3971  4159 D BluetoothAdapterProperties: Setting state to 16
,08-18 11:57:18.573  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-18 11:57:18.574  3971  4159 D BluetoothAdapterProperties: onBleDisable
08-18 11:57:18.574  3971  4159 I BluetoothAdapterState: Entering PendingCommandState
08-18 11:57:18.574  3971  4160 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-18 11:57:18.575  3971  4171 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-18 11:57:18.575  3971  4171 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-18 11:57:18.578  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 11:57:18.578  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:18.579  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:18.581  3971  4163 D BluetoothAdapterProperties: Scan Mode:20
08-18 11:57:18.582  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:18.583  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:18.584  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 11:57:18.590  3959  3959 D DockEventReceiver: finishStartingService: stopping service
,08-18 11:57:18.780  3971  4163 I bt_hci  : shut_down
,08-18 11:57:18.800  3971  4167 D bt_hwcfg: hw_epilog_process
,08-18 11:57:18.801  3971  4167 I bt_vendor: low_power_mode_cb
,08-18 11:57:18.817  3971  4167 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-18 11:57:18.817  3971  4167 I bt_vendor: epilog_cb
08-18 11:57:18.818  3971  4167 I bt_hci  : epilog_finished_callback
,08-18 11:57:18.825  3971  4163 I bt_hci_h4: hal_close
,08-18 11:57:18.827  3971  4163 I bt_userial_vendor: device fd = 51 close
,08-18 11:57:18.941  3971  4160 D bt_stack_manager: event_shut_down_stack finished.
,08-18 11:57:18.942  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-18 11:57:18.951  3971  4159 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-18 11:57:18.951  3971  3971 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 11:57:18.953  3971  3971 D BtGatt.GattService: Received stop request...Stopping profile...
08-18 11:57:18.953  3971  3971 D BtGatt.GattService: stop()
,08-18 11:57:18.953  3971  3971 D BtGatt.AdvertiseManager: advertise clients cleared
,08-18 11:57:18.958  3971  3971 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:18.958  3971  3971 V BluetoothAdapterState: isTurningOn()=false
08-18 11:57:18.959  3971  3971 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:18.959  3971  3971 V BluetoothAdapterState: isBleTurningOff()=true
08-18 11:57:18.960  3971  4159 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-18 11:57:18.960  3971  4159 D BluetoothAdapterProperties: Setting state to 10
08-18 11:57:18.961  3971  4159 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-18 11:57:18.963  3971  4159 I BluetoothAdapterState: Entering OffState
08-18 11:57:18.964   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-18 11:57:18.980  3971  3971 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-18 11:57:18.980  3971  3971 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-18 11:57:18.981  3971  4160 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-18 11:57:18.984  3971  4160 D bt_stack_manager: event_clean_up_stack finished.
,08-18 11:57:18.984  3971  3971 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-18 11:57:18.988  3971  3971 I art     : System.exit called, status: 0
,08-18 11:57:18.988  3971  3971 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-18 11:57:19.054   875  2040 I ActivityManager: Process com.android.bluetooth (pid 3971) has died
,08-18 11:57:19.850   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-18 11:57:19.873   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-18 11:57:19.873   875   895 I Adreno  : Build Date                       : 10/20/15
08-18 11:57:19.873   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-18 11:57:19.873   875   895 I Adreno  : Local Branch                     : M14
08-18 11:57:19.873   875   895 I Adreno  : Remote Branch                    : 
08-18 11:57:19.873   875   895 I Adreno  : Remote Branch                    : 
08-18 11:57:19.873   875   895 I Adreno  : Reconstruct Branch               : 
,08-18 11:57:19.882  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-18 11:57:19.923   281  2328 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (308 us)
,08-18 11:57:20.024  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:20.049  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:20.051  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:20.079  1509  1521 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-18 11:57:20.079  1509  1521 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-18 11:57:20.080  1509  1521 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-18 11:57:20.080  1509  1521 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:57:20.094  3516  3516 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-18 11:57:20.094  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-18 11:57:20.094  3516  3516 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-18 11:57:20.553  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 11:57:20.553  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-18 11:57:20.605   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-18 11:57:20.606  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6e3b967 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2357fcf, 16908290=android.view.AbsSavedState$1@2357fcf}, android:focusedViewId=100}]}]
,08-18 11:57:20.606  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-18 11:57:20.606  3831  3831 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-18 11:57:20.607  3831  3831 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-18 11:57:20.614   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-18 11:57:20.618   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-18 11:57:20.619   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-18 11:57:20.619   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-18 11:57:20.847   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-18 11:57:20.850   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-18 11:57:20.858   875  1339 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-18 11:57:20.861   875   895 I DreamManagerService: Entering dreamland.
,08-18 11:57:20.863   875   895 I PowerManagerService: Dozing...
,08-18 11:57:20.864   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-18 11:57:20.905   377  1285 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-18 11:57:20.905   377  1285 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-18 11:57:20.910   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 11:57:20.914   875  1312 E native  : do suspend false
,08-18 11:57:20.927  1936  4208 D NfcService: Discovery configuration equal, not updating.
,08-18 11:57:20.947   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 11:57:20.951   875  1312 E native  : do suspend true
,08-18 11:57:21.048   377  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-18 11:57:21.048   377  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-18 11:57:21.473  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 11:57:21.474  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:24.481  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:24.481  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d2ad5c added. We now have 6 listener(s)
08-18 11:57:24.482  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:24.485  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:24.486  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ae0865 added. We now have 7 listener(s)
08-18 11:57:24.486  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:24.487  3831  3880 I System.out: IsBluetoothEnabled
,08-18 11:57:24.499  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:24.549   875   892 I ActivityManager: Start proc 4214:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-18 11:57:24.684  4214  4214 D AdapterServiceConfig: Adding HeadsetService
,08-18 11:57:24.685  4214  4214 D AdapterServiceConfig: Adding A2dpService
,08-18 11:57:24.686  4214  4214 D AdapterServiceConfig: Adding HidService
,08-18 11:57:24.687  4214  4214 D AdapterServiceConfig: Adding HealthService
,08-18 11:57:24.688  4214  4214 D AdapterServiceConfig: Adding PanService
,08-18 11:57:24.688  4214  4214 D AdapterServiceConfig: Adding GattService
,08-18 11:57:24.689  4214  4214 D AdapterServiceConfig: Adding BluetoothMapService
,08-18 11:57:24.711   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7260b61:true
,08-18 11:57:24.712  4214  4214 D BluetoothAdapterState: make() - Creating AdapterState
,08-18 11:57:24.717  4214  4214 I bt_bluedroid: init
,08-18 11:57:24.718  4214  4226 I BluetoothAdapterState: Entering OffState
,08-18 11:57:24.721  4214  4227 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-18 11:57:24.722  4214  4227 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-18 11:57:24.722  4214  4227 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-18 11:57:24.722  4214  4227 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-18 11:57:24.723  4214  4214 I bt_bluedroid: get_profile_interface socket
,08-18 11:57:24.726  4214  4214 I bt_bluedroid: get_profile_interface sdp
,08-18 11:57:24.726  4214  4230 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 11:57:24.728  4214  4230 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 11:57:24.731  4214  4225 I bt_bluedroid: config_hci_snoop_log
,08-18 11:57:24.733   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-18 11:57:24.740  4214  4226 D BluetoothAdapterState: Current state: OFF, message: 0
,08-18 11:57:24.740  4214  4226 D BluetoothAdapterProperties: Setting state to 14
,08-18 11:57:24.741  4214  4226 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-18 11:57:24.745  4214  4226 D BluetoothBondStateMachine: make
,08-18 11:57:24.749  4214  4231 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-18 11:57:24.755  4214  4226 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:24.756  4214  4214 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-18 11:57:24.761  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:24.763  4214  4214 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-18 11:57:24.764  4214  4214 D BtGatt.GattService: Received start request. Starting profile...
08-18 11:57:24.764  4214  4214 D BtGatt.GattService: start()
,08-18 11:57:24.764  4214  4214 I bt_bluedroid: get_profile_interface gatt
,08-18 11:57:24.765  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
08-18 11:57:24.766  4214  4214 D BtGatt.AdvertiseManager: advertise manager created
,08-18 11:57:24.774  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:24.774  4214  4214 V BluetoothAdapterState: isTurningOn()=false
,08-18 11:57:24.774  4214  4214 V BluetoothAdapterState: isBleTurningOn()=true
08-18 11:57:24.774  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:24.775  4214  4226 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-18 11:57:24.776  4214  4226 I bt_bluedroid: enable
08-18 11:57:24.776  4214  4227 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-18 11:57:24.777  4214  4227 I bt_hci  : start_up
,08-18 11:57:24.792  4214  4227 I bt_vendor: alloc value 0xb399c189
,08-18 11:57:24.792  4214  4227 I bt_vendor: init
08-18 11:57:24.792  4214  4227 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-18 11:57:24.793  4214  4227 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-18 11:57:24.900  4214  4227 D bt_hci  : start_up starting async portion
08-18 11:57:24.901  4214  4234 I bt_hci  : event_finish_startup
08-18 11:57:24.901  4214  4234 I bt_hci_h4: hal_open
08-18 11:57:24.901  4214  4234 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-18 11:57:24.910  4214  4234 I bt_userial_vendor: device fd = 51 open
,08-18 11:57:24.943  4214  4234 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-18 11:57:24.975  4214  4234 D bt_hwcfg: Chipset BCM4354A2
,08-18 11:57:24.975  4214  4234 D bt_hwcfg: Target name = [BCM4354A2]
,08-18 11:57:24.976  4214  4234 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-18 11:57:25.640  4214  4234 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-18 11:57:25.641  4214  4234 D bt_hwcfg: Settlement delay -- 100 ms
08-18 11:57:25.642  4214  4234 I bt_hwcfg: Setting fw settlement delay to 100 
,08-18 11:57:25.716  1888  2645 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-18 11:57:25.758  4214  4234 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-18 11:57:25.759  4214  4234 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-18 11:57:25.789  4214  4234 I bt_hwcfg: vendor lib fwcfg completed
08-18 11:57:25.790  4214  4234 I bt_vendor: firmware callback
08-18 11:57:25.790  4214  4234 I bt_hci  : firmware_config_callback
,08-18 11:57:25.801  4214  4237 I bt_btu  : btu_task pending for preload complete event
,08-18 11:57:25.801  4214  4237 I bt_btu_task: Bluetooth chip preload is complete
08-18 11:57:25.801  4214  4237 I bt_btu  : btu_task received preload complete event
,08-18 11:57:25.811  4214  4237 I         : BTE_InitTraceLevels -- TRC_HCI
,08-18 11:57:25.812  4214  4237 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-18 11:57:25.812  4214  4237 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-18 11:57:25.813  4214  4237 I         : BTE_InitTraceLevels -- TRC_AVDT
08-18 11:57:25.813  4214  4237 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-18 11:57:25.813  4214  4237 I         : BTE_InitTraceLevels -- TRC_A2D
08-18 11:57:25.813  4214  4237 I         : BTE_InitTraceLevels -- TRC_BNEP
08-18 11:57:25.814  4214  4237 I         : BTE_InitTraceLevels -- TRC_BTM
,08-18 11:57:25.814  4214  4237 I         : BTE_InitTraceLevels -- TRC_GAP
08-18 11:57:25.814  4214  4237 I         : BTE_InitTraceLevels -- TRC_PAN
08-18 11:57:25.814  4214  4237 I         : BTE_InitTraceLevels -- TRC_SDP
,08-18 11:57:25.815  4214  4237 I         : BTE_InitTraceLevels -- TRC_GATT
08-18 11:57:25.815  4214  4237 I         : BTE_InitTraceLevels -- TRC_SMP
08-18 11:57:25.815  4214  4237 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-18 11:57:25.815  4214  4237 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-18 11:57:25.953  4214  4237 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3919d9d
,08-18 11:57:25.953  4214  4237 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3919d9d 
,08-18 11:57:25.966  4214  4230 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-18 11:57:25.968  4214  4230 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-18 11:57:25.968  4214  4230 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-18 11:57:25.972  4214  4230 D BluetoothAdapterProperties: Name is: Nexus 6
,08-18 11:57:25.975  4214  4230 D BluetoothAdapterProperties: Scan Mode:20
,08-18 11:57:25.975  4214  4230 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-18 11:57:25.976  4214  4230 D bt_hci  : do_postload posting postload work item
08-18 11:57:25.976  4214  4234 I bt_hci  : event_postload
08-18 11:57:25.976  4214  4234 I bt_vendor: sco_config_cb
08-18 11:57:25.976  4214  4234 I bt_hci  : sco_config_callback postload finished.
,08-18 11:57:25.979  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:25.982  4214  4230 D bt_bte_conf: Device ID record 1 : primary
,08-18 11:57:25.982  4214  4230 D bt_bte_conf:   vendorId            = 000f
08-18 11:57:25.982  4214  4230 D bt_bte_conf:   vendorIdSource      = 0001
,08-18 11:57:25.982  4214  4230 D bt_bte_conf:   product             = 1200
08-18 11:57:25.983  4214  4230 D bt_bte_conf:   version             = 1436
08-18 11:57:25.983  4214  4230 D bt_bte_conf:   clientExecutableURL = 
08-18 11:57:25.983  4214  4230 D bt_bte_conf:   serviceDescription  = 
08-18 11:57:25.983  4214  4230 D bt_bte_conf:   documentationURL    = 
08-18 11:57:25.983  4214  4230 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-18 11:57:25.984  4214  4227 D bt_stack_manager: event_start_up_stack finished
08-18 11:57:25.984  4214  4234 I bt_vendor: low_power_mode_cb
08-18 11:57:25.986  4214  4226 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-18 11:57:25.986  4214  4226 D BluetoothAdapterProperties: Setting state to 15
08-18 11:57:25.986  4214  4226 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-18 11:57:25.988  4214  4226 I BluetoothAdapterState: Entering BleOnState
,08-18 11:57:25.994  4214  4226 D BluetoothAdapterState: Current state: BLE ON, message: 1,
08-18 11:57:25.994  4214  4226 D BluetoothAdapterProperties: Setting state to 11
08-18 11:57:25.994  4214  4226 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-18 11:57:26.003  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.003  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:26.005  4214  4214 D HeadsetService: Received start request. Starting profile...
08-18 11:57:26.010  4214  4214 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-18 11:57:26.010  4214  4214 D HeadsetStateMachine: make
,08-18 11:57:26.019  4214  4226 I BluetoothAdapterState: Entering PendingCommandState
,08-18 11:57:26.019  4214  4214 D HeadsetStateMachine: max_hf_connections = 1
,08-18 11:57:26.019  4214  4214 I bt_bluedroid: get_profile_interface handsfree
08-18 11:57:26.019  4214  4230 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-18 11:57:26.020  4214  4230 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-18 11:57:26.024  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.025  4214  4214 D A2dpService: Received start request. Starting profile...
,08-18 11:57:26.026  4214  4214 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-18 11:57:26.026  4214  4214 I bt_bluedroid: get_profile_interface avrcp
,08-18 11:57:26.032  4214  4214 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-18 11:57:26.033  4214  4214 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-18 11:57:26.033  4214  4214 D A2dpStateMachine: make
,08-18 11:57:26.034  4214  4214 I bt_bluedroid: get_profile_interface a2dp
08-18 11:57:26.034  4214  4230 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-18 11:57:26.036  4214  4246 D A2dpStateMachine: Enter Disconnected: -2
,08-18 11:57:26.037  4214  4214 I BluetoothHidServiceJni: classInitNative: succeeds
,08-18 11:57:26.038  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.039  4214  4214 D HidService: Received start request. Starting profile...
,08-18 11:57:26.039  4214  4214 I bt_bluedroid: get_profile_interface hidhost
08-18 11:57:26.039  4214  4230 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38fb3e5
08-18 11:57:26.039  4214  4230 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-18 11:57:26.039  4214  4214 D HidService: setHidService(): set to: null
,08-18 11:57:26.040  4214  4214 I BluetoothHealthServiceJni: classInitNative: succeeds
08-18 11:57:26.041  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.041  4214  4214 D HealthService: Received start request. Starting profile...
,08-18 11:57:26.042  4214  4214 I bt_bluedroid: get_profile_interface health
,08-18 11:57:26.045  4214  4214 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-18 11:57:26.045  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-18 11:57:26.045  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.046  4214  4214 D PanService: Received start request. Starting profile...
08-18 11:57:26.046  4214  4214 D BluetoothPanServiceJni: initializeNative(L110): pan
08-18 11:57:26.046  4214  4214 I bt_bluedroid: get_profile_interface pan
,08-18 11:57:26.047  4214  4230 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-18 11:57:26.049  4214  4214 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:26.049  4214  4214 D BluetoothMapService: Received start request. Starting profile...
08-18 11:57:26.049  4214  4214 D BluetoothMapService: start()
,08-18 11:57:26.051  4214  4214 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-18 11:57:26.052  4214  4214 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-18 11:57:26.052  4214  4214 D BluetoothMapAppObserver: createReceiver()
,08-18 11:57:26.053  4214  4214 D BluetoothMapAppObserver: initObservers()
08-18 11:57:26.053  4214  4214 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-18 11:57:26.059  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:26.059  4214  4214 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:26.059  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:26.059  4214  4244 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-18 11:57:26.059  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
,08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:26.061  4214  4214 V BluetoothAdapterState: isTurningOn()=true
,08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isTurningOff()=false
08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isTurningOn()=true
08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:26.062  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:26.063  4214  4214 V BluetoothAdapterState: isTurningOff()=false
,08-18 11:57:26.063  4214  4214 V BluetoothAdapterState: isTurningOn()=true
08-18 11:57:26.063  4214  4214 V BluetoothAdapterState: isBleTurningOn()=false
08-18 11:57:26.063  4214  4214 V BluetoothAdapterState: isBleTurningOff()=false
08-18 11:57:26.063  4214  4226 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-18 11:57:26.063  4214  4226 D BluetoothAdapterProperties: ScanMode =  20
,08-18 11:57:26.063  4214  4226 D BluetoothAdapterProperties: State =  11
08-18 11:57:26.065  4214  4230 D BluetoothAdapterProperties: Scan Mode:21
08-18 11:57:26.065  4214  4230 D BluetoothAdapterProperties: Discoverable Timeout:120
08-18 11:57:26.065  4214  4226 D BluetoothAdapterProperties: Setting state to 12
08-18 11:57:26.065  4214  4226 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-18 11:57:26.066  3959  3970 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 11:57:26.067  4214  4226 I BluetoothAdapterState: Entering OnState
,08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:26.069  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-18 11:57:26.069   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 11:57:26.069   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 11:57:26.069  1364  1376 D BluetoothPan: onBluetoothStateChange on: true
08-18 11:57:26.070  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-18 11:57:26.072  3959  3969 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-18 11:57:26.072  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 11:57:26.072  1364  1364 D PanProfile: Bluetooth service connected
,08-18 11:57:26.074   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:26.074  1364  2075 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-18 11:57:26.075  3959  3959 D BluetoothInputDevice: Proxy object connected
08-18 11:57:26.075  3959  3959 D HidProfile: Bluetooth service connected
08-18 11:57:26.075  1364  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:26.076  1364  1364 D BluetoothA2dp: Proxy object connected
08-18 11:57:26.076  1364  1376 D BluetoothMap: onBluetoothStateChange: up=true
,08-18 11:57:26.077  3959  3969 D BluetoothPan: onBluetoothStateChange on: true
,08-18 11:57:26.078  1364  1364 D BluetoothMap: Proxy object connected
08-18 11:57:26.078  1364  1364 D MapProfile: Bluetooth service connected
,08-18 11:57:26.078  1364  1364 D BluetoothMap: getConnectedDevices()
08-18 11:57:26.079  4214  4214 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-18 11:57:26.079   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 11:57:26.080  4214  4214 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-18 11:57:26.080  3959  3969 D BluetoothHeadset: onBluetoothStateChange: up=true
08-18 11:57:26.080  3959  3959 D BluetoothPan: BluetoothPAN Proxy object connected
08-18 11:57:26.080  3959  3970 D BluetoothMap: onBluetoothStateChange: up=true
08-18 11:57:26.080  3959  3959 D PanProfile: Bluetooth service connected
,08-18 11:57:26.080   875   875 D BluetoothA2dp: Proxy object connected
08-18 11:57:26.081  4214  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:26.082  1945  1960 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-18 11:57:26.082  3959  3959 D BluetoothMap: Proxy object connected
08-18 11:57:26.082  3959  3959 D MapProfile: Bluetooth service connected
08-18 11:57:26.082  3959  3959 D BluetoothMap: getConnectedDevices()
,08-18 11:57:26.083  3959  3969 D BluetoothA2dp: onBluetoothStateChange: up=true
08-18 11:57:26.083  4214  4214 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:26.084  4214  4214 D ObexServerSockets: Succeed to create listening sockets 
,08-18 11:57:26.084  4214  4214 D ObexServerSockets0: startAccept()
08-18 11:57:26.084  1364  1387 D BluetoothPbap: onBluetoothStateChange: up=true
08-18 11:57:26.084  4214  4214 D ObexServerSockets0: prepareForNewConnect()
,08-18 11:57:26.086  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-18 11:57:26.086  3959  3959 D BluetoothA2dp: Proxy object connected
08-18 11:57:26.086  4214  4214 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-18 11:57:26.087  4214  4214 D BluetoothSdpJni: SDP Create record success - handle: 0
08-18 11:57:26.087  1364  1364 D BluetoothInputDevice: Proxy object connected
08-18 11:57:26.087  1364  1364 D HidProfile: Bluetooth service connected
08-18 11:57:26.090   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-18 11:57:26.090  4214  4214 D BluetoothMapService: onReceive
08-18 11:57:26.090  4214  4214 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-18 11:57:26.090  4214  4214 D BluetoothMapService: STATE_ON
,08-18 11:57:26.090  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:26.091  4214  4252 D ObexServerSockets0: Accepting socket connection...
08-18 11:57:26.091  4214  4253 D ObexServerSockets0: Accepting socket connection...
,08-18 11:57:26.097  3959  3959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-18 11:57:26.103  1509  1509 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-18 11:57:26.103  3959  3959 D DockEventReceiver: finishStartingService: stopping service
,08-18 11:57:26.111  3959  3959 D BluetoothPbap: Proxy object connected
,08-18 11:57:26.111  3959  3959 D PbapServerProfile: Bluetooth service connected
,08-18 11:57:26.114  1364  1364 D BluetoothPbap: Proxy object connected
08-18 11:57:26.114  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-18 11:57:26.117  4214  4214 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-18 11:57:26.117  4214  4214 D ObexServerSockets0: prepareForNewConnect()
,08-18 11:57:26.120  4214  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:26.135  4214  4262 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-18 11:57:26.137  4214  4262 I BtOppRfcommListener: Accept thread started.
,08-18 11:57:26.171  3959  3969 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.171   875   875 D BluetoothHeadset: Proxy object connected
08-18 11:57:26.171  3959  3959 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:26.172  1945  1958 D BluetoothHeadset: Proxy object connected
08-18 11:57:26.172   875   875 D BluetoothHeadset: Proxy object connected
08-18 11:57:26.172   875   875 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.172  1364  1376 D BluetoothHeadset: Proxy object connected
08-18 11:57:26.173  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:26.175   875   892 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.176  1364  2075 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.176  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:26.180  3959  3970 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.181  3959  3959 D HeadsetProfile: Bluetooth service connected
,08-18 11:57:26.183  1945  2097 D BluetoothHeadset: Proxy object connected
,08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:26.521  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:26.530  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:26.533  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:26.534  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c6893a added. We now have 8 listener(s)
08-18 11:57:26.534  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:26.540   875  1959 D WifiService: setWifiEnabled: false pid=3831, uid=10000
,08-18 11:57:26.540   875  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 11:57:26.554  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:26.555   875  2143 D WifiService: setWifiEnabled: true pid=3831, uid=10000
08-18 11:57:26.555   875  2143 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-18 11:57:26.566   875  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:26.585  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:26.591  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:26.603   875  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-18 11:57:26.604   875  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-18 11:57:26.605   875  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-18 11:57:26.605   875  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-18 11:57:26.606   875  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-18 11:57:26.606   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-18 11:57:26.606   875  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-18 11:57:26.622   875  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.23 delta 1000 -> 1000
,08-18 11:57:26.622   875  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-18 11:57:26.623   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-18 11:57:26.625   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:26.633   875  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-18 11:57:26.633   875  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-18 11:57:26.634   875  1312 E native  : do suspend true
,08-18 11:57:26.652   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-18 11:57:26.652   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:26.654   875  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-18 11:57:26.669   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-18 11:57:26.670   875  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-18 11:57:26.778   875  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-18 11:57:26.784  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-18 11:57:27.219  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-18 11:57:27.273  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-18 11:57:27.276  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-18 11:57:27.279   875  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-18 11:57:27.295   875  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 11:57:27.296   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-18 11:57:27.296   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:27.318   875  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-18 11:57:27.330   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:27.331   875  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,08-18 11:57:27.339   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-18 11:57:27.383   875  4270 D DhcpClient: Receive thread started
,08-18 11:57:27.470   875  1312 E native  : do suspend false
,08-18 11:57:27.490   875  1896 D DhcpClient: Broadcasting DHCPDISCOVER
,08-18 11:57:27.503   875  4270 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-18 11:57:27.504   875  1896 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-18 11:57:27.508   875  1896 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-18 11:57:27.520   875  4270 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-18 11:57:27.521   875  1896 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-18 11:57:27.527   373   873 D CommandListener: Setting iface cfg
,08-18 11:57:27.539   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-18 11:57:27.540   875  1896 D DhcpClient: Scheduling renewal in 86399s
,08-18 11:57:27.543   875  1312 E native  : do suspend true
,08-18 11:57:27.566   875  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-18 11:57:27.571   875  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-18 11:57:27.573   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-18 11:57:27.576   875  1314 D ConnectivityService: Adding iface wlan0 to network 102
,08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-18 11:57:27.577  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-18 11:57:27.584   875  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-18 11:57:27.587  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-18 11:57:27.596  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-18 11:57:27.596  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-18 11:57:27.599  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6e3b967 Bundle[{}]
,08-18 11:57:27.601  3831  3880 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-18 11:57:27.601  3831  3880 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-18 11:57:27.603  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-18 11:57:27.606  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-18 11:57:27.606  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-18 11:57:27.608  3831  3880 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-18 11:57:27.614  3831  3880 I System.out: Running OutgoingSocketThread
,08-18 11:57:27.616  3831  4273 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 432)
,08-18 11:57:27.617  3831  4273 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46839
,08-18 11:57:27.617  3831  4273 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-18 11:57:27.623   875  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-18 11:57:27.623   875  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-18 11:57:27.624   875  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-18 11:57:27.626   875  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-18 11:57:27.628   875  1314 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-18 11:57:27.638   875  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-18 11:57:27.642   875  1314 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-18 11:57:27.642   875  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-18 11:57:27.642   875  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-18 11:57:27.642   875  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-18 11:57:27.642   875  1314 D ConnectivityService:    accepting network in place of null
08-18 11:57:27.643   875  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-18 11:57:27.643   875  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-18 11:57:27.658   875  4269 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158129, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-18 11:57:27.693   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:27.724   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-18 11:57:27.725   875  4268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:810::200e
,08-18 11:57:27.732   875  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-18 11:57:27.734   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:27.737   875  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-18 11:57:27.739   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:27.752  3831  3831 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:57:27.758  3831  3831 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:27.789  1695  1695 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-18 11:57:27.792  1695  2453 I iu.UploadsManager: num queued entries: 0
,08-18 11:57:27.796  1695  1695 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-18 11:57:27.798  1695  1695 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-18 11:57:27.801  1695  2453 I iu.UploadsManager: num updated entries: 0,
,08-18 11:57:27.804  4015  4015 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-18 11:57:27.806   875  4268 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 18 Aug 2016 09:57:27 GMT], X-Android-Received-Millis=[1471514247806], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471514247776]}
,08-18 11:57:27.807   875  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-18 11:57:27.807   875  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-18 11:57:27.808   875  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-18 11:57:27.809   875  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-18 11:57:27.810  4015  4015 D SprintDMHelper: simOperator: 
08-18 11:57:27.811  4015  4015 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-18 11:57:27.815  1695  2453 I iu.SyncManager: NEXT; no task
,08-18 11:57:27.820  1695  4282 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-18 11:57:27.821  1695  4282 W BaseAppContext: Using Auth Proxy for data requests.
,08-18 11:57:27.823  1695  4282 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-18 11:57:27.838  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:27.843  1509  1509 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-18 11:57:27.890  1509  2298 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-18 11:57:27.890  1509  2298 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-18 11:57:27.891  1509  2298 I GLSUser : [GLSUser] Extracting token using key: Auth
08-18 11:57:27.891  1509  2298 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-18 11:57:27.921  1695  4282 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-18 11:57:27.933  3901  4285 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-18 11:57:28.619  3831  3880 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 433)
,08-18 11:57:28.620  3831  3880 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 433)
,08-18 11:57:28.628  3831  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 438)
,08-18 11:57:28.629  3831  3880 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-18 11:57:28.629  3831  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 439)
,08-18 11:57:28.631  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 11:57:28.632  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73449eb added. We now have 2 listener(s)
,08-18 11:57:28.633  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.634  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 11:57:28.634  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:57:28.634  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:28.634  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b4348 added. We now have 9 listener(s)
08-18 11:57:28.634  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.635  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:57:28.640  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:28.647  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:28.650  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:28.650  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:28.650  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.651  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d03ff06 added. We now have 3 listener(s)
,08-18 11:57:28.652  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 11:57:28.653  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.653  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:57:28.653  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:28.653  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70b99c7 added. We now have 10 listener(s)
08-18 11:57:28.653  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.653  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:28.653  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:28.653  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:28.653  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.654  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.654  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:28.654  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.654  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73449eb removed from the list
08-18 11:57:28.654  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.654  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b4348 removed from the list
08-18 11:57:28.656  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.657  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:28.657  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.657  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.657  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:28.660  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:28.660  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.660  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.661  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68b4348 not in the list
08-18 11:57:28.661  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.661  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:28.665  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:28.665  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:28.665  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.666  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@70b99c7 removed from the list
08-18 11:57:28.666  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:28.666  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.666  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.666  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.666  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.667  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d03ff06 removed from the list
,08-18 11:57:28.668  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.669  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb54bf4 added. We now have 2 listener(s)
,08-18 11:57:28.673  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.673  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.673  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.674  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:28.674  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddf1d added. We now have 9 listener(s)
08-18 11:57:28.674  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.674  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 11:57:28.677  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:28.681  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:28.683  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:28.683  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:28.683  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.683  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1e0b63 added. We now have 3 listener(s)
08-18 11:57:28.685  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 11:57:28.685  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.686  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.686  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:28.686  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d53360 added. We now have 10 listener(s)
,08-18 11:57:28.686  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.687  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 11:57:28.687  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 11:57:28.687  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 11:57:28.687  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:28.687  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 11:57:28.689  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:28.691  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-18 11:57:28.692  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 11:57:28.692  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.697  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 11:57:28.697  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-18 11:57:28.698  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-18 11:57:28.701  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 11:57:28.701  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-18 11:57:28.701  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 11:57:28.702  3831  3880 D BluetoothAdapter: STATE_ON
08-18 11:57:28.705  4214  4225 D BtGatt.GattService: registerClient() - UUID=d98a6cea-6503-4ba6-8dfb-29855f5fd241
,08-18 11:57:28.706  4214  4230 D BtGatt.GattService: onClientRegistered() - UUID=d98a6cea-6503-4ba6-8dfb-29855f5fd241, clientIf=5
08-18 11:57:28.707  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-18 11:57:28.708  4214  4254 D BtGatt.GattService: start scan with filters
,08-18 11:57:28.711  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 11:57:28.711  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 11:57:28.711  4214  4233 D BtGatt.ScanManager: handling starting scan
,08-18 11:57:28.711  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 11:57:28.712  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 11:57:28.714  4214  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@66baf8b
,08-18 11:57:28.714  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:28.714  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:28.715  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 11:57:28.716  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 11:57:28.718  4214  4230 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 11:57:28.718  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.719  4214  4233 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 11:57:28.720  3831  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-18 11:57:28.720  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:28.720  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-18 11:57:28.720  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:28.720  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 11:57:28.720  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-18 11:57:28.720  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 11:57:28.720  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 11:57:28.720  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 11:57:28.721  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:28.721  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-18 11:57:28.722  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:28.723  4214  4243 D BtGatt.GattService: stopScan() - queue size =1
08-18 11:57:28.723  4214  4224 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 11:57:28.724  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 11:57:28.724  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-18 11:57:28.724  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 11:57:28.724  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:28.724  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 11:57:28.725  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:28.725  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-18 11:57:28.725  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:28.726  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-18 11:57:28.726  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 11:57:28.727  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:28.727  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:28.727  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:28.729  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-18 11:57:28.729  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.729  4214  4233 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:28.730  4214  4233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 11:57:28.730  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-18 11:57:28.730  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:28.730  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 11:57:28.730  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.731  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.731  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 11:57:28.731  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.731  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb54bf4 removed from the list
,08-18 11:57:28.731  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.731  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddf1d removed from the list
08-18 11:57:28.731  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
,08-18 11:57:28.731  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.732  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.732  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:28.732   875  1314 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-18 11:57:28.733  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:28.733  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.733  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.733  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ddf1d not in the list
,08-18 11:57:28.733  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.733  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-18 11:57:28.735  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.735  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:28.735  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.735  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d53360 removed from the list
08-18 11:57:28.735  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:28.735  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.736  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.736  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.736  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1e0b63 removed from the list
08-18 11:57:28.736  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.736  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4a258c added. We now have 2 listener(s)
08-18 11:57:28.738  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.738  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.738  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.739  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:28.739  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ad4d5 added. We now have 9 listener(s)
08-18 11:57:28.739  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:28.739  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:57:28.741  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:28.746  4214  4230 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 11:57:28.746  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:28.748  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:28.752  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:28.752  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 11:57:28.753  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 11:57:28.753  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.754  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.754  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5f83db added. We now have 3 listener(s)
,08-18 11:57:28.755  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:28.758  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.758  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.758  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
,08-18 11:57:28.758  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:57:28.758  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:28.758  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3a0e78 added. We now have 10 listener(s)
,08-18 11:57:28.758  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.758  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 11:57:28.760  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 11:57:28.760  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-18 11:57:28.760  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 11:57:28.760  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:28.760  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-18 11:57:28.762  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 11:57:28.762  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.762  4214  4233 D BtGatt.ScanManager: stopping BLe Batch
08-18 11:57:28.764  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 11:57:28.764  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-18 11:57:28.768  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-18 11:57:28.768  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-18 11:57:28.768  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.769  4214  4233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-18 11:57:28.769  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 11:57:28.769  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 11:57:28.771  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-18 11:57:28.772  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 11:57:28.772  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 11:57:28.772  3831  3880 D BluetoothAdapter: STATE_ON
08-18 11:57:28.774  4214  4230 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 11:57:28.774  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.774  4214  4224 D BtGatt.GattService: registerClient() - UUID=7bb13141-44e1-4060-9403-edaea96e5e2e
08-18 11:57:28.775  4214  4230 D BtGatt.GattService: onClientRegistered() - UUID=7bb13141-44e1-4060-9403-edaea96e5e2e, clientIf=5
,08-18 11:57:28.775  3831  3881 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 11:57:28.775  4214  4243 D BtGatt.GattService: start scan with filters
,08-18 11:57:28.777  4214  4233 D BtGatt.ScanManager: handling starting scan
,08-18 11:57:28.778  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-18 11:57:28.778  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-18 11:57:28.778  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-18 11:57:28.778  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 11:57:28.782  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 11:57:28.782  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 11:57:28.783  4214  4230 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-18 11:57:28.783  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.783  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-18 11:57:28.783  4214  4233 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 11:57:28.786  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 11:57:28.788  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 11:57:28.788  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.788  4214  4233 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:28.788  4214  4233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-18 11:57:28.791  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 11:57:28.791  3831  3880 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-18 11:57:28.792  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 11:57:28.792  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:28.792  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-18 11:57:28.792  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.792  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.792  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-18 11:57:28.793  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.793  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4a258c removed from the list
08-18 11:57:28.793  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.793  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ad4d5 removed from the list
,08-18 11:57:28.793  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:28.793  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:28.794  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.794  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-18 11:57:28.794  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.794  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 11:57:28.796  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:28.796  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.796  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.796  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ad4d5 not in the list
08-18 11:57:28.796  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-18 11:57:28.796  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 11:57:28.796  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-18 11:57:28.797  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:28.797  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-18 11:57:28.797  4214  4230 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-18 11:57:28.798  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.798  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:28.798  4214  4225 D BtGatt.GattService: stopScan() - queue size =1
,08-18 11:57:28.799  4214  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-18 11:57:28.800  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-18 11:57:28.800  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 11:57:28.800  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-18 11:57:28.800  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:28.800  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 11:57:28.801  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:28.801  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-18 11:57:28.802  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:28.802  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 11:57:28.803  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.803  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-18 11:57:28.803  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.804  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:28.805  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-18 11:57:28.805  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:28.805  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:28.805  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:28.805  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:28.806  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3a0e78 removed from the list
,08-18 11:57:28.806  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.806  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-18 11:57:28.806  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.806  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-18 11:57:28.806  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5f83db removed from the list
,08-18 11:57:28.807  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.807  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93d9a24 added. We now have 2 listener(s)
,08-18 11:57:28.808  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-18 11:57:28.808  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-18 11:57:28.808  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.809  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:28.809  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c98d added. We now have 9 listener(s)
08-18 11:57:28.809  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-18 11:57:28.809  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-18 11:57:28.809  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.809  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-18 11:57:28.809  4214  4233 D BtGatt.ScanManager: stopping BLe Batch
,08-18 11:57:28.811  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:28.816  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 11:57:28.816  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.816  4214  4233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:57:28.816  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:28.818  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-18 11:57:28.819  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:57:28.819  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.819  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@589353 added. We now have 3 listener(s)
,08-18 11:57:28.821  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.821  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.821  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-18 11:57:28.822  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:28.822  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc3490 added. We now have 10 listener(s)
,08-18 11:57:28.822  4214  4230 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-18 11:57:28.822  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.822  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:28.822  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:57:28.823  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-18 11:57:28.823  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-18 11:57:28.823  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-18 11:57:28.823  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:57:28.823  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-18 11:57:28.825  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.826  3831  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-18 11:57:28.826  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-18 11:57:28.829  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-18 11:57:28.830  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-18 11:57:28.830  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-18 11:57:28.833  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-18 11:57:28.833  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-18 11:57:28.833  3831  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-18 11:57:28.834  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:28.835  4214  4225 D BtGatt.GattService: registerClient() - UUID=06b6faa9-ddec-46c8-a449-681a8374fa29
,08-18 11:57:28.836  4214  4230 D BtGatt.GattService: onClientRegistered() - UUID=06b6faa9-ddec-46c8-a449-681a8374fa29, clientIf=5
08-18 11:57:28.836  3831  3842 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-18 11:57:28.836  4214  4254 D BtGatt.GattService: start scan with filters
,08-18 11:57:28.838  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-18 11:57:28.839  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-18 11:57:28.839  4214  4233 D BtGatt.ScanManager: handling starting scan
08-18 11:57:28.839  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-18 11:57:28.839  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-18 11:57:28.841  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-18 11:57:28.842  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-18 11:57:28.842  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-18 11:57:28.844  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-18 11:57:28.846  4214  4230 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-18 11:57:28.846  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.846  4214  4233 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-18 11:57:28.848  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-18 11:57:28.848  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-18 11:57:28.849  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 11:57:28.849  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-18 11:57:28.849  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.849  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-18 11:57:28.849  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.849  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93d9a24 removed from the list
,08-18 11:57:28.849  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.850  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c98d removed from the list
08-18 11:57:28.850  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:28.850  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-18 11:57:28.850  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:28.850  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-18 11:57:28.850  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.850  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:28.851  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-18 11:57:28.852  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.852  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.852  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c98d not in the list
08-18 11:57:28.852  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-18 11:57:28.852  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-18 11:57:28.852  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-18 11:57:28.852  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-18 11:57:28.852  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-18 11:57:28.852  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-18 11:57:28.852  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.852  4214  4233 D BtGatt.ScanManager: Starting BLE batch scan
08-18 11:57:28.853  4214  4233 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-18 11:57:28.853  3831  3880 D BluetoothAdapter: STATE_ON
,08-18 11:57:28.856  4214  4254 D BtGatt.GattService: stopScan() - queue size =1
08-18 11:57:28.856  4214  4224 D BtGatt.GattService: unregisterClient() - clientIf=5
08-18 11:57:28.857  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-18 11:57:28.857  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-18 11:57:28.857  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-18 11:57:28.857  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-18 11:57:28.857  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-18 11:57:28.858  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-18 11:57:28.858  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-18 11:57:28.859  3831  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-18 11:57:28.859  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-18 11:57:28.859  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.860  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:28.860  3831  3831 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-18 11:57:28.860  3831  3831 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-18 11:57:28.860  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.861  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:28.861  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.861  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc3490 removed from the list
08-18 11:57:28.861  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.861  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.861  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.861  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.861  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@589353 removed from the list
08-18 11:57:28.862  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-18 11:57:28.862  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46809bc added. We now have 2 listener(s)
08-18 11:57:28.864  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.864  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.864  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.864  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-18 11:57:28.864  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab9d45 added. We now have 9 listener(s)
08-18 11:57:28.865  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:28.865  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:57:28.865  4214  4230 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-18 11:57:28.866  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.867  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true,
08-18 11:57:28.872  3831  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-18 11:57:28.873  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-18 11:57:28.873  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.874  3831  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,08-18 11:57:28.874  3831  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-18 11:57:28.875  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-18 11:57:28.876  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8519cb added. We now have 3 listener(s)
,08-18 11:57:28.877  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:57:28.877  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-18 11:57:28.878  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:57:28.878  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:57:28.878  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-18 11:57:28.878  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a05a8 added. We now have 10 listener(s)
,08-18 11:57:28.878  3831  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-18 11:57:28.878  3831  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-18 11:57:28.879  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-18 11:57:28.879  3831  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-18 11:57:28.879  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.879  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.879  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-18 11:57:28.879  3831  3831 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-18 11:57:28.879  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-18 11:57:28.879  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46809bc removed from the list
08-18 11:57:28.880  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-18 11:57:28.880  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab9d45 removed from the list
,08-18 11:57:28.880  3831  3880 D io.jxcore.node.ConnectivityMonitor: stop
08-18 11:57:28.880  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.880  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-18 11:57:28.880  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.881  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:28.881  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-18 11:57:28.882  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:28.882  3831  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ab9d45 not in the list
08-18 11:57:28.882  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.882  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.883  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-18 11:57:28.883  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-18 11:57:28.883  3831  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-18 11:57:28.883  3831  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a05a8 removed from the list
08-18 11:57:28.883  3831  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-18 11:57:28.883  3831  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-18 11:57:28.884  3831  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-18 11:57:28.884  3831  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-18 11:57:28.884  3831  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8519cb removed from the list
08-18 11:57:28.884  4214  4230 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-18 11:57:28.884  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-18 11:57:28.884  4214  4233 D BtGatt.ScanManager: stopping BLe Batch
08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-18 11:57:28.885  3831  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-18 11:57:28.895  3831  4291 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: My test thread name)
08-18 11:57:28.895  3831  4291 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: My test thread name)
08-18 11:57:28.895  3831  4291 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 11:57:28.897  4214  4230 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-18 11:57:28.897  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.898  4214  4233 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-18 11:57:28.898  3831  4292 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: My test thread name)
,08-18 11:57:28.898  3831  4292 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: My test thread name)
08-18 11:57:28.898  3831  4292 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-18 11:57:28.900  3831  3880 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-18 11:57:28.901  3831  3880 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-18 11:57:28.901  3831  3880 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-18 11:57:28.901  3831  3880 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-18 11:57:28.901  3831  3880 D com.test.thalitest.ThaliTestRunner: Total duration: 22808 ms
,08-18 11:57:28.903  3831  3880 I jxcore-log: Total number of executed tests:  80
08-18 11:57:28.903  3831  3880 I jxcore-log: 
,08-18 11:57:28.903  3831  3880 I jxcore-log: Number of passed tests:  80
08-18 11:57:28.903  3831  3880 I jxcore-log: 
,08-18 11:57:28.903  3831  3880 I jxcore-log: Number of failed tests:  0
08-18 11:57:28.903  3831  3880 I jxcore-log: 
,08-18 11:57:28.904  3831  3880 I jxcore-log: Number of ignored tests:  0
08-18 11:57:28.904  3831  3880 I jxcore-log: 
,08-18 11:57:28.904  3831  3880 I jxcore-log: Total duration:  22808
08-18 11:57:28.904  3831  3880 I jxcore-log: 
,08-18 11:57:28.905  4214  4230 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-18 11:57:28.905  3831  3880 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-18 11:57:28.905  3831  3880 I jxcore-log: 
,08-18 11:57:28.905  4214  4230 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-18 11:57:28.909  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.909  3831  3880 I jxcore-log: 
,08-18 11:57:28.916  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.916  3831  3880 I jxcore-log: 
,08-18 11:57:28.916  3831  3831 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-18 11:57:28.917  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.917  3831  3880 I jxcore-log: 
08-18 11:57:28.918  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.918  3831  3880 I jxcore-log: 
08-18 11:57:28.919  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.919  3831  3880 I jxcore-log: 
,08-18 11:57:28.920  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.920  3831  3880 I jxcore-log: 
08-18 11:57:28.923  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.923  3831  3880 I jxcore-log: 
,08-18 11:57:28.924  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.924  3831  3880 I jxcore-log: 
08-18 11:57:28.925  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.925  3831  3880 I jxcore-log: 
,08-18 11:57:28.926  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.926  3831  3880 I jxcore-log: 
08-18 11:57:28.927  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 11:57:28.927  3831  3880 I jxcore-log: 
,08-18 11:57:28.929  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 11:57:28.929  3831  3880 I jxcore-log: 
,08-18 11:57:28.930  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-18 11:57:28.930  3831  3880 I jxcore-log: 
,08-18 11:57:28.931  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.931  3831  3880 I jxcore-log: 
08-18 11:57:28.931  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.931  3831  3880 I jxcore-log: 
08-18 11:57:28.932  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.932  3831  3880 I jxcore-log: 
,08-18 11:57:28.933  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.933  3831  3880 I jxcore-log: 
08-18 11:57:28.933  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.933  3831  3880 I jxcore-log: 
,08-18 11:57:28.934  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.934  3831  3880 I jxcore-log: 
08-18 11:57:28.935  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.935  3831  3880 I jxcore-log: 
,08-18 11:57:28.935  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.935  3831  3880 I jxcore-log: 
08-18 11:57:28.936  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.936  3831  3880 I jxcore-log: 
,08-18 11:57:28.937  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-18 11:57:28.937  3831  3880 I jxcore-log: 
08-18 11:57:28.938  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 11:57:28.938  3831  3880 I jxcore-log: 
08-18 11:57:28.939  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-18 11:57:28.939  3831  3880 I jxcore-log: 
,08-18 11:57:28.939  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.939  3831  3880 I jxcore-log: 
08-18 11:57:28.940  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.940  3831  3880 I jxcore-log: 
,08-18 11:57:28.941  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.941  3831  3880 I jxcore-log: 
08-18 11:57:28.942  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.942  3831  3880 I jxcore-log: 
08-18 11:57:28.942  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.942  3831  3880 I jxcore-log: 
,08-18 11:57:28.943  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-18 11:57:28.943  3831  3880 I jxcore-log: 
,08-18 11:57:29.228  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 11:57:29.230  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 11:57:29.230  3831  3880 I jxcore-log: 
,08-18 11:57:29.306  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 11:57:29.308  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 11:57:29.308  3831  3880 I jxcore-log: 
,08-18 11:57:29.361  3831  3831 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-18 11:57:29.363  3831  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-18 11:57:29.363  3831  3880 I jxcore-log: 
,08-18 11:57:29.575  4293  4293 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-18 11:57:29.580  4293  4293 D AndroidRuntime: CheckJNI is OFF
,08-18 11:57:29.623  4293  4293 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-18 11:57:29.670  4293  4293 I Radio-JNI: register_android_hardware_Radio DONE
,08-18 11:57:29.693  4293  4293 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-18 11:57:29.705   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-18 11:57:29.706   875   888 I ActivityManager: Killing 3831:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-18 11:57:29.800   875   885 D GraphicsStats: Buffer count: 2
,08-18 11:57:29.800   875  1403 I WindowState: WIN DEATH: Window{3e49a5a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-18 11:57:29.802   875  1313 D WifiService: Client connection lost with reason: 4
,08-18 11:57:29.858   875   898 W PackageSettings: Skipping PackageSetting{5d784cc com.example.hello/10273} due to missing metadata
,08-18 11:57:29.879   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-18 11:57:29.879   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-18 11:57:29.880   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-18 11:57:29.880   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-18 11:57:29.880   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:29.880   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:29.880   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 11:57:29.880   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-18 11:57:29.881   875   888 I ActivityManager:   Force finishing activity ActivityRecord{a0a233 u0 com.test.thalitest/.MainActivity t2}
,08-18 11:57:29.885   875  2144 W ActivityManager: Spurious death for ProcessRecord{9f13156 0:com.test.thalitest/u0a0}, curProc for 3831: null
,08-18 11:57:29.890   875   898 I art     : Starting a blocking GC Explicit
,08-18 11:57:29.948   875   898 I art     : Explicit concurrent mark sweep GC freed 14113(975KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.139ms total 57.301ms
,08-18 11:57:30.012   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-18 11:57:30.017  4293  4293 I art     : System.exit called, status: 0
,08-18 11:57:30.017  4293  4293 I AndroidRuntime: VM exiting with result code 0.
,08-18 11:57:30.077   875   898 I ActivityManager: Start proc 4304:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-18 11:57:30.078   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-18 11:57:30.110   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-18 11:57:30.117  4214  4214 D BluetoothMapAppObserver: onReceive
,08-18 11:57:30.117  4214  4214 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-18 11:57:30.119  1888  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-18 11:57:30.120   875  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-18 11:57:30.122  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-18 11:57:30.124  3674  3674 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-18 11:57:30.141   875   886 I ActivityManager: Start proc 4319:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-18 11:57:30.148  1945  1945 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-18 11:57:30.149   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-18 11:57:30.150   875   887 E PackageManager: Failed to write settings, restoring backup
08-18 11:57:30.150   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-18 11:57:30.150   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-18 11:57:30.150   875   887 E PackageManager: 	,at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-18 11:57:30.150   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-18 11:57:30.150   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-18 11:57:30.150   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.150   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.150   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 11:57:30.156   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-18 11:57:30.156   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-18 11:57:30.156   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:30.156   875   888 E DropBoxManagerService: 	... 13 more
,08-18 11:57:30.157  1870  4317 I Keyboard.Facilitator.DecoderInitializer: run()
,08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp,
08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-18 11:57:30.161  1870  4317 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-18 11:57:30.163  1870  4317 I Decoder : createOrResetDecoder
,08-18 11:57:30.181   875  1310 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-18 11:57:30.195  1509  1509 I ConfigService: onCreate
,08-18 11:57:30.198  1509  4332 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 11:57:30.198  1509  4332 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-18 11:57:30.199  1509  4332 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-18 11:57:30.200  1509  4332 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-18 11:57:30.203   875  2143 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3831 uid 10000
,08-18 11:57:30.205  1870  1870 I Keyboard.Facilitator: onFinishInput()
08-18 11:57:30.208  4319  4319 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-18 11:57:30.214  1870  4317 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-18 11:57:30.227   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-18 11:57:30.243  1961  2063 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-18 11:57:30.255   875   885 I ActivityManager: Start proc 4333:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-18 11:57:30.256  1961  2063 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-18 11:57:30.256  1961  2063 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1961
08-18 11:57:30.256  1961  2063 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.256  1961  2063 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 11:57:30.258   875  1396 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 11:57:30.262   875  4343 E DropBoxManagerService: Can't write: system_app_crash
08-18 11:57:30.262   875  4343 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:30.262   875  4343 E DropBoxManagerService: 	... 5 more
,08-18 11:57:30.264  1961  2063 I Process : Sending signal. PID: 1961 SIG: 9
,08-18 11:57:30.283  1870  4317 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-18 11:57:30.285  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-18 11:57:30.285  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-18 11:57:30.288  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-18 11:57:30.288  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-18 11:57:30.289  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-18 11:57:30.289  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-18 11:57:30.290  1870  4317 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-18 11:57:30.290  1870  4317 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-18 11:57:30.290  1870  4317 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-18 11:57:30.291  1870  4317 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-18 11:57:30.291  1870  4317 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-18 11:57:30.291  1870  4317 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-18 11:57:30.324  4319  4319 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-18 11:57:30.332   279   279 E lowmemorykiller: Error writing /proc/1961/oom_score_adj; errno=22
,08-18 11:57:30.341   875   886 I WindowState: WIN DEATH: Window{fb8040c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-18 11:57:30.341   875  1396 D GraphicsStats: Buffer count: 1
,08-18 11:57:30.349  4319  4353 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-18 11:57:30.349   875  2010 I ActivityManager: Start proc 4354:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-18 11:57:30.350   279   279 E lowmemorykiller: Error opening /proc/1961/oom_score_adj; errno=2
08-18 11:57:30.350   875  2143 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1961) has died
08-18 11:57:30.351   875  2143 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-18 11:57:30.355   875  2143 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-18 11:57:30.373   875   888 I ActivityManager: Start proc 4367:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-18 11:57:30.397  4354  4354 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-18 11:57:30.401  4319  4353 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.401  4319  4353 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 11:57:30.401  4319  4353 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-18 11:57:30.401  4319  4353 E AndroidRuntime: Process: android.process.acore, PID: 4319
08-18 11:57:30.401  4319  4353 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.401  4319  4353 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-18 11:57:30.413   875  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-18 11:57:30.416   875  4379 E DropBoxManagerService: Can't write: system_app_crash
08-18 11:57:30.416   875  4379 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:30.416   875  4379 E DropBoxManagerService: 	... 5 more
08-18 11:57:30.417  4319  4353 I Process : Sending signal. PID: 4319 SIG: 9
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:30.421  4367  4367 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:30.422  4367  4367 D AndroidRuntime: Shutting down VM
,08-18 11:57:30.429  4367  4367 E AndroidRuntime: FATAL EXCEPTION: main
08-18 11:57:30.429  4367  4367 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4367
08-18 11:57:30.429  4367  4367 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417),
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-18 11:57:30.429  4367  4367 E AndroidRuntime: 	... 10 more
,08-18 11:57:30.430   279   279 E lowmemorykiller: Error writing /proc/4319/oom_score_adj; errno=22
08-18 11:57:30.431   875   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-18 11:57:30.432   875  4382 E DropBoxManagerService: Can't write: system_app_crash
08-18 11:57:30.432   875  4382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:30.432   875  4382 E DropBoxManagerService: 	... 5 more
,08-18 11:57:30.432  1509  1509 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-18 11:57:30.432  4367  4367 I Process : Sending signal. PID: 4367 SIG: 9
,08-18 11:57:30.433  1509  1509 D AndroidRuntime: Shutting down VM
08-18 11:57:30.433   279   279 E lowmemorykiller: Error writing /proc/4319/oom_score_adj; errno=22
08-18 11:57:30.434  1509  1509 E AndroidRuntime: FATAL EXCEPTION: main
08-18 11:57:30.434  1509  1509 E AndroidRuntime: Process: com.google.process.gapps, PID: 1509
08-18 11:57:30.434  1509  1509 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-18 11:57:30.434  1509  1509 E AndroidRuntime: 	... 8 more
,08-18 11:57:30.437   875  4383 E DropBoxManagerService: Can't write: system_app_crash
08-18 11:57:30.437   875  4383 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-18 11:57:30.437   875  4383 E DropBoxManagerService: 	... 5 more
,08-18 11:57:30.438  1509  1509 I Process : Sending signal. PID: 1509 SIG: 9
,08-18 11:57:30.449  1695  4365 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-18 11:57:30.450  1695  4365 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-18 11:57:30.455  1695  4365 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-18 11:57:30.455  1695  4365 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-18 11:57:30.461   875  2021 I ActivityManager: Killing 3455:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-18 11:57:30.470   875  1313 D WifiService: Client connection lost with reason: 4
,08-18 11:57:30.505   875   886 I ActivityManager: Process com.google.process.gapps (pid 1509) has died
,08-18 11:57:30.506   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-18 11:57:30.506   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
08-18 11:57:30.506   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 20999ms
08-18 11:57:30.506   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
08-18 11:57:30.508   875  2143 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4367) has died
,08-18 11:57:30.512   875  2143 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-18 11:57:30.513  1695  1695 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-18 11:57:30.525   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
